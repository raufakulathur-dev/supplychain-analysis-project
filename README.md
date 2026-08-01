# $${\color{green}SUPPLY \space CHAIN \space DELIVERY \space PERFORMANCE \space REPORT}$$

## $${\color{green}\text{End-to-End Order Fulfillment Analysis}}$$

## $${\color{blue}\text{1. Executive Summary}}$$

  This report presents a comprehensive analysis of the delivery operations of a global e-commerce company managing end-to-end order fulfillment across multiple regions. The analysis covers 172,765 orders spanning January 2015 through January 2018, focusing on identifying root causes of chronic late deliveries, quantifying their financial impact, and establishing a data-driven framework for improvement.
  The headline finding is stark: 54.71% of all orders are delivered late, costing the business $2.1M in eroded profitability on delayed orders alone. While total profit across fulfilled orders reached $7.5M, the persistent late-delivery problem represents both a significant financial drain and a major customer experience risk.

<img width="1506" height="597" alt="Screenshot 2026-08-01 121926" src="https://github.com/user-attachments/assets/7384e689-1c99-4b8b-ba6d-8788380d8308" />


## $${\color{blue}\text{2. Business Context and Objectives}}$$

  The company operates a global e-commerce platform selling products across categories including sporting goods, fitness equipment, outdoor gear, footwear, and apparel across multiple international regions.

## $${\color{lightblue}\text{Core Business Problem}}$$

  Actual shipping times frequently deviate from scheduled delivery windows, creating eroded customer trust, reduced order profitability, and an inability to make reliable commitments to buyers at point of purchase.

## $${\color{lightblue}\text{Analytical Objectives}}$$

  •	Understand the current state of delivery performance across all dimensions (region, mode, time, segment)
  •	Quantify the financial impact of delays on order profitability
  •	Identify the primary operational bottlenecks driving late deliveries
  •	Build a predictive model to flag high-risk orders before they are shipped
  •	Deliver actionable recommendations to improve on-time delivery and profitability

## $${\color{blue}\text{3. Key Performance Indicators (KPIs)}}$$

  The following KPIs were computed directly from the cleaned dataset to establish a performance baseline.

  <img width="1643" height="607" alt="Screenshot 2026-08-01 134719" src="https://github.com/user-attachments/assets/e39e2ff5-d9dc-408c-b4a8-60868429a06a" />

  <img width="1594" height="914" alt="Screenshot 2026-08-01 135056" src="https://github.com/user-attachments/assets/bfbb6688-a002-4c85-9e7a-44974bc0ee69" />


## $${\color{blue}\text{4. Profitability Analysis}}$$

## $${\color{lightblue}\text{4.1 Profitability Distribution}}$$

  Order-level profitability was classified into three tiers based on Order Profit Per Order. While 80.7% of orders are profitable, the 18.7% loss-making share represents a meaningful drag that is disproportionately concentrated among delayed shipments.

  <img width="959" height="710" alt="Screenshot 2026-08-01 135232" src="https://github.com/user-attachments/assets/3d94a06f-1347-4e73-994a-04cba373741d" />

## $${\color{lightblue}\text{4.2 Delay Distribution & Profit vs. Delay Days}}$$

  The delay distribution shows that 31.0% of all orders arrive exactly 1 day late the single largest cohort. combined, orders delayed by 1-4 days account for 54.7% of all order volume, directly mapping to the overall late delivery rate.

  <img width="1577" height="610" alt="Screenshot 2026-08-01 135445" src="https://github.com/user-attachments/assets/61548237-63b3-4342-9903-5ba1a685cf79" />

  A critical observation: mean profit per order remains stable at approximately $21-$23 across all delay levels. The profitability problem is therefore driven by volume of delayed orders, not by individual order economics making systemic throughput improvement the highest-leverage intervention.

## $${\color{blue}\text{5. Bottleneck Detection}}$$

  Delay percentage was computed across six key operational dimensions. The charts below reveal where the fulfilment process breaks down most severely

  <img width="1483" height="418" alt="Screenshot 2026-08-01 135740" src="https://github.com/user-attachments/assets/4f21625d-7b35-4fee-a143-bbfa177c4e66" />

  <img width="1560" height="499" alt="Screenshot 2026-08-01 135821" src="https://github.com/user-attachments/assets/9e83a1dc-13bb-4632-9c08-1592ebe18e9b" />

  <img width="1507" height="828" alt="Screenshot 2026-08-01 135902" src="https://github.com/user-attachments/assets/5c3133fc-28ea-4306-a717-d6a1b3af9e23" />

## $${\color{blue}\text{6. Root Cause Analysis}}$$

  Central Africa was selected for deep-dive root cause analysis as the highest-delay region (58.7%). The chart below ranks the top 10 driver factors by delay percentage within this region.

  <img width="1459" height="789" alt="Screenshot 2026-08-01 140044" src="https://github.com/user-attachments/assets/6ea24c88-4ee3-45b9-8813-ca8e83e7963e" />

## $${\color{blue}\text{7. Time-Based Delay Patterns}}$$

  Three temporal dimensions were analyzed: month of year, day of week, and hour of day. While delay rates are relatively stable across all dimensions (53-57%), specific peaks highlight opportunities for targeted capacity planning.

  <img width="1459" height="789" alt="Screenshot 2026-08-01 140044" src="https://github.com/user-attachments/assets/962c1f50-6884-42c2-b0bb-442d24cdc676" />

## $${\color{blue}\text{8. Strategic Recommendations}}$$  

Based on the findings across all analytical dimensions, the following prioritized actions are recommended:

<img width="1059" height="1290" alt="Screenshot 2026-08-01 140430" src="https://github.com/user-attachments/assets/dfe6edc6-9d38-45e5-abc1-a8719f4b4f80" />

## $${\color{blue}\text{9. Conclusion}}$$ 

  This analysis has surfaced a clear and urgent picture: a global e-commerce operation where the majority of orders (54.71%) fail to meet their promised delivery windows, costing $2.1M in at-risk profit and undermining customer trust at scale.
  The root causes are identifiable and addressable. Shipping mode misconfiguration (First Class at 100% late, Second Class at 79.8%) is the dominant operational failure. Payment processing friction creates a secondary bottleneck. Seasonal volume spikes are not adequately planned for. And geographic disparities, while present, are secondary to the systemic company-wide pattern.

  <img width="1062" height="306" alt="Screenshot 2026-08-01 140644" src="https://github.com/user-attachments/assets/6be47244-141e-449d-a178-b0916613fa8b" />













