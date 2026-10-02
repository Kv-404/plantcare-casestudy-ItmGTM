# PlantCare — Case 57

Home plant-care subscription for the GTM sprint. One technician visits flats in two nearby buildings, twice a month, for ₹399.

This folder has two files: `index.html` and this README. Open `index.html` in a browser. Nothing to install.

## The offer

PlantCare is for someone who is at the office when the plants need water. The worked example is Ananya Rao, 29, in Maple Residency. She has eight plants, a long office day, and a maid who overwatered a money plant.

The promise is simple. ₹399 a month. Two visits. Water, a light prune, a pest look, and a photo the same day. The resident can pause a month.

The service cost given in the case is ₹170 per customer. Contribution is:

**₹399 − ₹170 = ₹229** per paying subscriber (57.4%).

## Why the route is clustered

A technician can do 14 visits in a day only when the flats are in one building. The pilot uses two buildings inside 3 km:

- **Maple Residency — Thursday**
- **Cedar Heights — Friday**

Any other building is a waitlist name. No visit is placed, and it does not count in the money.

Working-day assumption: **26 days** in the month. Two visits per subscriber, so one full technician holds:

**(14 × 26) / 2 = 182 subscribers**

At that load the contribution is **182 × ₹229 = ₹41,678**. A thinner day earns less from the same person: 10 visits a day is ₹29,770, and 8 visits a day is ₹23,816. The gap between a full day and a scattered day is ₹17,862.

Pay Ravi **per visit** during the pilot, about ₹85 a visit, so the ₹229 is real from the first subscriber. A salary sized to a full route is ₹30,940 (182 × ₹170). Spread over a small list, that salary costs more than ₹399. The loss ends near **78 subscribers** (₹30,940 ÷ ₹399).

The 90-day gates for the pilot are 40, then 80, then 120 paying subscribers.

## Open the demo

1. Double-click `index.html` in this folder, or drag it into Chrome, Brave, Safari, or Edge.
2. The date inside the demo is **Friday 2 October 2026**. That is “today”.

The browser saves what you change on this computer. To get the original October list back, open **Customers** and press **Reset demo data**.

Each screen has a green note at the top. Read that note, then use the screen. The left menu is the same path:

1. **Today** — who is paying, and the next route.
2. **Customers** — one care card per flat.
3. **Book** — take ₹399 and place two visits.
4. **Route** — the 14-visit cap.
5. **Visit** — close a stop, or rebook a failed entry.
6. **Numbers** — the ₹229 against a fixed salary.

## What is already loaded

Ten people are paying. Six live in Maple and four live in Cedar. Contribution on this list is **10 × ₹229 = ₹2,290**. Twenty visits are booked.

| Person | Where | What to notice |
| --- | --- | --- |
| Ananya Rao | Maple, A-1204 | The main profile. Guard list, maid after 11. Do not move the money plant. |
| Kavya Iyer | Maple, B-0502 | Evening only, after 6 pm. The route marks her as a late stop. |
| Suresh Rao | Maple, C-0201 | Older resident. His son pays. Call the son if the key fails. |
| Vikram Nair | Cedar, T2-1501 | Paused. He is home all October, so he is off the route and out of the ₹2,290. |
| Priya Menon | Cedar, T1-0303 | Unpaid. October payment did not clear, so she has no visits. |
| Dev Patel | Lakeview, L-0902 | Waitlist. Lakeview is outside the 3 km zone. |

Maple’s first route is **Thursday 8 October** (6 stops). The second visit is **Thursday 22 October**. Cedar is **Friday 9 October** and **Friday 23 October**.

## What to try

**Book someone inside the zone.** Choose Maple, enter a name and a flat, and submit. The care card shows two Thursdays. Cedar does the same on Fridays.

**Book someone outside the zone.** Choose Another society, type Lakeview Towers, and submit. The card says waitlist and lists no visits.

**Search.** On Customers, type Kavya. The card warns that a morning batch will miss the flat.

**Close a visit.** Open Visit. Tick Watered, Light prune, Pest and health look, and Photo taken. Write a note. Then close the visit. Leave any box empty and the visit stays open.

**Fail an entry.** On a scheduled stop, write why the door stayed shut and press Access failed. The stop moves to the next Thursday or Friday for that building.

**Hit the cap.** Open Route, stay on Thursday 8 October, and press Fill this day to the cap. The squares turn full. Book a new Maple flat. The first visit skips to the next open Thursday. Press Remove slot holds when you want the original day back. Holds are empty squares. They are not subscribers.

**Pause.** On an active care card, press Pause this month. The later visits leave the route and the paying count drops by one, which drops the contribution by ₹229. Take payment and restore puts the visits back.

## How to read the numbers screen

The first contribution card always uses ₹229 × paying subscribers. Paused, unpaid, and waitlist names are excluded.

The fourth card is the other pay rule. It splits a ₹30,940 full-route salary across whoever is paying now. At 10 subscribers that cost is ₹3,094 each, and ₹399 − ₹3,094 is a loss. The bars underneath are the same technician on a dense day, a medium day, and a thin day. They do not change when you add a flat. They are the case ceiling.
