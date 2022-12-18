# Final Project: Windfarm Kinesis Data Stream

This is the final project of the Formação Engenharia de Dados[2022]: Domine Big Data course on Udemy.

The project aimed to build a data stream using AWS Kinesis of three fake sensor readings of a windfarm turbine - Power Factor, Battery Temperature and Hydraulic Pressure - generated randomly with python scripts with a range for each, being sent to a S3 Bucket raw layer, which AWS Glue read to it's ETL proccess and sent to a S3 Bucket for treated data, being finally ready for analysis inside AWS Athena.

![image](https://user-images.githubusercontent.com/103280317/207868753-57697906-b92a-4a3f-83c9-afa8832931b2.png)
Proposed proccess flowchart (Credits: Fernando Amaral)



This project was a bit simple but integrated some concepts like stream fundamentals and a simple ETL job, and the course served well to show an overview of AWS services, being a first step on the road ahead.
