# Custom Upsell Product Block for Shopify
The custom-upsell.liquid snippet creates an upsell product block that can be added to your product pages.

## How to:
1. Copy and paste the settings from product-block-settings.json into your product.liquid [section] file within your blocks array
2. Copy and paste product-snippet-reference to reference and pass all setting values into the custom-upsell snippet. This will need to be pasted where all your other product blocks are being rendered, most likely in a product.liquid snippet.
3. Create a new snippet labeled custom-upsell.liquid and copy and paste customer-upsell.liquid above.

You now have a custom upsell product block you can add to all your product pages. You can assign a product, title, description, and cta text. If you'd like for this to be dynamic, by default all of these settings can be used via metafields.
