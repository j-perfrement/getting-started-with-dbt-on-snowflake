# Getting Started with dbt on Snowflake

## Overview

This repository contains an example dbt project to get you started with dbt on Snowflake. 


Steps:
0. Run tasty_bytes_setup.sql (run once only)
1. dbt deps
2. dbt compile
3. dbt run
4. dbt test
5. deploy project (TASTY_BYTES_DBT_DB.RAW.tasty_bytes_dbt)
6. Schedule hourly execution (run & test) - in UI
7. Setup complex tasks & alerts (setup -> tasks_and_alerts.sql)
8. view task history for DAG
9. View traces & logs