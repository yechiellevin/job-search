# Customer Enablement — Lesson 2 Exercise Solution

## Purpose

Preserve the completed reasoning from the Lesson 2 exercise separately from the clean exercise prompt.

This document summarizes the exercise through the discussion of human intervention, Customer Enablement, and Technical Support. It intentionally omits the later tangent about parentheses, LLM interpretation, and writing semantics.

## Scenario Recap

The hypothetical customer is **Shaked Therapy Center**, a multidisciplinary clinic moving from a mixture of spreadsheets, Google Calendar, WhatsApp, Word documents, and a basic billing application onto TERP.

The main user roles are:

- **Yael — Clinic Manager**
- **Michal — Clinic Administrator**
- **Therapists**
- **Future new employees**

Michal also has limited local IT responsibilities, with outsourced outside support for deeper technical issues.

The assumed TERP workflows are:

- organization and account setup
- staff setup
- roles and permissions
- patient creation/import
- scheduling
- treatment documentation
- billing
- management reporting

## 1. Start With a Role/Workflow Matrix

The first move was to organize the workflows by role before designing any content or training.

The purpose is to establish **who needs what** before asking how to teach it.

A provisional matrix looked like this:

| Workflow | Clinic Manager — Yael | Administrator — Michal | Therapists | New Employees |
| --- | --- | --- | --- | --- |
| Organization/account setup | Owns/approves | May assist | — | — |
| Staff setup | Defines organizational needs | Adds/maintains staff | — | Added through established process |
| Roles & permissions | Decides/approves access model | Implements assignments | Understand own access | Assigned appropriate role |
| Patient creation/import | Oversees migration | Primary operator | May need limited capability | Learn role-specific interaction |
| Scheduling | Needs visibility/oversight | Primary operator | View/manage own schedule as appropriate | Learn role-specific scheduling |
| Treatment documentation | Needs governance/visibility | Possibly administrative involvement | Primary operator | Must learn before independent work |
| Billing | Needs business visibility | Primary operator | Possibly supply required treatment inputs | Role-dependent |
| Management reporting | Primary consumer/operator | May generate/support | Usually little or none | — |
| Routine administration | Escalation/ownership | Primary operator | — | — |
| Onboard future staff | Owns process/accountability | Likely operational owner | Possibly peer assistance | Recipient |

The matrix is explicitly **hypothetical** and should be validated against the actual product and real customer practices.

## 2. Workflow Order and Early Enablement Priorities

The workflow list is already close to chronological and dependency order.

A likely sequence is:

**Organization setup → staff population → roles/permissions → patient migration → operational workflows**

The first four are implementation prerequisites. They need to be completed before the clinic can meaningfully practice its recurring day-to-day workflows.

The initial instinct was that these should be the first workflows to be explained, optimized, and supported by Customer Enablement.

A refinement emerged from the discussion:

> Do not assume that every workflow needs explanation. First determine what the customer must accomplish, where friction actually occurs, and only then choose the appropriate intervention.

## 3. Product Capability Must Be Understood Before Designing Enablement

Patient migration exposed this principle clearly.

The enablement approach depends heavily on what the product actually supports:

- bulk import
- manual entry
- assisted migration
- customer-managed import
- vendor-managed import

The point is not to invent friction or solutions from a feature list.

The correct default is to inspect the product, review existing documentation, and use evidence from Customer Success, Support, analytics, and customer observation to determine where users really struggle.

In this exercise, that investigation is treated as axiomatic rather than something that needs to be repeatedly rediscovered.

A useful distinction is:

- **Product inspection** shows where users *might* struggle.
- **Customer evidence** shows where users *actually* struggle.

## 4. Avoid Choosing Media Too Early

There was an early inclination to associate particular media with particular task types, for example:

- illustrated articles for one-time setup activities
- short videos for repeated routines

That may prove correct in some cases, but it is too early to prescribe media before understanding the actual problem.

The stronger sequence is:

**What must the user accomplish? → What is difficult? → What intervention addresses the difficulty? → What medium best supports that intervention?**

This helps avoid “asset thinking,” where the enablement program is designed around guides, videos, webinars, or tooltips simply because those are familiar deliverables.

## 5. Move From Feature Workflows to End-to-End Customer Scenarios

Once setup and migration are complete, the next useful unit is not necessarily the individual product feature.

A stronger onboarding model is to build an **end-to-end patient story** that reflects the clinic's real operating process.

A representative sequence might be:

**Schedule appointment → conduct treatment → document treatment → complete billing**

This is the enablement equivalent of cross-service, end-to-end scenario thinking.

The customer learns the product in the context of the actual business process rather than as disconnected feature instruction.

