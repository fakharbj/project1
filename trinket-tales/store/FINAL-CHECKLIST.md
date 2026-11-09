# Trinket Tales: final production checklist (v8)

Open **admin.shopify.com** in Chrome and turn on "Desktop site" if you're on a phone. This is the full list. If a step is already done, tick it and move on. `STORE-FIXES.pdf` lists only what was still missing when I reviewed the store on 9 November, and it has the texts to paste (Text A to E).

**What's already built into theme v8** (no work needed):
- Home page sections: banner, trust bar, shop-by-category tiles, featured product, product grid, Instagram-style welcome card, photo gallery, quick answers.
- About, FAQ and Contact content.
- Delivery dates that switch on the `dropship` tag.
- Free-delivery bar, sticky Add to cart, equal 4:5 photos.
- Left-aligned layout and a hero that shows your banner image whole.
- WhatsApp chat button, plus an "Ask us on WhatsApp" line on product pages.

**Tags drive everything.** Give products the right tags, and the collections, home tiles and delivery dates fill themselves.

| Tag | What it does |
|---|---|
| `kids-makeup` | goes into **Kids Makeup Gifts** |
| `bracelets` | goes into **Handmade Bracelets** |
| `gift-boxes` | goes into **Gift Boxes and Bundles** |
| `dropship` | product page shows **10–20 working days** (imported). Without it: 3–5 days |

---

## 1. Products (20 min)

- [ ] **Instagram products, one import:** Products → **Import** → `instagram-products-import.csv` → Import.
  - This adds **Flower Bead Bracelet Set (3 Pieces)** in Pink Bow, Purple Bow, Sunshine Yellow and Cherry Red, at Rs 650.
  - It also adds **Pearl Bracelet with Jade Bead** in Light, Sage and Deep Jade, at Rs 450.
  - Both are tagged `bracelets` and `handmade`. **Change the prices if yours are different.**
  - **Stock:** the import doesn't carry stock over, so both show "Sold out". Go to Products → **Inventory** and type `10` next to each colour, then Save.
- [ ] **Add photos to the two new products** (from the `instagram-products` folder):
  - Bracelet set: `bracelet-set-pink/purple/yellow/red.jpg`. Under Variants, link each colour to its photo.
  - Pearl bracelet: `pearl-jade-bracelet.jpg`.
- [ ] **Tag the products you already have:** Products → tick the products → **More actions → Add tags**:
  - Dreamy Kids Makeup Set (from DSers) → `kids-makeup, dropship`
  - Flower bead bracelet set (from DSers) → `bracelets, dropship`
  - Mini makeup pouch → `kids-makeup, gift-boxes`. Add its photo from the `photos` folder.
  - Aesthetic Self-Care Gift Box and Customize box → `gift-boxes`
  - Handmade Butterfly Beaded Bracelet → `bracelets`
- [ ] **Main product: Dreamy Kids Makeup Set** (the one in the assignments). Open it in Products:
  - **Title:** `Dreamy Kids Makeup Set for Girls`
  - **Option:** rename **Color** to **Pack**, and the values to `1 Kit`, `2 Kits`, `3 Kits`, `4 Kits`. Drag **1 Kit** to the top.
  - **Prices:** DSers brings in the supplier's cost (Rs 1,687.70), so change them to these:

    | Pack | Price | Compare-at |
    |---|---|---|
    | 1 Kit | 2999 | 3999 |
    | 2 Kits | 5699 | 7999 |
    | 3 Kits | 8299 | 11999 |
    | 4 Kits | 10799 | 15999 |

  - **Description:** delete the supplier's text and paste **Text A** from STORE-FIXES.
  - **Images:** drag the cleanest photo to **first** place and delete the near-duplicates. Keep 6 to 8.
  - **Search engine listing:**
    - URL handle: **`dreamy-kids-makeup-set-for-girls`**. Leave "Create a URL redirect" ticked.
    - Page title and meta description: from Assignment 3, section 4.
  - **Tags:** `kids-makeup, dropship`
  - **Save**.
- [ ] **Second DSers product: flower bead bracelet set.**
  - Title: `Boho Daisy Flower Bead Bracelet Set`.
  - Price: `1199`, compare-at `1499`.
  - Option **Metal Color** → `Colour`.
  - Description: **Text B**.
  - Tags: `bracelets, dropship`.
  - Save.
- [ ] **Prices without decimals:** Settings → General → Store defaults → **Currency display → Change formatting**:
  - HTML without currency: `Rs {{amount_no_decimals}}`
  - HTML with currency: `Rs {{amount_no_decimals}} PKR`
  - Save. Prices then show **Rs 2,999** instead of Rs.1,687.70.

## 2. Collections (3 min, done once)

Products → Collections → **Create collection** → **Automated** → condition **Product tag is equal to**:

| Title (type it exactly) | Tag |
|---|---|
| `Kids Makeup Gifts` | `kids-makeup` |
| `Handmade Bracelets` | `bracelets` |
| `Gift Boxes and Bundles` | `gift-boxes` |

The home page category tiles show these collections and their first product photo by themselves.

## 3. Theme (already installed, don't upload it again)

