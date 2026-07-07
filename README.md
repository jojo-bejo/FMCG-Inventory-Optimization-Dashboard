FMCG Inventory Optimization Dashboard
Supply Chain Executive Analytics Solution
This project is a four-page Power BI dashboard designed to help FMCG supply chain leaders balance product availability, stockout risk, supplier performance, and working capital.
The dashboard is built as an executive decision-support tool, not only a reporting view. It highlights where inventory is at risk, where cash is tied up, and which supplier or warehouse actions should be prioritized.
Business Problem
FMCG companies often face a difficult tradeoff:
Too little inventory creates stockouts, lost sales, and service-level failures.
Too much inventory ties up working capital and increases aging, dead stock, and excess inventory risk.
Supplier delays and warehouse imbalances can make both problems worse.
This dashboard brings those issues into one connected Power BI solution so leaders can quickly answer:
What is the overall inventory health?
Where are we losing service?
How much working capital can be released?
Which supplier and warehouse actions are needed?
Dashboard Pages
1. Executive Inventory Health
Provides a high-level view of inventory value, service level, stockout risk, excess inventory, and days on hand.
Key features:
Executive KPI cards with status colors
Inventory Health Matrix
Inventory value by category
Top inventory risks table
Executive summary narrative

2. Service Level & Stockout Risk
Focuses on customer service risk and SKU-warehouse combinations requiring replenishment attention.
Key features:
Critical SKU-warehouse locations
Estimated lost sales
Fill rate vs target
Safety stock breaches
Stockout risk heatmap
Demand vs forecast alignment
At-risk SKU table

3. Excess & Working Capital
Quantifies tied-up inventory and estimates working capital release opportunities.
Key features:
Slow-moving SKU percentage
Dead stock value
Excess inventory value
Working capital release opportunity
Inventory aging analysis
Action-oriented SKU table with recommendations such as transfer, liquidation, bundling, and supplier return

4. Supplier & Warehouse Performance
Connects supplier performance and warehouse exposure to inventory availability.
Key features:
Supplier OTIF
Average lead time
Late purchase order value
Open purchase order quantity
Lead time by supplier
Open PO by warehouse
Supplier performance table
Reorder recommendations

KPI Status Logic
The dashboard uses a consistent executive status system:
Status	Meaning
Healthy	Performance is within target or acceptable operating range
Monitor	Management attention is required, but the issue is not yet an immediate operational crisis
Critical	Immediate action is required due to service, stockout, supplier, or working-capital risk

Examples:
Service Level below target is marked Critical.
Stockout Risk above threshold is marked Critical.
Excess Inventory and Days on Hand are marked Monitor because they represent tied-up working capital.
Inventory Value above working-capital budget is marked Monitor rather than Healthy.
Business Impact
This dashboard supports supply chain decisions by:
Highlighting critical SKU-warehouse stockout risks
Prioritizing replenishment and safety stock actions
Quantifying potential working capital release
Identifying excess, slow-moving, and dead stock
Connecting supplier performance to inventory availability
Improving executive visibility across inventory, service, finance, and supplier performance
Tools Used
Microsoft Power BI
Power Query
DAX
Star schema data modeling
Executive KPI design
Supply chain analytics logic
Project Files
FMCG Inventory Optimization_3.pbip - polished Power BI Project version
FMCG Inventory Optimization_3.Report/ - report definition
FMCG Inventory Optimization_3.SemanticModel/ - semantic model definition
FMCG Inventory Optimization.pbix - original Power BI file
data/ - source data folder
dax/ - DAX measure library
docs/ - dashboard specification and supporting documentation
themes/ - Power BI theme files
Portfolio Positioning
This project demonstrates both Power BI development skill and practical FMCG supply chain experience.
It was designed to show how analytics can move beyond static reporting and support executive decisions around inventory optimization, service protection, working capital recovery, and supplier performance management.
Author
Dashboard developed by:
Jose Jojo Bejo
ChainSight Analytics
Microsoft Power BI Portfolio Project
