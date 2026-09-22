# Going Forward Premium — website

The public price list at **https://yayyaylay1996.github.io/goingforward-premium/**

## How to change a price

Open the Google Sheet (`DigitalShop_Stock_Orders`), edit the **Products** tab,
and you are done. The website reads that tab live, the same way the Telegram bot
does, so the two can never disagree.

- Bot picks up a change in about **1 minute**
- Website picks it up in about **5 minutes** (Google caches the published file)

Nothing here needs to be re-uploaded when a price changes. You only touch this
repo if you want to change the page design or add a logo.

## What is in here

| File | What it is |
|---|---|
| `index.html` | The whole website — one file |
| `logos/` | App logos, matched to the sheet's **Logo** column |

## Safety

Only the **Products** tab of the sheet is published to the web. Inventory
(account credentials) and Orders are **not** published and never reach this page.
