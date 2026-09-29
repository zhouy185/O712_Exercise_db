# SwiftParcel Shipment Data — Exercise

## Scenario

You're handed one file from SwiftParcel, a package courier. Every shipment
from the past several weeks is recorded, along with whether the customer
later reported damage. Your manager wants to know: **are damaged shipments
a real problem, and if so, where is it concentrated?**

## The data (`swiftparcel_shipments.csv`)

| Column | Description |
|---|---|
| `shipment_id` | Unique shipment identifier |
| `customer_id` | Customer identifier |
| `hub` | Sorting hub the shipment was processed through |
| `ship_date` | Date the shipment was sent |
| `package_type` | Category of package (Fragile, Electronics, Clothing, Household) |
| `weight_kg` | Package weight |
| `declared_value` | Declared value of the package contents |
| `method` | Shipping method: `ground` or `express` |
| `delivered_on_time` | Whether the shipment arrived by its promised date |
| `damage_reported` | Whether the customer reported damage (the outcome of interest) |


## Question

Create a database using local DuckDB (in Colab) and add a table with the same content as the csv file. 

Then, create a database in MotherDB and move the local table there. 


## Submission

- Work in Colab.
- Download your notebook from colab
- Include your name in the file name
- Submit [here](https://mcmasteru365-my.sharepoint.com/:f:/g/personal/zhouy185_mcmaster_ca/IgDRG4A01HH_SrneWvHlPS-AAWaZpGnT7y3jKSTxa7b1olM)
