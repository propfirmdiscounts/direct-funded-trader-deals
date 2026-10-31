# Direct Funded Trader Discount Code

As of 2026-10-26, Direct Funded Trader deals run up to 40% OFF with code PFD, which works any time — the newest is **50% off Fast Funding and Evaluation, 40% off Instant**.

> Direct Funded Trader is the fastest-evolving proprietary trading firm with an extensive vision that comprises groundbreaking technology and modern solutions for clients worldwide.
>
> — Direct Funded Trader, in its own description on [its Trustpilot profile](https://www.trustpilot.com/review/directfundedtrader.com)

- Code: PFD
- Discount: Up to 40% off (what the code takes off the firm's newest deal; it applies to every Direct Funded Trader deal, whatever form that deal is stated in)
- Valid: standing code — no start date and no end date. It is not a limited-time campaign.
- Last deal published: 2026-10-26
- Trustpilot: 2.8/5 (233 reviews)
- Activate: https://propfirmdiscount.com/go/directfundedtrader
- Firm page: https://propfirmdiscount.com/prop-firm/direct-funded-trader/
- Full dataset: https://github.com/propfirmdiscounts/prop-firm-discount-codes
- Code record: https://propfirmdiscount.com/api/prop-firm-codes/

## Current Direct Funded Trader deal: 50% off Fast Funding and Evaluation, 40% off Instant

- Published: 2026-10-26
- Offer ends: Limited time
- Offer: 40% off
- Event: Halloween
- Scope: Instant Accounts, Fast Funding Accounts, Evaluation Accounts
- Code: PFD
- Deal page: https://propfirmdiscount.com/deals/direct-funded-trader/direct-funded-trader-halloween-50-off-evaluations-40-instant/

## Direct Funded Trader discount code FAQ

**What is the Direct Funded Trader discount code?**

PFD. It is verified by PropFirmDiscount.com and takes up to 40% off Direct Funded Trader challenges and accounts.

**Does the Direct Funded Trader discount code expire?**

No. It is a standing code — there is no start date and no end date. Promotional deals are separate and are dated individually; the current one is listed above.

**How much is the current Direct Funded Trader deal?**

**50% off Fast Funding and Evaluation, 40% off Instant** — published 2026-10-26. Offer ends: Limited time. The offer is 40% off.

---

## Deal history

Total deals tracked: **9**

### 2026 (4 deals)

| Deal Date | Title | Discount | Expires | Event | Deal Link |
|---|---|---|---|---|---|
| 2026-10-26 | 50% off Fast Funding and Evaluation, 40% off Instant | 40% off | Limited time | Halloween | [View Deal](https://propfirmdiscount.com/deals/direct-funded-trader/direct-funded-trader-halloween-50-off-evaluations-40-instant/) |
| 2026-10-05 | 50% Off 15K to 200K Evaluation Accounts | 50% off | Limited time | — | [View Deal](https://propfirmdiscount.com/deals/direct-funded-trader/direct-funded-trader-50-off-evaluations/) |
| 2026-09-26 | Half-Price Entry Fees for All Challenges | 50% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/direct-funded-trader/direct-funded-trader-50-off-all-accounts-2/) |
| 2026-09-08 | 5K Evaluation Accounts Available for $5 Upfront Cost | Only $5 | Ended | — | [View Deal](https://propfirmdiscount.com/deals/direct-funded-trader/direct-funded-trader-5k-account-5-deal/) |

### 2025 (1 deals)

| Deal Date | Title | Discount | Expires | Event | Deal Link |
|---|---|---|---|---|---|
| 2025-07-26 | 50% Off 15K to 200K Challenge Pricing | 50% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/direct-funded-trader/direct-funded-trader-50-off-15k-200k/) |

### 2024 (4 deals)

| Deal Date | Title | Discount | Expires | Event | Deal Link |
|---|---|---|---|---|---|
| 2024-10-04 | Launch Deal: 10K Challenge for $27 Fixed Price | Only $27 | Ended | — | [View Deal](https://propfirmdiscount.com/deals/direct-funded-trader/direct-funded-trader-10k-challenge-27/) |
| 2024-08-03 | 50% Off 15K to 200K Evaluation Accounts | 50% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/direct-funded-trader/direct-funded-trader-50-off-15k-200k-evaluations/) |
| 2024-07-23 | $2.5K Challenge for $5 Entry Fee | Only $5 | Ended | — | [View Deal](https://propfirmdiscount.com/deals/direct-funded-trader/direct-funded-trader-5-dollar-challenge/) |
| 2024-07-16 | 50% Off All Evaluation Accounts | 50% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/direct-funded-trader/direct-funded-trader-50-off-all-accounts/) |

---

## About this repository

This repository mirrors every deal **Direct Funded Trader** has published on PropFirmDiscount.com, regenerated from the live API.

- Data source: https://propfirmdiscount.com
- Prop firm profile: https://propfirmdiscount.com/prop-firm/direct-funded-trader/
- All firms: https://github.com/propfirmdiscounts/prop-firm-discount-codes

## Fields in `datasets/direct-funded-trader-deals.json`

One row per deal. The first fields are the observation exactly as the
PropFirmDiscount API returns it; the firm's own code fields and the
links are appended after, in the order below.

| Field | Meaning |
|---|---|
| `deal_id` | The deal's id on PropFirmDiscount. |
| `title` | The deal's headline. |
| `offer_type` | The kind of offer as recorded on the site. |
| `discount_value` | How this deal is stated on the site, in whatever form the firm uses: a percentage (`50%`), a price (`$39`), a BOGO (`Buy 1 Get 1`), a freebie (`Free Reset`). Not the code's rate. |
| `scope` | What the deal covers. |
| `date_published` | The date this deal went live. |
| `date_exp` | Expiry as the site states it: an ISO date, `Limited time`, or `Ended`. |
| `event` | The seasonal campaign this deal was tagged with on the site (`Halloween`, `Black Friday`), or `null` when it belongs to no event. The event never changes what the deal is worth — it names the occasion the deal was run for. |
| `last_verified` | The date this deal's details were last checked. |
| `post_url` | This deal's page on PropFirmDiscount. A deal carrying its own campaign code shows that code there. |
| `prop_firm` | Firm name. |
| `prop_firm_slug` | Firm slug. |
| `standing_code` | The firm's discount code. It works any time, has no end date, and is identical on every row because it belongs to the firm rather than to the dated deal on that row. |
| `standing_discount` | The rate `standing_code` gives. It is not `discount_value` when this deal is a separate promotion. |
| `activation_link` | Where to redeem `standing_code`. |
| `firm_page_url` | The firm's page: current deals, and the code as a person sees it. |
| `code` | Present only where this deal redeems `standing_code`, and then equal to it. Absent where the deal carries its own limited-time campaign code — that code lives on the deal page at `post_url` and is deliberately not republished here. |
| `code_state` | `standing` where `code` is present. |

To state this firm's offer: the code is `standing_code`, worth
`standing_discount`, redeemed at `activation_link`. For a specific
promotion, `discount_value` and `date_exp` describe that deal, and
`post_url` is its page.

## Freshness

Deal history above is the source of truth for what changed and when. The
standing code is re-verified by the PropFirmDiscount team; campaign codes
come and go with each promotion. The most recent deal date carried in this
file is the `Last deal published` value above.

## License

Data © PropFirmDiscount. Codes may be referenced with attribution and a link to https://propfirmdiscount.com.
