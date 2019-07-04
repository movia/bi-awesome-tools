# Awesome BI and Data Science Tools used by Movia
A curated list of awesome tools used by the Movia Business Intelligence Team


- ### Microsoft BI Stack
  - [Visual Studio 2017](https://visualstudio.microsoft.com/)
    Version: 15.9.8 [ [Download](https://visualstudio.microsoft.com/downloads/)
    | [Ealier releases](https://docs.microsoft.com/en-us/visualstudio/productinfo/installing-an-earlier-release-of-vs2017) ]
  - [SQL Server Data Tools (SSDT) for Visual Studio 2017](https://docs.microsoft.com/en-us/sql/ssdt/download-sql-server-data-tools-ssdt#ssdt-for-vs-2017-standalone-installer)
    Version:  15.9.0 [ [Download](https://go.microsoft.com/fwlink/?linkid=2052454) 
    | [Ealier releases](https://docs.microsoft.com/en-us/sql/ssdt/previous-releases-of-sql-server-data-tools-ssdt-and-ssdt-bi?view=sql-server-2017) ]
    Tool for building Analysis Services (AS) data models, Integration Services (IS) packages, and Reporting Services (RS) reports. 
  - Microsoft Access Database Engine 2016 Redistributable
    Version:  RTM
    
    [[Download](https://www.microsoft.com/en-us/download/details.aspx?id=54920)] and choose 32 bit or 64 bit depending on MS office version.
    
    Use Microsoft Access Database Engine when connections in SSIS-package has to be made to Excel files or other MS Office products.

 - [SQL Server Management Studio (SSMS)](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)
    Use SQL Server Management Studio (SSMS) to query, design, and manage your databases and data warehouses, wherever they are - on your local computer, or in the cloud.   
    Version: 18.0
  - Azure Data Studio
    Version: Always latest [ [Download](https://docs.microsoft.com/en-us/sql/azure-data-studio/download) ]
  - [PowerBI Desktop (Cloud)](https://powerbi.microsoft.com/en-us/downloads/)
    Desktop Client for Power BI Cloud.
    Version: Always latest
  - [PowerBI Desktop for Power BI Reporting Service (On-Prem)](https://powerbi.microsoft.com/en-us/report-server/)
    Desktop Client for Power BI Report Server.
    Version: [January 2019](https://www.microsoft.com/en-us/download/details.aspx?id=55329)
  - [RedGate SQL Developer Bundle](https://www.red-gate.com/products/) Bundle with different productivity tools from RedGate. Most notable: SQL Compare, SQL Data Compare, SQL Prompt.
    Version: [Log in to download right version](https://download.red-gate.com/SQLDeveloperBundle.exe)
  - [TabularEditor](https://tabulareditor.github.io/) A lightweight editor for SSAS Tabular Models built in .NET/WinForms.  
  
- ### PowerShell
  - [PowerShell Core](https://github.com/PowerShell/PowerShell/releases/tag/v6.1.0) Version: 6.1.0
  - [Posh-Git](https://github.com/dahlbyk/posh-git)
    PowerShell module that integrates Git and PowerShell by providing Git status summary information that can be displayed in the PowerShell prompt
  - [Invoke-MsBuild](https://github.com/deadlydog/Invoke-MsBuild) PowerShell module to make building projects and solutions with MsBuild easy.
  - [PowerShell](https://www.microsoft.com/en-us/download/details.aspx?id=54616) (Windows Management Framework 5.1)
  
  Remember to allow scripts to execute by executing the following statement from an elevated PowerShell prompt (e.g. *Run as administrator*)
  ```powershell
  Set-ExecutionPolicy Unrestricted
  ```
  
- ### Utilities
  - [Visual Studio Code](https://code.visualstudio.com/) Combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle. 
  - [Sublime Text](https://www.sublimetext.com/3) A sophisticated text editor for code, markup and prose.
  - [GitHub Desktop](https://desktop.github.com/) Extend your GitHub workflow beyond your browser with GitHub Desktop, completely redesigned with Electron. Get a unified cross-platform experience that’s completely open source and ready to customize.
  - [WinSCP](https://winscp.net/) SFTP/SCP and FTP(S) client for Windows
  - [7zip](https://www.7-zip.org/) Free and open-source file archiver used to zip/unzip compressed containers.
  - [Nuget](https://www.nuget.org/downloads) NuGet is a free and open-source package manager designed for the Microsoft development platform. We use this for maintaining dependencies for e.g. SSIS Script Tasks. Version: Always recommended latest
