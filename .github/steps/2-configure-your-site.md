<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: previous version checked for empty pull request, changed to the correct theme `minima`.
-->

## Samm 2: Seadista oma veebileht

_Sa lülitasid GitHub Pages'i sisse! :tada:_

Töötame harus `my-pages`, mille lõin sulle, et see veebileht hea välja näeks. :sparkle:

Jekyll kasutab faili nimega `_config.yml`, et salvestada sinu veebilehe seadeid, teemat ja korduvkasutatavat sisu nagu veebilehe pealkiri ja GitHubi kasutajanimi. Saad vaadata `_config.yml` faili oma repositooriumi vahekaardil **Code**.

Meil on vaja blogiks sobivat teemat. Selles tegevuses kasutame teemat nimega "minima".

### :keyboard: Tegevus: Seadista oma veebileht

1. Navigeeri faili `_config.yml` juurde harus `my-pages`.
1. Üleval paremal ava failiredaktor.
1. Lisa `theme:` väärtuseks **minima**, nii et `_config.yml` failis näeb välja selline:
   ```yml
   theme: minima
   ```
1. (valikuline) Saad muuta teisi seadistusmuutujaid nagu `title:`, `author:` ja `description:`, et oma veebilehte veelgi kohandada.
1. Commit'i oma muudatused.
1. (valikuline) Loo pull request, et näha kõiki muudatusi, mida selle kursuse jooksul teed. Kliki vahekaardil **Pull Requests**, kliki **New pull request**, sea `base: main` ja `compare:my-pages`.
1. Oota umbes 20 sekundit ja seejärel värskenda seda lehte (seda, kus sa juhiseid loed). [GitHub Actions](https://docs.github.com/en/actions) uuendab automaatselt järgmise sammu juurde.
