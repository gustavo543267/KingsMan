# KingsMan — Elevate Your Style

A responsive, premium menswear storefront built for the United Kingdom.

## Current storefront
- British English and GBP currency formatting.
- Responsive black, ivory and gold visual identity.
- Product collection with category filters and search.
- Shopping bag with quantity controls and subtotal.
- Editorial, newsletter and policy sections.
- Static-site compatible with Cloudflare Pages.

## Important launch requirements
This repository currently contains a **storefront prototype**, not a live transactional shop. Product names, prices and imagery are sample catalogue content. Do not accept orders until the following are configured and tested:

1. **Supplier / fulfilment:** create a merchant account with a dropshipping or print-on-demand provider (for example, Printful or Printify), choose actual products, confirm UK shipping, production costs, returns handling and delivery estimates.
2. **Payments:** connect a payment processor account (for example, Stripe) and configure a secure server-side checkout. Never put secret API keys in browser JavaScript or commit them to this repository.
3. **Legal pages:** publish accurate UK terms, privacy/cookie notice, returns/refunds policy, delivery information, business contact details and required company/tax information.
4. **Operations:** test a complete order, fulfilment, refunds, customer emails and stock/variant sync before launch.

The shopping bag is currently a front-end demonstration. Checkout and newsletter submission are intentionally not represented as active services.

## Free static hosting
Connect this GitHub repository to Cloudflare Pages:
- Framework preset: None
- Build command: leave blank
- Build output directory: repository root (/)
- Production branch: main

Enable automatic deployments from the GitHub integration. Every push to main will then trigger a new Pages deployment. Hosting can be free within Cloudflare's current free-plan limits; payment processing, supplier fulfilment, domain names and some business services may have separate costs.

## Files
- index.html — storefront structure
- styles.css — responsive visual design
- app.js — catalogue, filters and shopping bag
