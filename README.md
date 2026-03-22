# SplitSmart 🧾

A bill splitting web app I built because I was tired of the awkward "who ate what" argument every time we went out with friends especially when half the group is veg and the other half ordered everything non-veg on the menu.

---

## Why I built this

We were at a restaurant, 8 people, mixed veg and non-veg orders. Someone suggested Splitwise but it doesn't handle item-level veg/non-veg splitting natively. We ended up doing mental math for 15 minutes. That was enough motivation.

So I built SplitSmart — takes maybe 2 minutes to split a bill, and everyone pays exactly what they ordered.

---

## What it does

- Add everyone in the group and mark them as veg or non-veg
- Add bill items manually or just upload a photo of the bill and AI reads it automatically
- Veg items automatically go to veg people, non-veg items to non-veg people
- Shared items (drinks, rice, bread) — you choose who splits those
- Add tax, tip, and discount on top — works in both % and fixed amount
- Calculates who owes what and gives you the shortest settlement path (minimum transactions)
- Copy the full summary in one tap to share on WhatsApp

---

## Stack

Just plain HTML, CSS, and JavaScript. No frameworks, no build tools, no npm install. Open the file and it works.

---

## How to run

Download the `splitsmart.html` file and open it in any browser. That's it.


---

## Features

- 4-step wizard (Setup → Items → Adjustments → Results)
- AI-powered bill scanning via camera upload
- Veg / Non-Veg / Shared item tagging
- Tax, tip, discount with % or fixed amount toggle
- "Paid the bill" tracker for settlement calculation
- Debt simplification — minimizes number of transactions
- Works with ₹, $, €, £, ¥, AED, SGD
- Quantity support for items
- Copy summary to clipboard

---

## Screenshots


---

## Known issues / things I want to add

- Export as PDF
- QR code to share the split
- Dark mode
- UPI deep links for quick payment

---
