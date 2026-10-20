# The Ninth Door — Official Redirector Website

A responsive, gothic-style author/book landing page designed to send readers to your marketplace checkout. It does not host the book PDF and does not process payments itself.

## Before publishing
1. Create your product listing on your chosen marketplace (for example, Gumroad).
2. Open `config.js`.
3. Set `productUrl` to the exact HTTPS product/checkout URL supplied by your marketplace. Example format only: `https://your-marketplace.example/your-product` — replace this with your real link.
4. Upload the entire folder to your website host, preserving the `assets` folder and `config.js` alongside `index.html`.
5. Test both purchase buttons on desktop and mobile.

If `productUrl` is blank, the purchase buttons show a setup notice rather than sending customers to a fake URL.

## Included
- `index.html` — responsive single-page book site and redirect buttons
- `config.js` — one place to configure your real marketplace URL
- `assets/the-ninth-door-cover.png` — cover artwork

## Security and delivery
The site only redirects visitors; it does not contain the full manuscript or a public PDF download link. Marketplace purchase, payment confirmation, delivery, and any buyer-specific PDF stamping must be configured in the marketplace account. A redirector alone cannot verify payment or apply personalized watermarks.
