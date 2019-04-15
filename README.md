[![Build Status](https://ricardofiel2.visualstudio.com/UmbracoDevops/_apis/build/status/theplastictoy.umbracodevops?branchName=master)](https://ricardofiel2.visualstudio.com/UmbracoDevops/_build/latest?definitionId=2&branchName=master)

# Umbraco Devops

Sample project on how to have a fully automated CI/CD pipeline for Umbraco using Azure Devops. Goals:

* IaC (Infrastructure as code) to provision the required resources in Azure (Web Apps, SQL Database, App Insights)
* Out of the box with 2 environments - staging, production - and add more in an automated way
* Keep secrets (eg: SQL connection strings) out of config files
* Keep config files in a way that is compatible with running in localhost for development but also allowing for easy replacement per environment by Azure Devops
* Automate Database schema and data changes across environments
* Automate Umbraco specifics (eg: content, document types) across environments

## Solution Architecture

(Image here)

## CI/CD Pipeline description

## Issues and contributing

Please open an issue if you come across a problem. Contributions are welcome, just fork the project and open a pull-request. 

## References

[https://aaronpowell.github.io/Chauffeur/deploy-vsts-azure.html](https://aaronpowell.github.io/Chauffeur/deploy-vsts-azure.html)

[https://our.umbraco.com/forum/using-umbraco-and-getting-started/94398-usync-export-and-import-on-command-line](https://our.umbraco.com/forum/using-umbraco-and-getting-started/94398-usync-export-and-import-on-command-line)

## Disclaimer

THIS CODE IS PROVIDED AS IS WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.

## License

MIT