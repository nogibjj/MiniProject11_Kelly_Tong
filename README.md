# IDS 706 Mini Project 11

This repository is for IDS706 mini project week 11. 

## Purpose 
The purpose of this repository is to record the building process for a data pipeline in Azure Databricks. 
This pipeline includes performing ingestig, preparing, and analyzing the data "song" automatically. 
A workflow job is also built and created to automatically run this pipeline in Databricks. 
The data "song" is a subset of the Million Song dataset. 
The reference steps for creating the databricks is in !(Build an end-to-end data pipeline)[https://docs.databricks.com/en/getting-started/data-pipeline-get-started.html]

## Github actions
Status badges for CI.yml
`CI.yml`
[![CI](https://github.com/nogibjj/MiniProject6_KellyTong/actions/workflows/CI.yml/badge.svg)](https://github.com/nogibjj/MiniProject6_KellyTong/actions/workflows/CI.yml)

## Result Query

<img width="675" alt="result_query1" src="https://github.com/nogibjj/MiniProject11_Kelly_Tong/assets/142815940/15372aa1-164e-47e7-ae1a-d240290bbe6c">


<img width="676" alt="result_query2" src="https://github.com/nogibjj/MiniProject11_Kelly_Tong/assets/142815940/d9dd2019-c476-4e81-b86f-32774e0c9ca1">


## Building Process

1. Create a `Cluster` in Azure Databricks
2. Create 3 notebooks in `Workspace` to perform: Ingesting the raw data, Preparing the data, Analyzing the data. 

   <img width="729" alt="notebook" src="https://github.com/nogibjj/MiniProject11_Kelly_Tong/assets/142815940/1a19417f-9025-434c-a4e4-b0e4321a658a">

4. Raw Data is loaded into the notebook

<img width="1288" alt="catalog_raw" src="https://github.com/nogibjj/MiniProject11_Kelly_Tong/assets/142815940/8d0b9faf-037b-43c2-ad36-b7cbbbe218dc">

6. Data is transformed into database format and prepared for query
   
   <img width="1264" alt="catalog_prepare" src="https://github.com/nogibjj/MiniProject11_Kelly_Tong/assets/142815940/6156bf67-9cc8-4783-88ce-f39fd752c7cb">

8. Job Workflows is created to automate ingesting, preparing, analyzing
   
   <img width="1072" alt="workflow_job" src="https://github.com/nogibjj/MiniProject11_Kelly_Tong/assets/142815940/10bd68a0-09db-4619-b40a-29743ea3cb71">

   <img width="1084" alt="workflow_job_2" src="https://github.com/nogibjj/MiniProject11_Kelly_Tong/assets/142815940/c43e6437-82bb-4d64-9d34-b16258128754">



