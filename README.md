# Easy Recharge Solution — Services Portal

A responsive static front-end concept for the Easy Recharge Solution business API portal.

## Pages
- `index.html` — overview and API catalogue
- `apis/whatsapp.html` — WhatsApp API service page
- `apis/sms.html` — Mobile SMS API service page
- `apis/plan.html` — Plan API service page
- `apis/gst.html` — GST API service page
- `developers.html` — developer centre
- `pricing.html` — pricing enquiry page
- `support.html` — contact and support
- `login.html` — redirects customers to the existing portal
- `privacy.html`, `terms.html` — draft policy placeholders

## Design
Forest green, muted mint, and lime palette inspired by the supplied references; responsive layout; CSS depth and perspective effects; reduced-motion support; intersection-based reveal animation; mobile navigation.

## Important launch checklist
1. This repository was empty when inspected, so these files establish the initial front-end.
2. The login page intentionally links to the current portal at https://wp.easyrechargesolution.com/ until the authentication migration is verified.
3. API endpoint details, prices, authentication schemes, metrics and operational claims are intentionally not fabricated. Replace service-page placeholders with verified information from the live backend.
4. Review the privacy and terms drafts before publishing.
5. Configure the hosting and DNS for services.easyrechargesolution.com after testing the pages and existing API/backend flows.
6. Verify relative paths and all pages in the actual hosting environment before launch.
