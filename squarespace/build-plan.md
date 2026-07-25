# LOJ Photography Inc. — Squarespace Build Plan

This is your blueprint for rebuilding the mockup natively in Squarespace, scoped to **event photography** — weddings, portraits, and maternity. The mockup is the target look; this document tells you which Squarespace tool produces each piece, in what order to build, and how to handle bookings and inquiries. Pair it with the Custom CSS pack (separate file) to get the styling close to the mockup from the start.

One honest reminder up front: Squarespace is a closed builder, so the result will be strongly in the spirit of the mockup, not a pixel copy. The structure, palette, fonts, and features all carry over. The exact custom layout does not, fully.

> **Scope note (July 2026).** The print store, the fine-art landscape gallery/licensing, and the automated availability scheduler have been cut to keep the launch simple and the running cost low. Availability is now handled by hand through the inquiry form. This also removes the need for a commerce plan and for code injection.

---

## Before you start

**Plan.** Custom CSS is what carries your styling to the live site, so you need a plan that publishes Custom CSS and lets you connect your domain. With selling removed, you no longer need a Commerce plan — pick the lowest paid tier that publishes Custom CSS and connects www.lojphotography.com. Squarespace shifts its tier names and pricing, so confirm on the current plan page rather than committing from memory. Worth weighing before you pay: with the site now just a portfolio plus a contact form, a photographer-focused platform like Pixieset — which would also run your client galleries — may cover the whole thing for less, or free.

**Domain.** Already handled, www.lojphotography.com is reserved with Squarespace.

**Template.** On Squarespace 7.1 every template shares the same underlying engine, so a template is just a starting layout, not a locked design. Pick any clean photography or portfolio starting point and use Fluid Engine (the drag-and-drop editor) to shape sections. Do not agonize over the template choice; it is a starting point you will reshape anyway.

**Email.** Set up contact@lojphotography.com through the Google Workspace connection (or free email forwarding to start). Inquiries will route here.

---

## Global setup (do this first)

**Logo.** Upload your gold logo in Design, Logo and title. The trimmed PNG in `assets/logo.png` works; a transparent-background version is even better on light headers.

**Fonts.** In Design, Fonts, set headings to Bodoni Moda and body text to Jost. Both are in Squarespace's font picker. This single step does most of the visual work.

**Colours.** In Design, Colors, build the palette from the hex codes in the Custom CSS pack. The key three are the gold (#C6A23C), the cream background (#FBF7EE), and the near-black ink (#1A1410) for the dark sections and footer.

**Buttons.** Set buttons to a pill shape with uppercase text. The Custom CSS pack refines the letter spacing and the gold styling.

**Custom CSS.** Paste the Custom CSS pack into Design, Custom CSS. Read its comments; a few selectors may need small tweaks once your real sections exist.

---

## Section-by-section mapping

**Header and navigation.** Use the built-in header. Logo on the left, nav links across (Home, Portfolio, About, Pricing, Clients), and the "Inquire" link styled as a button on the right. "Clients" links out to your gallery tool (see Clients below).

**Home hero.** A full-width section with a background image, a dark gradient overlay for legible text, the headline, and two buttons ("View the work" and "Inquire"). Fluid Engine handles the overlay and text placement.

**Intro strip and featured gallery.** A centred text section followed by a Gallery section pulling a handful of your strongest images, with a "See full portfolio" button.

**Portfolio.** Build this as Portfolio pages or Gallery sections, one per category: Weddings, Portraits, Maternity. The cleanest approach is a Portfolio landing page with three category links, each opening its own gallery. Sequence each gallery to tell a story (for weddings: details, ceremony, couple, reception). This is where your real images go.

**About.** A two-column section, your portrait on one side, your story and signature on the other.

**Pricing: Portrait and Maternity.** A simple section with two pricing cards (flat session prices, plus HST). Each has a "Book" button leading to the inquiry form.

**Pricing: Weddings.** A dedicated wedding page with your four collections as pricing cards: Essential $2,000, Classic $2,800, Signature $3,500 (carry the "Most booked" highlight here), and Comprehensive $4,500. Add the note about the +$500 extra photographer (required for comprehensive weddings) and "T&C applies." Weddings should be reserved with a deposit (through a CRM later, or a manual invoice for now), not a straight checkout.

**Clients.** A button (in the nav and on a Clients page) that links out to your client gallery tool, Pixieset or Pic-Time, where clients enter a password to view, download, and order prints of their own photos. The website is just the front door.

**Instagram strip.** Near the bottom of the home page, either Squarespace's Instagram block (shows recent posts) or a curated image gallery you hand-pick, linking to your profile. The curated route looks more intentional.

**Footer.** Logo, social links (Instagram and Facebook, both wired in the mockup), your email, and the copyright line.

**Contact / inquiries.** A Form block. Set it to deliver submissions to contact@lojphotography.com and turn on an auto-reply so people hear back instantly. Because availability is handled here rather than by a scheduler, include a **"Preferred date(s)"** field so you can check your own calendar and reply. Keep a "What are you looking for?" dropdown with Weddings, Portraits, and Maternity.

---

## Availability and bookings

There is no automated scheduler. Clients tell you their preferred date(s) in the inquiry form; you check your own calendar and reply to confirm. This keeps your calendar private, costs nothing extra, and is completely normal for a photographer starting out. You can add self-serve scheduling (Squarespace Scheduling / Acuity) later if the manual back-and-forth ever gets tedious.

For weddings specifically, consider a CRM (HoneyBook, Dubsado, or Studio Ninja) down the line to turn an inquiry into a contract, deposit, and invoice — that is what protects you on cancellations. Not required to launch.

**A note on tax.** Photography services in Ontario are subject to HST (13%). Show session and collection prices as "plus HST," and apply the tax on your invoices or through a CRM — there is no store checkout on the site that needs to calculate it. Confirm the details with your accountant; I am not a tax professional.

---

## Recommended build order

1. Activate a plan that publishes Custom CSS; confirm the domain is connected.
2. Set up the Google Workspace email (or forwarding) for contact@lojphotography.com.
3. Pick a 7.1 template and do the global setup: logo, fonts, colours, buttons, paste the Custom CSS.
4. Build the pages with your real images: Home, About, Portfolio (Weddings / Portraits / Maternity), Pricing, Weddings.
5. Set up the inquiry Form to deliver to your email with an auto-reply, including the Preferred date(s) field.
6. Connect your client gallery tool (Pixieset or Pic-Time) and wire the Clients button to it.
7. (Later, optional) Add a CRM for wedding contracts and deposits.
8. Run the pre-launch checklist, then publish.

---

## Pre-launch checklist

- Submit a test inquiry and confirm it lands in contact@lojphotography.com with an auto-reply, and that the Preferred date(s) field comes through.
- Check every page on mobile, not just desktop.
- Set page titles and descriptions for SEO; weddings are found mostly through Google.
- Set up a Google Business Profile so reviews and local search work for you. This matters more than any single design choice for getting found.
- Consider Pinterest later; couples plan weddings there and it quietly drives traffic.

---

## Honest limitations

Custom CSS in Squarespace styles and refines; it does not rebuild layouts. The native style panel and Fluid Engine do the structural work, and the CSS pack nudges the details toward the mockup. Some CSS selectors may need small adjustments once your real sections exist, because Squarespace generates its own class names. Custom code sits outside Squarespace's official support and can occasionally break after platform updates, so keep any snippets labelled and minimal. None of this is a dealbreaker; it is the normal trade for staying on a managed platform that handles your hosting and forms for you.
