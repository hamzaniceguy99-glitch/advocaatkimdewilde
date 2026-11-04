# Kim De Wilde — advocaat kim de wilde bv

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `advocaatkimdewilde.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/advocaatkimdewilde.mjs`).
> To change the content, edit that file and run `node build.mjs advocaatkimdewilde` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@advocaatkimdewilde.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($€[AMOUNT] / $€[AMOUNT] / $Prohibited) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are the practice of Kim De Wilde, a lawyer working since 2022 from Beveren in East Flanders, also trading as FeraLex Advocaten. The rules on what a lawyer may say publicly exclude success rates, comparisons with other practitioners, client testimonials and any promise about an outcome, so what belongs here is how the relationship actually works. Professional secrecy is the foundation of it and is stronger than most people assume. In Belgium it is protected by criminal law, which means breaching it is an offence rather than a professional lapse. It covers not only what you tell us but everything we learn because of the matter, and it does not expire: it survives the end of the case, the end of the relationship and the death of the client. The part that surprises people is that it is not simply a right of yours to switch off at will, because the obligation is of public order and the lawyer remains its keeper. Alongside it sits a rule that makes negotiation possible at all: correspondence between lawyers is in principle confidential and cannot be produced in court, which is what allows two lawyers to explore a settlement without every opening becoming an admission. And we decline matters where interests conflict. Site: advocaatkimdewilde.shop
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
