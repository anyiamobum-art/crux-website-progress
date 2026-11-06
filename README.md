# CRUX website progress

[Open the visual checklist](https://anyiamobum-art.github.io/crux-website-progress/)

## Current delivery

**55% verified · 45% remaining**

6 of 11 delivery items verified. 5 remain (45%). 0 of 3 passing ratings.

Last verified 6 November, 23:21 UTC. Six of eleven delivery items are verified. Seven current iPhone journeys and three passing whole-draft ratings remain.

The public history first shows six on 13 October. A reversal on 14 October brought it to five. On 15 October it returned to six. As of 6 November, 22 days have passed without another full item closing. Each item counts once. The percentages track signed-off outcomes. The remaining testing and reviews have no verified time estimate.

## What changed

- The Add to bag plus passed both protected reviews and merged. Shopify returned both reviewed files from the unpublished draft. In a fresh Safari bag, one tap added one pendant and removing it returned the bag to empty. [Merged repair](https://github.com/EON-CRUX/3.09/pull/5354) · [Final code approval](https://github.com/EON-CRUX/3.09/pull/5354#issuecomment-6697482657)
- Four of five test groups passed for the closed-store repair. The fifth failed a shared test about which runner may take a job. Its test and reader match the base revision. The chair authorized a full retry with all checks intact. The release desk owns its placement. The store correction still awaits merge. [Failed shared test](https://github.com/EON-CRUX/3.09/actions/runs/42162738189/job/128098276032)
- A staff TEST repair hit a 30-second Runway timeout. Its nine interactions passed in 1.09 seconds in isolation, and that same test passed on another hosted run. The chair approved the next hosted attempt. Staff Use and Dismiss are still unverified. [Failing group](https://github.com/EON-CRUX/3.09/actions/runs/42191707389/job/128104504383) · [Passing comparison](https://github.com/EON-CRUX/3.09/actions/runs/42145632035/job/128095200115)
- The TEST tee returned zero looks and kept the rail hidden. Eight checks passed, including the signed panel. The separate tests for guest-to-sign-in and saved naira budgets passed both code reviews, merged and are now available to run. The saved-style download failed at step six and still needs repair. [TEST tee and panel receipt](https://github.com/EON-CRUX/3.09/actions/runs/42142774375) · [Merged test change](https://github.com/EON-CRUX/3.09/pull/5471) · [Download repair](https://github.com/EON-CRUX/3.09/pull/5472)
- The shopping assistant comparison finished. JEV answered 33 of 100 test cases and agreed with Fable on 24 of those 33. Neither proposed an incorrect bag. Fable stays in charge of shopping decisions. [Decision repair](https://github.com/EON-CRUX/3.09/pull/5394)

## What still needs to pass

- **5. Buyer trust and WhatsApp reviews** — The staff repair’s second hosted run timed out in a Runway test. The same test passed elsewhere, and all nine interactions passed on the exact source in isolation. Finish the chair-approved hosted retry, then verify the staff Use and Dismiss actions, buyer publication consent and withdrawal.
- **6. Assistant privacy facts** — The signed shopper saved a look, then the data download failed at step six. The diagnostic repair has its first code approval. Complete review of the diagnostic, use it on the original two TEST accounts, then verify export, deletion and account separation.
- **8. Final three-model ratings** — The current homepage still needs a 200% text check, connected shopping evidence, and small-iPhone timing. The last full reviews gave Fable 9.05 and Opus 8.75. Astra could score only one measure. Return the same tested draft to the three original readers for their final check of the named repairs. Each reader must average at least 9.5 with every measure at 9 or above.
- **10. Completed Shopify draft and handover** — The small iPhone booted but product discovery returned HTTP 429. The shared date-sensitive test has a merged fix. The separate product-discovery helper needs its protected rerun and device allocation. Both first-add journeys passed. The homepage integration and remaining connected TEST checks are open. Take the homepage integration through review and private installation, then test the installed homepage. The final checks include 200% zoom, selecting a size and store directions.
- **11. BIG BAG page and navigation** — The installed title fits at widths of 320, 380 and 1280 pixels. The native shopping journey and return to the collection still need a device check. Follow a product from Big Bag, use Back and verify that the shopper returns to the expected place. Include that result in the final review.

The delivery target is a tested, unpublished Shopify draft. The owner decides when to publish.

## Update custody

This repository is owned by the existing GitHub account `anyiamobum-art`. GitHub Pages publishes the root of `main`. It does not use a ChatGPT Sites project or a ChatGPT login.

The task owner exports the existing canonical report with its saved `export_public.py`, verifies the public projection, and runs the saved `publish_public.sh`. The publisher uses the existing GitHub CLI authentication; no credential is stored in this repository. Do not put private reports, credentials, customer data or account identifiers here.

Refresh report fetches the published `report.json`. The page preserves its last snapshot if refresh fails. No background worker, rating, release or continuous monitoring is implied by this website.

The presentation reuses the shared Your task, in view template with a static hosting adapter. All three displayed final ratings remain pending until exact-source acceptance evidence is recorded.
