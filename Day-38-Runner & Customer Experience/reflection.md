## Day 38/120 – Runner & Customer Experience (Pizza Runner Case Study)

![](https://github.com/omolola-A/120-days-data-analytics-journey/blob/main/Day_38.png)

Today I worked on the Runner and Customer Experience section of the Pizza Runner SQL case study, and this part was significantly more challenging than the earlier metrics.

Unlike the previous section, which focused more on counts and basic aggregations, this stage required deeper thinking around time-based calculations, performance metrics, and interpreting business questions correctly.

**What I worked on:**
* Runner sign-ups over weekly periods
* Average time taken for runners to pick up orders
* Relationship between number of pizzas and preparation time
* Average distance travelled per customer
* Delivery time comparisons (longest vs shortest)
* Average speed per runner per delivery
* Successful delivery percentage per runner

**What slowed me down:**

The difficulty here wasn’t just writing SQL queries—it was understanding the intent behind each question.

For example, calculating preparation time meant carefully defining:

* When an order was placed
* When it was picked up
* What counts as a valid or successful delivery

**There were also challenges around:**

* Handling time differences correctly
* Working with averages and percentages
* Making sure the filters didn’t distort the results

**I had to pause multiple times to rethink the logic before even writing the queries.**

**Key insight:**

* One interesting finding came from analyzing the relationship between the number of pizzas and preparation time.

* There is a clear positive relationship—orders with more pizzas generally take longer to prepare. For example, orders with 3 pizzas had the longest preparation times.

* However, the relationship is not perfectly linear. Some smaller orders took longer than expected, suggesting that other factors—like kitchen load, timing, or operational delays—may also influence preparation time.

This was a good reminder that:

* Data can show a trend, but it doesn’t always explain the full story.

**Reflection:**

This part felt like a shift from just “writing SQL” to actually thinking like an analyst—interpreting vague questions, defining metrics carefully, and being mindful of how assumptions affect results.

I’m not fully confident in all my approaches yet, especially around some of the calculations, so I plan to revisit and refine them.

Next step:

Review and optimize my queries, and then move on to the next section of the case study.
