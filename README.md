# Liquidity-Analysis

**Liquidity Profile of Euro Area Large Banks** (2018-2022) - University Group Project

## 01. INTRODUCTION
**DATA SOURCE**

The dataset is downloaded from the **BankFocus** database. The majority of *data_object* dataset consists of continuous attributes (about 83.33%), representing the annual liquidity ratios and the total assets collected from 2018 to 2022. The remaining features (about 16.67%) refer to the **company** name, the **country** where company is domiciled (Euro Area), and the **consolidation code** used to group similar object levels into categories for reporting.

Since we need to estimate the *liquidity* profile of Euro Area **large banks**, we notice that the banks presenting the consolidated accounts with an unconsolidated companion, show the *greatest* results in the **size** assessment. For this reason, we decide to filter our data by considering the **C2** Consolidation Code.

**REGULATORY INDICATORS**

To estimate the liquidity profile of Euro Area large banks, let's consider the following regulatory indicators:
1. The **NSFR** (Net Stable Funding Ratio) establishes a minimum acceptable amount of *medium-long* term funding in front of the banks' assets and activities. It aims to *limit* over-reliance on short-term wholesale funding during times of buoyant market liquidity and encourage better *assessment* of liquidity risk across all on- and off-balance sheet items.
2. The **LCR** (Liquidity Coverage Ratio) refers to the proportion of *highly liquid* assets held by financial institutions, to ensure their ongoing ability to meet *short-term* obligations. It aims to ensure that a bank maintains an adeguate level of *unecumbered*, high-quality liquid assets that can be converted into cash to meet ist liquidity needs for **30** calendar **days** time horizon. 

## 02. NSFR ANALYSIS
Discussing the Net Stable Funding Ratio (NSFR) behavior, despite missing values for 2018-2020, the average for *2018-2022* is **above** the regulatory minimum of 100%, with minimal variation. A year-to-year analysis revealed that in 2019, *two banks* (Credit Agricole and Landesbank Hessen-Thuringen Girozentrale) had NSFR **below** 100%. However, in *2020*, **all** banks exceeded the regulatory minimum. In 2021, there was a **decrease** in NSFR, likely due to *pandemic* effects on securing long-term funding. Similar trends were observed in 2022, indicating a potential decrease in funding with maturity over one year, yet all banks met regulatory requirements.

## 03. LCR ANALYSIS
Analyzing the Liquidity Coverage Ratio (LCR), we found that **63** out of **109** banks had complete LCR data for 2018-2021. The average LCR appeared high, prompting a more detailed year-to-year analysis. A forthcoming country analysis will complement the liquidity profile assessment. 

The LCR was introduced in **2018**, and the majority of the sample *complied*, except for Greek bank PIRAEUS FINANCIAL HOLDINGS SA with 62.0%. After removing *outliers*, the mean value **exceeded** the regulatory *minimum* by 1.5 times. A similar pattern was observed in 2019, with one Greek bank at 97.0% and reduced variability after removing outliers. From *2020* to *2022*, results remained consistent, and **all** banks met regulatory requirements. 

## 04. G-SIB banks
In this section of the analysis, we performed a size analysis by categorizing *large banks* into **eight** buckets based on their total *assets*, following ECB supervision criteria. Notably, banks with total assets **over** *150 billion* tend to show a **lower** average Liquidity Coverage Ratio *(LCR)*. This observation is supported by boxplots, indicating that **larger** banks exhibit a **wider** variation in LCR. The analysis of G-SIB banks in the euro area for 2020 and 2021 also confirms this trend, suggesting potential reasons such as the liquidity characteristics of large banks' assets and their complex liquidity needs.

Additionally, a general *country* analysis was conducted, comparing LCR data for countries in the sample with the euro area averages. Despite differences in scale due to data availability, some banks in the sample represent the average for their respective countries. The mean LCR values for the sample tend to be higher than the country averages, with exceptions like the Netherlands, where the sample's average exceeds the country's mean value.

## 05. CONCLUSION
While there are few exceptions with lower than regulatory minimum values for LCR and NSFR ratios, emphasizing the importance of maintaining *liquidity buffers* is crucial due to liquidity **risk** and potential **insolvency**. Despite the effectiveness of the regulatory minimum of 100% from 2018-2022, historical data from the Basel Committee's Quantitative Impact Study in 2013 revealed that prior to regulatory measures, some banks had lower LCR values. 

Examining the average LCR and NSFR for the **28** banks with data for the entire period, representing their full regulatory liquidity profile, demonstrates that these *large banks* not only **meet** but significantly **exceed** regulatory minimums. This highlights the positive evolution of liquidity management within the sample over time.
