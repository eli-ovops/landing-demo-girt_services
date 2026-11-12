# Demo QA — Owner self-check

Status: **READY FOR INDEPENDENT VISUAL ACCEPTANCE**. This is not independent acceptance and does not use `CLIENT-SHOWABLE DEMO` as a final status.

## Browser evidence

| Viewport | Result | Evidence |
| --- | --- | --- |
| Desktop 1440×900 | PASS | `evidence/desktop_1440x900.png`; local static URL HTTP 200; no console/page errors; viewport width equals scroll width. |
| Mobile 390×844 | PASS | `evidence/mobile_390x844.png`; local static URL HTTP 200; no console/page errors; viewport width equals scroll width. |

Screenshots are full-page captures. Top/middle/bottom visual review was performed from them: Hero, service mosaic, method/proof, and the patio/contact close each retain an individual visual and commercial task. `viewport_audit.json` is the machine-readable record.

## Gate checklist

- Business fidelity: PASS. Business name/location, carpet/upholstery focus, named secondary services, public telephone/email and external booking route map to the research ledger. The only broadening image is explicitly generic concept imagery.
- Static boundary: PASS. No form, input, script, payment, quote calculator, login, storage or data collection exists. External booking stays external.
- CTA/link scope: PASS in local markup. `Book via Girt Services` uses the public booking URL; call and email use public business details. External destination interaction was not performed.
- Image uniqueness: PASS. Three unique hashes, three different placements and no repeat crop. See `IMAGE_LEDGER.md`.
- Client-visible internal-text gate: PASS. The visible `Independent concept preview` label is permitted and correctly describes the page. No local paths, AI, rights, PMO, pricing, QA, hash, TODO or authorisation language appears in client-visible content.
- Copy/claim audit: PASS. No score, testimonial quotation, response-time claim, price, fabricated project or machine claim. Recent public feedback is linked rather than reproduced.
- Accessibility: PASS for static review. Semantic landmark/header/main/footer, skip link, visible focus outline, descriptive concept-image labels, 48px CTA minimum height and mobile one-column collapse are present. No automatic movement; reduced-motion rule retains the complete static page.
- Finesse static detector: PASS. `p0: 0`; no findings. Runtime screenshot confirms the static hero visually renders, so no claimed-but-missing engine issue exists at SPECTACLE 3.

## Finesse / design-taste preflight receipt

- One soul / one accent: locked slate/ink with citrus orange. No green cleaning-template palette, purple glow, gradient text or glass UI.
- Premium substrate: tinted dark neutrals, low-opacity grain, translucent lines, compact high-contrast display typography and layered photo overlays are all visible in implementation.
- Layout diversification: hero split, offset service mosaic, four-step method line, proof panel and image/contact close. No layout family is used more than twice.
- Hard-ban scan: no visible em dash, fake numeric metric, placeholder, generic six-icon card grid, fake dashboard or customer-project misrepresentation.

## Remaining gates and risks

- `INDEPENDENT VISUAL ACCEPTANCE = AWAITING`. A different Owner must review the final Desktop/Mobile render and apply the ten-part rubric.
- `OFFER / TRANSFER PLAN = NOT RUN`. All three image assets are original Concept Demo visuals and must be replaced, excluded or confirmed before any final source handover.
- `CUSTOMER AUTHORIZATION = NOT VERIFIED`. No deployment, public URL, contact or email permission follows from this local Demo.

## Revision 2 — information coverage

- User-requested information: PASS in source. Current page includes the complete published service set, published service-area list, street address, phone, public business email, external booking URL, public Checkatrade link and public owner/contact context.
- Official logo and attributable official project images: `NOT VERIFIED / NOT AVAILABLE IN RECORDED PUBLIC SOURCES`; the page does not invent either. Concept visuals remain explicitly described as non-project imagery.
- `DIRECTION-LEVEL REBUILD COUNT = 2`.
- Final browser self-QA: PASS. Local HTTP check returned `200`; 1440px and 390px captures have no horizontal overflow (`scrollWidth == clientWidth`) and no page errors. Evidence: `evidence/revision2/{desktop,mobile}.png`, `browser-audit.json`.
