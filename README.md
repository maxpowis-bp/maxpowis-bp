# Hi there, I'm Max 👋

Welcome to my GitHub profile! I'm a passionate developer working at BearingPoint, with a focus on building efficient and scalable solutions. Here’s a bit about me:

I am a dedicated data expert with a strong background in data governance, data architecture, data modeling, data integration, system integration, reference data management, and business analytics. My extensive experience spans across various industries and roles, including freelance consulting, data vault and BI expertise, and enterprise application integration.

I have a deep interest in delivering highly efficient and modular solutions that rely on strong data models for reuse across various data disciplines. My work includes developing roadmaps for data lineage, defining modern data platform architectures, implementing data governance frameworks, and engineering automated data management platforms.

- 🔭 I’m currently leading data governance and integration projects at BearingPoint, contributing to the Collibra ecosystem and developing advanced data solutions.
- 🌱 I’m constantly learning and exploring modern data platform architectures, data governance frameworks, and innovative data integration techniques.
- 👯 I’m looking to collaborate on challenging projects that involve data architecture, data modeling, and system integration to drive business efficiency and innovation.
- 💬 Feel free to ask me about data governance, data integration, data modeling, and advanced analytics.
- 📫 You can reach me at: [ce-maximilien.powis@bearingpoint.com](mailto:ce-maximilien.powis@bearingpoint.com)

## Main Technologies I Work With

Here are some of the key technologies and tools I frequently use in my projects:

