# Trinket Tales: final production checklist (v4)

Open **admin.shopify.com** in Chrome and turn on "Desktop site" if you're on a phone. It takes about 60 minutes. If a step is already done, tick it and move on.

**What sells where**

| Product | How it's fulfilled | Payment | Delivery |
|---|---|---|---|
| **Lollipop Makeup Kit** (the assignment product) | Dropshipped from AliExpress via DSers. Tag: `dropship` | Advance (bank / JazzCash / Easypaisa) | 10–20 working days |
| Extra AliExpress items (optional bracelets) | Dropshipped via DSers. Tag: `dropship` | Advance | 10–20 working days |
| **Your Instagram products**: bear-bag pouch, bracelets, gift bundles, gift boxes | Your own stock, **no DSers** | Cash on delivery | 3–5 working days |

The theme reads the `dropship` tag. Those products automatically show 10–20 days on the product page, and everything else shows 3–5 days.

---

## 1. Import the main product with DSers (10 min)

- [ ] Shopify → Apps → **DSers** → **Import List** → paste `https://www.aliexpress.com/item/4000781891981.html` → **Import**.
  - If that seller is unavailable, use the backup: `https://www.aliexpress.com/item/4000811549459.html`
- [ ] Before pushing, open the product's **Shipping** in DSers and note the cost to **Pakistan**. You need it for the price in step 2.
- [ ] Edit in DSers:
  - **Title:** `Lollipop Makeup Kit for Girls - Washable Gift Box`
  - **Tags:** add `dropship`
  - **Push to Shopify**
- [ ] If you mapped the **bear-bag pouch** to AliExpress earlier: DSers → My Products → pouch → Mapping → remove the supplier. The pouch is your own stock now.

## 2. Finish the product in Shopify (10 min)

Open Products → *Lollipop Makeup Kit for Girls*:
- [ ] **Price** Rs **3,499**, **Compare-at** Rs **4,499**, on every option.
  - If DSers showed shipping of around US$10 or more, read the decision in Assignment 2, section 6, before going live.
- [ ] **Description:** delete the supplier text and paste the description from **Assignment 3, section 2**.
- [ ] **Search engine listing → Edit:**
  - Page title: `Lollipop Makeup Kit for Girls | Washable Gift Box | Trinket Tales`
  - Meta description: `Cute washable makeup kit for girls in a lollipop-shaped gift box. Lip colours, eyeshadow, blush and nail polish. Delivered across Pakistan.`
  - URL handle: **`lollipop-makeup-kit-for-girls`** (exactly this, because the home page uses it)
- [ ] **Tags:** `kids makeup kit for girls, washable makeup kit for kids, lollipop makeup kit, makeup gift set for girls, birthday gift for girls, eid gift for girls, dropship`
- [ ] **Collections:** create *Kids Makeup Gifts* and add the kit.
- [ ] **Status** = Active → **Save**.

**Optional extra AliExpress products** (same way: Import List → tag `dropship` → Push → set price):
- Butterfly charm bracelet: `https://www.aliexpress.com/item/1005006413334032.html`
- Flower bead bracelet set: `https://www.aliexpress.com/item/1005011994527815.html`
- Pearl crystal bracelet: `https://www.aliexpress.com/item/1005004840626196.html`

Price rule: (supplier price + shipping in US$) × 280 × 1.4, rounded to …99. Example: (1 + 3) × 280 × 1.4 = 1,568 → **Rs 1,599**.

## 3. Your own Instagram products (5 min)

- [ ] Bear-bag pouch, bracelets, gift bundles, gift boxes: **Active**, **no `dropship` tag**, priced as on Instagram.
- [ ] Add them to a collection called *Our Handmade & Gift Range*.

## 4. Theme v4 (10 min)

- [ ] Online Store → Themes → **Add theme → Upload zip file** → `trinket-tales-theme-v4-UPLOAD.zip`. Don't unzip it first.
- [ ] **Customize** → Theme settings (paintbrush):
  - **Logo** → `trinket-tales-logo-round.png`
  - **Favicon** → `trinket-tales-favicon-512.png`
  - **Save**
- [ ] Check the home page:
  - Banner, then the **Lollipop kit** with Add to cart, then **More little joys** (all products).
  - If the kit shows as "Your product's name", click the section → Product → pick the kit → **Save**.
- [ ] Themes → new theme → **⋯ → Publish**. Old copies → **⋯ → Remove**.

