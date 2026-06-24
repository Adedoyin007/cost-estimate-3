Azure Cost Breakdown Report (Updated)

Summary

* Total Monthly Cost: $386.32
* Total Upfront Cost: $0.00

⸻

Cost by Service Category

* Compute: $10.22
* Database: $372.97
* Storage: $3.12
* Support: $0.00

⸻

Detailed Breakdown

Compute - Virtual Machines

* Region: East US
* Monthly Cost: $10.22
* Upfront Cost: $0.00

Description:
1 × B1s (1 vCPU, 1 GB RAM) running for 730 hours/month (pay-as-you-go), Windows OS (license included), with 5 GB outbound data transfer.

⸻

Database - Azure SQL Database

* Service Type: Azure SQL Database
* Tier: General Purpose (Provisioned, vCore)
* Region: East US
* Compute Size: 1–2 vCores (Gen5)
* Storage Allocated: 32 GB
* Monthly Cost: $372.97
* Upfront Cost: $0.00

Description:
Single database deployment using the vCore-based General Purpose tier. Includes locally redundant storage and RA-GRS backup redundancy. Designed for production workloads with moderate compute and storage requirements.

⸻

Storage - Azure Storage

* Region: East US
* Monthly Cost: $3.12
* Upfront Cost: $0.00

Description:
100 GB Block Blob Storage (Hot tier, LRS redundancy) with read/write operations and data transfer included.

⸻

Support

* Plan: None
* Monthly Cost: $0.00
* Upfront Cost: $0.00

⸻

Key Observations

* Database accounts for the majority of total cost (~96%)
* Compute and storage costs remain minimal
* Managed database services significantly increase overall spend
* Storage pricing is cost-efficient for small workloads

⸻

Conclusion

The Azure SQL Database is the primary cost driver in this configuration. While compute and storage remain low-cost, the managed database service dominates the total monthly estimate. Cost optimization should focus on database tier selection and resource sizing.

⸻

Notes

* Values are based on the Azure Pricing Calculator export
* Costs reflect pay-as-you-go pricing
* Suitable for comparison with equivalent AWS architecture