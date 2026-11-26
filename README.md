# FIS-Hackathon

## Topic

**Digital Trust and Programmable Controls**

## Our Project

Our product creates digital trust through transparency. It is we decided to build a browser extenstion to that screens publicly available regulatory databases — such as the UK's **Companies House** and the **FCA register**, verifying the businesses customers wish to buy from, in real time, at the point of purchase. Reducing the friction of customers accessing the relevant publicly available financial data.

We believe this works because transparency benefits both sides of the relationship:

- **Customers** want a reliable way to trust the businesses they are looking at buying from.
- **Businesses** want a credible way to *prove* they can be trusted by customers, especially small businesses with limited market share who have not yet developed that trust and reputation.

[CLARIFY: Our earlier notes mention "two-way trust" (businesses verifying customers too). Is that still in scope, or is v1 purely customer → business verification?]

[CLARIFY: One sentence on why this relates to digital money / programmable controls would strengthen this — even without the fraud example, e.g. verification results triggering a programmable payment or escrow release.]

## Problem & Relevance

- Small businesses struggle to compete with larger retailers because they lack the established reputation signals customers rely on (brand recognition, review volume). Our platform lets them **gain credibility and digital trust directly from regulatory data**, rather than from accumulated reviews they may never get.
- This fills a gap left by **Trustpilot and review-based platforms**: those rely on user-generated opinions, which can be faked, farmed, or biased. Our data comes from **regulatory bodies**, so it carries an inherent level of credibility and accountability.

### Scenario

> Backmarket-style refurb-tech marketplaces source from smaller sellers and take a significant cut of the profit. Those sellers often can't sell directly to customers because shoppers have no way of telling whether an unknown site is trustworthy. With our product, a customer can verify the business from a financial and regulatory standpoint before buying — letting the smaller seller go direct, offer a better price, and keep their margin.

## Commercial Viability

**Revenue model:** Businesses pay to be listed and verified on our platform (display of the trust badge/verification at checkout).

**The long-term thesis:** Once adoption is high enough, customers will come to *expect* to see our verification popup on any site they buy from — at which point being verified becomes a **de facto requirement** for any business selling online, similar to how SSL padlocks or "Verified by Visa" became table stakes.

**Key limitation — two-sided cold start:** Businesses only join if customers are present, and customers only install the extension if businesses are covered. Without breaking this loop, neither side gets value.

**Our strategy to address it — the "Amazon books" approach:** Rather than launching for all ecommerce at once, we target **one specific vertical first** to build density on both sides, then expand horizontally into adjacent categories.

[CLARIFY: Which vertical? Refurbished tech sellers? Second-hand marketplaces? Choose one for the pitch — judges will ask, and "books" only worked for Amazon because the inventory advantage was unique to books at the time.]

[CLARIFY: Rough pricing / cost assumptions? Even a guess ("free tier + ~£X/month for badge + API access") makes the model feel real.]

[CLARIFY: Why wouldn't a big business just build this themselves? One line on neutrality of a third party + cross-source data + presence in the buyer's browser would answer this.
