# Superstore Sales & Profit Analysis

## Overview
This project analyzes retail sales and profitability data from a global 
superstore using Excel PivotTables and PivotCharts to uncover regional, 
category, and product-level performance patterns.

## Dashboard
A single-page dashboard consolidates all four analyses with visualizations 
for quick scanning — see the `DashBoard` tab in the workbook.

## Key Findings

**1. Regional Performance**
- West generates the highest profit ($108,345), followed by East ($91,523)
- Central region underperforms significantly ($39,706), the lowest of 
  all four regions

**2. Category Performance**
- Technology is the most profitable category ($145,455), followed by 
  Office Supplies ($122,418)
- Furniture generates dramatically lower profit ($18,451) than the other 
  two categories despite being a core product line

**3. Regional × Category Cross-Analysis**
- Central region's Furniture category is the only region-category 
  combination operating at a loss (-$2,871)
- This isolated weak spot is invisible in either the regional or 
  category view alone — only the cross-tab reveals it

**4. Sub-Category Deep Dive**
- Three sub-categories operate at a loss company-wide: Tables (-$17,725), 
  Bookcases (-$3,473), and Supplies (-$1,189)
- Tables alone accounts for the vast majority of total losses, making it 
  the single biggest concern
- Tables and Bookcases both fall under the Furniture category, explaining 
  the root cause of Central's Furniture underperformance identified in 
  the cross-analysis
- Supplies falls under Office Supplies — a separate, smaller issue worth 
  monitoring but not currently dragging down its overall category profit

## Recommendations
- Investigate why Tables specifically loses money — likely candidates 
  include excessive discounting, high shipping/logistics costs, or 
  underpriced bulk orders
- Consider reviewing pricing strategy or discount policy for Tables and 
  Bookcases before continuing to stock them at current volumes
- Examine whether Central region's Furniture underperformance is driven 
  by the same product-level issue or a distinct regional factor

## Workbook Structure
- `Raw Data` — source dataset
- `Region Profit` — profit by region
- `Category Profit` — profit by category
- `Region Category` — cross-tab of region × category profit
- `Sub category` — profit by product sub-category
- `DashBoard` — consolidated view with all four charts

## Tools Used
Excel (PivotTables, PivotCharts)

## Data Source
Sample Superstore dataset via Kaggle
