Project Context – AccessGraph Cloud (One-Page Landing)
🧭 Business Goals

Explain, in plain language, what “OpenFGA management” is and why it matters.

Get visitors to start a free trial or book a demo (single primary CTA).

Build quick trust with concise security notes and lightweight social proof.

Rank for a few core terms (e.g., “OpenFGA management SaaS”, “Zanzibar-style auth”) with on-page SEO only.

⚙️ Technical Stack

Site type: Single static page (index.html) + one CSS + one JS file.

Styling: Tailwind via CDN or a small handcrafted CSS file (no build step).

Interactivity: Minimal vanilla JS (or Alpine.js via CDN) for mobile menu, FAQ accordion, pricing toggle.

Icons: Lucide/Heroicons via CDN.

Forms: Formspree (or GetForm/FormSubmit) for demo/contact capture—works on GitHub Pages without a backend.

Analytics (optional): Cloudflare Web Analytics or Plausible (single script tag).

Deployment: GitHub Pages from main branch (/docs folder or root), no CI/CD required.

🧩 Architecture & Structure

Header (sticky): Logo | “Product” (anchors) | Pricing | FAQ | Docs link (to external OSS docs) | Start free (button).

Hero: Clear value prop (“Managed OpenFGA control plane”), 1-sentence subhead, primary CTA (Start free), secondary (Book demo).

Problem → Solution: Brief bullets on policy sprawl, brittle rules, low visibility → how AccessGraph centralizes modeling, versioning, and audits.

Feature highlights (4–6 cards):

Visual model & relation designer

Schema versioning & environment promotion

Playground & policy tests (explained, not run here)

Import/Export compatible with OpenFGA

Audit trails & “who can access what” reports

Multi-tenant projects & environments

“How it works” (3 steps): Model → Connect SDKs → Observe/Audit (tiny code block for SDK snippet).

Security note: Data handling, SSO/SOC 2 status (short, honest).

Pricing (simple): Starter, Team, Enterprise (feature checklist + monthly price, one CTA per tier).

FAQ: 6–8 questions (setup time, compatibility with OpenFGA, rate limits, data residency, support).

Footer: Copyright, Privacy/Terms links, contact email, status link.

🔒 Project Assumptions

Brand basics (logo, primary color, font choice) are available or acceptable to set minimally.

We can reference OpenFGA and show non-sensitive UI screenshots.

One locale (English) and a single domain (GitHub Pages URL or custom CNAME).

Legal copy (Privacy/Terms) provided or approved short-form templates are acceptable.

🧠 Scope

Single responsive landing page with anchor navigation.

Copywriting: headline, subhead, feature blurbs, pricing, FAQ, security note.

Lightweight assets: 2–3 optimized screenshots and 1 small SVG illustration (optional).

Contact/demo form wired to Formspree (or equivalent).

On-page SEO: title/description tags, Open Graph/Twitter tags, canonical, basic schema.org.

Basic analytics script integration (optional toggle).

GitHub Pages setup instructions in README.md + favicon & social preview image.

⚖️ Out of Scope

Multi-page site (no blog, docs hosting, or changelog pages).

A/B testing, experimentation, or automated tests.

Build tooling, bundlers, or design systems; no Next.js/React required.

Backend services, auth flows, or in-app product work.

Complex CMS, localization, or gated content.

## Deployment

This site is designed to be deployed on GitHub Pages.

1. Push this repository to GitHub.
2. Go to your repository settings.
3. Scroll down to "Pages" section.
4. Under "Source", select "Deploy from a branch".
5. Choose "main" branch and "/ (root)" folder.
6. Click "Save".
7. Your site will be available at `https://yourusername.github.io/repository-name/`.

For custom domain, add a `CNAME` file with your domain and configure DNS.

## Form Setup

The demo form uses Formspree. To set it up:
1. Go to [Formspree](https://formspree.io) and create an account.
2. Create a new form and get the form ID.
3. Replace `your-form-id` in `index.html` with your actual form ID.

## Assets

Add the following files to the root:
- `favicon.ico`: 32x32 icon
- `social-preview.png`: 1200x630 image for social sharing