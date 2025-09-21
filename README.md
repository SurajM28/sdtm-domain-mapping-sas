📊 SDTM Domain Mapping using SAS






📌 Overview

This project demonstrates end-to-end SDTM mapping of raw clinical trial datasets into CDISC-compliant domains using SAS.
It is designed as a portfolio project to showcase skills in:

Clinical Data Management

SAS Programming

CDISC SDTM Standards

🔄 Workflow
flowchart LR
    A[Raw Data] --> B[Test Data Creation]
    B --> C[SDTM Mapping Programs]
    C --> D[Mapped SAS Datasets]
    D --> E[XPT Export for Submission]

📂 Repository Structure
sdtm-domain-mapping-sas/
│
├── README.md                # Documentation
├── data/                    # Raw & test datasets
│   └── test_data.sas
├── programs/                # Mapping programs
│   ├── dm_mapping.sas
│   ├── ae_mapping.sas
│   ├── vs_mapping.sas
│   ├── lb_mapping.sas
│   └── cm_mapping.sas
├── output/                  # SDTM mapped datasets
└── export/                  # XPT transport files
