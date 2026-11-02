# Risk Register

**Project Name:** Group 6 Montani Style Distributed Order Management  
**Date Created:** 2026-11-02  
**Last Updated:** 2026-11-02  

## Risk Register Table

| ID | Risk Description | Category | Probability (1-3) | Impact (1-3) | Risk Score | Response Strategy | Mitigation Plan | Owner | Status | Last Update |
|---|---|---|---|---|---|---|---|---|---|---|
| RSK-01 | Legacy POS software lacks sufficient documentation or API endpoints to support real-time inventory sync under 5 seconds. | Technical | 2 (Medium) | 3 (High) | 6 | Mitigate | Conduct early spike testing on legacy POS interfaces and develop custom middleware wrappers. | Lindsey Guhne (Solution Architect) | Active | 2026-11-02 |
| RSK-02 | Network instability or poor Wi-Fi coverage across the 45 retail stores prevents mobile handheld devices from syncing. | Operational | 2 (Medium) | 3 (High) | 6 | Mitigate | Implement offline data caching on mobile apps and require store Wi-Fi network audits prior to hardware rollout. | Lindsey Guhne (Solution Architect) | Active | 2026-11-02 |
| RSK-03 | Store associates fail to complete onboarding within the 2-hour window, causing operational disruption during store hours. | Operational | 3 (High) | 2 (Medium) | 6 | Mitigate | Develop bite-sized modular training materials and run pilot training runs at high-volume store locations first. | Gavin Morrisard (Business Analyst) | Active | 2026-11-02 |
| RSK-04 | Software development and integration costs exceed the $650,000 allocated budget due to unexpected API complexity. | Financial | 2 (Medium) | 3 (High) | 6 | Control | Monitor spending closely and enforce strict approval for any added integration features. | Rivka Abelow (Project Manager) | Active | 2026-11-02 |
| RSK-05 | Order routing logic fails to notify store associates within 2 minutes of order placement, delaying BOPIS fulfillment. | Technical | 2 (Medium) | 2 (Medium) | 4 | Control | Establish automated queue performance monitoring and fallback alert channels (e.g., push notifications + audio alerts). | Bryce Williams (Product Owner) | Active | 2026-11-02 |
| RSK-06 | Hardware supply chain delays prevent handheld mobile devices from arriving at all 45 store locations before deadline. | Schedule | 1 (Low) | 3 (High) | 3 | Avoid | Place hardware orders in advance with vendors and maintain a contingency pool of units. | Rivka Abelow (Project Manager) | Active | 2026-11-02 |