- [ ] If the Welcome card isn't on your home page yet, apply the v8 update from `code-update-v8/HOW-TO-UPDATE.txt`. It only adds files, so your settings stay.
- [ ] **Customize** → Theme settings (paintbrush):
  - **Logo** → `trinket-tales-wordmark.png`
  - **Favicon** → `trinket-tales-favicon-512.png`
  - **Trinket Tales → WhatsApp number**, in the form `923001234567`. The chat button and the product-page line only appear once a number is set.
  - **Save**
- [ ] **Banner:** set a **Desktop image** only and leave **Mobile image** empty. Phones then show the photo whole with the text underneath.
- [ ] **Featured product** ("Our favourite gift") → Product → **Dreamy Kids Makeup Set**.
- [ ] **Brand story** → hide it with the eye icon. The Welcome card tells the same story.
- [ ] **Payment wording.** The theme ZIP already has the right texts, but on your live theme change them by hand:
  - Quick answers → "How do I pay?" → **Text C**.
  - Products → Default product:
    - Icon row → `Cash on delivery` becomes `Easy payment`.
    - Delivery and payment tab → **Text D**.
  - Footer text block → **Text E**.
- [ ] **Save**.

## 4. Pages, policies, menus (8 min)

- [ ] **Online Store → Pages.** Create each page **with no page text**, and set the **Theme template**:

| Page title | URL handle | Template |
|---|---|---|
| About Us | `about-us` | **about** |
| FAQ | `faq` | **faq** |
| Contact | `contact` | **contact** |

- [ ] **Settings → Policies:**
  - **Shipping** and **Refund**: paste the texts below.
  - **Terms**: *Create from template*. Privacy is already there.
  - **Save**.
- [ ] **Navigation → Main menu:** Home · Shop · About · FAQ · Contact.
- [ ] **Footer menu:** FAQ · Contact · Shipping Policy · Refund Policy · Privacy Policy

## 5. Payments and delivery (8 min)

- [ ] **Settings → Payments → Manual payment methods:**
  - **Cash on Delivery (COD)** → Activate.
  - **Create custom payment method:**
    - Name: `Advance payment - Bank / JazzCash / Easypaisa`
    - Additional details: your account numbers and WhatsApp number.
    - Payment instructions: `We ship your order after we receive the payment screenshot.`
    - Activate.
- [ ] **Settings → Shipping and delivery → Pakistan:**
  - Rs 200 standard.
  - Rs 0 for orders of Rs 2,500 and up.
- [ ] **Settings → Checkout:** shipping address phone → **Required**.

Imported (`dropship`) items need advance payment, because the parcel comes straight from the supplier and no courier collects cash. If someone picks COD for one, ask for advance payment on WhatsApp before you order it in DSers.

## 6. Go live (5 min)

- [ ] Phone test:
  - Home: the banner text sits under the photo, there are 3 category tiles with photos, the makeup set is the featured product, and you see the New & loved grid, the Welcome card and the gallery.
  - The makeup set page says **Rs 2,999**, **10–20 working days** and **Easy payment**.
  - A bracelet from your own stock says **3–5** days.
  - The footer lists Shipping, Refund, Privacy and Terms.
  - Checkout shows COD and Advance payment.
- [ ] **Test order #1002:**
  - Don't place it in DSers.
  - Cancel it in Shopify: Orders → #1002 → More actions → Cancel order.
- [ ] **Online Store → Preferences:** copy the store password, or pick a plan to remove it.
- [ ] Instagram bio link → `https://wmyj10-ju.myshopify.com`
- [ ] Assignments: see `FINAL-DELIVERY.pdf` for Roll No., Course and the two screenshots.
- [ ] After marks: change the password and turn on 2-step verification.

---

## Final links

| What | Link |
|---|---|
| Store | https://wmyj10-ju.myshopify.com |
| Main product | https://wmyj10-ju.myshopify.com/products/dreamy-kids-makeup-set-for-girls (works once the URL handle is changed) |
| Supplier, makeup set (main) | https://www.aliexpress.com/item/1005012993298696.html |
| Supplier, flower bead bracelet set | https://www.aliexpress.com/item/1005011994527815.html |
| Collections | /collections/kids-makeup-gifts · /collections/handmade-bracelets · /collections/gift-boxes-and-bundles |
| Instagram | https://www.instagram.com/trinket_tales_1 |

---

## Text to paste

Texts A to E (product descriptions, FAQ, delivery tab, footer) are at the end of `STORE-FIXES.pdf`.

### Shipping Policy
We deliver all over Pakistan.

**Items from our own stock** (bracelets, gift bundles, little gift boxes) are dispatched within 1 to 2 working days and usually arrive in 3 to 5 working days. Cash on delivery is available.

**Imported items** (marked on the product page) ship from our supplier and usually arrive in 10 to 20 working days. They need advance payment by bank transfer, JazzCash or Easypaisa, and we share a tracking number once the parcel ships.

Delivery is Rs 200, and free on orders over Rs 2,500.

### Refund Policy
If your parcel arrives damaged or you received the wrong item, message us within 3 days of delivery with a photo or unboxing video. We'll send a replacement or give a full refund.

If an imported item hasn't arrived within 30 working days of your order, we'll refund you in full.

Unopened items from our own stock can be returned within 7 days of delivery, with return delivery paid by the customer. For hygiene reasons, opened or used makeup can't be returned.

Refunds are sent by bank transfer, Easypaisa or JazzCash within 5 working days.
