# ☕ Coffee Quality Analysis – Power BI

An end-to-end Power BI analysis of coffee quality using data from the Coffee Quality Institute (CQI). The dashboard explores which sensory attributes, processing methods, origins and defects influence a coffee's overall quality score.

## 📌 Project Overview
The Coffee Quality Institute (CQI) is a non-profit organisation that works to improve the quality and value of coffee worldwide. This project analyses Arabica coffee quality data (207 rows, 31 columns) and answers four business questions through an interactive 4-page Power BI report.

## 🛠️ Tools Used
- Power BI Desktop
- Power Query (data cleaning and transformation)
- DAX (measures)
- Microsoft Excel / CSV (source data)

## 🔄 Workflow
1. Imported the CSV into Power BI Desktop using **Get Data**.
2. Cleaned the data in **Power Query**: removed unnecessary columns and translated some values to English using *Replace Values*.
3. Created DAX measures such as Average Aroma, Average Flavour, Average Acidity and Average Total Cup Points.
4. Built the 4-page dashboard and wrote the insights.

## ❓ Business Questions and Key Findings

### 1. Key Quality Determinants
- Aroma (7.72), Flavour (7.74) and Acidity (7.69) are the main sensory attributes.
- Sum of Total Cup Points: **17.33K**; Average Total Cup Points: **83.71**.
- Coffees scoring higher on these attributes tend to get higher overall scores.

### 2. Processing Method and Origin
- **Washed / Wet** is the most common processing method, with the highest total cup points (10,372.07) and an average score of **84.49**.
- **Taiwan** has the highest total cup points by country (5,145.37) because it has the most samples, but its average score (**83.42**) is slightly below the overall average.
- Processing method and origin appear to influence quality. Note that totals are affected by sample count, so averages give a fairer comparison.

### 3. Defect Patterns
- Category Two defects (**466**) are far more common than Category One defects (**28**).
- Higher defect counts are likely to reduce quality, so quality control during processing and storage is important.

### 4. Variable Interaction
| Attribute | Average Score |
|---|---|
| Total Cup Points | 83.71 |
| Aroma | 7.72 |
| Flavour | 7.74 |
| Acidity | 7.69 |
| Body | 7.64 |
| Clean Cup | 10 |
| Sweetness | 10 |

- Aroma and flavour are strong drivers of quality.
- Clean Cup and Sweetness score a perfect 10 on average, so they separate samples less than the other attributes.
- Balance between acidity, body and sweetness shapes the overall flavour profile.

## 💡 Recommendations
- Optimise processing methods, with a focus on washed/wet processing.
- Source beans from regions known for high-quality coffee.
- Strengthen quality control to reduce Category Two defects.
- Focus on aroma, flavour, acidity and body to improve total cup points.
