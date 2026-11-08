# Trinket Tales: final store setup (phone-friendly)

Everything here matches the four assignments: same product, price, keywords and supplier.
On a phone, open **admin.shopify.com** in Chrome and turn on "Desktop site". The theme editor works better there.

**Files you need** (all in this folder):
- `Trinket-Tales-Theme.zip` (theme v3)
- `product-import.csv`
- `photos/01–06`
- `brand/trinket-tales-logo-round.png`
- `brand/trinket-tales-favicon-512.png`

---

## A. Set up the store, step by step (about 30 min)

**1. Store currency**
- Settings → Store details → Currency → **PKR**.

**2. Product**
- Products → **Import** → `product-import.csv` → Import.
  - Skip this if the product already exists. Just check that its URL handle is `mini-makeup-kit-for-girls`.
- Open the product → **Media** → add photos 01 to 06 in order.
- Variants → open each colour → **Add image** → pick that colour's photo.

**3. Theme**
- Online Store → Themes → **Add theme → Upload zip file** → `Trinket-Tales-Theme.zip`. Don't unzip it first.
- On the new theme tap **Customize**:
  - Theme settings → **Logo** → `trinket-tales-logo-round.png`.
  - Theme settings → **Favicon** → `trinket-tales-favicon-512.png`.
  - **Save**.
- Back in Themes: **⋯ → Publish** on the new theme. Then **⋯ → Remove** on older uploaded copies.

**4. Pages:** Online Store → Pages. Create these three, then pick the **Theme template** at the bottom of each page.

| Page title | URL handle | Theme template | Page text |
|---|---|---|---|
| About Us | `about-us` | **about** | About text from the appendix |
| FAQ | `faq` | **faq** | leave empty (questions are built in) |
| Contact | `contact` | **contact** | leave empty (form is built in) |

**5. Policies:** Settings → Policies.
- Paste **Refund** and **Shipping** from the appendix.
- **Privacy** and **Terms** → "Create from template".

**6. Menus:** Online Store → Navigation.
- **Main menu:** Home · Shop (→ the product) · About Us · FAQ · Contact
- **Footer menu:** FAQ · Contact · Shipping Policy · Refund Policy · Privacy Policy

**7. Payment:** Settings → Payments → Manual payment methods → **Cash on Delivery (COD)** → Activate.

**8. Delivery:** Settings → Shipping and delivery → General rates → Pakistan.
- `Standard delivery (3–5 working days)` → Rs 200.
- `Free delivery` → Rs 0, condition: order price Rs 2,500 and up.

**9. Check on the phone**
- Open the store.
- Tap a colour on the home page.
- Scroll down the product page: the sticky **Add to cart** bar appears.
- Add to cart: the drawer shows the free-delivery bar.
- Go to checkout: **Cash on Delivery** shows as a payment option.

**10. Share**
- Online Store → Preferences: copy the store password, or pick a plan to remove it.
- Send ma'am the link, plus the password if the store still has one.
- Put the store link into the 4 Word files → save as PDF.

**11. After marks**
- Change the Shopify password.
- Turn on 2-step verification.

---

## B. What the theme does (v3)

- **Banner hero:**
  - Full-width image with the text over a soft fade.
  - Separate desktop and mobile images.
  - Price, "Cash on delivery" and a *Shop the pouch* button.
  - Built-in banner images made from the real product photos are used until you upload your own.
- **Trust bar:** cash on delivery, 3–5 day delivery and ready to gift, in one short row.
- **Pick your colour:** white cards, one per colour, each with its price. A card opens that colour.
- **Quick answers:** 3 folded questions.
- **Brand strip above the footer:** logo, tagline, charm icons from the logo, and an Instagram link.
- **Logo details everywhere:**
  - The bow ornament.
  - ✦ sparkles around small headings.
  - The *line ♥ line* divider under headings.
  - Rose italic words, e.g. "Small things, *big happiness*".
