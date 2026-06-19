Data analysis case study for QuickBite, a Nairobi-based food delivery startup operating ghost kitchens across three neighborhoods. I Analyzed over 6 months data to assess expansion viability, resolve an internal leadership debate on location performance and deliver data-driven menu optimization recommendations

**Background**

QuickBite launched ghost kitchens (delivery-only locations) in three Nairobi neighborhoods; Kilimani, Westlands and Eastleigh. After 6 months, the leadership team was split:
- The CFO wanted to shut down Eastleigh since it has the lowest order volume of the three
- The Eastleigh GM argued customers loved them and asked for more time

**Key Questions**
1. Should QuickBite expand ghost kitchens? If yes, what locations/characteristics should they prioritize?
2. What's the real story with Eastleigh? Is the CFO right, or is the GM onto something?
3. What menu optimizations should they test?

**Datasets**
- orders_data: Every order placed
- menu_items: Menu pricing, prep times, ingredient costs
- weather_data: Daily rainfall and temperature
- kitchen_costs: Fixed monthly costs per location
- competitor_data: Competitive landscape per area

**Key Insights**

**Q1: Should QuickBite Expand?**

**Visual 1: 6-Month P&L by Location**

| Location | Revenue | Ingredient Costs | Fixed Costs | Net Profit |
|----------|---------|-----------------|-------------|------------|
| Kilimani | KES 6.4M | KES 2.5M | KES 2.4M | KES 1.6M |
| Eastleigh | KES 3.6M | KES 1.4M | KES 1.9M | KES 722K |
| Westlands | KES 4.8M | KES 1.8M | KES 2.7M | KES 387K |

All three ghost kitchens are profitable, validating the model. The key insight is that **Eastleigh is nearly 2x more profitable than Westlands (KES 722K vs KES 387K) despite having the lowest revenue** — a signal that order volume alone is a misleading measure of location performance.

**Visual 2: What Makes a Location Work?**

| Metric | Eastleigh *(Most Efficient)* | Kilimani *(Highest Revenue)* | Westlands *(Least Profitable)* |
|--------|------------------------------|------------------------------|--------------------------------|
| Net Profit (6 mo) | KES 722K | KES 1.6M | KES 387K |
| Monthly Fixed Costs | KES 313K | KES 408K | KES 455K |
| Delivery-Only Competitors | 3 | 8 | 12 |
| QuickBite Rating | 4.13 / 5 | 3.40 / 5 | 3.74 / 5 |
| Avg Delivery Time | 56 min | 69 min | 64 min |

The most profitable locations share a clear pattern: **low fixed costs, few delivery-only competitors, and room to outperform on quality**. Westlands' high rent and crowded competitive landscape compress margins despite decent revenue.

**Recommendation:** Expand to neighborhoods that resemble Eastleigh — low rent (under KES 150K/mo), fewer than 5 delivery-only competitors, and underserved by quality delivery (competitor ratings below 4.0). Avoid "Westlands-type" markets where high fixed costs and competition make margin advantages hard to sustain.