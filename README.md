# Nobel Prize Data Analysis Project

This project explores the Nobel Prize dataset provided by the Nobel
Foundation API, covering all laureates from **1901 to 2023**.\
The dataset is stored in the `nobel.csv` file.

## 📌 Project Overview

The Nobel Prize is one of the most prestigious international awards,
given each year in categories including: - Chemistry - Literature -
Physics - Physiology or Medicine - Economics - Peace

The project involves answering key analytical questions about Nobel
Prize laureates using **Python (pandas, seaborn, matplotlib, numpy)**.

## 🛠️ Libraries Used

-   pandas
-   numpy
-   seaborn
-   matplotlib

## 📊 Analysis & Findings

### 1. Most Commonly Awarded Gender and Birth Country

We analyzed the dataset to determine which gender and which birth
country have received the most Nobel Prizes.

-   **Top Gender**: Male
-   **Top Country**: United States of America

We also plotted a count plot of male vs female Nobel laureates.

### 2. Decade with Highest Ratio of US-born Laureates

We calculated, for each decade, the ratio of US-born Nobel laureates to
the total number of laureates.
- **Result**: The decade with the highest ratio is stored in
`max_decade_usa`.

### 3. Decade & Category with Highest Proportion of Female Laureates

We explored which **decade-category** combination had the highest
proportion of female laureates.
- **Result**: Stored in a dictionary `max_female_dict` with decade as
the key and category as the value.

### 4. First Woman Nobel Laureate

We identified the first woman to receive a Nobel Prize, along with the
category.
- **Result**: `first_woman_name` and `first_woman_category`
- Example: *Marie Curie, Physics*

### 5. Multiple Nobel Prize Winners

We checked which individuals or organizations have won more than one
Nobel Prize.
- **Result**: Stored in a list `repeat_list`.

## 📁 Dataset Columns

The `nobel.csv` dataset includes the following columns:

-   `year`
-   `category`
-   `prize`
-   `motivation`
-   `prize_share`
-   `laureate_id`
-   `laureate_type`
-   `full_name`
-   `birth_date`
-   `birth_city`
-   `birth_country`
-   `sex`
-   `organization_name`
-   `organization_city`
-   `organization_country`
-   `death_date`
-   `death_city`
-   `death_country`

## 🚀 How to Run

1.  Clone this repository.
2.  Place the `nobel.csv` dataset inside the `data` folder.
3.  Run the Python script to reproduce the results.

``` bash
python nobel_analysis.py
```

## 📌 Conclusion

This project highlights trends in Nobel Prize awards, gender
disparities, country dominance, and recurring winners.
Future extensions can include deeper visualizations, geographic
distributions, or temporal trends by category.
