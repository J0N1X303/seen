# Seen. — V7.7 evaluation version

A standalone interactive story about unwanted attention, perspective and safe bystander action. The 13-scene V7.5 story is preserved; later phone views now include the complete earlier conversation.

## Preview locally

Download docs/index.html and open it in a browser. Everything in the story and fact sequence works offline. Citations, support sites and films need internet access. There are no remote fonts, media embeds, analytics, forms or saved responses.

## Publish for evaluators: GitHub Pages

In this repository, open Settings → Pages. Under Source choose **Deploy from a branch**, select **main** and **/docs**, then Save. GitHub will show the actual live address once deployment completes. The expected address is https://j0n1x303.github.io/seen/ — do not treat it as live until GitHub confirms and the page loads.

The connected GitHub tools can upload code but cannot enable Pages. This one-time setting needs the repository owner. Subsequent edits to docs/index.html will redeploy automatically after Pages is enabled. No build command or paid service is needed.

## Cloudflare alternative

This is the same buildless HTML approach used by Hendry Commercial, with a separate Worker configuration. Connect this repository as a new Cloudflare Workers project and use the included wrangler.jsonc (static directory docs). Do not connect it to or change the existing hendry-commercial Worker. No AI or database binding is needed. Cloudflare’s setup and any domain choice remain a separate owner action. See https://developers.cloudflare.com/workers/static-assets/get-started/.

## Evaluation behaviour

- End of story opens a choice: manual facts, explicit autoplay, or resources. Silent autoplay advances every 18 seconds.
- Pause, previous, next and skip remain available. Source focus, leaving the browser window and opening About pause playback. Reduced-motion preferences disable visual transitions; nothing autoplays without a deliberate choice.
- The final conversation starts at the newest messages. Scroll upward for the full history, or use Latest to return to the end. Keyboard scrolling within the phone does not advance the story.
- Share uses the hosted page’s URL, removing query parameters and fragments. Native sharing is used where available, then clipboard, then a selectable link. Local-file and localhost copies explain why they cannot provide a public URL.
- Search indexing is discouraged through robots metadata and robots.txt. This is not access control; the repository and any enabled public hosting remain publicly reachable.

## Content and review

Evidence was checked on 26 October 2026. See EVIDENCE.md for scopes and exclusions and VALIDATION.md for checks and limits. The story has not received independent specialist or lived-experience review. It is an evaluation copy, not certified training.

The current invitation is **Notice. Listen. Make a difference.** The earlier “not all men” proposals are assessed in the resources section. Women’s safety is not justified through comparisons with a viewer’s mother or partner, and the site makes no claim that perpetrators are always men.

