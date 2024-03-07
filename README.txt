### OBD2 DBC ###

These OBD DBC files contain most of the standardized OBD PIDs from Mode 01.

The DBC files do not contain 'proprietary PIDs', though you can freely expand the DBC as you see fit.

We provide 3 variants:
- 11-bit OBD2: This is the most common type used in passenger cars (response ID 0x7E8)
- 29-bit OBD2: This is sometimes used in cars, vans or heavy-duty vehicles (response PGN 0xDA00)
- 29-bit WWH-OBD: This is sometimes used in heavy-duty vehicles (response PGN 0xDA00)

-----------------------------------------------------------------------
### RELEVANT LINKS ### 

- CANedge series: https://www.csselectronics.com/
- OBD2 intro: https://www.csselectronics.com/pages/obd2-explained-simple-intro
- UDS intro: https://www.csselectronics.com/pages/uds-protocol-tutorial-unified-diagnostic-services
- Contact us: https://www.csselectronics.com/pages/contact-us

-----------------------------------------------------------------------
### CHANGE LOG ###

2023.10.23 v2.1
- Updated signal names
- Added WWH-OBD version of DBC
- Added meta data to hide irrelevant fields (relevant when using the CANedge MF4 decoders)

2020.03.27 v1.3
- changed the structure of the OBD2 DBC back to only support PIDs from CAN ID 7E8 to keep things simple as 7E8 typically contains the relevant data.
  If use cases require the other CAN IDs, please contact us.

2020.02.24 v1.2
- added CAN IDs 7E9-7EF as per the OBD2 standard

2020.10.22 v1.4
- fixed PID 5C to use degC as unit

2021.10.12 v1.4 Extended
- added separate OBD2 DBC for extended identifiers