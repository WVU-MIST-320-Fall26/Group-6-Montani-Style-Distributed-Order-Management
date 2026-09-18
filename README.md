# Project Charter: Group 6 Montani Style Distributed Order Management

## Project Overview
Business Problem: Montani Style currently operates 45 brick-and-mortar retail stores alongside an e-commerce platform. Because online orders and physical store inventory run on disconnected legacy systems, the company frequently runs out of stock, and has elevated return processing expenses and high shipment costs. Additionally, real-time inventory inaccuracies prevent store managers from fulfilling online orders using local shelf stock.

Strategic Alignment: Unifying online and offline inventory streams into a single source aligns with Montani Style's strategic goal of transitioning to a modern retail model.

Quantifiable ROI & Benefits:
  Fulfillment Cost Reduction: Lower shipping costs by reducing split shipments and leveraging local store fulfillment.
  Increased Sales & Inventory Efficiency: Minimize out-of-stock lost sales by providing accurate, real-time stock levels across all 45 locations and e-commerce.
  Improved Customer Experience: Enable faster fulfillment times via local store pickups "Buy Online, Pick Up In-Store" (BOPIS) and streamline the return process.

## Project Scope & Objectives
Core Solution: 
  Develop a Distributed Order Management System (DOMS) to centralize inventory visibility across all channels. The system will route online orders to the optimal fulfillment node (warehouses or nearby retail stores), support "Buy Online, Pick Up In-Store" (BOPIS) workflows, and equip store associates with mobile tools for real-time inventory auditing and return processing.

Core Deliverables:
  Centralized Inventory Management Engine: A unified core platform that aggregates stock levels   from all 45 retail stores and e-commerce distribution centers in real time.
  Intelligent Order Routing Module: An automated routing engine that evaluates order location, store stock, and shipping costs to assign fulfillment to the optimal retail store or warehouse.
   BOPIS Application: Customer and staff interfaces to support in-store pickup for employees and customer hand-offs.
  Mobile Store Associate Tool: A handheld interface enabling store employees to perform real-time inventory audits, pick/pack online orders from shelf stock, and process customer returns.
  Legacy System Integration: API connectors linking the new DOMS to existing POS and e-commerce platforms.

In-Scope Features:
  Unified inventory sync across physical and digital storefronts.
  Automated order allocation and split-shipment minimization.
  Mobile-enabled store inventory auditing and local shelf-stock order fulfillment.
  Streamlined in-store return processing for online purchases.

Explicit Out-of-Scope Exclusions:
  Full hardware replacement of existing Point-of-Sale (POS) registers across retail locations.
  Overhauling external third-party logistics (3PL) or carrier delivery network infrastructure.
  Redesigning Montani Style's front-end e-commerce website UI/UX beyond the BOPIS checkout option.
  Warehouse Management System (WMS) overhaul outside of integrating inventory API endpoints.

## Budget & Milestone Schedule
### Estimated Budget
Total Estimated Project Budget: $1,150,000
Software Development & Integration: $650,000 (DOMS core engine, POS API connectors, and e-commerce integrations)
Mobile App Development & Hardware: $250,000 (Mobile app development and store handheld devices for 45 locations)
Testing & Quality Assurance: $150,000 (System integration, load testing, and store-level user acceptance testing)
Training: $100,000 (Store associate training programs and deployment support)

### Schedule
Deliverable 1:	9/21/26
Deliverable 2:	9/28/26
Deliverable 3:	10/5/26
Deliverable 4:	10/19/26
Deliverable 5:	10/26/26
Deliverable 6:	11/9/26
Final Deliverables: 12/4/26

## Team Roles & Governance
  Identifies Project Sponsor, PM authority level, key risks, assumptions, and formal executive signature blocks.
Executive Sponsor: Katherine Kopp
Project Manager: Rivka Abelow
Product Owner: Bryce Williams
Business Analyst: Gavin Morrisard
Solution Architect: Lindsey Guhne

Governance: 
