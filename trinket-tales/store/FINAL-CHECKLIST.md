# Trinket Tales: final Shopify checklist (desktop)

Open **admin.shopify.com** on a computer and log in with the store's account.
About 45 minutes in total. If a step is already done, tick it and move on.

**Files you need:**
- `trinket-tales-theme-v3-UPLOAD.zip`
- photos `01`–`06`
- `trinket-tales-logo-round.png`
- `trinket-tales-favicon-512.png`
- `product-import.csv`

---

## 1. Product (5 min)

- [ ] **Settings → General → Store defaults → Currency** = Pakistani Rupee (PKR) → Save.
- [ ] **Products** → open *Mini Makeup Kit for Girls - Cute Gift Pouch*.
  - If it isn't there: **Products → Import → `product-import.csv`**.
- [ ] **Media** → upload photos **01 to 06** in that order. 01 is the main image.
- [ ] **Variants** → click each colour → **image** → pick that colour's photo → Save.
- [ ] **Search engine listing → Edit** → URL handle = `mini-makeup-kit-for-girls`.
- [ ] **Status** = Active, **Sales channels** = Online Store ✔ → Save.

## 2. Theme (5 min)

- [ ] **Online Store → Themes → Add theme → Upload zip file** → `trinket-tales-theme-v3-UPLOAD.zip`. Don't unzip it.
- [ ] On the new theme click **Customize**.
- [ ] Click the **paintbrush (Theme settings)**:
  - **Logo** → `trinket-tales-logo-round.png`.
  - **Favicon** → `trinket-tales-favicon-512.png`.
  - **Save**.
- [ ] Optional, your own banner photos: on the home page click **Banner** → **Desktop image** and **Mobile image** → Save.
  - Desktop: 1920×800.
  - Mobile: 1080×1350.
  - The ChatGPT prompts are in `STORE-SETUP.pdf`, section C.
- [ ] Back in **Themes**:
  - New theme → **⋯ → Publish**.
  - Old copies → **⋯ → Remove**.

## 3. Pages (5 min)

**Online Store → Pages.** Make three pages, or open the existing ones, and set the **Theme template** box on the right:

| Page title | Content | Theme template | URL handle |
|---|---|---|---|
| About Us | paste the **About text** below | **about** | `about-us` |
| FAQ | leave empty | **faq** | `faq` |
| Contact | leave empty | **contact** | `contact` |

## 4. Policies and menus (5 min)

- [ ] **Settings → Policies**:
  - **Refund policy** → paste the Refund text below.
  - **Shipping policy** → paste the Shipping text below.
  - **Privacy** and **Terms** → *Create from template*.
  - **Save**.
- [ ] **Online Store → Navigation → Main menu**: Home · Shop (link: Products → the pouch) · About Us · FAQ · Contact → Save.
- [ ] **Footer menu**: FAQ · Contact · Shipping Policy · Refund Policy · Privacy Policy → Save.

## 5. Payment, delivery, checkout (5 min)

- [ ] **Settings → Payments → Manual payment methods → Cash on Delivery (COD) → Activate**.
- [ ] **Settings → Shipping and delivery → General shipping rates → Pakistan**:
  - **Add rate** `Standard delivery (3–5 working days)` = Rs 200.
  - **Add rate** `Free delivery` = Rs 0 → *Add conditions* → order price minimum Rs 2,500 → Save.
- [ ] **Settings → Checkout**:
  - Customer contact: **Phone number or email**.
  - Shipping address phone number: **Required** (needed for cash on delivery).
  - Save.

## 6. Dropshipping (10 min)

**DSers + AliExpress** (the connection shown inside Shopify):
- [ ] **Apps → search "DSers" → Install** → log in with Shopify.
- [ ] In DSers: **Link AliExpress** → log in or sign up with the store email → Authorize.
- [ ] On AliExpress, search `kids makeup set bag lipstick nail polish hand cream`. Pick a kit that:
  - matches our pouch,
  - has a rating of 4.5+ and 100+ sold,
  - ships to Pakistan.

  Copy its link.

- [ ] **DSers → Products** → our pouch → **Mapping → Basic mapping** → paste the link → match the 5 colours → Save.
- [ ] Take a **screenshot** of the mapping screen for the assignment.

**Markaz** (local cash-on-delivery supplier, phone app):
- [ ] Sign up with the mobile number and add Easypaisa, JazzCash or a bank account.
- [ ] Save the matching kit.

## 7. Go live and submit (10 min)

- [ ] **Online Store → Preferences → Password protection**: copy the password, or pick a plan to remove it.
- [ ] Test on the phone: home → tap a colour → Add to cart → Checkout shows **Cash on Delivery**.
- [ ] Instagram @trinket_tales_1 → Edit profile → **Links** → add the store link.
- [ ] In the 4 Word files: Roll No., Course, Store link → **Save as PDF** → submit.
- [ ] After marks: **change the password** and turn on **2-step verification**.

---

## Text to paste

### About Us
Trinket Tales started with a simple idea: small things can bring big happiness.

We pick cute, gift-ready little things for girls, the kind of surprise that makes a birthday, an Eid morning or an ordinary day a bit brighter. Every order is checked, packed with care and delivered with cash on delivery anywhere in Pakistan.

Follow us on Instagram @trinket_tales_1 for new colours and drops.


### Shipping Policy
We deliver all over Pakistan. After you order, we confirm it by WhatsApp or phone and dispatch within 1 to 2 working days. Delivery usually takes 3 to 5 working days in most cities, and a little longer for remote areas.

Delivery charge is Rs 200, and free on orders over Rs 2,500. Payment is cash on delivery.

### Refund Policy
If your parcel arrives damaged or you received the wrong item, message us within 3 days of delivery with a photo or unboxing video. We'll send a replacement or give a full refund.

Unopened items can be returned within 7 days of delivery; return delivery is paid by the customer. For hygiene reasons, opened or used makeup can't be returned.

Refunds are sent by bank transfer, Easypaisa or JazzCash within 5 working days of receiving the return.
