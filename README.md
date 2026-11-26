 # FIS-Hackathon

## Topic

**Digital Trust and Programmable Controls**

## Our Project

**Countersign helps customers understand who they are paying before a digital-money payment goes through.** It checks business identity and payment evidence, then uses the result to control the payment: **proceed, pause for review, or stop.** Customers get a clear explanation of the decision; businesses get a credible way to prove they can be trusted; payment providers see the evidence behind it.

The verification engine screens public regulatory sources — such as UK Companies House identity and filing records — combined with transaction evidence supplied at the point of payment. A verification result is not just a badge: it is a **programmable control** that directly changes what happens to the funds.

The browser extension is our v1 interface for shoppers. The core product is the shared payment decision sitting on the payment path.

## Problem & Relevance

- Small businesses struggle to compete with larger retailers because they lack the established reputation signals customers rely on (brand recognition, review volume). Our platform lets them **gain credibility and digital trust directly from verified records**, rather than from accumulated reviews they may never get.
- This fills a gap left by **Trustpilot and review-based platforms**: those rely on user-generated opinions, which can be faked, farmed, or biased. Our data starts from **verified identity records, not opinions**. One caveat we build around: a company register confirms a business *exists* — it does not guarantee a seller will deliver, and Companies House itself does not check the accuracy of filings. So the register is our **identity and negative-signal layer** (who are you, are there filing defaults, disqualifications or enforcement red flags), while **delivery assurance comes from the payment mechanics themselves** — funds held or released based on the transaction outcome, not from the register.

### Scenario

> Backmarket-style refurb-tech marketplaces source from smaller sellers and take a significant cut of the profit. Those sellers often can't sell directly to customers because shoppers have no way of telling whether an unknown site is trustworthy. With Countersign, a customer's payment is checked and protected at the point of purchase — letting the smaller seller go direct, offer a better price, and keep their margin.

## Commercial Viability

**Revenue model:** Businesses (or their payment providers) pay for **integration, ongoing monitoring, and reporting**. The verification outcome itself is determined by evidence and cannot be purchased — paying gets a business *checked*, not *approved*. This separation is deliberate: it's the conflict of interest that undermines paid review platforms, and we design it out from day one. Indicative tiers: free basic verification for consumers; merchant integration fee plus monitoring subscription (c. £20–100/month, to be validated); provider-side API pricing at scale.

**Why should a Business not build one themselves?** A business can run its own register checks, but a check by the party being assessed isn't trust — the value is neutrality, plus being present on the payment path where both sides contribute evidence. A shared decision needs a shared referee.

**Where this goes:** a trust layer on the payment path has network value — every verified business makes the standard more useful for the next. Our near-term plan is measured rather than assumed: run a **pilot in one vertical**, tracking hold-for-review rate, false positives, merchant conversion lift, and chargeback reduction, and let those numbers justify expansion. Longer term we believe machine-readable trust on payments becomes infrastructure — increasingly so as AI shopping agents transact on customers' behalf.

**Limitation — two-sided cold start:** businesses join only if customers are present; customers install only if businesses are covered.

**Our answer:** launch deep in **one vertical — independent refurb-tech sellers** (the Backmarket scenario), where the pain is sharpest on both sides: sellers have margin being taken by marketplaces, and buyers face real distrust of unknown sites. Density in one category beats presence in all of them.

## Prototype Scope

_See open question 3 at the bottom of this file — to be completed with what is live vs. simulated in the demo._

---

## Open Questions (CLARIFY) — with related lines

1. **Pricing figures (c. £20–100/month in "Revenue model", line 26)** — these are placeholder numbers; confirm, adjust or cut before submission.
2. **Vertical choice (line 34, "independent refurb-tech sellers")** — proposed answer to the cold-start question; confirm this is the pilot market you want to pitch.
3. **Prototype scope (line 36)** — we still need: which parts of the demo actually work (payer checks? held funds? reviewer decisions?) and which are simulated vs. live Companies House calls.
4. **FCA contextual checks — not yet added** — see discussion; decision pending on whether to insert a "right checks for the right business" note after the Scenario (ends line 24).
