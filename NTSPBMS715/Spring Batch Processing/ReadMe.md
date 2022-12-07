# Spring Batch -- Should Install Eclipse JEE Flavour

> #### Nov 18 2022 -- Spring Boot Batch Intro
> - <em>**`Topics:`**</em>
>     - What is Batch Processing.
>     - usecases
>     - examples
>     - When and why to use Batch processing ?
>     - Spring Batch High Level Architecture/
>     - The basic look of spring Batch app.
>     - Predefined ItemReaders
>     - Predefined ItemWriters
>     - Sequence Flow of Diagram of Step
> - <em>**`File Name :`**</em> *`NTSPBMS715- Spring boot Batch Intro  - NOV18th.png`*

> #### Nov 19 2022 -- No Class

> #### Nov 20 2022 -- No Class

> #### Nov 21 2022 -- Spring Batch Cfgs
> - <em>**`Topics:`**</em>
>     - Job
>     - Example
>     - Spring Batch Launch Environment
>         - Run Tier
>         - Job Tier
>         - Application Tier
>         - Data Tier
>     - Once we add "spring-boot-starter-batch" to the spring boot projects we get multiple objects related spring batch processing through AutoConfiguration like
>     - ItemReader
>     - The Readymade ItemReaders are
>     - ItemWriter
>     - The Readymade ItemWriters are
>     - ItemProcessor
>     - Example of ItemProcessor creation
>     - Step
>     - Every Step Object must contain the following 5 details
>     - method chaning
>     - Step object Diagram
> - <em>**`File Name :`**</em> *`NTSPBMS714- Spring Batch Cfgs  - NOV21st.png`*

> #### Nov 22 2022 -- NO Class

> #### Nov 23 2022 -- Spring Batch More Cfgs
> - <em>**`Topics:`**</em>
>     - Spring Batch Configurations
>     - Step Object Diagram
>     - JobExecutionListner(I)
>     - Example JobListner
>     - Job Object
>     - Job Object Diagram
>     - Sample Code
>     - @EnbleBatchProcessing
>     - End to End Technical View /flow of Spring Batch App (Diagram)
>     - Client App in Spring Batch App
>     - POC(Proof of Concept on Spring batch processing) (First App on Spring boot batch)
> - <em>**`File Name :`**</em> *`NTSPBMS715- Spring Batch More Cfgs  - NOV23rd-2022.png`*

> #### Nov 24 2022 -- Spring Batch POC
> - <em>**`Topics:`**</em>
>     - POC (Proof of Concept on Spring Batch Processing)
>     - BatchApp1-POC
>     - Another way of writing BatchConfig class.
> - <em>**`Project :`**</em> *`BatchApp1-POC`*
> - <em>**`File Name :`**</em> *`NTSPBMS715- Spring Boot Batch -- POC app  - NOV24th-2022.png`*

> #### Nov 25 2022 -- Spring Batch App Converting CSV File Data to Oracle DB table
> - <em>**`Topics:`**</em>
>     - Core java recap
>     - How many special blocks can be placed in java class ?
>     - When constructor is there to initialise non-static members variables then why should we take instance blocks ?
>     - regular blocks in java are
>     - Sample code to execute
>     - 4 types of inner classes
>     - Reading CSV File Data(Excel Data), Processing data and writing to Oracle DB table using Spring Batch
>     - FlatFileItemReader<T>
>     - jdbcBatchItemWriter
>     - Full diagram on each component instructions
> - <em>**`File Name :`**</em> *`NTSPBMS715- Spring Batch  App converting CSV File Data to Oracle DB table  - NOV25th-2022.png`*

> #### Nov 26 - Nov 28 2022 -- Spring Batch App Converting CSV File Data to Oracle DB table
> - <em>**`Topics:`**</em>
>     - Story Board of CSV file to DB table conversion using spring batch.
>     - Example App
>     - Step by Step execution
>     - Generte CSV File with Mock Data
> - <em>**`Project :`**</em> *`BootBatchProj02-CSVToDBTable`*
> - <em>**`File Name :`**</em> *`NTSPBMS715- Spring Batch  App conveting CSV File Data to Oracle DB table  -Nov26th-28th-2022.png`*
  
