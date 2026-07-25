# LOJ Photography Inc. — Pixieset (Free) Build Guide

Build the whole site on Pixieset's **free** plan first — no cost, no 14-day clock. You only ever pay (~US$8/mo Basic) when you're ready to attach **www.lojphotography.com**. Your domain and email stay exactly where they are (Squarespace registrar + Google Workspace) the entire time; this is only about where the *website* lives.

Scope is the same events-only plan as the Squarespace build: Home, Portfolio (Weddings, Portraits, Maternity), About, Pricing, Weddings, Clients, Contact. No print store, no landscape gallery, no scheduler — availability is handled through the contact form.

> The `squarespace/custom-css.css` pack does **not** apply here — it's written for Squarespace. On Pixieset you rebuild the look with the native theme editor. The `mockup/index.html` and the brand tokens below are your visual spec.

---

## What "free" gives you (and the limits to plan around)

Free plan, forever: a real, live, public website — but at a `yourname.mypixieset.com` subdomain, with a small Pixieset badge, and capped at **15 pages, 100 photos, 5 blog posts, 3 GB**.

The 100-photo cap is the real constraint. Curate tightly (good discipline for a portfolio anyway). A rough budget:

| Section | Photos |
|---|---|
| Home (hero + featured) | ~8 |
| Weddings | ~30 |
| Portraits | ~20 |
| Maternity | ~15 |
| About | ~3 |
| Spare | ~24 |

---

## Step 1 — Create the free account (you do this part)

Go to **pixieset.com** and sign up for the free account. (I can't create logins or enter passwords for you — do this yourself, then I can help with every design decision after.) You'll get Client Galleries, Website, Studio, and Store; we'll use **Website** now and **Client Galleries** later for delivery.

## Step 2 — Start a Website and pick a template

In Pixieset open **Website → create new site**. Choose a **clean, minimal, image-forward** template — one with a full-width hero, gallery-grid sections, and a simple nav. Templates are fully restyleable, so don't agonize; pick the one closest to the mockup's editorial, lots-of-whitespace feel.

## Step 3 — Set the brand look

**Fonts** (Design → Fonts / Font Themes):
- Headings: **Bodoni Moda** — it's likely in Pixieset's 1,000+ fonts; if not, upload the `.woff2` files (Bodoni Moda is free on Google Fonts).
- Body: **Jost** — same (built-in or upload).
- Give headings a little letter-spacing; use an italic accent word where the mockup does.

**Colours** (Design → Colors) — your brand tokens:
- Page background: cream `#FBF7EE` (or bone `#F1EADC`)
- Body text: espresso `#322822`
- Accent (buttons/links): gold `#C6A23C` (use gold-deep `#9A7A22` for gold text on light)
- Dark sections + footer: ink `#1A1410`

**Buttons:** pill shape, uppercase, gold — set in the theme's button style if available.

## Step 4 — Build the pages (mockup is the reference)

- **Home:** hero image + headline + two buttons (*View the work* / *Inquire*); a short intro line; a featured gallery of your 6–8 strongest images; a "See full portfolio" link.
- **Portfolio:** three galleries — Weddings, Portraits, Maternity. Sequence weddings as a story: details → ceremony → couple → reception.
- **About:** your portrait, your story, your signature.
- **Pricing:** portrait + maternity session cards (flat price, "plus HST"); each "Book" button goes to the contact form. Link out to the Weddings page.
- **Weddings:** four collection cards — Essential $2,000, Classic $2,800, Signature $3,500 (mark "Most booked"), Comprehensive $4,500. Note the +$500 extra photographer (required for Comprehensive) and "T&C applies."
- **Clients:** a button linking to your Pixieset **Client Gallery** (bonus — same platform), where clients log in to view and download their photos.
- **Contact:** a form delivering to contact@lojphotography.com.

## Step 5 — Contact form (this replaces the scheduler)

Fields: Name, Email, **Preferred date(s)**, "What are you looking for?" (Weddings / Portraits / Maternity), Message. Point submissions to contact@lojphotography.com and turn on an auto-reply if the plan allows. The Preferred date(s) field is how you handle availability by hand.

## Step 6 — Client galleries (bonus, same platform)

Since you're already on Pixieset, use **Client Galleries** (free tier, 3 GB) to deliver event photos, and wire the Clients page button to it. One fewer external tool to pay for or manage.

## Step 7 — Publish (free, at the subdomain)

Hit **Publish**. The site goes live at `yourname.mypixieset.com` — genuinely public, free, no expiry. Share it, check every page on mobile, refine.

## Step 8 — Only when you're ready to go live on your domain (later, paid)

1. Subscribe to **Basic** (~US$8/mo).
2. In Pixieset, add the custom domain **www.lojphotography.com**. Pixieset gives you the exact **DNS records** to add (an A and/or CNAME record).
3. Add those records at your registrar: **account.squarespace.com → the domain → DNS Settings**.
4. **Critical:** change only the *website* records (A/CNAME). **Leave the MX and email records untouched** so contact@ keeps working.
5. Wait for it to connect and for SSL to go active — then you're live at your real domain.

---

## Notes

- Domain + email don't move — they stay at Squarespace/Google. This is purely the website.
- Nothing here forces a decision: you can build the whole thing free, live with it at the subdomain, and only pay at the moment you want your real domain attached.
- Want help along the way? Screenshot any Pixieset screen and I'll advise on the exact setting — the same way we worked through Squarespace.
