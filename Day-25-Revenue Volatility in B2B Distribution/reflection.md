**When Volume Lies: What a Product Demand Dataset Revealed About Revenue Risk**

As part of my **120-day Data Analytics challenge**, I’ve been working through projects designed to simulate the type of thinking expected from a **Junior Business Intelligence Analyst**.

Recently, I analyzed a **B2B distribution dataset** from a company that sells productivity tools and business intelligence solutions to enterprise clients across the United States. The company operates a **multi-warehouse distribution model**, delivering hardware devices, installation kits, and training materials to customers across different regions.

Leadership had been dealing with several concerns:

* Month-over-month revenue volatility
* Unpredictable demand across warehouses and regions
* Uncertainty around inventory planning and warehouse utilization
* Limited clarity on which products and locations were truly driving performance

The goal of the analysis was simple in theory: **understand what is happening, why it is happening, and what the business should consider doing next.**

But once I started exploring the data, the story became more interesting.

---

### Looking Beyond the Surface

The dataset included order records with product categories, warehouse fulfillment locations, customer ZIP codes, timestamps, unit demand, and transaction values.

After cleaning and structuring the data, I built a dashboard to examine several core metrics:

* Revenue performance
* Order volume
* Product demand
* Warehouse utilization
* Time-based ordering patterns

At first glance, the **Berkeley warehouse** appeared to be the company’s top performer. It generated roughly **74% of total revenue**, making it look like the primary engine of the business.

But when I examined the **physical workload**, the narrative changed.

The **Cedar Park warehouse** was responsible for **about 72% of total unit demand** — meaning most of the physical product movement was happening there.

Yet Cedar Park only accounted for **around 14% of revenue**.

In other words, the warehouse doing the majority of the work was generating a relatively small portion of the money.

This raised an important question: **Is the business scaling volume, or just scaling costs?**

---

### A Hidden Operational Pattern

Another pattern appeared when I analyzed the **order timestamps**.

When the day was broken into time segments, demand wasn’t evenly distributed across the workday. In fact, **about 70% of orders occurred between 5 PM and 11 PM**.

That suggests that a significant portion of customer activity happens **outside traditional working hours**.

If warehouse operations follow a typical **9-to-5 staffing schedule**, this could create delays between when orders arrive and when fulfillment begins. Those delays can affect customer experience, operational efficiency, and ultimately revenue.

---

### What the Data Suggests

While this dataset cannot answer every operational question, a few potential business considerations emerge:

**1. Revenue concentration risk**

With **74% of revenue tied to a single warehouse**, the business may be vulnerable to localized disruptions. Expanding fulfillment capacity across additional hubs could reduce that risk.

**2. Pricing structure review**

If high-volume locations generate low revenue relative to workload, it may indicate a pricing structure that does not properly capture value for large orders.

**3. Operational alignment with demand**

If most orders arrive in the evening, warehouse staffing and fulfillment schedules may need to adapt to match real customer behavior.

---

### The Limits of the Data

Like most real-world datasets, this one has limitations.

For example, it does not include:

* Product cost data
* Shipping costs
* Inventory levels
* Customer segments

Without those variables, it is difficult to fully explain margin behavior or profitability at a deeper level.

This is a good reminder that **data analysis often reveals the next set of questions rather than the final answers.**

---

### A Personal Reflection

This project reinforced something I’m learning repeatedly throughout this challenge:

**The goal of analytics is not to build dashboards. The goal is to uncover how a business actually operates.**

Sometimes the most valuable insight isn’t the chart itself — it’s the moment you realize that the part of the organization doing the most work may not be the part generating the most value.

And those are the questions that lead to better decisions.
