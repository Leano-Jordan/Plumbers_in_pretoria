# Plumbers Pretoria Director System

## Mission
Turn the existing reputation and local-search demand around **Plumbers in Pretoria** into a credible digital front door that helps a customer move from plumbing problem → confidence → contact.

## Business thesis
The prospect appears to have a strong local-search identity and substantial customer proof, but its digital presence is fragmented across directory listings rather than being clearly owned by a dedicated first-party website. Rosscore's opportunity is therefore not "make a prettier website"; it is to create an owned conversion system around the business.

## Primary customer jobs
1. "I have a plumbing problem. Who do I call?"
2. "Can they handle my specific problem?"
3. "Are they actually local/relevant to me?"
4. "Can I trust them?"
5. "How do I contact them right now?"

## Product priorities
### P0
- Clear business identity
- Fast contact path
- Problem-first service discovery
- Verified trust proof
- Mobile-first usability
- Accurate business information

### P1
- Service detail pages
- Local service-area architecture once areas are verified
- Review integration using authentic review content
- FAQ/search intent coverage
- Quote/request workflow if the business confirms it supports one

### P2
- Deeper project proof
- Structured lead qualification
- Analytics/reporting
- Local SEO expansion
- Content/resource layer

## Positioning direction
Do not position the company using generic claims such as "Pretoria's #1", "best", "most trusted", "qualified", "licensed", "insured", "24/7", "fastest", or guaranteed response times unless the prospect verifies the claim.

The current safe positioning territory is:
**A local Pretoria plumbing service people can contact when they need help with a plumbing problem.**

This can become sharper after direct client verification.

## Design DNA gate
The current pack implementation is a reference implementation, not a permanent visual identity.

Before substantial visual changes, document:
- business personality
- customer emotional state
- market visual conventions
- desired perception
- typography
- colour behaviour
- composition/layout rhythm
- shape language
- imagery
- CTA language
- navigation model
- motion/interaction
- trust presentation
- explicit anti-patterns

## Anti-Slop Check
Reject or mutate the design if it looks like:
- generic AI/SaaS landing page
- cloned Rosscore plumbing demo
- generic agency site
- oversized abstract hero + three cards + testimonial + CTA with no business-specific reasoning
- visual choices that cannot be explained by this client's market, customer, evidence, or positioning

Ask:
**Could another AI produce essentially this interface from a generic "modern plumber website" prompt?**
If yes, iterate.

## Content rules
Use exact verified facts where available. If a fact is not verified, either omit it or label it internally as pending verification. Do not fabricate testimonials. Do not paraphrase reviews as quotations unless the source review is available.

## Conversion model
Primary: phone contact.
Secondary: service/problem discovery leading to contact.
Potential tertiary: WhatsApp or quote request only after availability is confirmed.

Track the existing Rosscore event conventions:
- PHONE_CLICK
- WHATSAPP_CLICK
- QUOTE_STARTED
- QUOTE_SUBMITTED
- SERVICE_PAGE_CTA
- LOCATION_PAGE_CTA
- REVIEW_CLICK
- MAP_CLICK

Do not imply an event channel exists unless the corresponding interaction actually exists.

## Commercial readiness gate
Before client presentation, verify:
- no invented claims
- all contact links work
- mobile experience is strong
- desktop experience is coherent
- service taxonomy matches evidence
- SEO titles/descriptions are accurate
- accessibility basics pass
- conversion paths are obvious
- Design DNA is documented
- Anti-Slop Check passes
- prospect/demo status is understood