**Optional own banner photo:**
- Click **Banner** → Desktop image (1920×800) and Mobile image (1080×1350).
- ChatGPT prompt (attach a product photo saved from the product page):
  > Edit the photo I attached into a website banner, landscape 3:2. Keep the product exactly as it is (same shape, colours and printing; don't redraw or add anything to it). Place it on the right, slightly tilted, with a soft shadow, on a clean cream (#FBF1E8) to blush pink (#F6E3DF) studio background with a pink satin bow, a few pearl beads and small rose (#C97B84) hearts. Leave the left 45% empty for text. Realistic photo, soft daylight, no text, no logos.
  - For mobile, ask for portrait 2:3, with the product in the upper half and the bottom 40% left empty.

## 5. Pages, policies, menus (10 min)

- [ ] **Online Store → Pages**, and set the **Theme template** on each:

| Page | URL handle | Template | Page text |
|---|---|---|---|
| About Us | `about-us` | **about** | About text below |
| FAQ | `faq` | **faq** | leave empty |
| Contact | `contact` | **contact** | leave empty |

- [ ] **Settings → Policies:**
  - **Shipping** and **Refund**: paste the texts below.
  - **Privacy** and **Terms**: *Create from template*.
  - **Save**.
- [ ] **Navigation:**
  - Main menu: Home · Kids Makeup Gifts · Our Handmade & Gift Range · About Us · FAQ · Contact
  - Footer menu: FAQ · Contact · Shipping Policy · Refund Policy · Privacy Policy

## 6. Payments and delivery (10 min)

- [ ] **Settings → Payments → Manual payment methods:**
  - **Cash on Delivery (COD)** → Activate.
  - **Create custom payment method:**
    - Name: `Advance payment - Bank / JazzCash / Easypaisa`
    - Additional details: `Send the order total to: Bank ____ (Account title ____, Account no. ____) / JazzCash ____ / Easypaisa ____. Then WhatsApp the payment screenshot with your order number to ____.`
    - Payment instructions: `We ship your order after we receive the payment screenshot.`
    - Activate.
  - Shopify can't block COD for one product without an app. If someone picks COD for the lollipop kit, ask for advance payment on WhatsApp before you order it in DSers.
- [ ] **Settings → Shipping and delivery → Pakistan:**
  - `Standard delivery` → Rs 200.
  - `Free delivery` → Rs 0 for orders of Rs 2,500 and up.
- [ ] **Settings → Checkout:** shipping address phone number → **Required**.

## 7. Go live (10 min)

- [ ] Test on your phone:
  - Home → kit → the date line says **10–20 working days**.
  - A bracelet (your own) says **3–5 working days**.
  - Add to cart → the free-delivery bar shows.
  - Checkout shows **COD** and **Advance payment**.
- [ ] **Online Store → Preferences:** copy the store password, or pick a plan to remove it.
- [ ] Instagram @trinket_tales_1:
  - Bio link → `https://wmyj10-ju.myshopify.com`
  - Post the kit with the caption from Assignment 3.
- [ ] In the Word files, fill in **Roll No.** and **Course**, then **Save as PDF** → submit.
  - Paste a screenshot of the live product page in Assignment 3, section 3.
- [ ] Take a **screenshot of DSers → My Products** showing the kit linked to AliExpress, for Assignment 2.
- [ ] After marks: **change the password** and turn on **2-step verification**.

---

## Final links

| What | Link |
|---|---|
| Store | https://wmyj10-ju.myshopify.com |
| Main product (after step 2) | https://wmyj10-ju.myshopify.com/products/lollipop-makeup-kit-for-girls |
| Main supplier (AliExpress) | https://www.aliexpress.com/item/4000781891981.html |
| Backup supplier (AliExpress) | https://www.aliexpress.com/item/4000811549459.html |
| Extra: butterfly bracelet | https://www.aliexpress.com/item/1005006413334032.html |
| Extra: flower bead set | https://www.aliexpress.com/item/1005011994527815.html |
| Extra: pearl bracelet | https://www.aliexpress.com/item/1005004840626196.html |
| Instagram | https://www.instagram.com/trinket_tales_1 |

---

## Text to paste

### About Us
Trinket Tales started with a simple idea: small things can bring big happiness.

We pick cute, gift-ready things for girls, from washable makeup gift boxes to handmade bracelets and little gift bundles. They're the kind of surprise that makes a birthday, an Eid morning or an ordinary day a bit brighter. Every order is checked, packed with care and delivered anywhere in Pakistan.

Follow us on Instagram @trinket_tales_1 for new arrivals.

### Shipping Policy
We deliver all over Pakistan.

**Items from our own stock** (bracelets, gift bundles, little gift boxes) are dispatched within 1 to 2 working days and usually arrive in 3 to 5 working days. Cash on delivery is available.

**Imported gift boxes** (shown on the product page) ship from our supplier and usually arrive in 10 to 20 working days. They need advance payment by bank transfer, JazzCash or Easypaisa, and we share a tracking number once the parcel ships.

Delivery is Rs 200, and free on orders over Rs 2,500.

### Refund Policy
If your parcel arrives damaged or you received the wrong item, message us within 3 days of delivery with a photo or unboxing video. We'll send a replacement or give a full refund.

If an imported item hasn't arrived within 30 working days of your order, we'll refund you in full.

Unopened items from our own stock can be returned within 7 days of delivery, with return delivery paid by the customer. For hygiene reasons, opened or used makeup can't be returned.

Refunds are sent by bank transfer, Easypaisa or JazzCash within 5 working days.
