# CRUX website progress

[Open the visual checklist](https://anyiamobum-art.github.io/crux-website-progress/)

## Current delivery

**55% verified · 45% remaining**

6 of 11 delivery items verified. 5 remain (45% of this checklist, not work hours). 0 of 3 passing ratings.

Last verified 08 November, 07:27 UTC. Six of eleven delivery gates are verified. Signed privacy is 8/9, native iPhone journeys 0/7, and final passing ratings 0/3.

The public history first shows six on 13 October. A reversal on 14 October brought it to five. On 15 October it returned to six. As of 8 November, 24 days have passed since six items were last verified. Each item counts once. The percentages track signed-off outcomes. The remaining testing and reviews have no verified time estimate.

## What changed

- [Shop This Look](https://github.com/EON-CRUX/3.09/pull/5518#issuecomment-6715286929) restored the right outfit on the plain homepage and the original collection link. Its second review found one more path: jump to a section after arriving on the homepage, open another outfit, visit its product and press Back. The original designer reproduced the failure and is qualifying the fix for the last review.
- [Stores](https://github.com/EON-CRUX/3.09/pull/5519#issuecomment-6715100263) passed its second code review and four of five hosted test groups. The fifth failed a board-feed timing check outside the Stores files. The release desk queued one whole rerun. The change removes the 16 px jump when the distance message wraps and handles Clear on its first frame.
- [Product gallery](https://github.com/EON-CRUX/3.09/pull/5524) held the back view when changing sizes and switched to the correct lead photo on a colour change. Six private Chromium cases passed. Hands accepted this revision; it awaits the release desk’s review slot.
- [Homepage return from Stores](https://github.com/EON-CRUX/3.09/pull/5532) restored the Find a store link to the original 386 px screen position after a trip to Abuja. Keyboard focus returned to the link and the next Tab reached Explore all. Both cached and recreated pages passed. Nine tests and thirteen mutation checks passed. Its five-file PR depends on the original homepage change #5504.
- [Collection viewer](https://github.com/EON-CRUX/3.09/pull/5531) enlarged the photograph from 253 to 465 px at a 380 × 667 viewport and kept the full product link reachable on a 320 × 568 screen. All six Chromium layouts passed. Mac WebKit opened the rendered 90s Rugged Shirt variant and returned to the collection at both widths. The full Linux WebKit suite still fails to load the collection on both the original and changed source.

## What still needs to pass

- **5. Buyer trust and WhatsApp reviews** — The original diagnostic writer fixed the requested message/event capture. Hands integrated the shared test fix into #5490. Its hosted suite is under way. After release the staff TEST captain still needs to exercise Use, Dismiss, buyer consent and withdrawal on the connected flow.
- **6. Assistant privacy facts** — 8 of 9 passed. The second signed shopper reached a storefront password screen. The shared dependency #5505 merged. Hands integrated it into #5502 at 06:30 UTC. The TEST captain can repeat the last account-isolation check after #5502 passes hosted checks, merges and is served.
- **8. Final three-model ratings** — Final source still needs the repaired shopping journeys, 200% text and small-iPhone evidence. Last full scores: Fable 9.05, Opus 8.75; Astra unqualified. The three original readers perform the remaining named-fix checks on the same finished draft. Close only when each averages at least 9.5 and no measure is below 9.
- **10. Completed Shopify draft and handover** — Homepage and Identity original reviews/tests, closed-store correction, TEST checkout repair and native helper must finish; 0/7 current native journeys are verified. The release owners finish the existing lanes. Website lead installs eligible files privately and the original captains run connected TEST and iPhone checks. Close with the exact final theme files, complete journey evidence and handover.
- **11. BIG BAG page and navigation** — Desktop title fitting passed. Native product-to-Back restoration is still unverified. The original iPhone captain follows a Big Bag product and returns to the expected collection and scroll position. Close with that device receipt; this shares the native run with item 10.

The delivery target is a tested, unpublished Shopify draft. The owner decides when to publish.

## Update custody

This repository is owned by the existing GitHub account `anyiamobum-art`. GitHub Pages publishes the root of `main`. It does not use a ChatGPT Sites project or a ChatGPT login.

The task owner exports the existing canonical report with its saved `export_public.py`, verifies the public projection, and runs the saved `publish_public.sh`. The publisher uses the existing GitHub CLI authentication; no credential is stored in this repository. Do not put private reports, credentials, customer data or account identifiers here.

Refresh report fetches the published `report.json`. The page preserves its last snapshot if refresh fails. No background worker, rating, release or continuous monitoring is implied by this website.

The presentation reuses the shared Your task, in view template with a static hosting adapter. All three displayed final ratings remain pending until exact-source acceptance evidence is recorded.
