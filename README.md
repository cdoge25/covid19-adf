# covid19-adf

## Overview
This project analyzes the spread and impact of COVID-19 across European countries using publicly available datasets. It aims to extract insights through data preprocessing, visualization, and time-series analysis.

## Table of contents
- [covid19-adf](#covid19-adf)
  - [Overview](#overview)
  - [Table of contents](#table-of-contents)
  - [Architecture](#architecture)
  - [Project Structure](#project-structure)
  - [Data Source](#data-source)
  - [Tech Stack](#tech-stack)


## Architecture
<p align="center">
    <img src="assets/architecture.png" alt="architecture" style="border-radius: 10px;">
    </br>
  Project Architecture
</p>

## Project Structure
```shell
.
├── assets/
├── dataflow/           
├── dataset/             
├── factory/
├── linkedService/
├── pipeline/
├── trigger/
├── publish_config.json
└── README.md
```

## Data Source
https://www.ecdc.europa.eu/en

## Tech Stack
1. Azure Data Factory
<p align="center">
    <img src="assets/df1.png" alt="dataflow" style="border-radius: 10px;">
    </br>
    <img src="assets/df2.png" alt="dataflow" style="border-radius: 10px;">
    </br>
    <img src="assets/df3.png" alt="dataflow" style="border-radius: 10px;">
    </br>
  Dataflow
</p>

2. Databricks
<p align="center">
    <img src="assets/databricks.png" alt="databricks" style="border-radius: 10px;">
    </br>
  Databricks
</p>

3. Azure Data Lake Gen 2
<p align="center">
    <img src="assets/adls.png" alt="adls" style="border-radius: 10px;">
    </br>
  Azure Data Lake Gen 2
</p>

4. Azure SQL Database
<p align="center">
    <img src="assets/asqldb.png" alt="asqldb" style="border-radius: 10px;">
    </br>
  Azure SQL Database
</p>

5. Power BI
<p align="center">
    <img src="assets/cv1.png" alt="cv1" style="border-radius: 10px;">
    </br>
    <img src="assets/cv2.png" alt="cv2" style="border-radius: 10px;">
    </br>
  Covid Trends by Country
</p>

<p align="center">
    <img src="assets/cv3.png" alt="cv3" style="border-radius: 10px;">
    </br>
  Covid Testing Cases
</p>

