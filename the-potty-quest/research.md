# Research: The Potty Quest (Facebook + Instagram)

## 1. Offer check
- **Slug:** `the-potty-quest`
- **What it is:** our own product, not an affiliate offer. A $9.99 one-time web app: a playful 14-day "Potty
  Island" adventure with Ellie the elephant for parents of toddlers (about 2–4) who refuse the potty. Bonus
  printables (reward chart, certificate, adventure cards). No subscription.
- **No landers:** the live site is the funnel, so this folder holds only the dashboard, ad copy and image ads.
  `campaign.json` tells the Campaigns page check which live pages to open.
- **Funnel:** homepage (long page) → free quiz at `/play/#/start` (how the toddler reacts picks the tip) → free tip
  on screen → email (optional marketing consent) → $9.99 offer → checkout.
- **Vertical:** Other (parenting). Not health, but next to it: no medical, developmental or expert claims.
- **Traffic:** Facebook + Instagram only.
- **EPC:** not applicable (own product).

### Meta ads policy check: allowed, with care
- **Personal attributes:** don't assert or imply that the viewer or their child has a condition. Potty refusal is
  described as a common stage ("Some toddlers…", "When toddlers refuse the potty…"). Ellie's tone stays gentle.
- **Misleading claims:** no "potty trained in 14 days", "guaranteed", "works for every toddler", "proven" or
  "cure". It's a 14-day activity programme, not a 14-day outcome.
- **No guilt, shame or fear** (partner brief 06).
- **Ads aimed at parents, not children.** No child data or quiz answers go to Meta.
- **No fake buttons or platform UI on the images.** The "Start with a free tip" line is plain text.

## 2. Avatar
1. **Who:** mostly moms, late 20s to 30s, with a toddler of about 2–4. Busy, on their phone, often scrolling at
   night after bedtime. They've read conflicting advice.
2. **Pain points:**
   - an instant NO at every potty mention
   - running off or hiding
   - tears or meltdowns
   - only wanting diapers
   - daycare or preschool deadlines
   - pressure from relatives
   - feeling they're "doing it wrong"
   - power struggles
   - progress that slides back
   - not knowing what to say
3. **Already tried:**
   - asking "Do you need to go?"
   - sticker charts with no plan
   - bribes
   - "big kids use the potty"
   - three-day boot camps
   - waiting it out
4. **What makes them click now:** something small, gentle and doable today. It's free to start, and it fits the
   reaction they see.
5. **Where they are:** Facebook groups for parents, Instagram Reels, Pinterest, and mom blogs.

## 3. Angles
| Angle | Score | Why |
|---|---|---|
| Curiosity | 5 | The free tip turns on a real insight (the yes-or-no "question trap", the chase, the big leap). |
| Direct Benefit | 5 | Easy to picture: one playful activity a day for 14 days with Ellie. |
| Pain Point | 4 | The NO standoff is universal at this stage. Framed as common, never about the viewer. |
| Social Proof | 1 | Skipped: no published reviews or numbers yet. Never invent them. |
| Fear | 1 | Skipped: guilt and worry are ruled out (brief 06), and it edges into health. |

**Destination per angle:**
- **Pain Point and Curiosity → the free quiz.** Cold social traffic converts on low effort, and the tip closes the
  hook's loop.
- **Direct Benefit → the homepage.** The benefit needs the "How it works" and "Peek inside" sections to land.

## 4. Tracking
- WooCommerce Order Attribution records the utm tags on the order.
- Paid links:
  - `utm_source=facebook&utm_medium=paid_social&utm_campaign=launch_nov26_long|short&utm_content=<angle>`
  - Short and long pages are told apart by the `_long` / `_short` suffix.
- On `/play/` links the tags go **before** `#/start`.
