# TODO - Image links + description cards

## Plan
- [ ] Audit current image/pdf references in:
  - [ ] en/wines.html
  - [ ] it/wines.html
  - [ ] en/home.html
  - [ ] it/home.html
- [ ] Fix all broken image references for product/wine cards by using the correct filenames that exist under `assets/images/`.
- [ ] Ensure every wine and product “card” opens the correct `Desc...` PDF/PNG in `assets/images/`.
  - [ ] Add missing clickable links for products (non-wine section) in both `en/wines.html` and `it/wines.html`.
- [ ] Split the Spumanti category into two cards/images (since both are now separated) and correct image sizing so most images remain visible.
- [ ] Adjust CSS/image sizing rules if needed (card image height / object-fit / fixed heights) to improve visibility across responsive breakpoints.
- [ ] Quick visual sanity check by opening:
  - [ ] en/wines.html
  - [ ] it/wines.html
  - [ ] en/home.html
  - [ ] it/home.html

## Notes
- `Pic...` files are the visible card images.
- `Desc...` files are the clickable targets (PDF/PNG) opened by the card link.

