# SAP ABAP Shipment Report 📦

## Overview
A comprehensive SAP ABAP shipment tracking report that integrates delivery, material, and shipping information across multiple SAP modules. The report combines data from shipment management (VTTP/VTTK), delivery processing (LIPS/LIKP), and billing (VBRK) to provide a complete view of shipment operations.

### Data Integration
- **Shipment Data (VTTP/VTTK)**
  - Shipment Numbers (TKNUM)
  - Creation Dates (ERDAT)
  - Delivery References (VBELN)
  - Shipment Texts (TEXT1-4)
  - Processing Users (ERNAM/AENAM)
  - Carrier Information (TDLNR)

- **Delivery Details (LIPS/LIKP)**
  - Plant Information (WERKS)
  - Storage Locations (LGORT)
  - Material Data (MATNR, MATWA)
  - Quantities and Units (LFIMG, VRKME)
  - Weights (NTGEW, GEWEI)
  - Reference Documents (VGBEL)
  - Delivery Dates and Times (ERDAT, ERZET)
  - Goods Movement Dates (WADAT_IST)
  - Shipping Points (VSTEL)
  - Routes (ROUTE)
  - Sold-to Parties (KUNAG)

- **Billing Information (VBRK)**
  - Net Values (NETWR)

### Key Features
- Multi-table data integration with optimized joins
- Comprehensive filtering options:
  - Delivery Numbers
  - Plants
  - Creation Dates
- Detailed material and shipping information
- Complete tracking of document flow
- User and time stamp tracking
- Carrier and route monitoring

### Business Benefits
- End-to-end shipment visibility
- Integrated delivery tracking
- Material movement monitoring
- Financial value tracking
- Complete audit trail
- Operational efficiency insights
