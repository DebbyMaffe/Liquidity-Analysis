# Liquidity-Analysis

**Liquidity Profile of Euro Area Large Banks** (2018-2022) by using regulatory indicators.

The dataset is downloaded from the **BankFocus** database. The majority of *data_object* dataset consists of continuous attributes (about 83.33%), representing the annual liquidity ratios and the total assets collected from 2018 to 2022. The remaining features (about 16.67%) refer to:
*   ***Company*** name in Latin alphabet;
*   ***Country*** in the Euro Area, where company is domiciled;
*   ***Consolidation code***, the attribute used to group similar object levels into categories for reporting.

Since we need to estimate the liquidity profile of Euro Area ***large*** *banks*, we notice that the banks presenting the consolidated accounts with an unconsolidated companion, show the *greatest* results in the ***size*** assessment. For this reason, we decide to filter our data by considering the **C2** Consolidation Code.

Let's proceed by considering the regulatory indicators:
1. The **NSFR** (Net Stable Funding Ratio) establishes a minimum acceptable amount of *medium-long* term funding in front of the banks' assets and activities. It aims to *limit* over-reliance on short-term wholesale funding during times of buoyant market liquidity and encourage better *assessment* of liquidity risk across all on- and off-balance sheet items.
2. The **LCR** (Liquidity Coverage Ratio) refers to the proportion of *highly liquid* assets held by financial institutions, to ensure their ongoing ability to meet *short-term* obligations. It aims to ensure that a bank maintains an adeguate level of *unecumbered*, high-quality liquid assets that can be converted into cash to meet ist liquidity needs for **30** calendar **days** time horizon. 
