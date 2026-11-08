# CRUX website progress

[Open the visual checklist](https://anyiamobum-art.github.io/crux-website-progress/)

## Current delivery

**55% verified · 45% remaining**

6 of 11 delivery items verified. 5 remain (45% of this checklist, not work hours). 0 of 3 passing ratings.

Last verified 08 November, 00:49 UTC. Six of eleven delivery gates are verified. Signed privacy is 8/9, native iPhone journeys 0/7, and final passing ratings 0/3.

The public history first shows six on 13 October. A reversal on 14 October brought it to five. On 15 October it returned to six. As of 8 November, 24 days have passed since six items were last verified. Each item counts once. The percentages track signed-off outcomes. The remaining testing and reviews have no verified time estimate.

## What changed

- [Shop This Look](https://github.com/EON-CRUX/3.09/pull/5518#issuecomment-6714903287) returned to the same outfit and exact scroll position after visiting Luffy Tee and pressing Back. Both starting points passed, at 1,157 px from home and 844 px from the collection link. Hands accepted the corrected version for its second review. The verdict and five queued test groups remain open.
- [Stores](https://github.com/EON-CRUX/3.09/pull/5519#issuecomment-6714936124) fixed a 16-pixel jump when the distance message wraps at a 390-pixel width. Clearing the selection now has a check on the first animation frame. All 21 Stores tests passed. [Second code review passed](https://github.com/EON-CRUX/3.09/pull/5519#issuecomment-6715100263). Five hosted test groups, merge, and the installed iPhone check remain open.
- [Product gallery](https://github.com/EON-CRUX/3.09/pull/5524#issuecomment-6715049052) held the inspected back view when changing sizes. Choosing Blue instead of Red switched to Blue’s lead photo. This passed six private Chromium cases across 380, 430 and 1,280 px with normal and reduced motion, using a test product. The change is in a separate pull request.
- [Homepage](https://github.com/EON-CRUX/3.09/pull/5504) now has an offline 42-file assembly with one Shop This Look, the saved edit, and a store invitation in that order. The combined preview opened the three-store directory and selected Abuja. On Back, Chrome could restore the focused link but jump 2,209 px to the top. When it recreated the page, it kept the scroll position but lost keyboard focus. The homepage builder traced the jump to the archived catalogue script and is repairing this return path.
- Collection viewer — At 380 × 667 the garment photo is now 465 px tall, up from 253 px. At 320 × 568 the full product link is reachable. The six Chromium sizes passed. The Linux WebKit browser crashed before its assertions. The private preview links to the 404 Tee, 90s Rugged Shirt and 99 Yellow Jersey product pages.

## What still needs to pass

- **5. Buyer trust and WhatsApp reviews** — All five automated groups passed for the diagnostic that records what happens when Prepare quote fails. Its reviewer requested changes to the captured messages and events. The shopper-facing result still needs a connected TEST run. The staff TEST captain checks Use, Dismiss, buyer consent and withdrawal on the served change.
- **6. Assistant privacy facts** — The signed run passed 8 of 9 checks. The second shopper reached a TEST password screen. Its #5502 fix passed one review, but two hosted test groups failed. The shared repair passed three test groups and two are queued. After #5505 merges, Hands merges main into #5502 and runs the suite once. After release, the TEST captain repeats the second-shopper check.
- **8. Final three-model ratings** — Final source still needs the repaired shopping journeys, 200% text and small-iPhone evidence. Last full scores: Fable 9.05, Opus 8.75; Astra unqualified. The three original readers perform the remaining named-fix checks on the same finished draft. Close only when each averages at least 9.5 and no measure is below 9.
- **10. Completed Shopify draft and handover** — Homepage and Identity original reviews/tests, closed-store correction, TEST checkout repair and native helper must finish; 0/7 current native journeys are verified. The release owners finish the existing lanes. Website lead installs eligible files privately and the original captains run connected TEST and iPhone checks. Close with the exact final theme files, complete journey evidence and handover.
- **11. BIG BAG page and navigation** — Desktop title fitting passed. Native product-to-Back restoration is still unverified. The original iPhone captain follows a Big Bag product and returns to the expected collection and scroll position. Close with that device receipt; this shares the native run with item 10.

The delivery target is a tested, unpublished Shopify draft. The owner decides when to publish.

## Update custody

This repository is owned by the existing GitHub account `anyiamobum-art`. GitHub Pages publishes the root of `main`. It does not use a ChatGPT Sites project or a ChatGPT login.

The task owner exports the existing canonical report with its saved `export_public.py`, verifies the public projection, and runs the saved `publish_public.sh`. The publisher uses the existing GitHub CLI authentication; no credential is stored in this repository. Do not put private reports, credentials, customer data or account identifiers here.

Refresh report fetches the published `report.json`. The page preserves its last snapshot if refresh fails. No background worker, rating, release or continuous monitoring is implied by this website.

The presentation reuses the shared Your task, in view template with a static hosting adapter. All three displayed final ratings remain pending until exact-source acceptance evidence is recorded.
