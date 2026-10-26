# Beacon: our solution

Beacon proposes a school-linked connection between young people and community activities. It combines discovery, attendance verification, recognition and aggregate reporting, giving schools a way to understand participation beyond the school gate.

**Source:** [19-page team pitch](presentations/beacon-pitch-19-pages.pdf), particularly pages 2–14. The descriptions below explain the team's proposal; they do not establish a deployed service.

## Problem and audience

The team's analysis identified five connected barriers: discovering suitable activities, cost and transport, attending alone, perceived safety and limited choice. It targeted students aged 12–16 within a school catchment.

Routine Activity Theory informed the emphasis on approved activities and trusted adult hosts. Social Bond Theory informed belonging, regular participation and youth leadership. These are design rationales. The deck also acknowledges that research findings on delinquency outcomes are mixed; the proposed pilot therefore measures participation and return visits directly.

## A student journey

1. **Discover.** A student browses a school-linked activity feed and sees the activity, location, timing, host and participation details.
2. **Decide and register.** Clear information and opportunities to connect with peers reduce uncertainty about a first visit. Beacon Pass is the proposed participation identity within the experience.
3. **Participate.** An approved host verifies attendance through the proposed QR workflow. A registration alone does not count as a completed session.
4. **Get recognised.** Verified attendance can trigger Torch Points. The prototype illustrates 10 points for a verified session, local vouchers, term rewards and longer-term Youth Champion opportunities.
5. **Return.** Recognition and social connection encourage another visit. Return participation is an outcome to test in a pilot.

![Original team screen mockups](assets/prototype-journey.png)

The displayed screens are design evidence from the supplied deck. They are not screenshots of a live service verified during repository preparation.

## Value for each stakeholder

| Stakeholder | Need | Proposed response |
| --- | --- | --- |
| Students | Accessible activities, friends, confidence and recognition | Verified activity feed, clear details, peer connection and rewards |
| Schools | Student wellbeing, limited coordination capacity and evidence of engagement | Approval workflows, attendance records, moderation and term reporting |
| Councils | Understand community participation and use of local facilities | Aggregate catchment reporting |
| Activity providers | Reach participants and coordinate sessions | Listings, venue/QR workflows and partner support |
| Prospective legacy partners | Understand community contribution | Moderated participation opportunities and aggregate impact reporting |

Partner relationships in the deck are prospective. Organisations named as potential partners are not represented as having signed Beacon agreements.

## Positioning and innovation

The pitch positions PCYC Queensland and council youth activities as potential providers, and school activity-management products as complementary parts of the existing ecosystem. Beacon's proposed role is to connect activity discovery, school trust, verified attendance and return incentives across that ecosystem.

The technical innovation is the service design and integration: a familiar school entry point connects to low-code participation workflows and a feedback loop for evaluating engagement. The concept does not require an unproven claim that software alone prevents crime.

## Delivery and next evidence

The [architecture](architecture.md) describes the components assigned in the pitch. The [pilot plan](pilot-and-evaluation.md) explains what would need to be measured before scaling. The [business model](business-model.md) identifies proposed payers and keeps conflicting financial versions separate.
