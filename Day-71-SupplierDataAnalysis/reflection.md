## Day 71/120 – From One Table to a Data Model

Today I started the Power BI part of the challenge, working with a supplier dataset that initially came as a single, wide table.

At first, it looked convenient—everything in one place. But it quickly became clear that it wasn’t structured for analysis.

I worked on breaking it down by separating dimension fields (category, plants, vendors, materials, defects) from the core values. This meant creating multiple tables and then cleaning and merging where necessary.

After that, I built a date table and set up relationships across all tables, which eventually formed a star schema.

I also created separate measure tables for defect reports, downtime, and defect quantity to organize the calculations I’ll need later.

This part felt more like structuring the foundation than doing analysis. A few relationship issues came up along the way, and I had to adjust things to make sure the model behaved correctly.

It’s interesting how much work happens before any dashboard is even built.

![](https://github.com/omolola-A/120-days-data-analytics-journey/blob/main/Day_71.png)

Next step: start building visuals and see if this structure actually holds up.
