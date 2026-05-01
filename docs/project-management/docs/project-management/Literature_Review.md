# Literature Review

## Introduction
E-commerce platforms generate vast amounts of transactional data that can be leveraged for business intelligence. Olist, as a Brazilian marketplace, connects small sellers to customers across thousands of product categories.

## Related Work

| Author | Focus | Key Finding |
|--------|-------|--------------|
| Kaggle user "thales" | Delivery performance | Delivery delays correlate with lower review scores |
| Kaggle user "muriloto" | Customer segmentation | RFM analysis identifies 20% of customers generating 80% of revenue |
| GitHub user "rajtulluri" | Product categories | Health & beauty products have highest review scores |

## Research Gaps (What This Project Adds)

1. Integration of all tables in a normalized SQL Server database
2. Automated KPI tracking using stored procedures
3. Interactive dashboard with real-time filtering
4. Actionable seller ranking system for logistics improvement

## Theoretical Framework

| Framework | Application |
|-----------|-------------|
| RFM Analysis | Customer segmentation for targeted marketing |
| Pareto Principle (80/20 rule) | Identify top 20% of products/sellers generating 80% of revenue |
| Cohort Analysis | Track customer retention over time |

## Data Source Credibility
- Source: Olist (real Brazilian e-commerce platform)
- Time period: 2016–2018
- Size: ~100,000 orders
- License: CC BY-NC-SA 4.0 (Kaggle)

## Limitations

| Limitation | Mitigation |
|------------|------------|
| Data is 5+ years old | Focus on analytical methodology |
| No product cost data | Work with revenue only |
| Portuguese categories | Manual mapping to English |