| **Category**            | **Technologies**                                                                                                                                                                        |
|-------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Data Governance**     | ![Collibra](https://img.shields.io/badge/-Collibra-1A1A1A?logo=collibra&logoColor=white) ![Azure Purview](https://img.shields.io/badge/-Azure%20Purview-0078D4?logo=azure-pipelines&logoColor=white) |
| **Data Integration**    | ![Apache Atlas](https://img.shields.io/badge/-Apache%20Atlas-D22128?logo=apache&logoColor=white) ![dbt Cloud](https://img.shields.io/badge/-dbt%20Cloud-FF694B?logo=dbt&logoColor=white) ![Fivetran](https://img.shields.io/badge/-Fivetran-0077C0?logo=fivetran&logoColor=white) |
| **Data Modeling**       | ![Data Vault](https://img.shields.io/badge/-Data%20Vault-0066CC?logo=data-vault&logoColor=white) ![Dimensional Modeling](https://img.shields.io/badge/-Dimensional%20Modeling-FFD700?logo=data-dimension&logoColor=black) ![Unified Star Schema](https://img.shields.io/badge/-Unified%20Star%20Schema-FF4500?logo=data-star&logoColor=white) |
| **Data Platforms**      | ![Snowflake](https://img.shields.io/badge/-Snowflake-29B5E8?logo=snowflake&logoColor=white) ![Google BigQuery](https://img.shields.io/badge/-Google%20BigQuery-4285F4?logo=google-cloud&logoColor=white) ![SQL Server](https://img.shields.io/badge/-SQL%20Server-CC2927?logo=microsoft-sql-server&logoColor=white) ![Oracle](https://img.shields.io/badge/-Oracle-F80000?logo=oracle&logoColor=white) |
| **Data Visualization**  | ![PowerBI](https://img.shields.io/badge/-PowerBI-F2C811?logo=power-bi&logoColor=black) ![QlikSense](https://img.shields.io/badge/-QlikSense-007DB8?logo=qlik&logoColor=white) ![Business Objects](https://img.shields.io/badge/-Business%20Objects-3498DB?logo=sap&logoColor=white) |
| **Programming & Scripting** | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![Java](https://img.shields.io/badge/-Java-007396?logo=java&logoColor=white) ![C#](https://img.shields.io/badge/-C%23-239120?logo=c-sharp&logoColor=white) ![Bash](https://img.shields.io/badge/-Bash-4EAA25?logo=gnu-bash&logoColor=white) ![PowerShell](https://img.shields.io/badge/-PowerShell-5391FE?logo=powershell&logoColor=white) |
| **API & Integration**   | ![REST](https://img.shields.io/badge/-REST-005C97?logo=api&logoColor=white) ![SOAP](https://img.shields.io/badge/-SOAP-0C457D?logo=soap&logoColor=white) ![Swagger](https://img.shields.io/badge/-Swagger-85EA2D?logo=swagger&logoColor=black) ![Postman](https://img.shields.io/badge/-Postman-FF6C37?logo=postman&logoColor=white) |
| **Version Control & CI/CD** | ![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=white) ![GitLab](https://img.shields.io/badge/-GitLab-FC6D26?logo=gitlab&logoColor=white) ![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white) |
| **IDEs & Tools**        | ![Visual Studio](https://img.shields.io/badge/-Visual%20Studio-5C2D91?logo=visual-studio&logoColor=white) ![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?logo=visual-studio-code&logoColor=white) ![Eclipse](https://img.shields.io/badge/-Eclipse-2C2255?logo=eclipse&logoColor=white) |


## My Approach to System Thinking for Collibra implementations

At BearingPoint, I focus on integrating system thinking into my work to build efficient, scalable, and cohesive solutions. The Collibra ecosystem plays a crucial role in data governance and management, and the repositories I maintain are designed to streamline and enhance integration and automation processes, providing significant value to our users.

```mermaid
graph TD
    A[API Documentation, Schema Management, and Integration Templates] -->|Centralized Schemas| B[API Client Generation]
    B -->|Automates Client Creation| C[API Clients]
    C -->|Core Functionalities| D[collibra-core-api-python-client]
    C -->|Maven Dependency| E[collibra-dgc-core-api-java]
    C -->|Data Import| F[collibra-importer-api-python-client]
    A -->|Supports| G[API Documentation Portal]
    A -->|Facilitates| H[API Change Tracking]
    A -->|Python Integrations| I[collibra-python-integration-template]
    J[Infrastructure Automation] -->|Setup/Destroy Automation| K[collibra-edge-gcp]
    L[Workflow Development] -->|Best Practices| M[collibra-workflows-template]
```

### API Documentation, Schema Management, and Integration Templates
The journey begins with [collibra-openapi-schemas](https://github.com/bearingpoint/collibra-openapi-schemas), which centralizes all Collibra OpenAPI schemas. This repository ensures that our API documentation is up-to-date and easily accessible, paving the way for automated client generation and documentation portals.

Next, [collibra-python-clients-generator](https://github.com/bearingpoint/collibra-python-clients-generator) automates the creation of Python API clients. This automation saves valuable development time and ensures consistency across our API clients.

With generated clients like [collibra-core-api-python-client](https://github.com/bearingpoint/collibra-core-api-python-client), [collibra-dgc-core-api-java](https://github.com/bearingpoint/collibra-dgc-core-api-java), and [collibra-importer-api-python-client](https://github.com/bearingpoint/collibra-importer-api-python-client), developers can easily integrate with the Collibra Data Governance Center. These clients provide robust interfaces for accessing core functionalities and specialized data import capabilities.

The [collibra-python-integration-template](https://github.com/bearingpoint/collibra-python-integration-template) provides a robust foundation for developing Python integrations with Collibra, incorporating best practices and powerful tools to deliver high-quality, efficient integrations.

### Infrastructure Automation
To support the deployment and management of Collibra Edge sites, [collibra-edge-gcp](https://github.com/bearingpoint/collibra-edge-gcp) provides Terraform automation scripts. This ensures that our infrastructure is scalable and easily maintainable.

### Workflow Development Templates
The [collibra-workflows-template](https://github.com/bearingpoint/collibra-workflows-template) standardizes best practices and enhances the developer experience around Collibra workflow development projects, featuring external script file management, Groovy syntax support, and dynamic resolution of external file contents.

Together, these repositories form a cohesive value stream that enhances the Collibra ecosystem, driving efficiency, consistency, and reliability in data governance and management. My personal focus on system thinking ensures that each component works seamlessly within the larger system, delivering maximum value.

## GitHub Stats

*Note: Those stats don't include the several internal organization repositories I manage and contribute to!*

![Max's GitHub Stats](https://github-readme-stats.vercel.app/api?username=maxpowis-bp&show_icons=true&theme=dark)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=maxpowis-bp&layout=compact&theme=dark)

## Connect with Me

- [LinkedIn](https://www.linkedin.com/in/maxpowis)

Thanks for visiting my profile! Feel free to check out my repositories and reach out if you want to collaborate or chat.