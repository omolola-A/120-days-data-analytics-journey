### Day 39/120 – What Happens After the Free Trial?

![](https://github.com/omolola-A/120-days-data-analytics-journey/blob/main/Day39.png)

After a short break, I resumed the challenge today with the Foodie-Fi case study—a subscription-based business—and started by trying to understand how customers actually move through the product.

The first step was simple on the surface: track the “flow” of a few sample customers. But even that revealed interesting patterns. Every customer starts with a trial, but what happens next varies. Some move to basic plans, some upgrade to pro, and others drop off early. Even within a small sample, the journeys were not the same.

Moving into the full dataset (1000 customers), the picture became clearer—and a bit more complex.

A few things stood out:

* About 30.7% of customers churn overall
* Around 9% churn immediately after the free trial
* The basic plan has the highest conversion rate (~54.6%)
* Pro monthly follows (~32.5%), while annual plans are much lower (~3.7%)
* On average, it takes about 105 days for a customer to move to an annual plan
* Interestingly, no customers downgraded from pro monthly to basic monthly in 2020

Working through this required more than basic SQL. I had to use JOINs, COUNT(DISTINCT), DATEDIFF, CASE logic for grouping, and LEAD() window functions to track customer movement over time.

The challenging part wasn’t just writing the queries—it was understanding how to model customer journeys step by step, especially when dealing with time differences and transitions between plans.

This felt like a shift from analyzing static data to analyzing behavior over time.

Next step: continue exploring the remaining sections and see what other patterns show up in customer behavior.
