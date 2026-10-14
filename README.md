# Unkicks Footwear Website

A responsive multi-page static website starter for Unkicks. It can be previewed locally and hosted using GitHub Pages.

## Pages
- `index.html` — home
- `shop.html` — product catalogue with search, category filtering and sorting
- `categories.html` — footwear categories
- `product.html` — reusable product details page
- `about.html` — about the brand
- `delivery.html` — delivery information
- `contact.html` — contact details and WhatsApp enquiry form
- `faq.html` — frequently asked questions

## Preview
Open `index.html` in a browser. For best results, run a local static server from this folder (for example, VS Code Live Server) so `data/products.json` can be fetched correctly.

## Edit products
Edit `data/products.json`. Each product has an `id`, `name`, `category`, `price`, `image`, `description`, and `sizes`. The current entries are sample content. A `price` of `0` is intentionally displayed as a price-to-be-confirmed state. Replace sample images and information with verified Unkicks catalogue data before launch.

Images currently reference temporary external stock photography for demonstration; they are not actual Unkicks products. For your own images, place them in `assets/images/products/` and update the relevant `image` values in `data/products.json`.

## Brand contact details
- Email: `Unkicks234@gmail.com`
- WhatsApp: `+234 816 659 3750` (WhatsApp URL uses `2348166593750`)
- Delivery coverage: throughout Nigeria

## GitHub Pages deployment
1. Create a GitHub repository and upload the contents of this folder (ensure `index.html` is at the repository root).
2. Open **Settings → Pages** and select **GitHub Actions** as the source.
3. The included workflow deploys the static site on pushes to the default branch. If your repository uses a branch other than `main`, edit `.github/workflows/deploy.yml` to match.

## Important limitations
This is a static catalogue and enquiry website, not a full online store. Product search/filtering works in the browser. The contact form opens WhatsApp with the user's message; the visitor must press Send in WhatsApp. No cart, payment processing, secure order database, or email-form backend is configured. Do not advertise checkout or confirmed inventory until those systems are implemented.
