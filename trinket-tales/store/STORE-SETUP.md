# Trinket Tales: Shopify store setup (phone-friendly)

Everything here matches the four assignments: same product, price, keywords and supplier.
On a phone, open **admin.shopify.com** in Chrome and switch on "Desktop site". The theme editor works better there than in the Shopify app.

---

## 0. Before you start (5 min)

- [ ] **Store currency must be PKR.** Settings → Store details → Store currency → Pakistani Rupee (PKR). The CSV prices (1200 / 1500) are read in the store currency, so if it is USD you'd get $1,200.
- [ ] **Security.** The login was shared on WhatsApp. After marks are in: change the password and turn on 2-step verification (Settings → Users → your account → Security).

## 1. Product (10 min)

1. Products → **Import** → choose `product-import.csv` → Upload and preview → Import.
   This creates **Mini Makeup Kit for Girls - Cute Gift Pouch** with 5 colours, SKUs, Rs 1,200 / Rs 1,500, tags, SEO title and meta description.
2. Open the product → **Media** → add the 6 photos from `photos/` in this order:
   1. `01-strawberry-pink.jpg` (main) 2. `02-cherry-red.jpg` 3. `03-kiwi-green.jpg` 4. `04-orange-sunshine.jpg` 5. `05-blueberry-blue.jpg` 6. `06-all-five-colours.jpg`
3. Click each image → **Add alt text** (copy from Assignment 3, section 3).
4. Variants → open each colour → **Add image** → pick that colour's photo. Now tapping a colour changes the picture.
5. If the old listing (made earlier) is still there, set it to **Draft** so there's only one product.

**Collections:** Products → Collections → Create
- **Gift Pouches** (Manual) → add the product.
- **Gifts Under Rs 1,500** (Automated) → condition: Price is less than 1500.

## 2. Look and feel: upload the ready theme (5 min)

`Trinket-Tales-Theme.zip` (v2) is Shopify's official free **Dawn 16.1.1** theme with our design and a few custom sections added. Theme Check shows no new issues compared with stock Dawn.

1. Do step 1 (product import) **first**. The home page finds the product by its handle `mini-makeup-kit-for-girls`.
2. Online Store → Themes → **Add theme → Upload zip file** → the theme ZIP. Don't unzip it first.
3. On the new theme: **Customize** → Theme settings → **Logo** → `brand/trinket-tales-logo-round.png`. Then **Favicon** → `brand/trinket-tales-favicon-512.png`. Save.
   A newly uploaded theme starts without a logo, so do this again after each upload.
4. **Preview**, then **⋯ → Publish**. Remove older uploaded copies afterwards (⋯ → Remove).

What the theme does:
- **Brand look:** cream `#FBF1E8`, blush `#F6E3DF`, cocoa `#3B2A25` and rose `#A85562`. Lora headings, pill buttons and rounded photos, plus a small bow ornament taken from the logo.
- **Home page:**
  1. Hero with the pouch photo, price and *Shop the pouch* button.
  2. A row of three promises.
  3. **Pick your colour** row, built automatically from the product's colours. Each card opens that colour.
  4. The pouch with *Add to cart* and *Buy it now*.
  5. FAQ.
  6. Brand story.
- **Product page:**
  - Colour pills and *Buy it now*.
  - **Delivery date line** ("Order today, arrives Wed 11 – Fri 13 Nov").
  - Trust icons: COD, easy returns, ready to gift.
  - Delivery and Returns tabs, then 3 quick FAQs.
- **Sticky Add to cart on mobile:** a bar slides up from the bottom once the main button scrolls away. It shows the photo, price and chosen colour.
- **Cart drawer:** a progress bar shows "Add Rs 1,300 more for free delivery". It has a gift-note box and *Buy it now* for a faster checkout.
- **Equal image sizes:** every product photo, card and colour tile shows in the same 4:5 frame. Photos of any size are cropped neatly to fit.
- **Pages:** custom templates for About, FAQ and Contact, plus a styled default page and styled policy pages.
- **Settings:** Theme settings → **Trinket Tales** has the free-delivery amount and the delivery-day range.

If the headings show in the default font, pick **Lora** under Theme settings → Typography → Headings.

## 3. Pages, policies and menus (10 min)

Online Store → **Pages** → Add page. On each page, scroll to **Theme template** and pick the one in the table. Publish the theme first, because the list only shows the live theme's templates.

| Page title | URL handle (under Search engine listing) | Theme template | What to put in the page text |
|---|---|---|---|
| About Us | `about-us` | **about** | The About text from the appendix |
| FAQ | `faq` | **faq** | Leave empty. The questions are built into the template |
| Contact | `contact` | **contact** | Leave empty. The form is built in |

Keep the handles exactly `faq` and `contact`, because the FAQ and Contact pages link to each other through them.

