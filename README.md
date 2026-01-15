# SQL_Omnichannel-Customer-Journey-Analysis

# omnichannel customer journey analytics

this project analyzes end-to-end customer journeys across multiple channels
to understand how campaigns, devices, payments, and demographics impact
conversions and revenue.

## problem statement
customer interactions are spread across ads, sessions, funnels, and transactions,
making it difficult to understand the complete path to purchase and identify
revenue leakage points.

## objective
build a unified, sql-based analytics framework to:
- track customer journeys from impression to purchase
- identify drop-offs and conversion bottlenecks
- measure campaign, channel, and device effectiveness
- uncover revenue loss and optimization opportunities

## data model
tables used:
- customers
- sessions
- ads
- transactions
- funnel_dirty
- funnel_processed

an er diagram is included to show table relationships.

## key analyses
- campaign and channel funnel completion
- device-level conversion comparison
- age-group and platform performance
- payment method drop-offs and revenue loss
- repeat purchase behavior by category and device
- discount vs non-discount revenue trends
- city-level drop-offs and growth opportunities
- monthly and seasonal performance patterns

## insights
- mobile drives the highest funnel activity, while desktop shows stronger conversion efficiency
- instagram and youtube contribute high revenue through different volume-value dynamics
- paypal and net banking failures cause significant revenue leakage on specific devices
- fashion converts efficiently with lower volume, while beauty drives awareness
- october shows peak revenue, while discount-heavy months do not always maximize earnings

## tools
- sql (analytical queries and window functions)

this repository focuses on analytical reasoning and sql problem-solving rather than dashboarding.
