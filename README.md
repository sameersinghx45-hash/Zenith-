# GameXReed — Gaming Redeem Store Demo

A mobile-friendly static storefront demo for Android beginners.

## Included
- Dark neon gaming storefront
- Product search and category filter
- Simulated checkout (does not collect money)
- Fictional demo-code delivery
- Demo orders and sample inventory panel
- Browser localStorage persistence

## Run on Android
1. Download and unzip `gamexreed-demo.zip`.
2. Open `index.html` in a browser, or open the files in a code editor app with an HTML preview.
3. To publish a static demo, create a GitHub repository and upload `index.html` (GitHub Pages can serve this static demo).
4. Keep the demo notice visible. Do not advertise demo codes as genuine or accept real payments through this static project.

## Before a real launch
This project is deliberately not a real payment or code resale system. It has no backend, secure admin authentication, server-side inventory, payment gateway, or webhook verification. Browser localStorage can be edited by visitors and must not be trusted for payment status or real code delivery.

For a legitimate production service, first secure authorized supply of genuine redeem codes and confirm the game/publisher and payment provider permit resale. Then build a server-side API and database, verify payment signatures and webhooks on the server, ensure each code is delivered at most once, protect admin access, and never expose secrets in frontend JavaScript. Work with a parent/guardian and the relevant provider for any real-money business setup.
