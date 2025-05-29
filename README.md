# AzureFormulaOne

This repository holds the code and instructions to spin up a Databricks notebook and cluster, upload and process data, and create a Medallion Architecture. The dataset used is the Ergast F1 dataset.

(1) Create a Databricks workspace.
(2) Create a storage account and container.
(3) Connecting the storage account to the workspace:
        (a) Service Principal
              (1) Register Azure Active Directory/Service Principal
              (2) Generate a secret/password for application
              (3) Set Spark Config with App/Client ID, Directory/Tenant ID, and Secret
              (4) Assign role the Storage Blob Data Contributor to the data lake
        (b)
        (c)
