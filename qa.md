# ARETY Beauty House — QA

## Research sources

- Google Maps place: `ChIJPVVxyt2RqkARp0Q7LTLnjMc`; verified name, category, address, phone, geo, no official website, visible open/close status.
- Grabo official page: verified Facebook link, address, hours `Понеделник - Неделя: 11:00 - 19:00ч.`, services/description, one named client review by Галина, and gallery photos.
- Facebook: `https://www.facebook.com/aretybeautyhouse`, `/photos`, `/photos_albums`; verified public page and one usable work-result hairstyle image.
- Yahoo/search snippets: checked revieweuro, Grabo, Facebook, Instagram location, D&B. No official standalone website found.
- Studio24/Fresha/Oink: no verified official booking profile found for this exact business.

## Gates

1. Source/fact audit — PASS. Name, profession, address, phone, hours, map/place_id, Facebook, Grabo, testimonial, and images are source-backed. No prices, certifications, awards, guarantees, review counts, or invented claims in public copy.
2. Visual-result image audit — PASS with limitation. Facebook/Google Maps/Grabo/Instagram routes checked. Site uses the one verified public work-result image once near the top and supports it with real interior images. No duplicate visible images.
3. Testimonial audit — PASS. Uses exact Grabo review text with real reviewer name Галина. Google Maps reviews were checked but limited UI did not expose names/text; Grabo exposed a legitimate named review.
4. Copy audit — PASS. Bulgarian copy pass done; H1 includes category + location; no internal research language, no review counts, no dynamic details except stable hours.
5. Link/schema/SEO audit — PASS. Title, description, robots, canonical, OG tags, twitter card, one H1, schema, phone, Facebook, Grabo, map links present.
6. Image/layout audit — PASS pending screenshot. No repeated image files; portrait/landscape assets are placed in matching cards; no made-up captions.
7. Map/local SEO audit — PASS pending screenshot. Bottom map block directly above footer, one visible navigation CTA in map block, iframe URL uses full name/address.
8. Responsive visual QA — PASS after local screenshots: `artifacts/arety-local-desktop.png`, `artifacts/arety-local-mobile.png`; footer icons are consistent SVG circles.
9. Final live QA — PASS after deploy: live page HTTP 200; contains business name, Grabo testimonial phrase, canonical/OG/schema/map block.
