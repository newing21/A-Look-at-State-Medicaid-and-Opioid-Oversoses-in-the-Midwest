# A-Look-at-State-Medicaid-and-Opioid-Oversoses-in-the-Midwest
R Programming Capstone Project - University of Iowa

---

### Project Overview

Millions of Americans suffer from unmanaged pain and are often prescribed opioids to treat their conditions. However, the dangers of prescription misuse, opioid use disorder, and overdose have been a growing problem throughout the United States for decades. We will analyze the number of opioids, synthetic opioids, and methadone overdose deaths in 2018 to find out which midwestern states have the highest (lowest) number of deaths due to opioids overdose. In addition, we hope to further examine the state with the largest number of opioid related deaths, discovering how funding and Medicaid expenses contribute (or attempt to curb) to the growing epidemic.


### Data Description 

The number of drug overdose deaths data is publicly available from Center for Disease Control and Prevention website (https://www.cdc.gov/nchs/nvss/vsrr/drug-overdose-data.htm), in the form of one Excel spreadsheet. This spreadsheet includes basic variables such as state, year, month, drug name, the actual number of deaths, and the predicted number of deaths. Other variables that we are not interested in were eliminated from the datasets. We read this “csv” file into data frames, cleaned, and extracted relevant data for analysis. To analyze state funding, we extracted data from (http://statehealthcompare.shadac.org/Data). This information enabled us to draw on financial statistics between the Midwestern states. Similar to the data on drug overdose deaths, the data on Medicaid funding was loaded into R as a “csv” file and merged using a for loop. Additionally, Medicaid prescription drug claims data was used to analyze Medicaid’s role (or lack thereof) in the opioid crisis (https://www.medicaid.gov/medicaid/prescription-drugs/state-drug-utilization-data/index.html).

### Results

![Screenshot (315)](https://user-images.githubusercontent.com/54378394/99928931-81774e00-2d08-11eb-80c8-4bdc13e6c0d9.png)


![medicaid_state_budget](https://user-images.githubusercontent.com/54378394/99928861-36f5d180-2d08-11eb-982d-ac8a75ac49ab.png)



### Final Report

[Final Report](https://github.com/newing21/A-Look-at-State-Medicaid-and-Opioid-Oversoses-in-the-Midwest/blob/main/R_Project.pdf)
