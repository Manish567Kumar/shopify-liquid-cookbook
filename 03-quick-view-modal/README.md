# 03 - Quick View Modal

Injects a "Quick View" button into collection/product grid cards and loads the product fragment via `?view=quick-view` into an accessible modal.

Usage
- Copy `snippet.liquid` into a global include or your theme's footer so it runs on collection pages.
- Add `templates/product.quick-view.liquid` (or include the `quick-view.liquid` fragment from this folder) so `?view=quick-view` returns the minimal product HTML.

Customization
- `CARD_SELECTOR` at the top of `snippet.liquid`: ``

Accessibility
- Close on overlay click and Escape key. Focus is moved into the modal when opened.

Demo
- demo.gif placeholder pending — please record and add `demo.gif` in this folder.
