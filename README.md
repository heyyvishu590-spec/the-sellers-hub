# The Sellers Hub

A static marketplace prototype with:
- Buyer product browsing/search
- Cart and demo checkout
- Seller product dashboard
- Add/delete products
- Local browser storage

## Live on GitHub Pages

1. Create a GitHub repository named `the-sellers-hub`.
2. Upload `index.html`, `style.css`, `app.js`, and `README.md`.
3. GitHub → **Settings** → **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then **Save**.
6. Wait 1–3 minutes. GitHub will show your Pages URL.

For a custom domain such as `thesellershub.in`, add the domain under GitHub Pages → Custom domain, then configure DNS at your domain provider.

## Important

This is a frontend prototype. Data is stored in each browser's localStorage. It is NOT a real multi-user marketplace yet.

For production, connect:
- Supabase/Firebase/PostgreSQL backend
- Real authentication
- Product/image storage
- Payment gateway
- Orders database
- Seller/admin permissions
- Shipping and notifications
