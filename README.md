# dp-203-lab-22

Data Management and Data Lineage with Microsoft Purview and Azure Synapse Analytics
This project covers the process of cataloging data assets in Azure Synapse Analytics and tracking data lineage using Microsoft Purview. It focuses on data governance, security, and monitoring, which are crucial components for managing large datasets and ensuring data quality.

Contents
Cataloging data assets in Azure Synapse Analytics

Scanning and tracking data lineage with Microsoft Purview

Interacting with Azure Data Lake Storage Gen2

Integration between Synapse Studio and Microsoft Purview

Querying data using SQL Data Pools and Serverless SQL Pools

Prerequisites
The following prerequisites are required to run this project:

Azure Account with administrative rights

Access to Microsoft Purview and Azure Synapse Analytics services

Ability to run commands in PowerShell

Access to Git and Cloud Shell

Setup
Step 1: Start Azure Cloud Shell
Open PowerShell in the Azure Portal and prepare to run the required commands.

Step 2: Clone the GitHub Repository
Use the following commands to clone the repository to your local environment:


rm -r dp-203 -f
git clone https://github.com/MicrosoftLearning/dp-203-azure-data-engineer dp-203
Step 3: Navigate to the Lab Directory and Setup

cd dp-203/Allfiles/labs/22
./setup.ps1
This command will set up the necessary Azure resources.

Step 4: Explore Azure Synapse Analytics Workspace
Open Synapse Studio and run the associated SQL pool to get started. Use Synapse Studio for managing and querying your data.

Step 5: Create and Configure Microsoft Purview Account
Create a Microsoft Purview account and configure it with access to your Azure Synapse Analytics resources.

Step 6: Register Data Sources in Microsoft Purview
Register your Azure Synapse Analytics and Azure Data Lake sources with Microsoft Purview. Once registered, start scanning them.

Step 7: Scan and Catalog Data Sources
Scan and catalog your resources through Microsoft Purview. This will help visualize the data assets and their lineage.

Step 8: Integrate Microsoft Purview with Synapse Analytics
Enable integration between Microsoft Purview and Azure Synapse Analytics to explore your data assets and utilize data lineage tracking features.

Usage
This repository is designed for data engineers and analysts who want to build data governance solutions using Microsoft Purview and Azure Synapse Analytics. Follow the steps below to manage and track your data:

Set up the Azure Synapse Analytics workspace.

Create and configure your Microsoft Purview account.

Register and scan your data sources.

Integrate Microsoft Purview with Azure Synapse Analytics.

Explore and analyze your data assets.

Contributing
To contribute to this project, follow these steps:

Fork the repository.

Create a new feature branch (git checkout -b feature/FeatureName).

Make your changes and commit them (git commit -am 'Add new feature').

Push your changes to GitHub (git push origin feature/FeatureName).

Create a pull request.
![22 linage-2](https://github.com/user-attachments/assets/7d9f7ffe-2d10-4d3a-bfe0-86b016ebbb46)
![21 pureviewde lineage gorntusu](https://github.com/user-attachments/assets/1fe00dad-2eed-4312-a0e6-49e83f20ebc7)
![20 pipeline calisiyor](https://github.com/user-attachments/assets/9619dfa3-1e12-45d0-bf1e-8b8f2f1a4e98)
![19 copy data from Azure Data Lake Storage Gen2 to Azure Synapse dedicated SQL pool](https://github.com/user-attachments/assets/f028edef-10ed-4a5d-8ae1-51c379371587)
![18 create a pipeline to move txt file](https://github.com/user-attachments/assets/2ec190d3-d12e-4e27-a35a-4f37faf917e3)
![17 Enable Microsoft Purview integration in Azure Synapse Analytics](https://github.com/user-attachments/assets/668a8c50-e84a-47c0-bda0-2706595ce29e)
![16 preview de scan olusturmak](https://github.com/user-attachments/assets/18afa02c-32b0-4632-ba40-cc3f557708a6)
![15 pureview e assign ettikten sonraki goruntu](https://github.com/user-attachments/assets/2add1293-f0b0-4b21-adf7-ab0043c90ca4)
![14 register a second source for the data lake storage used by your Azure Synapse workspace](https://github.com/user-attachments/assets/33e8bb9a-98f3-4d2f-9171-038d651c9caf)
![13 In the Register sources tab that appears, select Azure Synapse Analytics, and continue to register a source](https://github.com/user-attachments/assets/5bf6f89a-21cb-4735-8ea0-e996a947fe09)
![12 which creates a user in the dedicated SQL pool for the managed identity used by Microsoft Purview, and adds it to the db_datareader role in the sqlxxxxxxx database](https://github.com/user-attachments/assets/2f76a4a7-4ab9-40e5-a08a-df2b8ab8ad79)
![11 creates a login and a user in the lakedb user for the managed identity used by Microsoft Purview, and adds the user to the db_datareader role in the lakedb database](https://github.com/user-attachments/assets/16ce853b-de93-4d14-bb09-31a3edf04a1d)
![10 lakedb e erisim icin pureview deki reader kullaniciya k adi vs olusturacagiz](https://github.com/user-attachments/assets/9aadd3fa-ced9-41a3-8091-b329ea3915f7)
![9 Storage Blob Data Reader teykisi atadik](https://github.com/user-attachments/assets/ad09b88d-a64b-429e-bb19-7912515b6326)
![8 data storage imiza yeni erisim yetkisi verecegiz ki pureview ile verilerimizin yolunu takip edebilelim](https://github.com/user-attachments/assets/036e2a9c-dae7-40e4-bc37-2ae965193bb0)
![7 resourcegroup umuza bir pureview resource ekledik](https://github.com/user-attachments/assets/9ce1566d-6e58-4246-a5de-f28b53cc3565)
![6 yeni tablr daki verileri gosrduk](https://github.com/user-attachments/assets/37faa890-06fe-43c8-9b1d-14e6c20e2d89)
![5 datalake e harici tablo ekledik3](https://github.com/user-attachments/assets/d21e8970-f770-40bd-8c46-9da0e1338f49)
![4 datalake e harici tablo ekledik2](https://github.com/user-attachments/assets/3d7df1eb-3a4d-4413-8b6e-7e5e35e7e87d)
![3 datalake e harici tablo ekledik1](https://github.com/user-attachments/assets/602fe136-3b83-41c0-a0de-0e4973f7f918)
![2 yeni bir data lake olusturuyoruz](https://github.com/user-attachments/assets/fff15899-a0bd-463c-bf28-49f23a0ee6ae)
![1 snapse analytics uzerinde dedicated sql  databse i aktiflestirdik](https://github.com/user-attachments/assets/f7ef8b25-3f99-4f7a-a40b-18beeb1fd8e3)



