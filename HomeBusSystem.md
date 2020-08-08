# Home Bus System (HBS)  

The RC-EX3 Controller has a MM1192 HBS-compatible Driver And Receiver IC it is widely used in Air-conditioning equipment 
It supports transmitting data and power on a single pair of wires for HomeBus System (HBS) applications.

This points to the Superlink System being based on the Home Bus System

HMS INDUSTRIAL NETWORKS (Parent company of Intesis) has a EC Declaration of Conformity for a Communication Gateway for the integration of Ethernet and "HBS" installation.

P1P2Serial:
---------
The following repository is hopefully the path forward for this project, I will likely need to reverse engineer the raw bytes but it is a step forward.
https://github.com/Arnold-n/P1P2Serial

The MAX22088 transceiver from "maximintegrated" is an newer alternative to the MM1192 with more features. Likely going forward to use this IC for some initial tests.

Resources:
---------
* https://www.maximintegrated.com/en/products/interface/transceivers/MAX22088.html
* https://www.digchip.com/datasheets/parts/datasheet/304/MM1192-pdf.php
* https://www.maximintegrated.com/en/design/technical-documents/app-notes/7/7226.html
* https://www.maximintegrated.com/en/design/technical-documents/app-notes/7/7224.html
* https://cdn.hms-networks.com/docs/librariesprovider11/other-documentation/ec-declaration-of-conformity/ce-declaration-of-conformity-is-ibv6-eth-hbs-hbs.pdf?sfvrsn=f15420d7_4
