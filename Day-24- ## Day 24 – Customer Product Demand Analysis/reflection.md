## Day 24 – Customer Product Demand Analysis

![](https://github.com/omolola-A/120-days-data-analytics-journey/blob/main/Day_24.png)

Today I spent time reviewing the Customer Product Demand dashboard and digging deeper into the operational story behind the numbers.

At first glance, the Berkeley warehouse appears to be the top performer, generating 74% of total revenue. However, when I analyzed the Order Demand (units moved), the picture changed.

The Cedar Park warehouse handles 72% of total unit volume, yet it only contributes 14% of the revenue. This suggests a potential pricing or operational imbalance where high-volume fulfillment does not translate into proportional revenue.

To better understand ordering behavior across the day, I moved beyond simple visualizations and created a custom Sort Index using DAX. This allowed the demand timeline to follow a logical sequence:

Morning → Afternoon → Evening Surge → Overnight

With this structure, a clear pattern emerged: about 70% of orders occur between 5 PM and 11 PM. If warehouse operations follow a traditional 9–5 staffing model, this could mean many orders sit unprocessed for extended periods before fulfillment begins.

Key Observations

* Berkeley generates 74% of revenue, creating a heavy dependence on a single hub.

* Cedar Park processes 72% of unit demand, indicating a high operational workload with relatively low revenue return.

* A significant evening order surge (5 PM – 11 PM) suggests possible misalignment between customer demand and warehouse staffing hours.

Reflection

This stage of the project reinforced that the goal of analysis is not just to build dashboards, but to uncover operational patterns that may be limiting business efficiency.
