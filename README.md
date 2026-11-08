# CRUX website progress

[Open the visual checklist](https://anyiamobum-art.github.io/crux-website-progress/)

## Current delivery

**55% verified · 45% remaining**

6 of 11 delivery items verified. 5 remain (45% of this checklist, not work hours). 0 of 3 passing ratings.

Last verified 08 November 2026, 16:50 UTC.

The public history first shows six on 13 October. A reversal on 14 October brought it to five. On 15 October it returned to six. As of 8 November, 24 days have passed since six items were last verified. Each item counts once. The percentages track signed-off outcomes. The remaining testing and reviews have no verified time estimate.

## What changed

- [Product size guide #5555](https://github.com/EON-CRUX/3.09/pull/5555) adds cm and inches to the product page. Forty size and option tests passed. Chromium at 380, 430 and 1280 px verified size selection and the saved unit. Mac WebKit also verified conversion, selection and touch targets at 320, 380 and 430 px. All 34 hosted mutation checks passed. The website lead has handed this revision to Hands for protected review. Shopify installation and iPhone verification are pending.
- [Collection button alignment #5554](https://github.com/EON-CRUX/3.09/pull/5554) corrects an offset of up to 42 px. All 78 rows tested in Best sellers and New arrivals now align.
- In the private [Shop This Look preview change #5556](https://github.com/EON-CRUX/3.09/pull/5556), twelve garment hotspots across five outfits opened ten matching product destinations. The phone-width browser returned from Luffy Tee to the same look and scroll position. The underlying change passed its [final named-fix code review](https://github.com/EON-CRUX/3.09/pull/5518#issuecomment-6723771752). Hosted testing and private installation are still open.
- [Shop navigation #5542](https://github.com/EON-CRUX/3.09/pull/5542) gives Collections its own header control. The [collection review](https://github.com/EON-CRUX/3.09/pull/5535#issuecomment-6723508212) found that Quick buy could offer an excluded variant and menu URLs with options could lose their selected state. Both repairs are committed. Tests and the independent visual check are in progress.
- [Stores motion #5519](https://github.com/EON-CRUX/3.09/pull/5519) merged and was installed in the Shopify draft. The served source maps match the approved files. A phone-width browser selected Chevron, then Palms. The first tap before the page became interactive did not switch stores. Native iPhone testing and removal of the closed Osapa listing are separate. The [signed privacy test](https://github.com/EON-CRUX/3.09/actions/runs/42475063547) passed all nine steps.

## What still needs to pass

- **5. Buyer trust and WhatsApp reviews** — The TEST desk draft needs to be linked to the correct Shopify customer. The repair is in review intake under #5546. Once that repair is served, the original TEST captain uses a fresh test order to check Use and Dismiss. Buyer publication consent and withdrawal each need a recorded result.
- **6. Assistant privacy facts** — The signed export and deletion journey passed all nine steps. Switching between two shoppers in the same browser still needs its attended check. The original TEST captain verifies that the second shopper cannot see the first shopper’s saved look or recommendations.
- **8. Final three-model ratings** — Final source still needs the repaired shopping journeys, 200% text and small-iPhone evidence. Last full scores: Fable 9.05, Opus 8.75; Astra unqualified. The three original readers perform the remaining named-fix checks on the same finished draft. Close only when each averages at least 9.5 and no measure is below 9.
- **10. Completed Shopify draft and handover** — Homepage and Identity original reviews/tests, closed-store correction, TEST checkout repair and native helper must finish; 0/7 current native journeys are verified. The release owners finish the existing lanes. Website lead installs eligible files privately and the original captains run connected TEST and iPhone checks. Close with the exact final theme files, complete journey evidence and handover.
- **11. BIG BAG page and navigation** — The installed draft previously moved the selected lamp by 394 px on Back. The builder reproduced and fixed the position in a controlled browser, and corrected the stale TEST file fingerprint. The updated source is in hosted checks. Narrow-layout repair #5544 has separate checks. Verify the same card, scroll and focus on the installed theme on desktop and iPhone. Check the narrow title and sort label. [Browser result and repair](https://github.com/EON-CRUX/3.09/pull/5541#issuecomment-6724212379)

The delivery target is a tested, unpublished Shopify draft. The owner decides when to publish.

## Update custody

This repository is owned by the existing GitHub account `anyiamobum-art`. GitHub Pages publishes the root of `main`. It does not use a ChatGPT Sites project or a ChatGPT login.

The task owner exports the existing canonical report with its saved `export_public.py`, verifies the public projection, and runs the saved `publish_public.sh`. The publisher uses the existing GitHub CLI authentication; no credential is stored in this repository. Do not put private reports, credentials, customer data or account identifiers here.

Refresh report fetches the published `report.json`. The page preserves its last snapshot if refresh fails. No background worker, rating, release or continuous monitoring is implied by this website.

The presentation reuses the shared Your task, in view template with a static hosting adapter. All three displayed final ratings remain pending until exact-source acceptance evidence is recorded.
