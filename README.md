# Smart India Hackathon Workshop
# Date:25/11/2026
## Reference Number:26008976
## Name: Ragave K

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
HarvestLoop — a demand-locked, shared logistics network
Instead of building another marketplace that simply connects farmers and buyers, HarvestLoop coordinates the whole trip from farm to customer. It groups nearby farmers’ produce, collects confirmed orders from households and businesses, and sends the combined load through the shortest practical route—with transparent prices at every step.

How it works
1. Farmers post expected harvests by crop, quantity, location, and ready date. They can use a basic phone, SMS, or a local coordinator.
2. Buyers place orders before harvest—for example, a hostel orders 200 kg of tomatoes for next week. Households can join a neighborhood group order.
3. The system pools nearby supply and demand to match orders with farmers and estimate a fair farm-gate price using recent local market prices, quality, and transport costs.
4. A shared collection route is planned. A local pickup point or mobile vehicle collects produce from several farms, then delivers consolidated loads to buyers or neighborhood hubs.
5. Payment and delivery are recorded. Farmers see the agreed price, deductions, and payment status. Buyers see where the produce came from and what each part of the price covers.
   
What makes it different
HarvestLoop reduces the need for several separate traders by combining three things: orders placed ahead of harvest, pooled transport, and transparent settlement. It doesn’t assume every middleman is unnecessary: local people can still earn by grading, collecting, or transporting produce, but their service and fee are visible.

## Technical Approach

1. Technologies to Be Used
- Mobile app: Flutter for Android phones, with a simple, multilingual interface.
- Web dashboard: React for farmer groups and administrators.
- Backend: Python with FastAPI to manage listings, orders, payments, and delivery updates.
- Database: PostgreSQL for user, produce, and order records.
- Maps and location: OpenStreetMap with Leaflet to find nearby farmers, buyers, and collection points.
- Notifications: Firebase Cloud Messaging for order and delivery updates.
- Payments: A secure payment gateway that supports the selected region’s payment methods.
- Hosting: A cloud platform such as AWS, Azure, or Google Cloud.
- Optional hardware: Android smartphones for farmers and delivery partners; QR-code labels for identifying produce batches at collection points.
  
2. Methodology and Implementation Process

1. Gather requirements: Identify the needs of farmers, buyers, and delivery partners; define user roles and essential features.
2. Design the prototype: Create app screens for registration, produce listings, search, ordering, payment, and delivery tracking.
3. Build the platform: Develop the mobile app, web dashboard, backend APIs, and database.
4. Add core features: Enable produce listings, nearby matching, grouped orders, digital payments, notifications, and order tracking.
5. Pilot locally: Test with a small group of farmers and buyers; collect feedback on usability, pricing, and delivery.
6. Improve and expand: Fix issues from the pilot, add requested features, and gradually onboard more users and locations.

   
## Feasibility and Viability
1. Feasibility Analysis
The solution is technically feasible using widely available smartphones, mobile apps, mapping tools, cloud services, and digital payment systems. A basic prototype can be built with modest resources and tested in one village or local market before expanding. It is also practical to involve farmer groups, cooperatives, or local collection centers to help farmers who have limited internet access or experience with apps. The main feasibility factors are reliable delivery arrangements, enough farmers and buyers in each area, and affordable operating costs.
2. Potential Challenges and Risks
- Limited internet access or digital skills: Some farmers may find app-based services difficult to use.
- Unreliable supply and quality: Produce availability, quantity, and quality can vary by season.
- Delivery and spoilage: Delays or poor handling can damage perishable produce.
- Trust and payment concerns: Buyers and farmers may worry about payment delays, incorrect orders, or disputes.
- Low participation: The platform may not attract enough farmers or buyers at the start.
- Price changes: Market prices can shift quickly, creating disagreements over listed prices.
- Data privacy and security: Personal, location, and payment information must be protected.
3. Strategies for Overcoming Challenges
- Provide a simple local-language app, phone support, and assisted registration through farmer groups.
- Allow listings to be updated easily and show current stock, quality details, and harvest dates.
- Start with nearby buyers and shared collection points; use suitable packaging and clear delivery schedules.
- Use a trusted payment provider, digital receipts, order confirmation, and a clear dispute process.
- Launch a small pilot with cooperatives, shops, and institutions, then expand based on feedback.
- Show transparent prices and let farmers confirm orders before they are finalized.
- Collect only necessary information, restrict access to it, and use secure payment services.

  
## Impact and Benefits
1. Potential Impact on the Target Audience.
Farmers can connect with more buyers, gain greater control over the prices they offer, and receive clearer information about orders and payments. Consumers, shops, and institutions can more easily find fresh produce from nearby farms. The platform can also help farmer groups coordinate sales and reach larger markets.
2. Benefits of the Solution
- Economic: Fewer intermediaries may mean farmers keep a larger share of the sale price, while buyers may face fewer added costs.
- Social: Direct connections can strengthen trust between farmers and their communities and help smaller farmers access more customers.
- Environmental: Grouping nearby orders can reduce separate delivery trips, and faster local sales may help reduce food spoilage.
- Practical: Digital listings and order records make available produce, prices, and transactions easier to track.

## Research and References
Research on digital agriculture shows that online platforms can help farmers find buyers and access market information. The proposed solution builds on these ideas by focusing on direct local sales, grouped deliveries, and clear order and payment records.
1. e-NAM — National Agriculture Market, Government of India
   e-NAM is an electronic trading platform that connects agricultural markets across India. It provides a useful reference for online produce trading and price information.
   Visit the e-NAM portal
2. World Bank — From Fields to Markets: The Role of Digital Platforms in West Africa
   This article describes how digital marketplaces can improve farmers’ access to buyers and market information, and help reduce barriers to trade. It also highlights the importance of digital infrastructure and skills.
   Read the World Bank article
3. FAO — Feasibility Study on Digital Technologies for Agrifood Value Chains
   This report looks at using digital tools to improve transparency and traceability in food supply chains. It also discusses challenges such as limited logistics and food loss, which are relevant to planning produce collection and delivery.
   Read the FAO study
4. MANAGE — Agricultural Market Portals and Apps
   This resource lists Indian agricultural platforms, including e-NAM and Agmarknet, which can help inform features such as market connections and price information.
   
