# Shopify Dawn Theme Customization

**Base Theme Version:** Dawn v15.3.0

## Setup & Testing

1. **Install theme** as usual in your Shopify store (Dawn v12+ recommended).
2. **Add/Configure sections and settings** in the Shopify Theme Editor:
   - Add the "Featured Banner" section to your homepage and configure its settings.
   - On product pages, enable the "Show back in stock message" option in the Buy Buttons block to display dynamic inventory messages.
3. **Test**:
   - Check the homepage for the Featured Banner section (responsive, with all settings).
   - On product pages, select different variants to see the stock message update live.

## Files Added or Edited

- `sections/featured-banner.liquid`  
  Custom homepage banner section (configurable, responsive, translation-ready)
- `assets/section-featured-banner.css`  
  Styles for the Featured Banner section
- `snippets/back-in-stock-message.liquid`  
  Renders dynamic stock message on product page
- `assets/product-info.js`  
  Handles live updates for the stock message
- `sections/main-product.liquid`  
  Edited to conditionally include the stock message snippet
- `locales/en.default.json` and `locales/en.default.schema.json`  
  Added translation keys for new features

---

All code is compatible with Dawn v12+ and uses only native Shopify Liquid, JS, and CSS. No external dependencies required.
