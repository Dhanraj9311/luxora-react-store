# LUXORA — React Fashion Storefront

A responsive fashion ecommerce frontend inspired by the supplied LUXORA reference image. Built with React, Vite, plain CSS, and Lucide icons.

## Features
- Editorial hero, brand story, newsletter, and responsive footer
- Product grid with Women / Men / Accessories categories
- Search and sort (featured, price low-high, price high-low, name)
- Quick-view product modal with size selection
- Add to cart, quantity changes, remove items, subtotal, shipping progress
- Cart and wishlist saved in `localStorage`
- Demo checkout confirmation (does not take payment or submit a real order)
- Responsive mobile navigation and layouts

## Run locally
1. Install [Node.js](https://nodejs.org/) (Node 18+ recommended).
2. Extract this ZIP and open a terminal in the `luxora-store` folder.
3. Run:
   ```bash
   npm install
   npm run dev
   ```
4. Open the local URL Vite prints (usually `http://localhost:5173`).

## Production build
```bash
npm run build
npm run preview
```

## Notes
- Product photography is loaded from Unsplash URLs, so an internet connection is required for those images.
- This is a frontend demo. Real payments, user authentication, inventory, order storage, and admin management need a backend and payment provider integration.
- To edit products, change the `products` array in `src/main.jsx`.
