# Feature status — Construction, design & project delivery

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 397 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 2 | 0 | Native records/view |
| Work items & projects | records | 6 | 0 | Native records/view |
| Contacts & parties | records | 2 | 0 | Native records/view |
| Tasks | records | 1 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 2 | 0 | Native records/view |
| Time tracking | records | 1 | 0 | Native records/view |
| Messages & communications | records | 3 | 0 | Native records/view |
| Reports & analytics | report | 7 | 0 | Native records/view |
| Activity & audit trail | audit | 3 | 0 | Native records/view |
| Provider connections | integration | 0 | 0 | Provider request records only |
| Payroll Project | records | 1 | 0 | Native records/view |
| Worker | records | 1 | 0 | Native records/view |
| Wage Determination | records | 1 | 0 | Native records/view |
| Timecard | records | 1 | 0 | Native records/view |
| Payroll Line | records | 1 | 0 | Native records/view |
| Fringe Contribution | records | 1 | 0 | Native records/view |
| Classification Exception | records | 1 | 0 | Native records/view |
| Weekly Payroll | records | 1 | 0 | Native records/view |
| Restitution | records | 1 | 0 | Native records/view |
| Operational Task | records | 1 | 0 | Native records/view |
| Rule Version | records | 1 | 0 | Native records/view |
| Document Requirement | records | 1 | 0 | Native records/view |
| Classification evidence mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fringe discrepancy explanation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Timecard reconciliation brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payroll packet draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Restitution follow-up draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contractor correction request | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence completeness review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Operations handoff draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract and subcontract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Schedule-of-values ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pay-application reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retainage calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Substantial completion tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Punch-list evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Change-order linkage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Conditional waiver management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unconditional waiver management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Preliminary notice deadlines | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lien deadline control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Surety bond support | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retainage demand package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Collection workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Project cash forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subcontract scope library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Daily log ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Issue notice tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Responsible party analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Labor cost reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equipment cost reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material cost reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rework quantity validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cleanup allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Schedule impact calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract notice compliance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Backcharge package generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subcontractor response workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deduction reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Project trade analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Data center construction coordinator work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Building Design Generator | integration | 1 | 0 | AI question-and-answer workspace; records available as context |
| Code Compliance Checker | records | 1 | 0 | Native records/view |
| Energy Modeling | records | 1 | 0 | Native records/view |
| Material Estimation | records | 2 | 0 | Native records/view |
| Floor Plan Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Structural Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost Estimation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Site Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sustainability Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lighting Design | integration | 1 | 0 | Provider request records only |
| HVAC Design | integration | 1 | 0 | Provider request records only |
| Interior Design | integration | 1 | 0 | Provider request records only |
| Landscape Design | integration | 1 | 0 | Provider request records only |
| Construction Timeline | records | 1 | 0 | Native records/view |
| Parking Design | integration | 1 | 0 | Provider request records only |
| Acoustic Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fire Safety Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Precedent Search | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Design to BIM | integration | 1 | 0 | Provider request records only |
| Render Spec | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Structural Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Energy Model | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Plugin Export | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CAD Conversion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Design Versions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Comments + Lock | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material Library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Csv | records | 1 | 0 | Native records/view |
| Extras | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| History | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compare | records | 1 | 0 | Native records/view |
| Backlog | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Permit set readiness | records | 1 | 0 | Native records/view |
| Bids | records | 1 | 0 | Native records/view |
| Contractors | records | 4 | 0 | Native records/view |
| Materials | records | 5 | 0 | AI question-and-answer workspace; records available as context |
| Labor Costs | records | 1 | 0 | Native records/view |
| Subcontractors | records | 2 | 0 | Native records/view |
| Change Orders | records | 2 | 0 | Native records/view |
| Risk Assessment | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Cost Estimates | records | 1 | 0 | Native records/view |
| Compliance | records | 1 | 0 | Native records/view |
| Bid Comparisons | records | 1 | 0 | Native records/view |
| Timelines | records | 1 | 0 | Native records/view |
| Approvals | records | 1 | 0 | Native records/view |
| Audit Trail | records | 1 | 0 | Native records/view |
| Documents: Extraction | records | 1 | 0 | Native records/view |
| Bids: Risk Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Costs: Estimate Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance: Permits | records | 1 | 0 | Native records/view |
| Compliance: Safety | records | 1 | 0 | Native records/view |
| Subs: Scoring | records | 1 | 0 | Native records/view |
| Change Orders: Impact | records | 1 | 0 | Native records/view |
| Projects: Risk Metrics | records | 1 | 0 | Native records/view |
| Bid Bond Readiness | records | 1 | 0 | Native records/view |
| AI Workbench | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bid Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Compliance Check | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scope Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Timeline Estimation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bid Comparison | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Material Optimization | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Subcontractor Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Value Engineering | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash Flow Projection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispute Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Budget vs Actual | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Schedule Risk Mitigation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Supplier Intelligence | records | 2 | 0 | Native records/view |
| Vision-Based Site Inspection | records | 2 | 0 | Native records/view |
| Agentic Contract Negotiation | records | 2 | 0 | Native records/view |
| Real-Time Cost Variance Alerts | records | 1 | 0 | Native records/view |
| Liability Insurance Recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subcontractor Performance Scoring | records | 2 | 0 | Native records/view |
| Site-Vision AI (Progress / Safety) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contractor / Subcontractor AI Scoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agentic Bid Negotiation | records | 1 | 0 | Native records/view |
| Supplier Directory / Vendor Mgmt | records | 1 | 0 | Native records/view |
| RFQ Automation / Vendor Outreach | records | 1 | 0 | Native records/view |
| Equipment Rental / Availability | records | 1 | 0 | Native records/view |
| Calendar Integration | integration | 1 | 0 | Provider request records only |
| Mobile / Field App Surfaces | records | 1 | 0 | Native records/view |
| Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Lab | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing features | records | 1 | 0 | Native records/view |
| Production readiness | records | 1 | 0 | Native records/view |
| Real time cost tracking with variance alerts | records | 1 | 0 | Native records/view |
| Liability insurance recommendation engine | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Cost Estimate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Schedule Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Safety Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Change Order Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Risk Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Weather Impact Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Environmental Compliance Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI BIM Coordination Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Projects full | records | 1 | 0 | Native records/view |
| Change orders full | records | 1 | 0 | Native records/view |
| Daily reports full | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi modal progress tracking | records | 1 | 0 | Native records/view |
| Predictive project completion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Autonomous site monitoring | records | 1 | 0 | Native records/view |
| Supply chain optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Worker wellness fatigue monitoring | records | 1 | 0 | Native records/view |
| Permitting regulatory prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sites | records | 1 | 0 | Native records/view |
| Workers | records | 4 | 0 | Native records/view |
| Equipment | records | 5 | 0 | Native records/view |
| Incidents | records | 3 | 0 | Native records/view |
| Inspections | records | 2 | 0 | Native records/view |
| Permits | records | 2 | 0 | Native records/view |
| Trainings | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hazards | records | 3 | 0 | Native records/view |
| Jha | records | 1 | 0 | Native records/view |
| Near misses | records | 1 | 0 | Native records/view |
| Safety meetings | records | 1 | 0 | Native records/view |
| Ppe inventory | records | 1 | 0 | Native records/view |
| Drug tests | records | 1 | 0 | Native records/view |
| Dot records | records | 1 | 0 | Native records/view |
| Claims | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendors | records | 2 | 0 | Native records/view |
| Predict hazards | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Toolbox talk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Synthesize inspection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Analyze incident | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Verify permit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend training | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ppe detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fatigue predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Weather stop work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Jha generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Near miss cluster | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contractor score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim fraud | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Training gap | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lift plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scaffold inspector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rca analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Near miss similarity | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Osha narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hazard image classifier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Leading indicator predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Osha reports | records | 1 | 0 | Native records/view |
| Certifications | records | 1 | 0 | Native records/view |
| Subcontractor onboarding | records | 1 | 0 | Native records/view |
| Lone worker | records | 1 | 0 | Native records/view |
| Wearables | records | 1 | 0 | Native records/view |
| Drones | records | 1 | 0 | Native records/view |
| Scaffold tag compliance | records | 1 | 0 | Native records/view |
| Attachments | records | 1 | 0 | Native records/view |
| Webhooks | integration | 1 | 0 | Provider request records only |
| Bulk import | records | 1 | 0 | Native records/view |
| Environmental Monitoring | records | 3 | 0 | Native records/view |
| Worker Fatigue Detection | records | 3 | 0 | Native records/view |
| PPE Compliance | records | 2 | 0 | Native records/view |
| Fall Detection | records | 2 | 0 | Native records/view |
| Heat Stress Monitoring | records | 3 | 0 | Native records/view |
| Noise Exposure | records | 2 | 0 | Native records/view |
| Air Quality | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Proximity Alerts | records | 2 | 0 | Native records/view |
| Training Compliance | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Emergency Response | records | 2 | 0 | Native records/view |
| Evacuation Muster Trace | records | 2 | 0 | Native records/view |
| Predictive Maintenance | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Advanced Suite | records | 1 | 0 | Native records/view |
| CF: MultiModalFatigueDetecti | records | 1 | 0 | Native records/view |
| CF: PredictiveInjuryPreventi | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CF: AutonomousSafetyAudits | records | 1 | 0 | Native records/view |
| CF: BehaviorBasedSafetyBbsCo | records | 1 | 0 | Native records/view |
| CF: WorkerCohortAnalysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CF: InsurancePremiumOptimiza | records | 1 | 0 | Native records/view |
| Safety Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equipment Health | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Worker Wellness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Environmental Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance Report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Emergency Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Training Recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predictive Alerts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident Probability (8h) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PPE Compliance Scan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dynamic Evacuation Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Collision Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fall Risk Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Space Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Zoning Compliance (advisory) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Renovation Roadmap | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insurance Risk Review (advisory) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Resale Value Projection (advisory) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Room Detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Home Staging | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Furniture Placer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Maintenance | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Energy Auditor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Home Inspector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Floor plans | records | 1 | 0 | Native records/view |
| Rooms | records | 2 | 0 | Native records/view |
| Suggestions | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Estimates | records | 1 | 0 | Native records/view |
| Full analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dimensions | records | 1 | 0 | Native records/view |
| Optimize layout | records | 1 | 0 | Native records/view |
| Cost estimate | records | 1 | 0 | Native records/view |
| Accessibility checker | records | 1 | 0 | Native records/view |
| Sustainability analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contractor bid comparison | records | 1 | 0 | Native records/view |
| Advanced ai tools | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Egress path clearance | records | 1 | 0 | Native records/view |
| Budget | records | 1 | 0 | Native records/view |
| Designs | integration | 2 | 0 | Provider request records only |
| Timeline | records | 1 | 0 | Native records/view |
| Punch List | records | 1 | 0 | Native records/view |
| Warranties | records | 1 | 0 | Native records/view |
| Daily Log | records | 1 | 0 | Native records/view |
| Photos | records | 1 | 0 | Native records/view |
| Payments | records | 1 | 0 | Native records/view |
| Permit inspection readiness | records | 1 | 0 | Native records/view |
| agentic project coordinator scheduling i | records | 1 | 0 | Native records/view |
| vision based construction progress track | records | 1 | 0 | Native records/view |
| change order ai advisor estimating costt | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| contractor performance scoring extending | records | 1 | 0 | Native records/view |
| material supply chain optimization monit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| lien payment automation flagging payment | records | 1 | 0 | Native records/view |
| timeline predictor based on scope | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| budget optimizer overspend flagger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| contractor recommendation engine | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| material cost estimator | records | 1 | 0 | Native records/view |
| vision based inspection analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| schedule conflict detector across tra | records | 1 | 0 | Native records/view |
| lien management | records | 1 | 0 | Native records/view |
| formal change order workflow | records | 1 | 0 | Native records/view |
| contractorsupplier marketplace | records | 1 | 0 | Native records/view |
| webhook surface | integration | 1 | 0 | Provider request records only |
| real time homeowner update feed | records | 1 | 0 | Native records/view |
| Irrigation | records | 2 | 0 | Native records/view |
| Proposals | records | 3 | 0 | Native records/view |
| Plant Database | records | 1 | 0 | Native records/view |
| Cost Calculator | records | 1 | 0 | Native records/view |
| Soil Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Weather Plans | records | 2 | 0 | Native records/view |
| Crew Scheduling | records | 1 | 0 | Native records/view |
| Photo Gallery | records | 1 | 0 | Native records/view |
| Suppliers | records | 2 | 0 | Native records/view |
| Expenses | records | 2 | 0 | Native records/view |
| Calculator | records | 2 | 0 | Native records/view |
| Design Feasibility Check | integration | 1 | 0 | Provider request records only |
| Maintenance Cost Projector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Crew Skill Matcher | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Seasonal Demand Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material Price Monitor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Plant survivability zone check | records | 1 | 0 | Native records/view |
| Split optimize | records | 1 | 0 | Native records/view |
| Approval bottleneck | records | 1 | 0 | Native records/view |
| Scenario model | records | 1 | 0 | Native records/view |
| Partner anomalies | records | 1 | 0 | Native records/view |
| Payout reconcile | records | 1 | 0 | Native records/view |
| Erp revrec | records | 1 | 0 | Native records/view |
| Governance routing | records | 1 | 0 | Native records/view |
| Strategic partner recommend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Workflows | records | 1 | 0 | Native records/view |
| Workflow config | records | 1 | 0 | Native records/view |
| Workflow new | records | 1 | 0 | Native records/view |
| Approval workflows | records | 1 | 0 | Native records/view |
| Organizations | records | 1 | 0 | Native records/view |
| Leads | records | 1 | 0 | Native records/view |
| Opportunities | records | 1 | 0 | Native records/view |
| Products | records | 1 | 0 | Native records/view |
| Partners | records | 1 | 0 | Native records/view |
| Agreements | records | 1 | 0 | Native records/view |
| Governance | records | 1 | 0 | Native records/view |
| Conflict queue | records | 1 | 0 | Native records/view |
| Visibility approvals | records | 1 | 0 | Native records/view |
| Risks | records | 1 | 0 | Native records/view |
| Referrals | records | 1 | 0 | Native records/view |
| Status tracker | records | 1 | 0 | Native records/view |
| Payout summary | records | 1 | 0 | Native records/view |
| Shared items | records | 1 | 0 | Native records/view |
| Compliance reviews | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deal paths | records | 1 | 0 | Native records/view |
| Demo queue | records | 1 | 0 | Native records/view |
| Integration map | integration | 1 | 0 | Provider request records only |
| Advisory requests | records | 1 | 0 | Native records/view |
| Meeting notes | records | 1 | 0 | Native records/view |
| Economics | records | 1 | 0 | Native records/view |
| Split templates | records | 1 | 0 | Native records/view |
| Resource view | records | 1 | 0 | Native records/view |
| Activities | records | 1 | 0 | Native records/view |
| Kpi | records | 1 | 0 | Native records/view |
| Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Split structure optimization partner satisfaction margin | records | 1 | 0 | Native records/view |
| Approval workflow prediction likely bottlenecks | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Economic scenario modeling what if on deal terms | records | 1 | 0 | Native records/view |
| Partner performance dashboards with anomaly alerts | records | 1 | 0 | Native records/view |
| Automated payout reconciliation with dispute detection | records | 1 | 0 | Native records/view |
| Erp integration for revenue recognition | integration | 1 | 0 | Provider request records only |
| Governance exception management with ai routing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Strategic partner recommendation based on capability gaps | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Workflow bottleneck detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Economics split optimization ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deal structure recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payout prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Governance exception triage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi level governance approvals board cfo sequenced | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Full e signature integration | integration | 1 | 0 | Provider request records only |
| Mobile partner portal ui | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| External tax reporting 10991042 generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sox grade sod controls reporting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material | records | 1 | 0 | Native records/view |
| Remnant | records | 1 | 0 | Native records/view |
| Optimization job | records | 1 | 0 | Native records/view |
| Service | records | 1 | 0 | Native records/view |
| Testimonial | records | 1 | 0 | Native records/view |
| Team member | records | 1 | 0 | Native records/view |
| Faq | records | 1 | 0 | Native records/view |
| Quote request | records | 1 | 0 | Native records/view |
| Favorite | records | 1 | 0 | Native records/view |
| Setting | records | 1 | 0 | Native records/view |
| Consultation | records | 1 | 0 | Native records/view |
| Result | records | 1 | 0 | Native records/view |
| Attribution touch | records | 1 | 0 | Native records/view |
| Consent record | records | 1 | 0 | Native records/view |
| Suppression entry | records | 1 | 0 | Native records/view |
| Outreach message | records | 1 | 0 | Native records/view |
| Integration endpoint | integration | 1 | 0 | Provider request records only |
| Integration event | integration | 1 | 0 | Provider request records only |
| Integration link | integration | 1 | 0 | Provider request records only |
| Privacy request | records | 1 | 0 | Native records/view |
| Rate limit bucket | records | 1 | 0 | Native records/view |
| Audit event | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 397 feature pages were visited in the browser; 395 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 181 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

181 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
