# dateapp 💌

A one-page, mobile-first date invitation (in Hungarian), addressed to Beáta.

1. **Igen / Nem** – the "Nem" button can't be pressed: it runs away whenever someone tries, and "Igen" grows a bit each time.
2. **Calendar** – pick a day (past days are disabled; swipe or use the arrows to change month) and a time.
3. **Program** – forralt bor és korcsolyázás, romantikus vacsora és kaszinó, or csillagnézés teleszkóppal.
4. **Summary** – she can send her answer back (WhatsApp, or the phone's share menu) and add the date to her calendar.

## Settings

At the top of the `<script>` in `index.html`:

- `NAME` – the name in the question (`"Beáta"`).
- `PHONE` – number her answer goes to via WhatsApp / SMS (country code, digits only).
- `EMAIL` – address for the "E-mailben" button.

## Hosting with a neutral URL

The site is a single static `index.html`, so any static host works.

**Netlify (free, custom name):** sign in at app.netlify.com with GitHub → Add new site → Import an existing project → GitHub → `dateapp` → Deploy. Then Site configuration → Change site name → pick a neutral name, e.g. `esti-csillagok` → `https://esti-csillagok.netlify.app`.

**GitHub Pages:** rename the repo to `nagybotondvilmos.github.io`, then Settings → Pages → Deploy from a branch → `main` / `(root)` → `https://nagybotondvilmos.github.io/`.
