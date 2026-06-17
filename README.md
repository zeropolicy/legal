---
title: Zeropolicy — Legal
permalink: /
---

# Zeropolicy — Legal

Privacy policies for **Zeropolicy** apps. Every Zeropolicy app is free, has no ads,
no tracking, and stores your data only on your device.

## Privacy policies

| App | Live policy | Source |
|---|---|---|
| **TeamFamily** | <https://zeropolicy.github.io/legal/teamfamily/privacy-policy/> · [Terms](https://zeropolicy.github.io/legal/teamfamily/terms-of-service/) | [`teamfamily/privacy-policy.md`](teamfamily/privacy-policy.md) · [`teamfamily/terms-of-service.md`](teamfamily/terms-of-service.md) |
| **Stockpile** | <https://zeropolicy.github.io/legal/stockpile/privacy-policy/> | [`stockpile/privacy-policy.md`](stockpile/privacy-policy.md) |
| **20 Arcade Club** | <https://zeropolicy.github.io/legal/arcade-club/privacy-policy/> | [`arcade-club/privacy-policy.md`](arcade-club/privacy-policy.md) |

## Adding a new app

1. Create `<app>/privacy-policy.md` starting with this front matter:

   ```yaml
   ---
   title: "Privacy Policy — <App>"
   permalink: /<app>/privacy-policy/
   ---
   ```
2. Write the policy below the front matter (Markdown).
3. It goes live at `https://zeropolicy.github.io/legal/<app>/privacy-policy/`.

> **GitHub Pages must be enabled** for these URLs to work:
> repo **Settings → Pages → Source: Deploy from a branch → `main` / root**.

---

Mehdi Fadaei · Zeropolicy · <mehdifadae@gmail.com>
