# Azure Finance Data Platform

Production-style Azure Data Engineering project.

Architecture:
SQL Server / SFTP → ADF → ADLS Gen2 → Databricks
→ Delta Lake → Reporting

Development workflow:
Feature Branch → Pull Request → Main → CI/CD
