<!--
  <<< Author notes: Step 4 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: previous version checked the file path. Previous version checked the front matter formatting.
-->

## Samm 4: Loo blogipostitus

_Sinu avaleht näeb suurepärane välja! :cowboy_hat_face:_

GitHub Pages kasutab Jekyll'it. Jekyll'is saame luua blogi, kasutades spetsiaalselt nimetatud faile ja frontmatter'it. Failid peavad olema nimetatud `_posts/YYYY-MM-DD-pealkiri.md`. Pead ka oma frontmatter'isse lisama `title` ja `date`.

**Mis on _frontmatter_?**: Jekyll'i failide süntaksit nimetatakse YAML frontmatter'iks. See läheb faili algusesse ja näeb välja umbes selline:

```yml
---
title: "Tere tulemast minu blogisse"
date: 2019-01-20
---
```

Lisainfot frontmatter'i seadistamise kohta leiad [Jekyll'i frontmatter'i dokumentatsioonist](https://jekyllrb.com/docs/frontmatter/).

### :keyboard: Tegevus: Loo blogipostitus

1. Navigeeri harusse `my-pages`.
1. Kliki rippmenüül `Add file` ja seejärel `Create new file`.
1. Nimeta fail `_posts/YYYY-MM-DD-pealkiri.md`.
1. Asenda `YYYY-MM-DD` tänase kuupäevaga ja muuda oma esimese blogipostituse `pealkiri`, kui soovid.
   > Kui muudad pealkirja, veendu, et sõnade vahel on sidekriipsud.
   > Kui sinu blogipostituse kuupäev ei järgi õiget kuupäeva formaati, saad veateate ja sinu veebileht ei ehitu. Lisainfot leiad artiklist "[Page build failed: Invalid post date](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/troubleshooting-jekyll-build-errors-for-github-pages-sites)".
1. Kirjuta oma blogipostituse algusesse järgmine sisu:
   ```yaml
   ---
   title: "SINU-PEALKIRI"
   date: YYYY-MM-DD
   ---
   ```
1. Asenda `SINU-PEALKIRI` oma blogipostituse pealkirjaga.
1. Asenda `YYYY-MM-DD` tänase kuupäevaga.
1. Kirjuta oma blogipostituse kiire mustand. Pea meeles, et saad seda hiljem alati muuta.
1. Commit'i oma muudatused oma harusse.
1. Oota umbes 20 sekundit ja seejärel värskenda seda lehte (seda, kus sa juhiseid loed). [GitHub Actions](https://docs.github.com/en/actions) uuendab automaatselt järgmise sammu juurde.
