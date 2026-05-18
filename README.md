# Performance Marketing Campaign Analysis
I worked on a simulated digital marketing analytics work overview involving campaign performance analysis across ecommerce beauty brand. I used SQL for KPI calculations, campaign analysis, funnel tracking, and platform performance evaluation

## Objectives

1. **Set up a retail sales database**: Created and populated an ecom beauty brand performance marketing database with the campaigns data.
2. **Data Cleaning**: Identified and removed records with missing or null values.
3. **Exploratory Data Analysis (EDA)**: Performed basic exploratory data analysis to understand the dataset.
4. **Business Analysis**: Use SQL to answer specific business questions and derive insights from the sales data.

5. ## Project Structure

### 1. Database Setup

- **Database Creation**: The work overview starts by creating a database named `nykaa_marketcampperf`.
- **Table Import**: A table named is nykaa_campaign_data imported which contains the clean data for analysis. The table structure includes columns for campaign_id, campaign_type, target_audience, duration, channel_used, impressions, clicks, leads, ROI, revenue_cost, aqusition_cost, language, customer_segment and date.

```sql
create database nykaa_marketcampperf;
use nykaa_marketcampperf;
```

## Data Modelling

1. **Changing the date format**:
2. 
3. Created a new date column with date data type. 
4. ```sql
alter table nykaa_campaign_data
add new_date date;
```
