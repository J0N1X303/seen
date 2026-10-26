# Verification

Tested 26 October 2026 in installed Microsoft Edge through Playwright, using isolated headless browser contexts.

- desktop: full story, exact message continuity, no horizontal overflow, manual facts, autoplay opt-in/pause, skip, return, restart, local-share explanation; no remote requests
- mobile: full story, exact message continuity, no horizontal overflow, manual facts, autoplay opt-in/pause, skip, return, restart, local-share explanation; no remote requests
- small-mobile: full story, exact message continuity, no horizontal overflow, manual facts, autoplay opt-in/pause, skip, return, restart, local-share explanation; no remote requests
- Timing: opt-in required; 18-second advancement; source focus pauses; pause focus preserved; end opens resources
- No JavaScript runtime errors.

Viewport sizes: 1440×1000, 390×844 and 320×740. Small-phone run uses prefers-reduced-motion: reduce. Screenshots reviewed for desktop facts, narrow-phone facts, phone message history and mobile resources.

Story scenes 2–13 match V7.5 exactly, including perspectives and ordering. Cover has a content note. For slides 8, 10 and 13, the rendered message arrays were checked against the original arrays; slides 10 and 13 contain the cumulative chronological history.

Limits: these are responsive browser checks, not tests on physical iOS/Android devices or a full assistive-technology audit. Hosted platform sharing, permissions and deployment cannot be claimed verified before a live URL exists. External support pages and source content were read; third-party film playback was not tested. Specialist/lived-experience review remains outstanding.

Live verification: https://j0n1x303.github.io/seen/ returned HTTP 200 on 26 October 2026. Published HTML matched the local package exactly. Live desktop and mobile checks passed for the full story, cumulative final conversation, optional facts, resources and share control. Hosted URL simulation separately verified native-share data, clipboard, denied-permission fallback and cancellation without sending a share.

V7.7 amendment checks: full functional suite passed against the revised HTML at 1440×1000, 390×844 and 320×740. Exact original story and cumulative message arrays preserved. New About copy and all three replacement fact cards checked in all three layouts; screenshots reviewed. About contains the direct call for men to step up and no prototype/review disclaimer. Scope, dates and source links remain visible on each fact card. Deployment verification follows separately.

