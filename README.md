# Awesome BI and Data Science Tools used by Movia
A curated list of awesome tools used by the Movia Business Intelligence Team


- ### Microsoft BI Stack
  - [Visual Studio Professional 2019](https://visualstudio.microsoft.com/)
    Version: 16.7.6 [ [Download](https://visualstudio.microsoft.com/downloads/)| [Ealier releases](https://docs.microsoft.com/en-us/visualstudio/releases/2019/history) ] It is **very important** that you install the **Professional Edition** as SSIS and other projects are not suported in the other editions, e.g. Community Edition.
    
    Popular extensions:
    - [Integration Services Projects](https://marketplace.visualstudio.com/items?itemName=SSIS.SqlServerIntegrationServicesProjects) Allows for building high performance data integration and workflow solutions, including extraction, transformation, and loading (ETL) operations for data warehousing. Currently the supported target server version starts from SQL Server 2012 up to 2019.
    - [Analysis Services Projects](https://marketplace.visualstudio.com/items?itemName=ProBITools.MicrosoftAnalysisServicesModelingProjects) Allows for building professional data models hosted in SQL Server Analysis Services on-premises, Microsoft Azure Analysis Services, and Microsoft Power BI.
    - [Reporting Services Projects](https://marketplace.visualstudio.com/items?itemName=ProBITools.MicrosoftReportProjectsforVisualStudio) The Microsoft RDL report designer, projects and wizards for creating professional reports. This package provides support for the .rptproj type and is designed for the most recent versions of Microsoft Reporting Services.
    - [Azure Feature Pack for Integration Services (SSIS)](https://docs.microsoft.com/en-us/sql/integration-services/azure-feature-pack-for-integration-services-ssis?view=sql-server-ver15) SQL Server Integration Services (SSIS) Feature Pack for Azure is an extension that provides the components listed on this page for SSIS to connect to Azure services, transfer data between Azure and on-premises data sources, and process data stored in Azure.
  - [SQL Server Management Studio (SSMS)](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms) 
    Version: 18.3    
    Use SQL Server Management Studio (SSMS) to query, design, and manage your databases and data warehouses, wherever they are - on your local computer, or in the cloud.       
  - Azure Data Studio
    Version: Always latest [ [Download](https://docs.microsoft.com/en-us/sql/azure-data-studio/download) ]
  - [PowerBI Desktop (Cloud)](https://powerbi.microsoft.com/en-us/downloads/)
    Desktop Client for Power BI Cloud.
    Version: Always latest
  - [PowerBI Desktop for Power BI Reporting Service (On-Prem)](https://powerbi.microsoft.com/en-us/report-server/)
    Desktop Client for Power BI Report Server.
    Version: [January 2020](https://www.microsoft.com/en-us/download/details.aspx?id=55329)
  - [RedGate SQL Developer Bundle](https://www.red-gate.com/products/) Bundle with different productivity tools from RedGate. Most notable: SQL Compare, SQL Data Compare, SQL Prompt.
    Version: [Log in to download right version](https://download.red-gate.com/SQLDeveloperBundle.exe)
  - [Microsoft Access Database Engine 2016 Redistributable](https://www.microsoft.com/en-us/download/details.aspx?id=54920)
    Version: RTM [ [Download](https://www.microsoft.com/en-us/download/details.aspx?id=54920) ]
    Use Microsoft Access Database Engine when connections in SSIS-package has to be made to Excel files or other MS Office products. Choose 32 bit or 64 bit depending on MS office version.
  - [TabularEditor](https://tabulareditor.github.io/) A lightweight editor for SSAS Tabular Models built in .NET/WinForms.  
  
- ### PowerShell
  - [PowerShell Core](https://github.com/PowerShell/PowerShell/releases/latest) Version: latest
  - [Posh-Git](https://github.com/dahlbyk/posh-git)
    PowerShell module that integrates Git and PowerShell by providing Git status summary information that can be displayed in the PowerShell prompt
  - [Invoke-MsBuild](https://github.com/deadlydog/Invoke-MsBuild) PowerShell module to make building projects and solutions with MsBuild easy.
  - [PowerShell](https://www.microsoft.com/en-us/download/details.aspx?id=54616) (Windows Management Framework 5.1)
  
  Remember to allow scripts to execute by executing the following statement from an elevated PowerShell prompt (e.g. *Run as administrator*)
  ```powershell
  Set-ExecutionPolicy Unrestricted
  ```
  
- ### Utilities
  - [Visual Studio Code](https://code.visualstudio.com/) Combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle. Popular extensions:
    - [Azure Functions](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurefunctions) An Azure Functions extension for Visual Studio Code
    - [Azure Storage](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azure-account) Manage your Azure Storage accounts including Blob Containers, File Shares, Tables and Queues
    - [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) Linting, Debugging (multi-threaded, remote), Intellisense, Jupyter Notebooks, code formatting, refactoring, unit tests, and more.
  - [GitHub Desktop](https://desktop.github.com/) Extend your GitHub workflow beyond your browser with GitHub Desktop, completely redesigned with Electron. Get a unified cross-platform experience that’s completely open source and ready to customize.
  - [WinSCP](https://winscp.net/) SFTP/SCP and FTP(S) client for Windows. Remember to add WinSCP to PATH during installation.
  - [7zip](https://www.7-zip.org/) Free and open-source file archiver used to zip/unzip compressed containers.
  - [Nuget](https://www.nuget.org/downloads) NuGet is a free and open-source package manager designed for the Microsoft development platform. We use this for maintaining dependencies for e.g. SSIS Script Tasks. Version: Always recommended latest
