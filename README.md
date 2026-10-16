# St. Anton am Arlberg — browser ski game

A single static page (`index.html`), no build step.

## Deploy to Vercel
1. Go to vercel.com → Add New → Project → drag this folder in (or push it to a GitHub repo and import it).
2. Framework preset: **Other**. No build command, output directory = root.
3. Deploy. That's it.

CLI alternative: `npm i -g vercel` then run `vercel --prod` inside this folder.

## What's real
Lift lengths, capacities, cabin sizes and published ride times/speeds (Galzigbahn 2,542 m in 9:08 at 6 m/s, Nassereinbahn 1,950 m in 5:24, Kapallbahn 1,252 m to 2,330 m, Vallugabahn II no-skis rule, etc.) come from skiresort.info and lift-world.info. Cabin spacing is derived from each lift's real hourly capacity. Lifts run 08:30–16:30.

## What's approximated
Terrain is generated to match real station altitudes (within ~30–40 m), not a survey-grade elevation model. Piste routes, restaurant positions and prices are hand-placed approximations.
