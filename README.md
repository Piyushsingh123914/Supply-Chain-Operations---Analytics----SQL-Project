## Questions

## Basic

* Summarise the supplier base: total suppliers and the average, minimum and maximum lead time, plus average reliability score. (Q1)
* Count suppliers by country, with average lead time and reliability, sorted by number of suppliers. (Q1b)
* Classify suppliers into High, Medium and Low reliability using `CASE`, and count the suppliers in each class. (Q4)
* Analyse each warehouse: suppliers served, product lines received and total inbound quantity. (Q3)
* Analyse purchase orders per supplier: number of orders, total quantity, average order quantity and total value (cancelled orders excluded). (Q5)
* Analyse inventory movement by warehouse and movement type (received, partial, open). (Q11)
* Identify the warehouses with the highest overall movement volume. (Q11b)
* Calculate the overall supply chain KPIs: total orders, quantity, order value, average lead time, on-time %, average days late and fill rate. (Q20e)

## Advanced

* Identify the suppliers with above-average order volume, using a subquery. (Q14)
* Count how many suppliers are above the average order volume. (Q14b)
* Identify the high-risk suppliers: reliability below average and lead time above average. (Q15)
* Count the high-risk suppliers. (Q15b)
* Identify the warehouses with above-average movement and how far each is from the average, using a subquery in `HAVING`. (Q12)
* Flag the suppliers with high volume and low reliability. (Q6)
* Classify the suppliers as Fast & Reliable, Fast but Less Reliable, Slow but Reliable or Slow & Less Reliable using `CASE`. (Q8)
* Count the suppliers in each lead-time class. (Q8b)
* Calculate the order-status mix: orders, % of orders, quantity ordered and quantity received for each status. (Q20d)
* Calculate how much purchase volume sits with the high-volume, low-reliability suppliers, using a CTE. (Q6b)
* Build a supplier performance summary with a priority class (High Priority, Monitor, Stable), using CTEs. (Q16)
* Count the suppliers in each priority class. (Q16b)
* Rank suppliers within each country and show the top 3, using `RANK()` with `PARTITION BY`. (Q18)
* Compare warehouses within their region against the regional average, using window functions. (Q19)
* Calculate the share of total volume held by the top 25 suppliers (the top 10%). (Q20c)
* Build a supply chain performance report with fill rate, cancel and open-order %, rank in country, supplier class and a management attention flag. (Q20)
* Summarise the supplier classes and the management-attention flags: suppliers, volume and % of volume. (Q20b)
