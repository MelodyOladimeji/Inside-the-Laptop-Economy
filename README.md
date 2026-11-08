# Inside-the-Laptop-Economy

![Laptop](Laptop.jpg)

## Executive Summary
This project answers the question: What does it actually cost to own a laptop based on its brand? It does this by analyzing data to benchmark price tiers, compare the cost-per-weight, and establish the average price for different system types.

## Business Context
The consumer electronics market is driven by complex pricing dynamics where hardware specifications such as RAM capacity, form factor, and system weight significantly impact retail valuation. This project examines these market dynamics to uncover how manufacturers price performance tiers and how form factor tradeoffs influence end-consumer cost.


## 🎯 Project Objectives

* **Benchmark Average Cost per Hardware Spec:** Analyze pricing scaling across RAM tiers, tracing average market costs.
* **Assess Device Category Valuation:** Evaluate average pricing across form factors, benchmarking entry-level 
* **Evaluate Brand Dominance:** Measure catalog volume distribution across major manufacturers, evaluating top-tier brand presence.
* **Quantify Weight vs. Inventory Distribution:** Correlate system weight ($kg$) with catalog volume, isolating key physical weight segments
* **Determine Price Tier Share:** Segment overall inventory into distinct cost bands, measuring the distribution across **Budget (13.64%)**, **Mid-Range (42.06%)**, and **Premium (44.30%)** market tiers.

## Data Overview
This dataset analyzes a total of 1,303 laptop configurations across key hardware specifications, brand categories, and price tiers to evaluate retail market pricing dynamics.
  
## Data Preview
 ![LaptopData](LaptopData.png)

## Data Cleaning and Transformation
* Removed duplicate entries to ensure data integrity.
* Formatted the dataset into a structured table for efficient querying.
* Standardized text entries and applied consistent numerical formatting (including comma separators across all price amounts).
  
  ## Detailed Findings & Analysis
  ### Key Performance Indicators
  * The overall average price of all systems sum up to a whopping total of $1,123
  * The total catalog for this data set under consideration is one thousand three hundred and three
  * **Most Common Brands:** Dell and Lenovo tied for the most prevalent, with 297 models each.

  ### Price Tier Per Ram Capacity
  Using Excel's `=IFS` formula, we split the market into three clear buckets:

* 🟣 **Budget (< $700) | 13.64%**  
  *The Wallet Savers.* Only a tiny slice of the market sits down here.
* 🔵 **Mid-Range ($700 – $1,500) | 42.06%**  
  *The Sweet Spot.* A chunk of all laptops fall under this category here, balancing solid performance with reasonable prices.
* 🟢 **Premium (> $1,500) | 44.30%**  
  *The Heavy Hitters.* The single biggest category! Power users, gamers, and workstations dominate the catalog landscape.

### Total Amount According to RAM Weight
Laptop prices reach their highest average at $3,975 for 64GB RAM. Notably, moving from 24GB to 32GB RAM creates a sharp $1,210 price spike, which is significantly larger than the price jump between any other RAM levels in the dataset.

### Total Valuation by System Weight
Catalog valuation is heavily clustered around specific mass density brackets:
* 2.2 kg: $84,950 total valuation (Dominant market)   
* 2.5 kg: $49,069 total valuation  
* 2.4 kg: $39,238 total valuation   
* 2.3 kg: $35,602 total valuation  
* 2.1 kg: $33,291 total valuation


### 🚀 Strategic Recommendations

Based on the market analysis, manufacturers and retailers should focus inventory strategies on the **Mid-Range ($700–$1,500)** and **Premium (> $1,500)** segments, which collectively make up **86.36%** of catalog volume.. Stocking strategy should heavily center around the **2.2 kg weight class**, as it represents the highest catalog valuation at **$84,950**

From a component pricing perspective, the **$1,210 price surge** between 24GB and 32GB RAM highlights a major transition into professional-grade computing, Retailers should market 32GB and 64GB configurations alongside high-end form factors like **Workstations ($2,280 avg)** and **Gaming systems ($1,731 avg)**, ensuring premium pricing is clearly backed by top-tier graphics, cooling, and processing capabilities

## Tools Used
Excel 

## Conclusion
This analysis reveals a laptop market centered on high-performance productivity, with Mid-Range and Premium tiers accounting for **86.36%** of inventory and a **2.2 kg** mass density driving **$84,950** in total catalog valuation. System pricing scales with form factor—peaking at **$2,280 for Workstations** while a key **$1,210 price surge** between 24GB and 32GB RAM marks the clear transition from consumer to enterprise hardware.
