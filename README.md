# 🥔 Quantium Chips Analysis

**Author:** Priyanshi Singh  
**Date:** June 2025

This project analyzes customer purchasing behavior for chips using real-world retail data provided by Quantium. The insights support data-driven decision-making for category managers to target the most valuable customer segments effectively.

---

## 📊 Project Overview

We explore and analyze:
- 💰 Which customer segments purchase the most chips
- 🧮 How much they spend and their average price per unit
- 🏷️ Preferred chip brands per segment
- 📦 Most popular pack sizes across different customer groups

---

## 📁 Folder Structure

Quantium_Chips_Project/

│

├── data/ # Raw input datasets (CSV files)

│ ├── QVI_purchase_behaviour.csv

│ └── QVI_transaction_data.csv

│

├── scripts/ # Main RMarkdown scripts and outputs

│ ├── R_solution_template.Rmd

│ ├── R_solution_template.html/pdf

│ ├── output/

│ ├── cleaned_data.csv

│ ├── segment_summary.csv

│ └── pack_size_summary.csv

│

├── chips_trial_analysis/ # Optional R project environment files

├── README.md # ✅ This file

├── .gitignore


---

## 🛠️ Technologies Used

- **Language:** R  
- **Libraries:** `tidyverse`, `dplyr`, `readr`, `ggplot2`, `lubridate`
- **Tools:** RStudio, Git, GitHub

---

## 📈 Key Insights

- 🧍‍♂️ *Older Families (Budget)* and *Young Singles/Couples (Mainstream)* are the highest-spending segments.
- 🏆 **Top brands** include: Kettle, Smiths, Doritos, and Pringles.
- 📦 **175g** pack size is the most popular among almost all segments.
- 🎯 Premium segments pay more per chip, indicating potential for upselling larger pack sizes or premium brands.

---

## 🚀 How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/spriyanshi180/Quantium-Chips-Analysis.git
Open RStudio and load the .Rproj file or directly open:

scripts/R_solution_template.Rmd
Run each code chunk or knit the file to HTML/PDF to generate the output visualizations and data summaries.

📎 Output Files

File	Description

-segment_summary.csv	: Summary of total sales and average prices by customer segment

-pack_size_summary.csv  :	Chip sales by pack size per segment

-cleaned_data.csv	:  Merged and cleaned transaction-customer dataset

-top_brands_per_segment.pdf	 :  Visualization of top 3 brands for each segment

-pack_size_plot.pdf	:  Line chart of pack size preferences

💡 Recommendations

-📣 Focus marketing on Young Singles/Couples and Budget Older Families.

-📦 Promote 175g pack sizes for mainstream and budget segments.

-🛍️ Offer premium brand bundles to high-spending segments.

-📨 Use loyalty programs to target top-performing segments with personalized offers.


🤝 Acknowledgements

This project is based on Quantium's retail data challenge, offering real-world data analytics experience in consumer insights.

📬 Contact

Priyanshi Singh
GitHub: spriyanshi180


---

✅ **Next Step:**  
- Save this as `README.md` in your project folder.
- Then run:

```bash
git add README.md
git commit -m "Add project README.md"
git push
## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/spriyanshi180/Quantium-Chips-Analysis.git
