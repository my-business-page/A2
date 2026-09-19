# Website Blueprint — SOFT HOUR

## Research snapshot — 20 Sep 2026
- Business: soft hour
- Type: Home-based matcha/hojicha takeaway
- Area: Yew Tee, Singapore
- Public pickup location: 680543, level 12, first unit on the left, next to Yew Tee CC.
- Instagram: @hello.softhour — independently evidenced.
- Current ordering: Take App / Tabaous. Listings state takeaway-only and direct customers to Instagram for operating hours.
- Current menu evidence: iced matcha latte, strawberry matcha, Earl Grey whisper matcha, honey lemon matcha, banana comfort matcha, Biscoff comfort matcha, sea-salt foam matcha, honey miso mellow matcha, hojicha variants and seasonal drinks.
- Phone/WhatsApp: not independently verified.
- Standalone official domain: none found in this pass.
Sources: https://take.app/hellosofthour ; https://tabaous.com/hellosofthour ; https://newsletter.myttc.org.sg/our-community/soft-hour/

## Product/website objective
Give the community-focused brand a calm, memorable digital home that reduces dependence on Instagram for menu discovery, hours and ordering.

## Multipage architecture
1. Home — “quiet sips & slower hours”, live status, signature drink, preorder.
2. Matcha Menu — matcha/hojicha grouped by flavour profile.
3. Our Ritual — hand-whisking and ingredient story.
4. Community — founders, Yew Tee roots, community initiatives, customer notes.
5. Visit & Order — pickup directions and ordering workflow.
6. Seasonal Journal — rotating drinks and announcements.
7. FAQ.
8. Contact.

## Visual direction
Soft cream, matcha green, muted cocoa and cloud white. Japanese-inspired editorial minimalism without clichés. Rounded but disciplined cards, lots of breathing room, subtle hand-drawn accents.

## Motion + VFX
- Hero: restrained matcha whisk particle/ink texture.
- Scroll reveals: opacity + y + blur with staggered drink ingredients.
- Desktop ingredient/story rail with mobile vertical fallback.
- Drink cards: gentle 3D tilt + image-mask reveal.
- Ritual sequence animates sift → water → whisk → pour.
- Section exit fade/scale; never abrupt.
- Page transition: cream-to-green wipe.
- Reduced-motion fallback.

## Functional requirements
- Prominent current ordering-platform CTA.
- Editable hours/status and sold-out/seasonal states.
- Instagram link/feed integration without scraping private content.
- Owner-approved pickup/map information only.
- Contact/enquiry route.
- Mobile-first performance and accessibility.

## Content rules
Preserve the documented community story. Do not claim health benefits. Do not expose unnecessary residential details. All current prices/hours remain editable.

## Technical direction
Separate CSS/JS/components; GSAP + ScrollTrigger; lightweight WebGL only for hero texture/whisk effect; lazy-loaded optimized imagery.