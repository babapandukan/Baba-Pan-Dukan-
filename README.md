# Baba Pan Dukan — Premium Web App

## Included
- Premium responsive black/green UI
- Paan catalog
- Cart and checkout
- Automatic Order ID
- Order tracking
- Sign Up / Login
- Account and order history
- Cash on Delivery (COD) only
- Demo admin order-status panel
- No WhatsApp order button

## GitHub Pages
1. Create a GitHub repository.
2. Upload all files in this folder to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. Open the generated GitHub Pages URL.

## Important
This version is a frontend demo. `localStorage` is used for accounts/orders, so it is browser-specific and not suitable for real multi-user production use.

For real production:
- Use a backend/database (e.g. Firebase/Supabase).
- Use a real payment gateway (e.g. Razorpay/Cashfree) and server-side verification.
- Never store passwords in localStorage.
