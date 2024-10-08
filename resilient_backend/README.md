# Database Backend

### 2. **This module is aimed at managing the database API and reports API.**

1. **api folder** contains the source code and configuration for a Django-based REST API that interacts with a PostgreSQL database. The API is responsible for managing database operations, including creating, reading, updating, and deleting (records, as well as ensuring efficient data management and security. It includes models, views, serializers, and migrations essential for database interaction, along with the necessary configurations for PostgreSQL integration.
   
   > Please be aware that the use of this api is currently for Withings devices (2/10/2024)
   
2.  **reports folder** contains the source folder for generating the reports through the Resilient web application. This module calls **utils** folder which is the baseline code for report generation.
3.  **utils folder** contains the source folder that analyse the upcoming health and usage data, to generate the pdf files for reports.
   
    > Please be aware that the use of this module is currently for Withings devices (2/10/2024)
   

```markdown
# Folder Structure

root-folder
│
├── api (database api)
├── reports (reports api)
├── utils
│   ├── Resilient.py
│   └── Devices_Oauth2flow.py
│   └── ...
└── ...
└── manage.py

# End of Folder Structure


