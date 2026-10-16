# Deployment checklist (mandatory)
1. Upload/deploy to Vercel and confirm actual **production domain** equals `rautenbach-associates.vercel.app`; if not, update absolute og:url, og:image, twitter:image, canonical, sitemap + structured data before approaching client.
2. Production should be publicly accessible without a Vercel login. Preview deployments may remain protected.
3. Request `https://rautenbach-associates.vercel.app/assets/rautenbach-whatsapp-preview.jpg` anonymously: HTTP 200 / Content-Type image/jpeg / 1200 × 630.
4. View page source (not only DOM inspector) and ensure og:image and twitter:image point to the absolute JPEG URL on the actual production domain.
5. Meta Sharing Debugger: force rescrape the final page URL, then test WhatsApp link preview. WhatsApp may cache prior previews; appearance is not guaranteed instantaneously.
6. Confirm photographs load and there are no duplicates across pages (stock image references are unique).
7. Inspect 320px, 390px, 768px, 1024px, 1440px; hero, mobile menu, forms, footer and map.
8. Client approval of identity, biographies, trademarks, photos, service claims and privacy notice required before official publication.