- Settings → **Policies** → paste **Refund** and **Shipping** from the appendix. Use "Create from template" for **Privacy** and **Terms of service**. The theme styles these pages automatically.
- Online Store → **Navigation**
  - Main menu: Home · Shop (→ the product or Gift Pouches) · About Us · FAQ · Contact
  - Footer menu: FAQ · Contact · Shipping Policy · Refund Policy · Privacy Policy

## 4. Payment and delivery (5 min)

- Settings → **Payments** → Manual payment methods → **Cash on Delivery (COD)** → Activate.
- Settings → **Shipping and delivery** → General shipping rates → Pakistan zone (add it if missing):
  - `Standard delivery (3–5 working days)` – Rs 200
  - `Free delivery` – Rs 0, condition: order price Rs 2,500 and up

## 5. Dropshipping connection

**A) Markaz – main supplier (Pakistan, COD, 2–5 days)**
1. Install **Markaz** from the Play Store and sign up as a reseller.
2. Search `makeup kit for girls` / `kids makeup pouch` and pick the pouch kit that matches our photos. Save it to favourites and note its Markaz price.
3. Keep our own Shopify listing (our photos and text). When a Shopify order comes in: confirm it on WhatsApp → place the same order in Markaz with the customer's name, address and COD amount (Rs 1,200 + delivery). Markaz delivers and collects the cash; our margin is paid to us.
4. Markaz also has **Export to My Store** (exports a product file for Shopify import) if you want to add more Markaz products later.

**B) DSers + AliExpress – automatic link (backup)**
1. Shopify → Apps → search **DSers** → Install (free Basic plan).
2. Create the DSers account and link an AliExpress account.
3. On AliExpress find a matching kit (search `kids makeup bag lipstick nail polish hand cream set`) and copy the product link.
4. DSers → My Products → *Mini Makeup Kit for Girls* → **Mapping** → Basic mapping → paste the AliExpress link → match each of the 5 colours → Save.
5. From then on, orders for this product appear in DSers → **Place order to AliExpress** (one click) and tracking syncs back to Shopify.

## 6. Instagram (@trinket_tales_1)

- Edit profile → Links → add the store link.
- Post the 5 colour photos as a carousel with the caption from Assignment 3; post the packing video as a reel.
- Optional, takes days for Meta approval: Shopify → Sales channels → **Facebook & Instagram** → connect the account for Instagram Shopping tags. Not needed for the assignment.

## 7. Sharing the store with ma'am

- Trial stores are password protected. Online Store → Preferences → Password protection shows the password.
  Either pick a plan to remove the password, or send ma'am the link **and** the password.
- Put the store link and product link into the **Store link / Product link** lines in the Word files, then save as PDF.

## Final checklist

- [ ] Currency PKR
- [ ] Product imported, 6 photos, alt text, colour images linked
- [ ] Theme ZIP (v2) uploaded, logo + favicon added, previewed and published
- [ ] About / FAQ / Contact pages set to the about / faq / contact templates
- [ ] About / FAQ / Contact pages + Refund / Shipping / Privacy / Terms
- [ ] Main and footer menus
- [ ] COD on, delivery rates set
- [ ] Markaz account + matching product saved (DSers optional)
- [ ] Instagram bio link + first post
- [ ] Store link filled in all four assignments
- [ ] Password changed + 2-step verification after submission

---

## Appendix: copy-paste text

### About Us
Trinket Tales started with a simple idea: small things can bring big happiness.

We pick cute, gift-ready little things for girls, the kind of surprise that makes a birthday, an Eid morning or an ordinary day a bit brighter. Every order is checked, packed with care and delivered with cash on delivery anywhere in Pakistan.

Follow us on Instagram @trinket_tales_1 for new colours and drops.

### Contact
Questions about an order? Message us on Instagram @trinket_tales_1 or use the form below. We usually reply within a day.

### FAQ
**How do I pay?**
Cash on delivery. You pay the rider when your parcel arrives.

**How long does delivery take?**
3 to 5 working days in most cities, a little longer for remote areas.

**How much is delivery?**
Rs 200. Free on orders over Rs 2,500.

**Is the kit okay for children?**
It's best for ages 8 and up. Try a small patch test on the hand first and keep it away from eyes. Younger girls should use it with a grown-up.

**Do all colours have the same items?**
The main items are the same. Small extras like the clip can vary a little by colour.

**Can I return it?**
Yes, see our Refund Policy. For hygiene reasons, opened makeup can't be returned.

### Shipping Policy
We deliver all over Pakistan. After you order, we confirm it by WhatsApp or phone and dispatch within 1 to 2 working days. Delivery usually takes 3 to 5 working days in most cities, and a little longer for remote areas.

Delivery charge is Rs 200, and free on orders over Rs 2,500. Payment is cash on delivery.

### Refund Policy
If your parcel arrives damaged or you received the wrong item, message us within 3 days of delivery with a photo or unboxing video. We'll send a replacement or give a full refund.

Unopened items can be returned within 7 days of delivery; return delivery is paid by the customer. For hygiene reasons, opened or used makeup can't be returned.

Refunds are sent by bank transfer, Easypaisa or JazzCash within 5 working days of receiving the return.
