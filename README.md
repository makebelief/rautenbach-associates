# Rautenbach & Associates — Wakili wa Tech demonstration

Independent nine-page static HTML, CSS and JS website concept, based on the original Wakili wa Tech house design.

Production target: https://rautenbach-associates.vercel.app (confirm alias after Vercel deploy; production link must be public for WhatsApp crawlers).

## Content sources
- Original uploaded assets: firm logo, Magda Rautenbach portrait, advertising brochure.
- Public business details: https://www.attorneys.co.za/CompanyHomePage.asp?CompanyID=2005 and https://www.attorneys.co.za/AttorneyHomePage.asp?AttorneyID=8551&CompanyID=2005
- Legal Directory: https://legaldirectory4sa.co.za/listing/rautenbach-associates

## WhatsApp preview
A local 1200x630 JPEG combines the **firm logo + attorney portrait** in `assets/rautenbach-whatsapp-preview.jpg`.
All 9 website pages have absolute OG/Twitter image URLs. Before sharing, check direct JPEG URL responds HTTP 200 anonymously without Vercel Authentication, then use the Meta Sharing Debugger and rescrape.

## Notes
- Enquiry form intentionally opens an email draft to magda@rautenbach.associates, not WhatsApp.
- Published number 082 925 3886 is not independently confirmed WhatsApp-enabled.
- Draft is noindex pending client approval and eventual privacy/legal review.
- Local homepage images: hero and property legal still-life. Remote Pexels images are unique per content placement and require live loading checks.
- Magda's uploaded portrait is relatively small (317 x 600); intentionally used on one team page only without upscaling beyond display need.
