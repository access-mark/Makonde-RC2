# Makonde Investments — Draft 1.1 (polished review build)

A dependency-free static HTML/CSS/JavaScript website prototype. Open `index.html` locally or deploy the directory to GitHub Pages for private review.

## Brand
- `assets/makonde-logo-transparent.png`: new transparent logo supplied/approved in the conversation, best on light backgrounds.
- `assets/makonde-logo-light.png`: adapted silver/white treatment for dark header and footer; verify visually with Makonde.
- The previous dark-background logo is not used by the pages.

## Structure
Home, About, Solutions overview, three solution pages, Industries, Technology Partners, Insights, Contact, Privacy, Terms and Accessibility.

## Important: draft, not production-ready
- Contact form prepares a `mailto:` message in the visitor's email application; it does not submit data to a server. Configure authenticated delivery and test before launch.
- All pages intentionally have `noindex,nofollow`; `robots.txt` disallows crawling while the site is a draft. Remove these only after launch approval.
- Partner agreements, logos, endorsements, case studies and any B-BBEE level / registrations / accreditations must be verified before publishing.
- Privacy, terms and accessibility pages are draft copy requiring review.
- No tracking or third-party JavaScript is installed.
- All functionality should be browser-tested on desktop/mobile and verified in staging before launch.

## Security
- No executable binaries, PowerShell, batch scripts, external script dependencies, or remote embeds are included.
- The archive was created afresh from the locally available Draft 1 rebuilt source, not from the previously Defender-flagged archive.
- A successful ZIP integrity test is not an antivirus clearance. Scan locally before extraction and keep Defender enabled.

## Draft 1.2 executive refinement
- Desktop content max-width expanded to 1440px, with responsive fallbacks.
- Header wordmark, navigation, hero typography, priority panels, solution cards and section spacing increased.
- Home solution summaries rewritten around outcomes; each dedicated solution page has five explanatory capability cards and a three-part outcome band.
- No backend changes: contact form remains mailto-based and is not a verified submission service.
- Editorial and design changes require human review. Browser and mobile acceptance testing is not claimed.
