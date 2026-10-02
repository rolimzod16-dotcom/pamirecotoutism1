# Pamir Ecotourism

Redesigned travel website. The deploy-ready static site is in `dist/`; `vercel.json` configures Vercel to serve it and permanently redirect the old URLs.

## Preview

https://pamir-ecotourism-reimagined.rolimzod16.chatgpt.site

## Deployment

Import this GitHub repository into Vercel. The static output directory and legacy 301 redirects are defined in `vercel.json`. After checking the Vercel deployment, connect `pamirecotourism.com` and `www.pamirecotourism.com`, then update only the necessary DNS records while preserving email records.

The contact form prepares an email in the visitor's mail app; it does not send server-side. Confirm prices, detailed itineraries and photography with the operator before the final launch.
