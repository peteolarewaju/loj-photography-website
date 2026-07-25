# LOJ Photography Inc. — Squarespace Build Plan

This is your blueprint for rebuilding the mockup natively in Squarespace. The mockup is the target look; this document tells you which Squarespace tool produces each piece, in what order to build, and how to handle tax, bookings, and payments. Pair it with the Custom CSS pack (separate file) to get the styling close to the mockup from the start.

One honest reminder up front: Squarespace is a closed builder, so the result will be strongly in the spirit of the mockup, not a pixel copy. The structure, palette, fonts, and features all carry over. The exact custom layout does not, fully.

---

## Before you start

**Plan.** Selling prints and using custom code both need a commerce-capable paid plan. Squarespace shifts its tier names and pricing, so check the current plan page and pick the lowest tier that allows selling products plus code injection. Do not commit to a tier from memory or from this document, confirm it live.

**Domain.** Already handled, www.lojphotography.com is reserved with Squarespace.

**Template.** On Squarespace 7.1 every template shares the same underlying engine, so a template is just a starting layout, not a locked design. Pick any clean photography or portfolio starting point and use Fluid Engine (the drag-and-drop editor) to shape sections. Do not agonize over the template choice; it is a starting point you will reshape anyway.

**Email.** Set up contact@lojphotography.com through the Google Workspace connection (or free email forwarding to start). Inquiries will route here.

---

## Global setup (do this first)

**Logo.** Upload your gold-on-black logo in Design, Logo and title. The PNG used in the mockup is fine; a transparent-background version is even better if you have one.

**Fonts.** In Design, Fonts, set headings to Bodoni Moda and body text to Jost. Both are in Squarespace's font picker. This single step does most of the visual work.

