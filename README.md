# Gold Trade Analysis (2017-2023): Zambia and Democratic Republic of Congo

## Project Overview

This project focuses on a comprehensive analysis of the gold trade between Zambia, the Democratic Republic of Congo (DRC), and major global partners from 2017 to 2023. Specifically, it examines the trends in gold export values and volumes, the geopolitical factors that influenced the trade, and the impact of key economic events on gold trading patterns. The gold trade's impact on BRICS countries (Brazil, Russia, India, China, South Africa) is analyzed in comparison with the trade to other major economic regions such as the UK, USA, and EU. The project aims to assess both the direct and indirect influences of geopolitical events on the gold trade within this time frame.

## Contents

1. [Background Research](#background-research)
2. [Argument](#argument)
3. [Objectives](#objectives)
   - [General Objectives](#general-objectives)
   - [Questionnaire](#questionnaire)
4. [Methodology](#methodology)
   - [Data Wrangling](#data-wrangling)
   - [Simplifying the Dataset](#simplifying-the-dataset)
   - [Column Description and Reasoning for Removal](#column-description-and-reasoning-for-removal)
5. [Data Mining](#data-mining)
6. [Research on Geopolitical Aspects](#research-on-geopolitical-aspects)
   - [Zambia Geopolitical Research (2017-2023)](#zambia-geopolitical-research-2017-2023)
   - [Challenges of Zambia's Mining Sector](#challenges-of-zambias-mining-sector)
   - [DRC Geopolitical Research (2017-2023)](#democratic-republic-of-congo-geopolitical-research-2017-2023)
7. [References](#references)

## Background Research

BRICS (Brazil, Russia, India, China, and South Africa) represents a group of major emerging economies, accounting for over 40% of the global population and contributing about 24% to the global GDP. The group's primary objectives focus on enhancing economic development and fostering political cooperation. The BRICS strategy includes trade, investment, and infrastructure projects, supported by initiatives like the New Development Bank and the Contingent Reserve Arrangement. 

In recent years, BRICS countries have sought to diversify their economies, reduce reliance on Western markets, and increase their financial and political influence globally. Gold, as a major reserve asset, plays a key role in this strategy by enhancing economic resilience and providing a hedge against currency risks. 

This project seeks to analyze the gold trade activities of Zambia and the Democratic Republic of Congo, with a particular focus on their export patterns to BRICS countries, in comparison to the UK, USA, and EU. 

### Key Research Points:

- **Economic Impact:** The role of gold in driving economic stability and reflecting economic policies of BRICS countries.
- **Financial Health Indicators:** Gold reserves as indicators of financial stability.
- **Geopolitical Context:** Understanding responses to global political events and economic sanctions through gold trade analysis.

## Argument

BRICS countries have strategically accumulated gold reserves to reduce their dependency on Western markets, especially the US dollar. Countries like Russia and China have notably increased their gold reserves, positioning gold as a financial safeguard in times of geopolitical uncertainties. India and China, as two of the largest gold consumers globally, also utilize domestic demand to fuel the gold market. 

By increasing their gold reserves, BRICS nations aim to enhance economic resilience, hedge against currency risks, and strengthen their influence in the global financial system. In this context, sourcing materials from African nations like Zambia and the DRC further strengthens their geopolitical ties and cost-efficiency.

## Objectives

### General Objectives

The analysis of gold trading during 2017-2023 includes both general and specific objectives aimed at providing a detailed understanding of trade patterns and influences. The objectives include:

1. Analyze historical gold price trends and trading volumes.
2. Examine the correlation between gold trading and other financial instruments.
3. Assess the impact of geopolitical and economic events on gold prices and trade.

### Questionnaire

To meet the objectives, the following questions guided the research:

1. **What is the trend in trade value?**
   - **DRC:** The DRC’s trade value drastically dropped from $95.28 million in 2017 to $2.67 million in 2022, indicating a severe decline after 2020.
   - **Zambia:** Zambia’s trade value experienced a consistent downturn from $95.28 million in 2017 to $45.68 million in 2023.

2. **What is the volume of trade?**
   - **DRC:** Trade volume peaked in 2018 at 178.3 million units but significantly dropped to just 5.3 million units by 2022.
   - **Zambia:** The volume of trade dropped from 190.6 million units in 2017 to 91.4 million units in 2023.

3. **Were there years where trade volume was significantly higher or lower than average?**
   - **DRC:** Higher volumes were noted in 2018 and 2019 but sharply decreased post-2020.
   - **Zambia:** 2017 showed the highest volume, but from 2018 onwards, trade plummeted with a steep decline during 2020-2021.

4. **What was the trend in the number of trades?**
   - **Zambia:** The number of trades steadily increased from 22 trades in 2017 to 29 in 2023.
   - **DRC:** The DRC saw a fluctuating trend, peaking in 2019 with 44 trades but dropping to 26 trades by 2022.

5. **How does the trade volume to BRICS compare to the UK, USA, and EU?**
   - Trade volume to BRICS countries consistently outpaced that with the UK, USA, and EU. For example, Zambia’s trade with BRICS totaled $1.32 billion over the period, whereas trade with the USA was only $463,123 and with the EU, $234,840.

## Methodology

### Data Wrangling

For this analysis, data was sourced from the UN Comtrade database, focusing on annual gold exports from Zambia and the DRC between 2017-2023. Key steps included:

1. **Removing Unnecessary Columns**:
   - Removed redundant columns such as `TypeCode`, `FreqCode`, and `RefPeriodId` to simplify the dataset.
   
2. **Handling Missing and Estimated Data**:
   - Columns with significant missing or estimated data, such as `IsNetWgtEstimated`, were excluded to ensure data accuracy.

3. **Detail Level**:
   - The dataset was filtered to include only the most relevant data, focusing on specific years, commodity codes for gold (`7108`), trade volumes, and trading partners.

### Simplifying the Dataset

- **Duplicate or Similar Data**: Columns with duplicated information (e.g., `Cifvalue` vs. `Fobvalue`) were simplified by retaining only the necessary details for analysis.
- **Columns Removed**: Examples include `AltQtyUnitCode`, `AltQty`, `IsAggregate`, etc., which were irrelevant to the primary objectives of the research.

### Column Description and Reasoning for Removal

1. **TypeCode, FreqCode, RefPeriodId**:
   - Metadata columns not necessary for the analysis.
   
2. **GrossWgt, IsGrossWgtEstimated**:
   - Weight columns were irrelevant for a value-focused analysis of trade.
   
3. **Alternative Quantity Units**:
   - These columns were excluded because alternative unit information was not needed for the analysis of the main dataset.

## Data Mining

The research employed Excel to analyze and visualize the dataset, using techniques like pivot tables and time series visualizations to examine trends over the years. The focus areas included:

1. **Total Trade Value**: From Zambia and DRC to BRICS, USA, EU, and other regions.
2. **Year-by-Year Comparison**: Trade data from 2017-2023, showing fluctuations over time.
3. **Comparative Analysis**: BRICS versus Western markets, exploring how the volume of trade varied.

The data mining process helped reveal significant trends and insights, such as the clear preference for BRICS nations over Western partners in terms of trade volume and value.

## Research on Geopolitical Aspects

### Zambia Geopolitical Research (2017-2023)

**Key Events and Impacts**:

1. **2017**:
   - The Minamata Convention on Mercury came into force, affecting the small-scale mining sector by imposing stricter regulations.
   
2. **2018**:
   - New mining taxes and royalty reforms led to reduced production and trade protests by mining companies.
   
3. **2019**:
   - Illegal mining activities became more prominent, with significant gold smuggling operations impacting trade and revenue.
   
4. **2020-2021**:
   - The COVID-19 pandemic disrupted mining operations, further reducing gold output.
   
5. **2022-2023**:
   - Rising commodity prices due to the Russia-Ukraine conflict boosted Zambia's gold trade revenues.

### Challenges of Zambia's Mining Sector

Zambia’s mining industry faces several challenges:

1. **Mono-dependency on Copper**: The economy’s reliance on copper has stunted growth in other sectors like gold.
2. **Lack of Refining Infrastructure**: Gold is exported unrefined, complicating its valuation.
3. **Inconsistent Fiscal Policies**: Frequent changes in mining taxes discourage long-term investment.
