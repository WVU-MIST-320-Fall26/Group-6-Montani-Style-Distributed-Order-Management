# Scope Change Impact Assessment

## Executive Summary
The VP of Retail Operations & Store Experience requested the addition of a customer-facing "Curbside Geo-Arrival Tracking" feature to the Buy Online, Pick Up In Store (BOPIS) module. This feature would track customer background GPS within a 0.5-mile radius of a store, trigger real-time alerts on store associate handheld devices, initiate a 3-minute delivery countdown timer, and track associate dispatch metrics for employee KPIs.


## Impact Analysis
### Timeline & Schedule Impact
* Implementing background GPS geolocation tracking, real-time proximity alerts, and live countdown timers introduces significant complexity that is outside the scope of current Sprint 2 and Sprint 3 backlogs.
* Introducing mobile background location tracking and KPI logging engine will delay the core BOPIS rollout scheduled for Sprint 2/Sprint 3 and jeopardize pilot store onboarding.
### Infrastructure & Resource Constraints
* Requires building and supporting persistent web push notification services to reliably alert associate handheld devices in real time.
* Requesting continuous background location permissions from customer devices introduces high regulatory compliance risk (GDPR/CCPA privacy consents, location permission prompting, and data retention policies).
* Integrating countdown timers directly into employee performance KPI tracking requires connections to workforce management systems that are not part of the core DOMS architecture.


## Team Recommendation

### Recommendation: **DEFER**

**Justification:**
1. The primary goal of Sprints 2 and 3 is to deliver core BOPIS functionality (order allocation, store pickup selection, associate notifications, and customer hand-off verification). Adding curbside tracking at this stage creates a high risk of project failure.
2. A dedicated spike is needed during post-launch planning to assess privacy compliance, battery usage constraints on mobile devices, and handheld integration overhead.