**Colours.** In Design, Colors, build the palette from the hex codes in the Custom CSS pack. The key three are the gold (#C6A23C), the cream background (#FBF7EE), and the near-black ink (#1A1410) for the dark sections and footer.

**Buttons.** Set buttons to a pill shape with uppercase text. The Custom CSS pack refines the letter spacing and the gold styling.

**Custom CSS.** Paste the Custom CSS pack into Design, Custom CSS. Read its comments; a few selectors may need small tweaks once your real sections exist.

---

## Section-by-section mapping

**Header and navigation.** Use the built-in header. Logo on the left, nav links across (Home, Portfolio, About, Availability, Pricing, Clients), and the "Inquire" link styled as a button on the right. "Clients" links out to your gallery tool (see Clients below).

**Home hero.** A full-width section with a background image, a dark gradient overlay for legible text, the headline, and two buttons. Fluid Engine handles the overlay and text placement.

**Intro strip and featured gallery.** A centred text section followed by a Gallery section pulling a handful of your strongest images, with a "See full portfolio" button.

**Portfolio.** Build this as Portfolio pages or Gallery sections, one per category: Weddings, Portraits, Maternity, Landscape. The cleanest approach is a Portfolio landing page with four category links, each opening its own gallery. Sequence each gallery to tell a story (for weddings: details, ceremony, couple, reception). This is where your real images go.

**About.** A two-column section, your portrait on one side, your story and signature on the other.

**Availability.** Use Squarespace Scheduling (Acuity). Connect it to your Google Calendar with two-way sync so blocked dates show as unavailable and new bookings write back. Embed the scheduler so clients check and request their own date without ever seeing your full calendar. See "Bookings and calendar" below for the full picture.

**Pricing: Portrait and Maternity.** A simple section with two pricing cards (flat session prices, plus HST). Each has a "Book" button leading to the inquiry form or a Scheduling link.

**Pricing: Weddings.** A dedicated wedding page with your four collections as pricing cards: Essential $2,000, Classic $2,800, Signature $3,500 (carry the "Most booked" highlight here), and Comprehensive $4,500. Add the note about the +$500 extra photographer (required for comprehensive weddings) and "T&C applies." Weddings should be reserved with a deposit through your CRM, not a straight checkout.

**Prints shop.** Use Squarespace Commerce. Create each print size as a product (or one product with size variants), set the prices, and let the cart handle the rest. Configure HST and the Niagara delivery rule in commerce settings (see "Tax and delivery" below). Add a "Custom size, inquire" link that opens the inquiry form set to the "Wall art & prints" category.

**Fine art licensing (landscape).** Display watermarked, lower-resolution previews only. Sell either as inquiry-based exclusive licensing or as products you mark "sold" and remove after a sale, since each piece sells once. Add the right-click and drag deterrent via code injection (snippet below). Be clear-eyed: this deters casual saving, it cannot stop screenshots. The real protection is showing only watermarked low-res online, delivering the full file only after purchase, and backing the sale with a written licensing agreement.

**Clients.** A button (in the nav and on a Clients page) that links out to your client gallery tool, Pixieset or Pic-Time, where clients enter a password to view, download, and order prints. The website is just the front door.

**Instagram strip.** Near the bottom of the home page, either Squarespace's Instagram block (shows recent posts) or a curated image gallery you hand-pick, linking to your profile. The curated route looks more intentional.

**Footer.** Logo, social links (Instagram and Facebook, both wired in the mockup), your email, and the copyright line.

**Contact.** A Form block. Set the form to deliver submissions to contact@lojphotography.com and turn on an auto-reply so couples hear back instantly. Keep the "What are you looking for?" dropdown including the Wall art & prints option.

---

## Bookings and calendar

Use Squarespace Scheduling (Acuity) as the layer between your site and Google Calendar. Connect it to your Google account with two-way sync. From then on: a date you block in Google shows as unavailable to clients, and any booking made on the site drops into Google automatically. The public-facing piece only ever reveals whether a given date is free, never your whole calendar. This is the private-but-accurate setup you wanted, and it is the industry norm. The Google connection is a one-time sign-in you do during setup.

For weddings specifically, pair this with a CRM (HoneyBook, Dubsado, or Studio Ninja) that turns an inquiry into a contract, deposit, and invoice. The CRM is what protects you on cancellations and keeps deposits clean. Its embeddable form can replace the basic contact form on the wedding pages.

---

## Tax and delivery

**Tax.** HST in Canada is destination-based, charged on where the client or service lands, not where your business sits. For local Ontario work that is 13%. Set this in Squarespace's tax settings so checkout calculates it automatically. Confirm the out-of-province edge cases with your accountant; I am not a tax professional.

**Delivery.** In commerce shipping settings, create a flat-rate option of $30 for the Niagara region and a free local pickup option, so clients choose. In Ontario, HST generally applies to the delivery charge as well when the goods are taxable, which the mockup cart reflects.

---

## Recommended build order

1. Choose and activate a commerce-capable plan; confirm the domain is connected.
2. Set up the Google Workspace email (or forwarding) for contact@lojphotography.com.
3. Pick a 7.1 template and do the global setup: logo, fonts, colours, buttons, paste the Custom CSS.
4. Build the static pages first: Home, About, Portfolio (with your real images), Pricing, Weddings.
5. Set up Commerce for the prints shop, including tax and the Niagara delivery rule.
6. Connect Squarespace Scheduling to Google Calendar and embed the availability checker.
7. Set up the inquiry Form to deliver to your email with an auto-reply.
8. Connect your client gallery tool (Pixieset or Pic-Time) and wire the Clients button to it.
9. Add the CRM for wedding contracts and deposits, and embed its form on the wedding pages.
10. Run the pre-launch checklist, then publish.

---

## Fine art right-click deterrent (code injection)

Paste this into Settings, Advanced, Code Injection, Footer. It blocks right-click and drag on images. It is a deterrent only and does not stop screenshots. Code injection needs a Business-level or higher plan.

```html
<script>
  document.addEventListener('contextmenu', function(e){
    if (e.target.closest('img, .sqs-gallery, .gallery-fullscreen')) e.preventDefault();
  });
  document.addEventListener('dragstart', function(e){ e.preventDefault(); });
</script>
```

---

## Pre-launch checklist

- Test a real print order end to end: add to cart, see HST and delivery, reach checkout.
- Test the availability checker against a blocked Google Calendar date.
- Submit a test inquiry and confirm it lands in contact@lojphotography.com with an auto-reply.
- Check every page on mobile, not just desktop.
- Set page titles and descriptions for SEO; weddings are found mostly through Google.
- Set up a Google Business Profile so reviews and local search work for you. This matters more than any single design choice for getting found.
- Consider Pinterest later; couples plan weddings there and it quietly drives traffic.
- Confirm tax settings and the licensing agreement wording with the appropriate professional.

---

## Honest limitations

Custom CSS in Squarespace styles and refines; it does not rebuild layouts. The native style panel and Fluid Engine do the structural work, and the CSS pack nudges the details toward the mockup. Some CSS selectors may need small adjustments once your real sections exist, because Squarespace generates its own class names. Custom code sits outside Squarespace's official support and can occasionally break after platform updates, so keep the snippets labelled and minimal. None of this is a dealbreaker; it is the normal trade for staying on a managed platform that handles your bookings, payments, and tax for you.
