# dateapp 💌

A one-page, mobile-first date invitation (in Hungarian), addressed to Beáta.

1. **Igen / Nem** – the "Nem" button can't be pressed: it runs away whenever someone tries, and "Igen" grows a bit each time.
2. **Calendar** – pick a day (past days are disabled; swipe or use the arrows to change month) and a time.
3. **Program** – forralt bor és korcsolyázás, romantikus vacsora és kaszinó, or csillagnézés teleszkóppal.
4. **Summary** – she can send her answer back (WhatsApp, or the phone's share menu) and add the date to her calendar.

## Settings

At the top of the `<script>` in `index.html`:

- `NAME` – the name in the question (`"Beáta"`).
- `PHONE` – optional WhatsApp number (country code, digits only, e.g. `"36301234567"`). Empty = the phone's share menu opens.

## Hosting with a neutral URL (GitHub Pages)

The repository name ends up in the Pages URL, so to keep the link from giving anything away:

1. **Settings → General → Repository name** → rename to `nagybotondvilmos.github.io` → Rename.
2. **Settings → Pages → Source: Deploy from a branch → `main` / `(root)` → Save**.

The site is then at `https://nagybotondvilmos.github.io/` – nothing in the link hints at what it is.
