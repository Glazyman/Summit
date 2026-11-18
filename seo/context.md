# Summit Mergers — SEO context

Site: https://summitmergers.com (static HTML on GitHub Pages; push to main = live)
Product: boutique BUY-SIDE M&A brokerage for owners of $2M–$50M service businesses (index.html hero)
Conversion: confidential assessment form → Formspree (index.html #contact)
Buyer: first-time seller, owner of an established service business (HVAC, access control/security, fencing, professional services, tech, healthcare services, manufacturing — index.html FAQ)
Fees: sellers pay nothing upfront or at closing; purchaser-side economics (index.html fee callout + FAQ)
Timeline claim: most deals close in 3–6 months (index.html FAQ)
Contact: info@summitmergers.com · (845) 402-6614 (index.html)
Competitors (confirmed 2026-11-17 via web search for "sell my HVAC business broker" / "how to sell an HVAC company"): BizBuySell learning center, Sunbelt Network, Synergy Business Brokers, Cowen Partners, Robbinex, Raincatcher, OffDeal, Axial forum, TruForte Business Group (FL)
Data sources connected: none (no Search Console, no Ahrefs). Volumes/positions are NOT measured.

Money pages: /sell-hvac-business.html (HVAC owners, primary funnel), /sell-and-retire.html (general retiring owners). Both use Formspree mzzvwzvb; HVAC leads carry source=hvac funnel + utm in `campaign`.
Ship mode: merge when the build passes (static site, push to main = live via GitHub Pages).

Bing Webmaster Tools: verified via msvalidate.01 meta tag in index.html <head> (NEVER remove it).
IndexNow key: 8b2f38b6f4bf481384733f5d66e576a6 (key file /8b2f38b6f4bf481384733f5d66e576a6.txt at site root, never delete or edit). After every push that changes pages, ping IndexNow (feeds Bing -> ChatGPT search): curl -s -o /dev/null -w "%{http_code}" -X POST https://api.indexnow.org/IndexNow -H "Content-Type: application/json; charset=utf-8" -d '{"host":"summitmergers.com","key":"8b2f38b6f4bf481384733f5d66e576a6","keyLocation":"https://summitmergers.com/8b2f38b6f4bf481384733f5d66e576a6.txt","urlList":["<each changed URL>"]}' (expect 200 or 202; log the code).
Google Search Console: verified via google-site-verification meta tag in index.html <head> (NEVER remove it).

## POSITIONING RULE (owner-confirmed 2026-11-17): Summit is BUY-SIDE
Summit works with buyers (PE, family offices, strategics) and is paid by the buyer at closing. That is WHY sellers pay nothing.
NEVER write that Summit "represents" owners/sellers, is a "sell-side advisor", negotiates "for you"/"on your behalf", is "on your side", or "won't let you settle for less".
DO say: connects owners with vetted buyers; brings several serious buyers to the table; keeps it confidential; coordinates offers, terms and timelines through closing; walks owners through how offers are structured; recommends owners have their own attorney and CPA review final terms.
Describing OTHER firms as "sell-side brokers that charge sellers" is fine. Testimonial wording is never edited (real client quotes).

## OFFER RULE (owner-confirmed 2026-11-17): Summit does NOT offer valuations
The conversion offer is a FREE CONFIDENTIAL BUYER CALL: a follow-up call to see if Summit has a buyer for the company and to introduce the owner to PE groups / family offices / strategic buyers.
NEVER promise a "valuation", "free valuation", "confidential assessment", "what your company is worth" or "an honest read on what it could sell for". Educational content explaining HOW HVAC companies are valued is fine.
