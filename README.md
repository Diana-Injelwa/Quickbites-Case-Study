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

**6-Month P&L by Location**

| Location | Revenue | Ingredient Costs | Fixed Costs | Net Profit |
|----------|---------|-----------------|-------------|------------|
| Kilimani | KES 6.4M | KES 2.5M | KES 2.4M | KES 1.6M |
| Eastleigh | KES 3.6M | KES 1.4M | KES 1.9M | KES 722K |
| Westlands | KES 4.8M | KES 1.8M | KES 2.7M | KES 387K |

All three ghost kitchens are profitable, validating the model. The key insight is that Eastleigh is nearly 2x more profitable than Westlands (KES 722K vs KES 387K) despite having the lowest revenue, a signal that order volume alone is a misleading measure of location performance.

**What Makes a Location Work?**

| Metric | Eastleigh *(Most Efficient)* | Kilimani *(Highest Revenue)* | Westlands *(Least Profitable)* |
|--------|------------------------------|------------------------------|--------------------------------|
| Net Profit (6 mo) | KES 722K | KES 1.6M | KES 387K |
| Monthly Fixed Costs | KES 313K | KES 408K | KES 455K |
| Delivery-Only Competitors | 3 | 8 | 12 |
| QuickBite Rating | 4.13 / 5 | 3.40 / 5 | 3.74 / 5 |
| Avg Delivery Time | 56 min | 69 min | 64 min |

The most profitable locations share a clear pattern: low fixed costs, few delivery-only competitors, and room to outperform on quality. Westlands' high rent and crowded competitive landscape compress margins despite decent revenue.

**Recommendation:**
Expand to neighborhoods that resemble Eastleigh. Low rent (under KES 150K/mo), fewer than 5 delivery-only competitors, and underserved by quality delivery (competitor ratings below 4.0). Avoid "Westlands-type" markets where high fixed costs and competition make margin advantages hard to sustain.

---

**Q2: What's the Real Story with Eastleigh?**

The CFO and the GM were looking at the same location through completely different lenses.

**Two Views of Eastleigh**

*CFO's View (Volume)*
| Metric | Value |
|--------|-------|
| Total orders | 6,637 (lowest) |
| Avg order value | KES 597 (lowest) |
| Total revenue | KES 3.6M (lowest) |

*GM's View (Quality & Growth)*
| Metric | Value |
|--------|-------|
| Customer rating | 4.13 / 5 (best of all 3) |
| Avg delivery time | 56 min (13 min faster than Kilimani) |
| Net profit | KES 722K — 2x Westlands |
| Delivery-only competitors | 3 (fewest) |
| Order growth | +38% over 6 months |

**Verdict:** 
The GM is right. Eastleigh is more profitable than Westlands and is the only location growing consistently.

**Month-over-Month Order Growth**

| Month | Eastleigh | Kilimani | Westlands |
|-------|-----------|----------|-----------|
| Sep '24 | +7.3% | -1.0% | -0.5% |
| Oct '24 | +4.0% | +4.8% | +1.4% |
| Nov '24 | +15.8% | -4.8% | -2.9% |
| Dec '24 | +3.6% | +5.6% | +4.0% |
| Jan '25 | +2.8% | -5.7% | -9.2% |

Eastleigh is the only location with positive growth in every single month. Kilimani and Westlands both ended January in decline Westlands at -9.2%.

**Breakeven Safety Buffer**

| Location | Breakeven Orders/Month | Avg Monthly Orders | Buffer |
|----------|----------------------|-------------------|--------|
| Eastleigh | 799 | 1,106 | +38.4% |
| Kilimani | 807 | 1,348 | +67.0% |
| Westlands | 969 | 1,106 | +14.1% |

Westlands sits just 14% above breakeven — the most operationally vulnerable kitchen despite its higher revenue. Eastleigh operates 38% above breakeven and is trending upward.

**Recommendations:**
1. Keep Eastleigh open and give the GM 3 more months with a clear milestone: reach 1,300 orders/month by month 9. The current trajectory (922 → 1,270) makes this achievable.
2. Invest modestly in local marketing. Eastleigh's growth has been entirely organic against only 3 delivery competitors. A small push could accelerate an already positive trend.
3. If cuts are needed, scrutinize Westlands first, it has the highest fixed costs (KES 455K/mo), most competition (12 delivery-only), thinnest net profit (KES 387K), and the smallest breakeven buffer of the three.