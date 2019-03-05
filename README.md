# App Templates
These are the language kernel templates for deployment and consumption of applications deployed into an on premise SQL Server Big Data Cluster.

Each directory listed is a separate language kernel that is supported for app deployment:
- Python
- R
- SSIS
- Mleap

Each template contains three primary files:
- spec.yaml
    - This is the deployment definition given to the cluster
- run-spec.yaml
    - This is the app consumption definition given to the VS Code Ext. client
- app code
    - Example code for deployment of that particular type of language kernel

These templates are automatically pulled by the mssqlctl CLI and the App Deploy VS Code Extension.  Customers may also download these templates themselves outside of the clients, if desired.

Future language kernels supported for app deployment will be contributed as templates here.