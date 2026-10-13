# Notes

## 1. What I changed
- Rebuilt the storefront around Mistvale's branding rules: calm tea-green palette, serif + sans-serif typography, softer card shapes and refined spacing.
- Fixed the broken cart and checkout logic so quantities, stock limits, coupon rules and shipping calculations follow the business rules.
- Reworked the shop experience so search, category filters and sorting stay in sync and sold-out teas stay last in every sort order.
- Replaced the placeholder visuals with lightweight SVG assets for the logo, hero banner and all eight product packs.
- Added accessible FAQ accordion behavior, keyboard-friendly form states, and a proper delivery pincode check with clear error states.

## 2. What the AI got wrong
- The starting page used loud, off-brand colours, exaggerated copy, fake sales claims and broken product logic.
- The cart logic had math errors, unbounded quantities, broken coupon handling and a checkout flow that never used the contract form correctly.
- Search and filter logic were not coordinated, and the page relied on heavy placeholder visuals instead of web-ready assets.
- The original page also used no real accessibility or SEO structure and did not respect the product/business rules.

## 3. Images
- Created new SVG or png artwork for the Mistvale logo, hero banner and all eight product packs in the `images/` directory.
- Product design uses consistent framing, earthy palettes and matching package styling for each item.

## 4. How I tested it
- Reviewed the store in a browser at desktop and narrow widths for layout and overflow issues.
- Checked that search, category filters and sort act together.
- Verified the cart logic for stock limits, coupon eligibility, shipping and final total rounding.
- Tested the delivery check with both valid and invalid pincode flows.
- Confirmed the page structure includes visible labels, keyboard focus states and accessible FAQ controls.

## 5. Questions for the team
- No blocking questions. The only ambiguous item was whether any additional store extensions were required; I kept the implementation focused on the core brief and quality bar.

## 6. Time spent
- Approximately 4 hours.

## 7. Extra features I added
- Modern FAQ accordion with accessible states.
- Countdown offer ticker in the hero section.
- Responsive cart drawer with quantity controls and shipping progress.
- Quick view product modal for faster browsing.

## 8. With more time I would…
- Add a dedicated product detail page, wishlist persistence and shareable URL state.
- Better tune the motion and micro-interactions for a more premium feel.
- Replace the vector product art with photoreal AI-generated product marketing images if the brand wanted a more luxurycampaign look.
