# Customer Enablement — Lesson 2

## The Machinery of Customer Enablement

## Purpose

Make the Customer Enablement function concrete: not merely why Enablement exists, but what an enablement owner actually builds, maintains, and operates.

A useful first-pass model divides the machinery into five overlapping systems:

1. Onboarding
2. Ongoing education
3. In-product guidance
4. Knowledge and self-service
5. Measurement and feedback

Together, these systems support the larger objective established in Lesson 1: helping customers become successful and increasingly self-sufficient users of a product.

## 1. Onboarding

Onboarding is the structured path from "the customer bought the product" to "the customer can use it successfully."

A mature onboarding program asks questions such as:

- What must the customer know before first use?
- What should happen on Day 1, Week 1, and Month 1?
- Which workflows are prerequisites for others?
- Which activities require live guidance?
- Which can be self-service?
- How do we know the customer has reached a first meaningful success point?

That meaningful success point is often described as **activation**.

Activation should represent useful customer behavior, not merely content consumption or account access. For example, "logged in" is rarely a meaningful activation event. A better activation definition describes something the customer has successfully accomplished with the product.

### Relationship to technical writing

A documentation set can explain every feature correctly and still fail as onboarding if customers encounter the information in the wrong sequence.

This is an important expansion beyond documentation: the enablement owner is responsible for the **progression itself**, not only for the information supporting individual steps.

### Existing overlap

There is strong conceptual and practical overlap with Yechiel's prior work.

At Microsoft, scenario-based, customer-focused documentation increasingly emphasized cross-service, end-to-end solution scenarios: beginning with what customers were trying to accomplish and guiding them through the technologies needed to get there.

At CyberArk, that principle became explicit information architecture work: reorganizing documentation around user journeys and outcomes rather than product structure.

The unfamiliar part is therefore not designing a user journey through knowledge. It is owning the broader onboarding program and orchestrating non-documentation mechanisms around that journey.

## 2. Ongoing Education

Enablement continues after initial onboarding.

Customers may need education around:

- advanced workflows
- new features
- role-specific skills
- refresher learning
- changed product behavior
- best practices
- underused functionality

Possible mechanisms include:

- webinars
- short video walkthroughs
- office hours
- structured learning paths
- release or change education
- certification programs

A certification program can be understood as a formal answer to:

> What should someone know and be able to do before we consider that person proficient?

### Existing overlap

Yechiel has direct experience training product managers and writers, onboarding colleagues, and presenting a live product demonstration. Teaching and explaining are therefore familiar activities.

The gap is designing and operating a **customer education curriculum at scale**.

## 3. In-Product Guidance

Enablement can move directly into the product experience.

Examples include:

- tooltips
- walkthroughs
- checklists
- contextual help
- next-step prompts
- new-feature banners
- empty-state guidance
- embedded links to learning resources

Tools such as Pendo, WalkMe, and Appcues can provide infrastructure for creating these interventions without requiring every piece of guidance to be engineered directly into the application.

The core design question is:

> At the moment the user is trying to perform this action, what is the minimum guidance needed to get them through it successfully?

This area overlaps substantially with UX writing and microcopy, but adds an explicit learning and adoption objective.

### Existing overlap

CyberArk UX and microcopy work provides strong adjacent experience. The unfamiliar tools are likely a smaller gap than the judgment required to recognize when and how users need contextual guidance.

## 4. Knowledge and Self-Service

This is the part of Customer Enablement closest to traditional technical writing.

Typical assets include:

- help-center articles
- FAQs
- troubleshooting content
- onboarding guides
- workflow documentation
- searchable knowledge bases
- release/change documentation

Enablement, however, treats documentation as one component of a larger learning system rather than as an independent publishing operation.

The question therefore expands from:

> Is this help article accurate and findable?

into:

> Is a help article the right intervention at this point in the customer journey?

Sometimes the answer is no.

If a large proportion of users fail at the same product step, improving the article may be less effective than adding contextual guidance or changing the product itself.

### Existing overlap

This is Yechiel's strongest area. The existing orientation toward documentation as part of the product experience, user journeys, discoverability, and customer outcomes already fits naturally into an enablement model.

## 5. Measurement and Feedback

A mature enablement system should create a closed loop:

**Intervention → behavior → measurement → adjustment**

Possible measures include:

- onboarding completion
- time to activation
- feature adoption
- course or video completion
- webinar attendance
- search success
- article usefulness
- support-ticket volume
- repeated support issues
- demonstrated user proficiency
- retention/churn
- expansion

These measures operate at different distances from the intervention.

For example:

- **Direct metric:** Did users complete the onboarding module?
- **Behavior metric:** Did they successfully perform the workflow afterward?
- **Product metric:** Did adoption of the relevant feature increase?
- **Business metric:** Did retention improve?

The further the metric is from the intervention, the harder it becomes to establish causation. Good enablement measurement therefore uses proximate measures of customer behavior as well as downstream business outcomes.

### Existing overlap and gap

This appears to be the largest unfamiliar area. The conceptual feedback-loop thinking is familiar, but direct ownership of activation, adoption, retention, and enablement-effectiveness measurement would be new.

## Putting the Machinery Together

Consider a hypothetical case in which new clinic administrators repeatedly struggle to configure staff permissions.

An ad hoc response might be:

> A Customer Success Manager explains permissions individually to every new customer.

A somewhat more mature response might be:

> Write a help-center article.

A stronger enablement response could combine several mechanisms:

- include permissions in the onboarding path;
- create a short walkthrough;
- provide contextual guidance on the permissions screen;
- give Customer Success a standardized intervention for customers who still struggle;
- measure completion and error rates;
- review the workflow with Product;
- simplify the product experience if the problem persists.

The important idea is that these mechanisms form a **system**. Documentation is one available intervention, not the assumed answer to every learning or adoption problem.

## Current Fit Map

| Enablement machinery | Current position |
| --- | --- |
| Knowledge / self-service | Already strong |
| In-product guidance | Strong adjacent experience |
| Onboarding / journey design | Strong conceptual and practical overlap; limited ownership of customer onboarding programs |
| Ongoing education | Some direct experience; limited program design |
| Measurement / feedback | Largest gap |

The central stretch is therefore narrower than "never having built an enablement function."

Yechiel has already worked with substantial pieces of the machinery. What is new is **owning their orchestration as one operating system**.

## Next Step

The accompanying exercise, `lesson-2-exercise.md`, applies this model to a hypothetical therapy clinic adopting TERP. The exercise is intentionally preserved separately from Yechiel's eventual answer so that the original problem statement remains available for later review.