## 6. Use Representative Test Cases to Build and Validate Capability

A natural extension is to create representative **test cases** that let users practice these recurring end-to-end workflows.

At the theoretical level, the exact number of cases or details of the training environment are implementation decisions.

The important principle is:

> Before go-live, users complete representative end-to-end scenarios in a safe environment until they can perform their core workflows independently.

The test case serves both as **instruction and validation**.

The resulting pattern is:

**Teach through execution → observe execution → establish proficiency**

This is stronger than measuring whether users consumed content.

Successful performance of the workflow is direct evidence of capability.

## 7. Reuse Successful Onboarding for Future Staff

The same test-case approach can be incorporated into onboarding for future employees.

This creates a maturity progression:

**Tipuli-led onboarding → standardized customer learning path → customer-administered new-employee onboarding**

The successful initial learning experience becomes a reusable process that the customer can operate independently.

This reflects the Lesson 1 maturity-model principle of converting ad hoc intervention into standardized, scalable capability.

## 8. Measurement: Focus on Observable Capability

The exercise emphasized that successful enablement should not be measured only through content-consumption metrics such as:

- watched the video
- completed the module
- attended the webinar

A stronger measure is whether users can actually perform the workflow.

For example:

> Can the clinic staff take a representative patient through scheduling, treatment documentation, and billing without outside intervention?

That is direct evidence that the customer has developed operational capability.

The same principle can be applied to setup and administrative tasks.

## 9. Human Intervention Should Decline Over Time

Under routine circumstances, human intervention should be **greatest near the beginning of the customer journey, though still kept as limited as possible, and should trend downward over time**.

The goal is not high-touch service for its own sake.

The goal is to provide enough intervention to establish capability and then progressively remove dependency on that intervention.

A useful lifecycle model is:

- **Early journey:** readily available human guidance plus structured enablement
- **Growing proficiency:** guided self-service plus escalation
- **Mature customer:** self-service by default plus human help when genuinely needed

## 10. Customer Enablement vs. Technical Support

The difficult boundary appears under non-routine circumstances.

The distinction is best drawn by **objective** rather than by whether a human is involved.

### Customer Enablement

Primary question:

> How do we increase the customer's capability to succeed independently?

### Technical Support

Primary question:

> How do we resolve the customer's current problem?

A practical default is:

> **Enablement owns repeatable capability. Support owns exceptions and failures requiring resolution.**

For example:

- “How do I correct a billing entry?” may be an enablement/self-service problem.
- “I followed the documented correction procedure and TERP gives me an unexplained error” is likely a Support problem.

If Support sees the same error repeatedly across customers, the exception has become a pattern and should feed back into Enablement and/or Product.

That creates a closed loop:

**Enable → customer operates independently → exception occurs → Support resolves → recurring pattern identified → Enablement standardizes or Product eliminates → customer capability increases**

## 11. Self-Sufficiency Does Not Mean Abandonment

There is an important tension between enabling customers to be as self-sufficient as possible and making sure they still feel supported.

Self-service should not become a mechanism for preventing customers from reaching a human being when help is appropriate.

The key distinction is between **capability** and **obligation**:

- Enablement should make customers capable of solving an appropriate range of problems themselves.
- Customers should not necessarily be required to solve every problem themselves.

A mature customer can still encounter defects, outages, undocumented edge cases, corrupted data, or situations where independent troubleshooting would be inefficient or unreasonable.

## Exercise Conclusion

The exercise effectively covered all five original questions:

1. **What must the customer accomplish, and in what order?**  
   Model the transition through prerequisite setup and migration, then move into end-to-end operating scenarios.

2. **Who needs to learn what?**  
   Begin with a role/workflow matrix before designing interventions.

3. **Where should human intervention be used or avoided?**  
   Use the minimum necessary intervention, especially early in the journey, and design for dependency to decline over time. Preserve human support for genuine exceptions and failures.

4. **Where are likely failure points?**  
   Do not invent them from insufficient context. Inspect the product and use evidence from customers, Customer Success, Support, analytics, and observation to identify and validate friction.

5. **What demonstrates successful enablement?**  
   Observable independent performance of real or representative end-to-end workflows, not merely consumption of enablement content.

## Overall Assessment

The exercise revealed strong existing instincts for:

- role and workflow modeling
- dependency and sequence analysis
- end-to-end scenario design
- product-first investigation
- learning by execution
- capability-based measurement
- maturity-model thinking
- reducing repeated human intervention through standardization

The main developmental need is not learning how to think about customer workflows from scratch. It is gaining experience with the specific operational machinery used to run and measure a formal Customer Enablement function at scale.
