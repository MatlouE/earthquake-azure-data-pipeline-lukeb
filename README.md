# earthquake-azure-data-pipeline
Data engineering pipeline for processing earthquake data using Azure, Databricks and Azure Synapse Analytics. The pipeline automates data ingestion, processing and storage into bronze, silver and gold layers, processing the data for analysis and visualization

<h2>Business Case</h2>
Earthquake data is vital for understanding major events and migating risks
<ul>
  <li>lanning emergency responses</li>
  <li>Assessing risks</li>
  <li>Making data-driven decisions</li>
</ul>

<h2>Pipeline Architecture</h2>
<ol>
  <li>Azure Databricks. For distributed data processing</li>
  <li>Azure Data Factory. For orchestrating data workflows</li>
  <li>Azure Data Lake Storage. For Scalable data storage in bronze, silver, gold containers</li>
  <li>Azure Synapse Analytics. For querying and analyzing processed data</li>
</ol>
<img src='https://private-user-images.githubusercontent.com/144802491/399150923-bdadd2e0-89be-4683-b53b-fe331be6f6bf.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Njg2MzAzNTQsIm5iZiI6MTc2ODYzMDA1NCwicGF0aCI6Ii8xNDQ4MDI0OTEvMzk5MTUwOTIzLWJkYWRkMmUwLTg5YmUtNDY4My1iNTNiLWZlMzMxYmU2ZjZiZi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMTE3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDExN1QwNjA3MzRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00ZTI1MmQ3NTVhZDUwYzU2Y2NmMzI1ZDk5YjhkYTM3NWY4MzdiNGZhZWVhMWYwNjA4MjFlYWVjYmMyZWUxNThlJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.63U9URjl1qRgdRHb_VJZgIHAHV6MVewfnUZ4NzayfcQ' alt='Pipeline Architecture'>
