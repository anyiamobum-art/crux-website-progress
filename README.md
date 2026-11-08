# CRUX website progress

[Open the visual checklist](https://anyiamobum-art.github.io/crux-website-progress/)

## Current delivery

**55% verified · 45% remaining**

6 of 11 delivery items verified. 5 remain (45% of this checklist, not work hours). 0 of 3 passing ratings.

Last verified 08 November, 08:11 UTC. Signed-off delivery 6/11. Four signed TEST journeys 35/35 steps. Two-account privacy 8/9. Native iPhone 0/7. Whole-draft ratings at 9.5 or above 0/3.

The public history first shows six on 13 October. A reversal on 14 October brought it to five. On 15 October it returned to six. As of 8 November, 24 days have passed since six items were last verified. Each item counts once. The percentages track signed-off outcomes. The remaining testing and reviews have no verified time estimate.

## What changed

- Shopping regression reproduced. The preview returned HTTP 501 for Add to bag and 404 for the bag. The restored shopping journey remains open until a real selected variant persists, updates quantity and reaches the checkout handoff.
- Collection regression reproduced. Page 2 repeated page 1 and Looks opened the product grid. The earlier merchant menu still contains the Men, Women, Denim, Accessories, Footwear and Lifestyle departments. The Shopify draft returned availability, price, colour and size filters. Grid/Focus and filter interaction are under repair.
- A new private Come Through candidate displays three real store addresses and directions. Its homepage and shared assets loaded. Mobile, keyboard and no-JavaScript interactions are being checked.
- [Signed shopper on TEST](https://github.com/EON-CRUX/3.09/pull/5493#issuecomment-6717837105) passed 10/10. A guest selected three pieces, signed in and got a styled look using one of them. Signing out cleared the next guest’s panel. Three related journeys passed another 25/25 steps on the same build. A second signed account still needs its separate privacy check.
- [October 3 homepage assembly](https://github.com/EON-CRUX/3.09/pull/5504) now renders exactly one Shop This Look, then Your edit and the Come Through store chapter, from eight candidate changes. The main Shop link and eight collection links reach the regular catalogue. The combined changes still need protected merges and installation on the private Shopify draft.

## What still needs to pass

- **5. Buyer trust and WhatsApp reviews** — The original diagnostic writer fixed the requested message/event capture. Hands integrated the shared test fix into #5490. Its hosted suite is under way. After release the staff TEST captain still needs to exercise Use, Dismiss, buyer consent and withdrawal on the connected flow.
- **6. Assistant privacy facts** — Two-account isolation is 8/9. Guest-to-signed styling and clearing the panel on sign-out passed 10/10. The second signed account reached a storefront password screen. The shared dependency #5505 merged. Hands integrated it into #5502 at 06:30 UTC. The TEST captain can repeat the last account-isolation check after #5502 passes hosted checks, merges and is served.
- **8. Final three-model ratings** — Final source still needs the repaired shopping journeys, 200% text and small-iPhone evidence. Last full scores: Fable 9.05, Opus 8.75; Astra unqualified. The three original readers perform the remaining named-fix checks on the same finished draft. Close only when each averages at least 9.5 and no measure is below 9.
- **10. Completed Shopify draft and handover** — Homepage and Identity original reviews/tests, closed-store correction, TEST checkout repair and native helper must finish; 0/7 current native journeys are verified. The release owners finish the existing lanes. Website lead installs eligible files privately and the original captains run connected TEST and iPhone checks. Close with the exact final theme files, complete journey evidence and handover.
- **11. BIG BAG page and navigation** — Desktop title fitting passed. Native product-to-Back restoration is still unverified. The original iPhone captain follows a Big Bag product and returns to the expected collection and scroll position. Close with that device receipt; this shares the native run with item 10.

The delivery target is a tested, unpublished Shopify draft. The owner decides when to publish.

## Update custody

This repository is owned by the existing GitHub account `anyiamobum-art`. GitHub Pages publishes the root of `main`. It does not use a ChatGPT Sites project or a ChatGPT login.

The task owner exports the existing canonical report with its saved `export_public.py`, verifies the public projection, and runs the saved `publish_public.sh`. The publisher uses the existing GitHub CLI authentication; no credential is stored in this repository. Do not put private reports, credentials, customer data or account identifiers here.

Refresh report fetches the published `report.json`. The page preserves its last snapshot if refresh fails. No background worker, rating, release or continuous monitoring is implied by this website.

The presentation reuses the shared Your task, in view template with a static hosting adapter. All three displayed final ratings remain pending until exact-source acceptance evidence is recorded.
