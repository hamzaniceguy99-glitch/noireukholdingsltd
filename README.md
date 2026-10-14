# Noire UK Holdings — noire uk holdings ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `noireukholdingsltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/noireukholdingsltd.mjs`).
> To change the content, edit that file and run `node build.mjs noireukholdingsltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@noireukholdingsltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Group / $Internal / $None) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Noire UK Holdings Ltd, a private limited company registered in England and Wales (company number 14842543), is a holding company that owns and oversees shareholdings in its subsidiary companies: maintaining the group's shareholding and governance records, setting the reporting and board cycle its subsidiaries follow, keeping statutory filings, insurance and corporate records current across the group, and allocating the group's own capital between its subsidiaries. The company holds its investments on its own behalf. It carries on no regulated activity, is not authorised by the Financial Conduct Authority, accepts no funds from the public and offers no securities. Site: noireukholdingsltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
