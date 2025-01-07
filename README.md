# Project-2-Crowdfunding_ETL

**File Structure:**
```
Project-2-Crowdfunding_ETL
│  .gitignore
│  LICENSE
│  README.md
│
└─Crowdfunding
    │  crowdfunding_db_schema.sql
    │  data_verification.sql
    │  ETL_Mini_Project_JKlucher.ipynb
    │  QuickDBD-export.png
    │
    ├─output
    │      campaign.csv
    │      category.csv
    │      contacts.csv
    │      subcategory.csv
    │
    └─Resources
            contacts.xlsx
            crowdfunding.xlsx
```

**Instructions:**
1. Clone the repository.
2. Open up **ETL_Mini_Project_JKlucher.ipynb** using Jupyter Notebook or Visual Studio Code and run all cells.
3. Open up pgAdmin 4 or other Database Management Software and create a new Database **crowdfunding_db**.
4. Open the **crowdfunding_db_schema.sql** inside the newly created database and run the script to generate tables.
5. Import each csv file from the *output* folder into the newly created database tables in this order:
   * category
   * subcategory
   * contacts
   * campaign
6. After successful import, open up **data_verification.sql** and run each query to check the data in each table.
