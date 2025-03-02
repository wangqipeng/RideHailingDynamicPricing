# RideHailingDynamicPricing
Surge pricing is a dynamic pricing strategy used by ride-hailing platforms to balance supply (drivers available) and demand (riders requesting rides). When demand exceeds supply, prices are increased to encourage more drivers to enter the system while discouraging non-urgent ride requests. This helps ensure that ride availability is optimized, reducing long wait times.

However, surge pricing can also lead to several challenges:

Customer Dissatisfaction: Riders often feel frustrated when prices suddenly spike, especially during peak hours or emergencies.
Driver Dependency on Surge: Some drivers may only operate during surge pricing periods, leading to inconsistent availability.
Fairness and Transparency Issues: If the pricing model is not transparent, users may perceive it as unfair or exploitative.

To address these challenges, a well-structured surge pricing algorithm considers multiple factors beyond just demand and supply. The approach implemented in this dataset leverages:

Demand-Supply Ratio: If more riders are requesting rides than drivers are available, the price increases.
Time of Booking: Night and evening rides are priced higher due to increased demand and lower driver availability.
Location Category: Urban areas typically have higher demand fluctuations, so surge pricing is adjusted accordingly.
Vehicle Type: Premium rides have a higher base fare and can also be subject to increased surge pricing.
Customer Loyalty Status: Regular customers receive slight discounts to maintain long-term engagement.
By incorporating these factors, the surge pricing model ensures:

Fairer pricing for riders based on real-time conditions.
Incentives for drivers to participate in high-demand periods.
Better ride availability by encouraging demand elasticity.
