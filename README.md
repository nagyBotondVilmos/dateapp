# dateapp 💌

A one-page, mobile-first "will you go on a date with me?" app.

1. **Yes / No** – the No button can't be pressed: it runs away whenever someone tries, and the Yes button grows a bit each time.
2. **Calendar** – pick a day (past days are disabled; swipe or use the arrows to change month) and a time.
3. **Program** – Glühwein & ice skating, romantic dinner & casino, or stargazing with a telescope.
4. **Summary** – she can send her answer back to you (WhatsApp, or the phone's share sheet) and add the date to her calendar.

## Personalise the link

Add these to the end of the URL (all optional):

| Parameter | Example | Effect |
|---|---|---|
| `name` | `?name=Anna` | "Anna, will you go on a date with me?" |
| `from` | `&from=Boti` | Button reads "Send Boti my answer" |
| `phone` | `&phone=36301234567` | Answer opens WhatsApp straight to this number (country code, digits only) |

Example: `https://nagybotondvilmos.github.io/dateapp/?name=Anna&from=Boti&phone=36301234567`

## Hosting (GitHub Pages)

Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / `(root)` → Save**.
After a minute the site is at `https://nagybotondvilmos.github.io/dateapp/`.