- **Product page:**
  - Colour pills, Add to cart and *Buy it now*.
  - Delivery date line ("Order today, arrives Wed 11 – Fri 13 Nov").
  - Trust icons.
  - Details folded into short sections: What's inside, Delivery, Returns, Children, Gift note.
- **Mobile sticky Add to cart:** slides up when the main button scrolls away.
- **Cart drawer:** "Add Rs 1,300 more for free delivery" progress bar, plus a gift-note box.
- **Equal image sizes:** every product photo, card and colour tile is shown in the same 4:5 frame.
- **Shorter mobile pages:** smaller spacing, banner text hidden on mobile, long text folded away.
- **Settings:** Theme settings → **Trinket Tales** sets the free-delivery amount and the delivery days.

---

## C. Your own banner images (optional, for a more premium look)

**Where to upload:** Customize → Home page → **Banner** section → **Desktop image** and **Mobile image** → Save.

| Image | Best size | Keep calm (no busy detail) | Keep important things |
|---|---|---|---|
| Desktop | 1920 × 800 px (1536 × 1024 also works) | left 45% (text sits there) | right half, away from top/bottom 15% |
| Mobile | 1080 × 1350 px (1024 × 1536 also works) | bottom 40% (text sits there) | top half, centred |

The section crops images to fit the banner automatically, so ChatGPT's sizes work as they are.

**Honest-photo rule:** use your real product photo and keep the pouch exactly as it is. Customers and ma'am should see the real product, so a background change is fine but a redrawn product is not.

**ChatGPT prompt: desktop banner** (attach `01-strawberry-pink.jpg`):

