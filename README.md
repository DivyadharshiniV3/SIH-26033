# Smart India Hackathon Workshop
# Date: 30-10-2026
## Reference Number: 26004428
## Name: DIVYADHARSHINI V

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
FairShare Market is a digital marketplace that helps farmers connect directly with consumers, retailers, and bulk buyers, reducing dependency on multiple intermediaries. The platform's key feature, NetEarning Compare, helps farmers understand how much they can actually earn after deducting transportation, handling, packaging, commission, and other selling-related costs.

Farmers can enter crop details, quantity, expected price, and location, while buyers can post their requirements and offers. The system compares available opportunities and displays the estimated net earnings for each option. It can also identify nearby orders and estimate potential savings through shared transportation, helping farmers make more informed selling decisions and improve profitability.

The uniqueness of FairShare Market lies in its focus on actual farmer earnings rather than selling price alone. By providing transparent cost breakdowns and comparing multiple selling options, the platform enables farmers to choose the most beneficial offer while promoting fair and efficient agricultural trade.

## Technical Approach
The platform will be developed using HTML, CSS, and JavaScript for the frontend, Python with Flask for backend processing, and SQLite for data storage. OpenStreetMap will be used for distance estimation and transportation planning.

The workflow begins with farmer and buyer registration. Farmers list their crops and expected prices, while buyers submit purchase requirements. The system matches suitable buyers and sellers, calculates estimated selling costs, compares net earnings across different offers, evaluates shared transportation opportunities, and presents a comparison report to support decision-making.

The Net Earnings calculation is:

Net Earnings = Gross Revenue − Total Selling Costs

where selling costs may include transportation charges, handling fees, packaging expenses, commissions, and other applicable costs.

## Flowchart

+--------------------------------------+
|       Farmer & Buyer Registration   |
+--------------------------------------+
                   |
                   v
+--------------------------------------+
|       Enter Crop Details,            |
|       Prices & Locations             |
+--------------------------------------+
                   |
                   v
+--------------------------------------+
|       Match Suitable Buyer           |
|       Opportunities                  |
+--------------------------------------+
                   |
                   v
+--------------------------------------+
|       Estimate Selling Costs         |
+--------------------------------------+
                   |
                   v
+--------------------------------------+
|       NetEarning Compare              |
|       Calculates Earnings            |
+--------------------------------------+
                   |
                   v
+--------------------------------------+
|       Compare Available              |
|       Selling Options                |
+--------------------------------------+
                   |
                   v
+--------------------------------------+
|       Estimate Shared                |
|       Transportation Savings         |
+--------------------------------------+
                   |
                   v
+--------------------------------------+
|       Generate Comparison            |
|       Report                         |
+--------------------------------------+
                   |
                   v
+--------------------------------------+
|       Farmer Selects Most            |
|       Suitable Offer                 |
+--------------------------------------+

## Feasibility and Viability
FairShare Market can be implemented as a web-based application using widely available and cost-effective technologies, making it suitable for a hackathon prototype. The initial version only requires basic information such as farmer records, buyer offers, and cost details, making development practical and achievable within a limited timeframe.

Some challenges may include changing market prices, incomplete cost information, limited internet access for farmers, and variations in transportation expenses. These challenges can be addressed by allowing users to update information regularly, displaying calculation assumptions clearly, supporting local languages, and labeling all earnings and transportation savings as estimates until confirmed.

## Impact and Benefits
FairShare Market can create positive economic, social, and environmental impact by improving market transparency and reducing supply chain inefficiencies.

Economically, it helps farmers compare buyer offers, understand actual earnings, and potentially reduce logistics expenses through shared transportation. Socially, it supports informed decision-making, encourages direct farmer-buyer interaction, and improves access to market information for small and marginal farmers. Environmentally, better transportation planning and order consolidation can reduce unnecessary travel, improve logistics efficiency, and help minimize food wastage.

## Research and References
1. e-NAM (National Agriculture Market) - Reference for digital agricultural trading and market connectivity.
2. AGMARKNET - Reference for agricultural commodity prices and market information.
Ministry of Agriculture & Farmers Welfare, Government of India - Reference for farmer-related initiatives and agricultural policies.
3. OpenStreetMap - Reference for location-based services, route planning, and distance estimation.

These resources support the platform's pricing comparison, buyer matching, cost estimation, and transportation planning functionalities.

## application of research
Agricultural market data will support price comparison and help farmers evaluate different selling options. Location-based information will be used to estimate delivery distances and identify opportunities for shared transportation.
     The NetEarning Compare feature will be included in the prototype and tested using sample
 crop transactions and selling-cost data to assess its effectiveness and accuracy.