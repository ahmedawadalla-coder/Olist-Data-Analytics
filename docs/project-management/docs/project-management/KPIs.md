# Key Performance Indicators (KPIs)

## Business KPIs

| KPI | Formula | Target |
|-----|---------|--------|
| Total Revenue | SUM(payment_value) | Monitor growth |
| Average Order Value (AOV) | SUM(payment_value) / COUNT(DISTINCT order_id) | > 150 BRL |
| Number of Orders | COUNT(DISTINCT order_id) | Monthly trend up |

## Delivery Performance KPIs

| KPI | Formula | Target |
|-----|---------|--------|
| On-Time Delivery Rate | (orders_delivered_on_time / total_delivered) * 100 | > 90% |
| Average Delivery Delay | AVG(actual_delivery_days - estimated_delivery_days) | < 2 days |
| Maximum Delivery Delay | MAX(actual_delivery_days - estimated_delivery_days) | < 15 days |

## Customer Satisfaction KPIs

| KPI | Formula | Target |
|-----|---------|--------|
| Average Review Score | AVG(review_score) | > 4.0 / 5 |
| 5-Star Review Rate | (5_star_reviews / total_reviews) * 100 | > 60% |
| Low Rating Rate | (reviews 1 or 2 / total_reviews) * 100 | < 15% |

## Customer Segmentation (RFM)

| Segment | Recency (days) | Frequency | Monetary (BRL) |
|---------|---------------|-----------|----------------|
| Champions | 0–30 | > 5 | > 500 |
| Loyal | 31–90 | 3–5 | 200–500 |
| At Risk | 91–180 | 1–2 | < 200 |
| Lost | > 180 | 0 | 0 |