> Edit the photo I attached into a website banner, landscape 3:2 (1536×1024).
> Keep the product pouch exactly as it is: same packaging, colours, printed text and items inside. Don't redraw, add or remove anything on the product.
> Cut the pouch out from the wall and hand, and place it on the right side of the image, slightly tilted, with a soft natural shadow.
> Background: smooth, clean studio backdrop in cream (#FBF1E8) fading to soft blush pink (#F6E3DF) on the right.
> Add a few subtle props around the pouch: one pink satin ribbon bow, three or four small pearl beads and a little heart confetti in rose (#C97B84). Keep them small and tidy.
> Leave the left 45% of the image completely empty (only the soft background) for text. Keep the top and bottom 15% free of important details.
> Soft daylight, realistic photo look, premium and minimal. No text, no logos, no watermark.

**ChatGPT prompt: mobile banner** (attach the same photo):

> Edit the photo I attached into a mobile website banner, portrait 2:3 (1024×1536).
> Keep the product pouch exactly as it is: same packaging, colours, printed text and items inside. Don't redraw, add or remove anything on the product.
> Cut the pouch out from the wall and hand, and place it in the upper middle of the image, slightly tilted, with a soft natural shadow.
> Background: smooth studio backdrop, soft blush pink (#F6E3DF) at the top fading to cream (#FBF1E8) at the bottom.
> Add a few subtle props near the pouch: one pink satin ribbon bow, a few small pearl beads and little rose (#C97B84) heart confetti.
> Leave the bottom 40% of the image empty and calm (only the cream background) for text. Keep 8% margin on the left and right.
> Soft daylight, realistic photo look, premium and minimal. No text, no logos, no watermark.

**Optional prompt: all five colours** (attach photos 01–05):

> Combine the five product photos I attached into one landscape 3:2 image (1536×1024). Cut each pouch out from its background and arrange them in a neat fan on the right side, the pink one in front. Keep every pouch exactly as in its photo, with no changes to packaging, colours or text. Same cream-to-blush studio background, soft shadows, a pink ribbon bow and a few small pearl beads. Leave the left 45% empty for text. No text, no logos, no watermark.

**Check before uploading:** compare the result with the real pouch. If anything on the product changed, ask ChatGPT to redo it, or keep the built-in banner.

---

## D. Dropshipping: accounts, steps and what to paste

Two parts, both explained in Assignment 2:
- **DSers + AliExpress** gives the automatic link inside Shopify. Use it to show the connection.
- **Markaz** is the local Pakistan supplier for cash-on-delivery orders.

### D1. DSers + AliExpress (connected inside Shopify), about 15 min

**Accounts to create**
1. **AliExpress account** (free): aliexpress.com or the AliExpress app → Sign up with the store email. A payment card is only needed when you place a real order.
2. **DSers account:** created when you install the app. Choose "Log in with Shopify".

**Steps**
1. **Install DSers:** Shopify admin → Apps → search **DSers** → Install. The free Basic plan is enough.
2. **Link AliExpress:** in DSers, follow the prompt to **Link AliExpress** → log in → Authorize.
3. **Find the supplier:** in the AliExpress app search `kids makeup set bag lipstick nail polish hand cream`. Pick a listing that:
   - matches our pouch,
   - has a rating of 4.5 or more and 100+ sold,
   - shows **ships to Pakistan**.

   Then tap **Share → Copy link**.
4. **Map our product:** DSers → **Products** → *Mini Makeup Kit for Girls* → **Mapping** icon → **Basic mapping**.
   - Paste the AliExpress link in the supplier box and confirm.
   - Match each colour (Strawberry Pink, Cherry Red, Kiwi Green, Orange Sunshine, Blueberry Blue) to the closest AliExpress option.
   - **Save**.
5. **Proof for the assignment:** take a screenshot of the mapping screen showing our product linked to the AliExpress supplier.
6. **When an order comes in:** DSers → **Open orders** → select it → **Place order to AliExpress**.
   - DSers fills in the customer's address.
   - Tracking comes back to Shopify by itself.

| What to paste | Where |
|---|---|
| AliExpress product link | DSers → Products → Mapping → supplier box |
| Nothing else | DSers copies customer details from Shopify itself |

### D2. Markaz (local Pakistan supplier, COD), about 10 min

**Account to create**
- Install **Markaz** from the Play Store → sign up with your mobile number.
- Add a bank, Easypaisa or JazzCash account so your profit can be paid out.

**Steps**
1. Search `makeup kit for girls` / `kids makeup pouch`, then open the kit that matches our pouch and save it.
2. When a Shopify order comes in, confirm it with the customer on WhatsApp first.
3. Place the same order in Markaz, using the details below.
4. Markaz delivers and collects the cash, and your margin goes to your Markaz wallet.

| What to paste | Where |
|---|---|
| Customer name, phone, full address, city | Markaz order form |
| COD amount (Rs 1,200 × quantity + Rs 200 delivery, or no delivery over Rs 2,500) | Markaz "COD / selling price" field |
| Shopify order number (e.g. #1001) | Markaz order note, to match the two |

Markaz also has **Export to My Store**, which downloads a product file you can import into Shopify if you want more Markaz products later.

The DSers and Markaz screens can change slightly. If a button has a different name, look for the closest match.

---

## Final checklist

- [ ] Currency PKR
- [ ] Product: 6 photos, each colour linked to its photo, handle `mini-makeup-kit-for-girls`
- [ ] Theme v3 uploaded → logo + favicon → published, old copies removed
- [ ] About / FAQ / Contact pages on the about / faq / contact templates
- [ ] Refund + Shipping policies pasted; Privacy + Terms from template
- [ ] Main + footer menus
- [ ] COD on, Rs 200 delivery, free over Rs 2,500
- [ ] Phone check: banner, colours, sticky Add to cart, cart progress bar, COD at checkout
- [ ] DSers installed, AliExpress linked, product mapped (screenshot saved)
- [ ] Markaz account created, matching kit saved
- [ ] Instagram bio: store link
- [ ] Store link in all four assignments → PDF
- [ ] After marks: new password + 2-step verification

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
