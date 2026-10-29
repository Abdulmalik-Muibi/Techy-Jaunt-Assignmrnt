E-commerce Performance Dashboard (Power BI)

A Power BI dashboard that lets management monitor e-commerce business performance: revenue, orders, payment method distribution and monthly trend.

Business Problem

Management needs a single page to track how the business is performing and where to focus growth.

Dataset;

ecommerce_orders.csv  has 200 rows and the column titles are as follows; order_id, customer_id, product_name, quantity, price, total_amount, payment_method, order_date, delivery_city.

ecommerce_customers.csv has 200 rows and column titles are as follows; customer_id, name, email, phone, city, gender, signup_date
Period covered: 17 May 2025 to 14 May 2026 (May 2025 and May 2026 are partial months).

Dashboard Contents;

KPI cards: Total Revenue, Total Orders, Average Order Value(AOV),
Revenue by City,
Revenue by Category (product),
Monthly Revenue Trend,
Payment Method Distribution.

DAX Measures;

Total Revenue = SUM(orders[total_amount]),

Total Orders  = COUNT(orders[order_id]),

AOV = DIVIDE([Total Revenue], [Total Orders])

Key Insights;

Headline: Revenue of ₦11.34M,
200 orders,
AOV is ₦56.7K.

City:

Abuja total revenue is 2.34M, 37 orders and 63.11k AOV.

Port Harcourt total revenue is 2.22M, 36 orders and 61.67K AOV.

Lagos total revenue is 1.97M, 30 orders and AOV is 65.50k.

Ibadan total revenue is 1.28M, 31 orders and 41.13K AOV.

Kano total revenue is 1.12M, 23 orders and 48.70k AOV.


Category: 

Laptops (₦2.09M) and Keyboards (₦2.07M) are the top earners. Mice (₦1.19M) and Tablets (₦1.30M) are the weakest.

Trend: Revenue is volatile. Peaks came in Oct 2025 (₦1.42M), Aug 2025 (₦1.41M) and Mar 2026 (₦1.25M), with sharp dips in Jun 2025 (₦0.13M) and Nov 2025 (₦0.29M).

Payments: Orders are evenly split: PayPal 26.5%, Cash 25.5%, Card 24.5%, Transfer 23.5%.


Business Recommendations;


Fix data capture at checkout. Make delivery city and price required, and validate that orders cannot predate signup. About 15% of orders have no price and 21% have no city, which limits reliable reporting.

Focus on top cities and categories. Direct marketing and delivery capacity to Abuja, Port Harcourt and Lagos and to Laptops and Keyboards. Test bundles (for example a mouse with every laptop) to lift weak categories.

Grow repeat purchases and smooth the dips. Offer first-purchase deals to the 71 non-buyers and second-order incentives to one-time buyers, reward the top 20% with a loyalty tier, and run promotions ahead of the June and November slumps.

