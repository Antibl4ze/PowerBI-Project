# Data Professionals Survey – Power BI Dashboard

What do people working in data earn, which tools do they use, and how happy are they in their jobs? This Power BI dashboard summarises the answers of 630 data professionals to a survey about their roles, salaries, favourite programming languages and job satisfaction.

## Dashboard
![Data professionals survey Power BI dashboard](images/powerbi-dashboard.png)

The dashboard shows the number of respondents and their average age, average salary by job title, favourite programming language, the countries respondents live in, satisfaction scores (salary, work/life balance and management) and how hard people found it to get into the data field.

## Key findings
- **Data Scientists earn the most** on average, followed by Data Engineers and Data Architects. Data Analysts are in the middle, and students and job-seekers are lowest.
- **Python is by far the most popular language** across all job titles, ahead of R.
- **Satisfaction is middling:** on a 0–10 scale, salary satisfaction averages 4.27, management 5.33 and work/life balance 5.74.
- **Breaking into data is not easy for everyone:** 43% found it neither easy nor difficult, 32% found it difficult or very difficult and 25% found it easy or very easy.
- The average respondent is about **30 years old**, and the largest groups live in the United States, India, the United Kingdom and Canada.

## What I did
- Cleaned the survey data in Power Query: removed unneeded columns and split and grouped free-text answers (such as job titles, salary ranges and "Other" responses) into usable categories
- Turned salary ranges into numeric values so averages could be calculated
- Wrote DAX measures, for example average salary and the satisfaction averages
- Chose a visual for each question (bar charts, stacked columns, treemap, gauges, donut) and arranged them so the main results can be read at a glance

## Files
The Power BI report (`.pbix`) and the Excel data are too large for this repository. Download them from [Google Drive](https://drive.google.com/drive/folders/1hOs4zFPrEIcvKfETtUMs_JxG9FxRybmZ?usp=sharing) and open the report in Power BI Desktop.

| File | Description |
|---|---|
| `PowerBI+ExcelData Link` | The same Google Drive link |
| `images/` | Dashboard screenshot |

## Tools
Power BI (Power Query, DAX), Excel
