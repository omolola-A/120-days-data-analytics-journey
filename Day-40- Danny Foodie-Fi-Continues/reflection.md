**Day 40/120 of my Data Analytics Challenge**

![](https://github.com/omolola-A/120-days-data-analytics-journey/blob/main/Day-40.png)

How do you actually model payments for a subscription business?

Today I worked on the payments section of the Foodie-Fi case study, and this was easily one of the most challenging parts so far.

The task was to create a new payments table for 2020, but with real-world conditions:

* Monthly payments must follow the customer’s original billing date
* Upgrades within a month must account for what has already been paid
* Annual upgrades only start at the end of the current billing cycle
* Once a customer churns, payments stop completely

This wasn’t just querying data—it was building logic that mimics how a real billing system works.

I had to do a lot of research and ended up using approaches like **WITH RECURSIVE**, **COALESCE**,**UNION ALL** and **DATE_ADD** to handle the time-based logic and transitions between plans.

There were moments where my queries returned results, but I wasn’t fully confident they were correct. That forced me to slow down, test assumptions, and rethink parts of the logic.

This felt like a different level of SQL—less about pulling data, more about modeling how a business actually operates.

Still not 100% confident in my approach, so I’ll revisit it and try to simplify where possible.

Next step: validate the output more carefully and see if there’s a cleaner way to structure the logic.
