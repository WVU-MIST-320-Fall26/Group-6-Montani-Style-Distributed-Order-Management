# Project Scope Statement

## Product Scope Description
Montani Style is implementing a centralized Distributed Order Management System (DOMS) to bridge the gap between its 45 brick-and-mortar retail locations and digital e-commerce channels. Currently, disconnected legacy systems result in frequent stockouts, elevated return processing costs, high shipping fees, and an inability to fulfill online orders using local store inventory.
The DOMS solution will serve as the single source of truth for enterprise-wide inventory. It will intelligently route customer orders to optimal fulfillment nodes (warehouses or local stores), enable Buy Online, Pick Up In-Store (BOPIS) functionality, and provide store associates with dedicated mobile tools to conduct real-time inventory audits, pick/pack local orders, and process customer returns efficiently.

## Deliverables
**Centralized Inventory Management Engine:** A robust core backend platform aggregating real-time stock levels across all 45 physical retail stores and centralized e-commerce distribution centers.
**BOPIS Application:** Customer-facing checkout modules and staff fulfillment interfaces designed to manage local order pickup workflows and customer hand-offs seamlessly.
**Mobile Store Associate Tool:** Handheld software deployed across all 45 locations to enable store employees to conduct real-time inventory audits, pick/pack online orders directly from shelf stock, and process customer returns on the floor.
**Legacy System Integration:** Custom APIs and middleware linking the new DOMS engine directly to Montani Style's existing Point-of-Sale (POS) software and e-commerce platform.
**Training & Onboarding Package:** Comprehensive training programs, user documentation, and operational protocols for store associates and logistics personnel.

## Acceptance Criteria
**Inventory Synchronization Accuracy:** Real-time inventory sync across physical and digital storefronts must maintain a minimum accuracy rate of 99% with latency under 5 seconds.
**Order Allocation Efficiency:** The automated order allocation engine must correctly identify and route orders to the nearest fulfillment node with available stock, reducing split-shipment rates by at least 25%.
**BOPIS Processing Speed:** The BOPIS interface must process and notify store associates of new pickup orders within 2 minutes of customer placement.
**Mobile Tool Performance & Usability:** Handheld auditing tools must execute stock updates instantaneously and feature an intuitive UX requiring less than 2 hours of staff training.
**System Uptime & Integration Reliability:** Legacy POS and e-commerce integrations must maintain 99.9% uptime during operational store hours without disrupting existing checkout processes.
**Sign-off:** Formal sign-off and approval from Product Owner (Bryce Williams) and Executive Sponsor (Katherine Kopp) following User Acceptance Testing (UAT).

## Project Exclusions / Out-of-Scope Items
**Third-Party Logistics & Carrier Overhaul:** No physical modifications, contract renegotiations, or infrastructure changes to external shipping carrier networks or 3PL operations.
**E-Commerce Front-End Redesign:** Redesigning the main e-commerce website UI/UX beyond integrating the BOPIS checkout and inventory availability widgets.
**Warehouse Management System Overhaul:** Core warehouse management system upgrades outside of basic inventory integration with the DOMS core engine.
**Hardware Procurement for Non-Store Facilities:** Hardware deployment is strictly limited to store handheld devices; no new hardware for corporate or warehouse logistics facilities is included.

## Project Constraints
**Budget Constraint:** Total project expenditure must not exceed the approved budget of $1,150,000 allocated across software integration ($650k), mobile development/hardware ($250k), testing/QA ($150k), and training ($100k).
**Schedule Constraint:** All deliverables and final project deployment must be completed no later than December 4, 2026.
**Operational Constraint:** System deployment, testing, and store associate training must occur without disrupting regular store operating hours or standard customer service operations.
**Technical Constraint:** Integration must function within the limitations of Montani Style's existing legacy POS architecture without requiring a total POS replacement.

## Project Assumptions
**Legacy API Access:** Legacy POS and e-commerce platforms will provide sufficient API documentation, database access, and vendor support necessary for real-time inventory integration.
**Infrastructure Readiness:** All 45 retail store locations have or will receive stable Wi-Fi/internet coverage and compatible handheld devices prior to hardware rollout.
**Staffing Availability:** Store management can schedule associate training sessions without incurring overtime costs or compromising store operational coverage.
**Stakeholder Engagement:** Key stakeholders (Executive Sponsor, PM, Product Owner, BA, Solution Architect) will be available for timely reviews, UAT validation, and sign-offs as outlined in the project schedule.
