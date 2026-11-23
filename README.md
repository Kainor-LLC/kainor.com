# kainor.com

The Kainor LLC company site: static pages in `docs/`, served by Cloudflare Pages (project kainor-site, build output
directory `docs`, no build step). Moved here from the LAPSlock repository on 2026-10-15 so the product repositories
hold code only. GitHub Pages is not used: it does not allow purchase links.


Since the redesign of November 2026 this site is the company: the home page, the blog, the privacy policy and the
terms. TenantKeep's product pages are on tenantkeep.app, and `docs/_redirects` sends the addresses they used to have
here (`/how-it-works/`, `/pricing/`, `/glossary/`) to their new ones. The old pages are still in `docs/` beneath the
redirects. Files a program reads stay here and must keep their addresses: `app-registrations.json`,
`entitlement-jwks.json`, `.well-known/`, and `instant-alerts/approved/`, where the Instant alerts service returns an
administrator after an approval. `/privacy` and `/terms` are linked from inside shipped builds of the app.