> #### Nov 29 2022 -- Spring Batch App Converting CSV File Data to Oracle DB table
> - <em>**`Topics:`**</em>
>     - Improving Reader and Writer object creation using anonymous sub class + instance block.
>     - Improving Reader and Writer objects creation using Builder classes.
> - <em>**`File Name :`**</em> *`NTSPBMS715- Spring Batch  App conveting CSV File Data to Oracle DB table  - NOV29th-2022.png`*
  
> #### Nov 30 2022 -- No Class

> #### Dec 01 2022 -- Using Spring Batch V5 with Spring Boot 3.0.0. Failed to create DB tables.

> #### Dec 02 2022 -- Spring Batch  App converting DB table records to CSV file 
> - <em>**`Topics:`**</em>
>     - Spring Batch  App converting DB table records to CSV file (Excel file).
>     - DB script creating huge number of random records in mysql DB table.
>         - Step by Step procedure
>     - Story board of batching (DB table records to csv file).
>         - Procedure with diagram
>         - Syntax lamda based interface implementation class obj creation.
>         - JdbcCursorItemReder and FlatFileItemWriter with anonyomous sub class + instance block and Builder class creation.
> - <em>**`File Name :`**</em> *`NTSPBMS715- Spring Batch  App converting DB table records to CSV file  - dec2nd 2022.png`*

> #### Dec 03 2022 -- Spring Batch  App converting DB table records to CSV file 
> - <em>**`Topics:`**</em>
>     - Story board of batching (DB table records to csv file).
>         - Procedure with diagram
>         - Syntax lamda based interface implementation class obj creation.
>         - JdbcCursorItemReder and FlatFileItemWriter with anonyomous sub class + instance block and Builder class creation.
>         - Config File
> - <em>**`File Name :`**</em> *`NTSPBMS715- Spring Batch  App converting DB table records to CSV file  - dec2nd -3rd-2022.png`*
  
> #### Dec 04 2022 -- No Class

> #### Dec 05 2022 -- Spring Batch  App conveting   csv file  to MongoDB Collections 
> - <em>**`Topics:`**</em>
>     - Spring Batch  App conveting   csv file  to MongoDB Document.
>         - Diagram Flow
>         - example app1 (Writing data value to mongodb collection as string value). -- like a story board
>         - Example app2 (date value as java.time.LocalDate in @Document class). -- like a story board
> - <em>**`File Name :`**</em> *`NTSPBMS715- Spring Batch  App conveting   csv file  to MongoDB Collections  - dec5th-2022.png`*

> #### Dec 06 2022 -- Spring Batch  App conveting   csv file  to MongoDB Collections 
> - <em>**`Topics:`**</em>
>     - Spring Batch  App conveting   csv file  to MongoDB Document.
>         - Diagram Flow
>         - example app1 (Writing data value to mongodb collection as string value). -- like a story board
>         - Example app2 (date value as java.time.LocalDate in @Document class). -- like a story board
>         - Flow of execution
>         - In application.properties
>         - To enable scheduling on Batch Processing.
> - <em>**`File Name :`**</em> *`NTSPBMS715- Spring Batch  App conveting   csv file  to MongoDB Collections  - dec5th-6th-2022.png`*
  
> #### Dec 07 2022 -- Spring Batch  App conveting   csv file  to MongoDB Collections 
> - <em>**`Topics:`**</em>
>     - Spring Batch  App conveting   csv file  to MongoDB Document.
>         - Diagram Flow
>         - example app1 (Writing data value to mongodb collection as string value). -- like a story board
>         - Example app2 (date value as java.time.LocalDate in @Document class). -- like a story board
>         - Flow of execution
>         - In application.properties
>         - To enable scheduling on Batch Processing.
> - <em>**`File Name :`**</em> *`NTSPBMS715- Spring Batch  App conveting   csv file  to MongoDB Collections  - dec5th-6th-2022.png`*
