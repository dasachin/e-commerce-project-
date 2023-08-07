This project focuses on verifying the charges levied by courier companies for delivering orders for a large e-commerce company in India (referred to as X). X receives thousands of orders daily, which need to be delivered quickly. To ensure cost accuracy, X has tied up with multiple courier companies. However, the high charges incurred by X prompted them to verify if the charges per order are correct.

Business Scenario X pays a significant amount to courier companies for deliveries, with charges dependent on the weight of the product and the distance between the warehouse (pickup location) and the customer's delivery address. On average, X pays approximately Rs. 100 per shipment. With a monthly volume of 1,00,000 orders, this amounts to nearly Rs. 1 crore in charges.

To ensure the accuracy of these charges, X needs to compare their internal data with the courier company's invoices. X's internal data comprises an order report listing Order IDs and the products (SKUs) included in each order, along with an SKU master providing the gross weight of each product.

Approach To verify the charges, the following steps are undertaken:

1.Calculating Total Weight per Order: Using the SKU master data, the total weight of each order is calculated by summing the weights of the individual products. This provides an accurate representation of the shipment's weight.

2.Determining Weight Slabs: The courier company calculates weight in slabs of 0.5 KG multiples. The total weight is rounded to the nearest 0.5 KG increment to determine the applicable weight slab. This step ensures consistency with the courier company's weight calculation methodology.

3.Comparing Weight Slabs: The weight slabs calculated internally by X are then compared with the weight slabs reported by the courier company in their CSV invoice for each corresponding Order ID. Discrepancies between the two can indicate potential errors in the charges levied by the courier companies.

4.Analyzing Charge Discrepancies: For orders with mismatched weight slabs, a further analysis is conducted. By cross-referencing the weight slabs with the charges levied per weight slab provided by the courier company, any overcharges or undercharges can be identified. This analysis assists X in identifying discrepancies in the charges levied by their courier partners.

Summary The Courier Charges Verification project aims to ensure the accuracy of charges incurred by X for order deliveries. By comparing internal data with the courier company's invoices, potential discrepancies and inaccuracies in weight slabs and charges can be identified. This process allows X to have a transparent understanding of the charges levied by their courier partners, leading to cost optimization and improved financial efficiency.
