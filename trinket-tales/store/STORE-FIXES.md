# Trinket Tales: store review and fixes (9 Nov)

I reviewed the 4 pages you saved: home, makeup kit, bracelet set and all products. The design works. Most of what's left is product data, and a few pieces of it would cost you marks or money.

Do the steps in this order. Everything is in Shopify admin (Chrome, "Desktop site" on).

## 1. Makeup kit (most important)

Products → open **Kids Makeup Set for Girls Dreamy Style…**

| What | Now | Change to |
|---|---|---|
| Title | the long AliExpress title | `Dreamy Kids Makeup Set for Girls` |
| Price | Rs 1,687.70 for 1 kit, which is the supplier's cost, so you'd earn nothing | see the table below |
| Option name | Color | `Pack` |
| Option values | 4 kit, 3 kit, 2 kit, 1 kit X 12pcs | `1 Kit`, `2 Kits`, `3 Kits`, `4 Kits`. Drag 1 Kit to the top, so the page opens on Rs 2,999 and not the 4-kit price. |
| Tags | no `dropship` tag | `kids-makeup, dropship`. This makes the page show 10 to 20 working days. Right now it promises 3 to 5. |
| Description | the supplier's text ("Brand Name: NONE", "semi_Choice: yes"…) | delete all of it and paste **Text A** |
| Photos | 22 photos; the first one is a 4-box grid with the supplier's brand name | drag the cleanest photo to first place and delete the near-duplicates. Keep 6 to 8. |
| URL handle | the long AliExpress one | Search engine listing → Edit → URL handle: `dreamy-kids-makeup-set-for-girls`. Leave "Create a URL redirect" ticked. **The product link in your assignments only works after this.** |

| Pack | Price | Compare-at price |
|---|---|---|
| 1 Kit | 2999 | 3999 |
| 2 Kits | 5699 | 7999 |
| 3 Kits | 8299 | 11999 |
| 4 Kits | 10799 | 15999 |

Save.

## 2. Flower bead bracelet set (from AliExpress)

Products → open **Bohemian Daisy Flower Charm…**

- Title: `Boho Daisy Flower Bead Bracelet Set`. The current title also has a spelling mistake ("Wrsit").
- Price: `1199`, compare-at `1499`. Rs 681.73 is the supplier's cost. Only keep this price if DSers shows free or low shipping for it.
- Option name: `Metal Color` → `Colour`.
- Tags: `bracelets, dropship`.
- Description: delete the supplier text and paste **Text B**.
- Save.

## 3. Prices without decimals

Settings → General → Store defaults → Currency display → Change formatting:
- HTML without currency: `Rs {{amount_no_decimals}}`
- HTML with currency: `Rs {{amount_no_decimals}} PKR`

Save. Prices will then show "Rs 2,999" instead of "Rs.1,687.70".

## 4. Other products

- **Flower Bead Bracelet Set (3 Pieces)** and **Pearl Bracelet with Jade Bead** show "Sold out". The import didn't carry over the stock. Go to Products → **Inventory** and type `10` next to each colour, then Save.
- **Flower Bead Bracelet Set (3 Pieces)** is using the butterfly bracelet photo. Replace it with `bracelet-set-pink.jpg`, `-purple`, `-yellow` and `-red` from the instagram-products folder.
- **Mini Makeup Kit for Girls – Cute Gift Pouch** has no photo. Add one from the `photos` folder.
- **Gift boxes:** the home page shows only 2 category tiles, because the third collection is missing.
  1. Tag Aesthetic Self-Care Gift Box, Customize box and Mini Makeup Kit pouch with `gift-boxes`.
  2. Create the automated collection `Gift Boxes and Bundles`, with the condition "Product tag is equal to gift-boxes".

## 5. Policies (only Privacy exists right now)

Settings → Policies:
- **Shipping** and **Refund**: paste the texts from the last page of FINAL-CHECKLIST.
- **Terms of service**: Create from template.

Save. They'll show in the footer by themselves.

## 6. Customize (Online Store → Themes → Customize)

**Home page**
- **Banner** → Mobile image → remove it (X). You've set the same picture as both the desktop and the mobile image, so on phones the heading sits on top of the photo. Without a mobile image, phones show the photo whole with the text underneath.
- **Featured product** ("Our favourite gift") → Product → pick the **Dreamy Kids Makeup Set**. It's showing the bracelet set now.
- **Brand story** → click the eye icon to hide it. The Welcome card already tells the same story, and the round logo was showing 3 times on one page.
- **Welcome card** → you have 2 items. Add more if you like: Snack boxes, Bracelets, Phone charms, Keychains, Customized bangles.
- **Quick answers** → "How do I pay?" → replace the answer with **Text C**. Right now it says cash on delivery for everything.

**Product page** (top dropdown: Home page → Products → Default product)
- Icon row → first heading `Cash on delivery` → `Easy payment`. That row shows on imported items too.
- **Delivery and payment** tab → replace the text with **Text D**.

**Footer**
- Text block "Trinket Tales" → replace the text with **Text E**.

**Theme settings** (paintbrush) → **Trinket Tales** → **WhatsApp number**, e.g. `923001234567`. It's empty, so the chat button and the "Ask us on WhatsApp" line don't show yet.

Save.

## 7. Test it on your phone

- Home: the banner text sits under the photo, there are 3 category tiles, and the kit appears as the featured product.
- Kit page: Rs 2,999, the 1 Kit option selected, "arrives in 10 to 20 working days" and "Easy payment".
- A bracelet from your own stock: 3 to 5 days.
- The footer shows Shipping, Refund, Privacy and Terms.

---

## Texts to paste

### Text A: makeup kit description

Dress-up time, made dreamy.

A pretty makeup play set for girls who love dress-up games: soft eyeshadow colours, lipstick and press-on nails, all in one gift-ready set. A lovely birthday, Eid or return gift.

What's inside (per kit)
- Eyeshadow palette
- Lipstick
- 20 press-on nails with 12 sticky tabs
- 5 makeup brushes
- Nail file and finger separator

Good to know
- Choose 1, 2, 3 or 4 kits. Bigger packs are perfect for return gifts.
- Best for ages 6 and up. Younger girls should play with a grown-up.
- Try a small patch test first and keep away from eyes.

Delivery and payment: this set ships from our supplier and arrives in about 10 to 20 working days. Pay in advance by bank transfer, JazzCash or Easypaisa. We confirm every order on WhatsApp.

### Text B: bracelet set description

A bright boho bracelet set with glass and crystal beads and a little daisy flower charm. It's stretchy, so it slips on easily and fits most wrists.

- Glass, crystal and acrylic beads
- Elastic cord, about 18 cm
- Colours: White, Black, Blue, Red, Pink and Green

Delivery and payment: this set ships from our supplier and arrives in about 10 to 20 working days. Pay in advance by bank transfer, JazzCash or Easypaisa. We confirm every order on WhatsApp.

### Text C: FAQ "How do I pay?"

Items from our own stock are cash on delivery: you pay the rider when your parcel arrives. Imported items ship straight from our supplier, so they're paid in advance by bank transfer, JazzCash or Easypaisa. Each product page tells you which one it is.

### Text D: product page "Delivery and payment"

Our own stock: cash on delivery, arrives in 3 to 5 working days. Imported items (the page shows 10 to 20 working days): advance payment by bank transfer, JazzCash or Easypaisa. Delivery is Rs 200, free on orders over Rs 2,500.

### Text E: footer

Small things, big happiness. Cute, gift-ready little things for girls, delivered all over Pakistan.
