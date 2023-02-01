<p align="center">
 <img width="100px" src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">Krijg dynamisch gegenereerde GitHub statistieken op je readme's!</p>
</p>
  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats/actions">
      <img alt="Tests Passen" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/graphs/contributors">
      <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/anuraghazra/github-readme-stats" />
    </a>
    <a href="https://codecov.io/gh/anuraghazra/github-readme-stats">
      <img src="https://codecov.io/gh/anuraghazra/github-readme-stats/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/issues">
      <img alt="Kwesties" src="https://img.shields.io/github/issues/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/pulls">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <br />
    <br />
    <a href="https://a.paddle.com/v2/click/16413/119403?link=1227">
      <img src="https://img.shields.io/badge/Supported%20by-VSCode%20Power%20User%20%E2%86%92-gray.svg?colorA=655BE1&colorB=4F44D6&style=for-the-badge"/>
    </a>
    <a href="https://a.paddle.com/v2/click/16413/119403?link=2345">
      <img src="https://img.shields.io/badge/Supported%20by-Node%20Cli.com%20%E2%86%92-gray.svg?colorA=61c265&colorB=4CAF50&style=for-the-badge"/>
    </a>
  </p>

<p align="center">
    <a href="#demo">Bekijk Demo</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Rapporteer een Bug</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Vraag een nieuwe toepassing aan</a>
  </p>
  <p align="center">
    <a href="/docs/readme_fr.md">Français </a>
    ·
    <a href="/docs/readme_cn.md">简体中文</a>
    ·
    <a href="/docs/readme_es.md">Español</a>
    ·
    <a href="/docs/readme_de.md">Deutsch</a>
    ·
    <a href="/docs/readme_ja.md">日本語</a>
    ·
    <a href="/docs/readme_pt-BR.md">Português Brasileiro</a>
    ·
    <a href="/docs/readme_it.md">Italiano</a>
    ·
    <a href="/docs/readme_kr.md">한국어</a>
    .
    <a href="/docs/readme_nl.md">Nederlands</a>
.
    <a href="/docs/readme_np.md">नेपाली</a>
    <a href="/docs/readme_tr.md">Diefstal</a>
  </p>
</p>

<p align="center">Bevalt het project? <a href="https://www.paypal.me/anuraghazra">Doneer</a> om het te verbeteren!</p>

<a href="https://indiafightscorona.giveindia.org">
  <img src="https://indiaspora.org/wp-content/uploads/2021/04/give-India-logo.png" alt="Geef india logo" width="200" />
</a>

Overweegt u het project te steunen door te doneren? Alstublieft, GEMAKT NU!

Help India in plaats daarvan de tweede dodelijke golf van COVID-19 te bestrijden. In India sterven duizenden mensen door een gebrek aan zuurstof & ook COVID-gerelateerde infrastructuur.

Bezoek <https://indiafightscorona.giveindia.org> en doe een kleine donatie om ons te helpen COVID te bestrijden en deze crisis te boven te komen. Een kleine donatie gaat heel ver. :heart:

</p>

# Functionaliteiten

-   [GitHub Statistieken Kaart](#github-stats-card)
-   [GitHub Extra Pins](#github-extra-pins)
-   [Top Programmeertalen Kaart](#top-languages-card)
-   [Wekelijkse Wakatime Statistieken](#wakatime-week-stats)
-   [Thema\'s](#themes)
    -   [Responsieve kaart thema](#responsive-card-theme)
-   [Aanpassen](#customization)
    -   [Veel gebruikte opties:](#common-options)
    -   [Pas statistieken kaart aan](#stats-card-exclusive-options)
    -   [Pas repo kaart aan.](#repo-card-exclusive-options)
    -   [Taalkaart Exclusieve Opties](#language-card-exclusive-options)
    -   [Exclusieve opties voor Wakatime Kaart:](#wakatime-card-exclusive-options)
-   [Zelf deployen](#deploy-on-your-own-vercel-instance)
    -   [Houd je vork up-to-date](#keep-your-fork-up-to-date)

# GitHub Statistieken Kaart

Kopieer en plak dit in je markdown content, zo simpel is het! Eenvoudig!

Verander de waarde `?username=` naar jou gebruikersnaam.

```md
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

> Notitie: Beschikbare rangen zijn S+ (top 1%), S (top 25%), A++ (top 45%), A+ (top 60%), and B+ (iedereen). De waarden worden berekend met behulp van de zogeheten [cumulative distribution function](https://en.wikipedia.org/wiki/Cumulative_distribution_function) met de waardes van de commits, bijdragens, issues, sterren, PR's, volgers en eigen repositories. De implementatie hiervan kan bekijken op [src/calculateRank.js](../src/calculateRank.js)

### Verberg individueele statistieken

Om specifieke statistieken te verbergen, kan je een `?hide=` query parameter toevogen, verdeeld met komma\'s.

> Opties: `&hide=stars,commits,prs,issues,contribs`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,prs)
```

### Voeg privé contributies toe aan totale commits.

Je kan de hoeveelheid privé commits toevoegen aan je totale hoeveelheid commits door de query parameter `?count_private=true` te gebruiken.

> **Let op** Als u dit project zelf implementeert, worden de privébijdragen standaard geteld. Als u gebruik maakt van de openbare Vercel, moet u kiezen om [uw privébijdragen](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/managing-contribution-settings-on-your-profile/showing-your-private-contributions-and-achievements-on-your-profile) te delen.

> Opties: `&count_private=true`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&count_private=true)
```

### Laat icoontjes zien

Om icoontjes te gebruiken kan je `show_icons=true` gebruiken in de query parameter, zoals hier:

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true)
```

### Thema\'s

Met ingebouwde thema\'s kan je het uiterlijk van de kaart aanpassen zonder enige [handmatige opmaak](#customization).

Gebruik `?theme=THEME_NAME` parameters zo :-

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
```

#### Alle ingeboude thema\'s :-

GitHub readme statistieken worden geleverd met verschillende ingebouwde thema's (bijv. `donker`, `radicale`, `merko`, `rooi box`, `tokyonight`, `onedark`, `kobalt`, `synthese`, `hoog contrast`, `dracula`).

<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Statestieken Thema's" width="600px" />

Je kan een preview van alle [beschikbare thema\'s](../themes/README.md) bekijken, of zie het [thema configuratie bestand](../themes/index.js) en **je kan aan nieuwe thema\'s bijdragen** als je dat leuk lijkt :D

#### Responsieve kaart thema

[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![Anurag's GitHub stats-Light](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

Omdat GitHub de kaarten opnieuw zal uploaden en ze zal dienen van hun [CDN](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-anonymized-urls), we kunnen het browser/GitHub thema niet op de server beluisteren. Er zijn echter vier methoden die je kunt gebruiken om dynamiekthema's te creëren aan de kant van de klant.

##### Transparante thema gebruiken

We hebben een `transparant` thema toegevoegd met een transparante achtergrond. Dit thema is geoptimaliseerd om er goed uit te zien op GitHub's donkere en lichte standaard thema's. Je kunt dit thema inschakelen met behulp van de `&theme=transparant` parameter zoals zo:

```md
<code>show_owner</code> - Laat de eigenaar van de repo zien <em x-id="4">(boolean)</em>
```
 - Laat de eigenaar van de repo zien _(boolean)_
</code>

<details>
<summary>:eyes: Toon voorbeeld</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=transparent)

</details>

##### Transparante alpha kanaal toevoegen aan een thema felle kleur

Je kunt de `bg_color` parameter gebruiken om een van [de beschikbare thema's](./themes/README.md) transparant te maken. Dit wordt gedaan door het instellen van de `bFlits kleur` op een kleur met een transparant alfa kanaal (d.w.z. `bg_color=00000000`):

```md
<code>icon_color</code> - Icoon kleuren, wanneer beschikbaar <em x-id="4">(hex kleur)</em>
```
 - Icoon kleuren, wanneer beschikbaar _(hex kleur)_
</code>

<details>
<summary>:eyes: Toon voorbeeld</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)

</details>

##### Gebruik GitHub's thema context tag

Je kunt [GitHub's thema context](https://github.blog/changelog/2021-11-24-specify-theme-context-for-images-in-markdown/) tags gebruiken om het thema automatisch te veranderen op basis van het GitHub thema. Dit wordt gedaan door `#gh-dark-mode-only` of `#gh-light-mode-only` toe te voegen aan het einde van een afbeelding-URL. Deze tag zal bepalen of de afbeelding die is opgegeven in de markdown alleen wordt getoond aan kijkers met behulp van een lamp of een donker GitHub thema:

```md
[![Top Talen](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

<details>
<summary>:eyes: Toon voorbeeld</summary>

[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![Anurag's GitHub stats-Light](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

</details>

##### Gebruik GitHub's nieuwe media-functie

U kunt [GitHub's nieuwe mediafunctie](https://github.blog/changelog/2022-05-19-specify-theme-context-for-images-in-markdown-beta/) in HTML gebruiken om aan te geven of u afbeeldingen wilt weergeven voor lichte of donkere thema's. Dit wordt gedaan met behulp van het HTML `<picture>` element in combinatie met het `prefers-color-scheme` media-functie.

```html
[![Top Talen](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&exclude_repo=github-readme-stats,anuraghazra.github.io)](https://github.com/anuraghazra/github-readme-stats)
```

<details>
<summary>:eyes: Toon voorbeeld</summary>

<picture>
<source 
  srcset="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark"
  media="(prefers-color-scheme: dark)"
/>
<source
  srcset="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true"
  media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
/>
<img src="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true" />
</picture>

</details>

### Aanpassen

Je kan het uiterlijk van je `Statistieken kaart` of `Repo kaart` aanpassen hoe je ook maar wilt met URL parameters.

#### Opmaak

-   `title_color` - De kleur van de titel van de kaart _(hex kleur)_ Default: `2f80ed`.
-   `text_color` - Tekstkleur _(hex kleur)_. Standaard: `434d58`.
-   `icon_color` - Pictogrammen indien beschikbaar _(hex kleur)_. Standaard: `4c71f2`.
-   `border_color` - Kaart rand kleur _(hex kleur)_. Standaard: `e4e2e2` (Niet van toepassing wanneer `hide_border` is ingeschakeld).
-   `bg_color` - Card's achtergrondkleur _(hex kleur)_ **of** een verloop in de vorm van _hoek,start_. Standaard: `ffftaxes,`
-   `hide_border` - Verbergt de rand van de kaart _(boolean)_. Standaard: `false`
-   `theme` - Naam van het thema, kies uit [alle beschikbare thema\'s](../themes/README.md) Standaard: `standaard` thema.
-   `cache_seconds` - stel de cache header handmatig in _(min: 14400, max: 86400)_. Standaard: `14400 seconden (4 uur)`.
-   `locale` - Stel taal van de kaart in _(e.g. cn, de, es, etc.)_
-   `card_width` - Stelt de breedte van de kaart handmatig in. _(nummer)_

> **Waarschuwing** We gebruiken caching om de belasting op onze servers te verlagen (zie <https://github.com/anuraghazra/github-readme-stats/issues/1471#issuecomment-1271551425>). Notities i.v.b.m. cache: Repo kaarten hebben een standaard cache van 4 uur (14400 seconden) als de fork hoeveelheid en de star hoeveelheid minder is dan 1k, anders is het 2 uur (7200 seconden). Daarnaast ligt de cache vast aan een minimum van 2 uur en een maximum van 24 uur.

##### Kleurenverloop in bg_color (achtergrond kleur):

Je kan meerdere komma verdeelde waarden in de bg_color optie geven om een kleurenverloop te creeëren, het formaat van het kleurenverloop is:-

    &bg_color=GRADEN,KLEUR1,KLEUR2,KLEUR3...KLEUR10

#### Exclusieve opties voor Statistieken Kaart:

-   `hide` - Verbergt gespecificeerde items van de statistieken. _(komma gescheiden waardes)_
-   `hide_title` - _(boolean)_. Standaard: `false`.
-   `card_width` - Breedte van de kaart handmatig instellen _(nummer)_. Standaard: `500px (approx.)`.
-   `hide_rank` - _(boolean)_ verbergt de rank en verkleint de kaart automatisch breedte. Standaard: `false`.
-   `show_icons` - _(boolean)_. Standaard: `false`.
-   `include_all_commits` - Totaal aantal commits in plaats van alleen de huidige jaar commits _(boolean)_. Standaard: `false`.
-   `count_private` - Prive commits _(boolean)_. Standaard: `false`.
-   `line_height` - Stelt de regelhoogte tussen tekst _(nummer)_ in. Standaard: `25`.
-   `exclude_repo` - sluit sterren uit van specifieke repositories _(door komma's gescheiden waarden)_. Standaard: `[] (lege array)`.
-   `custom_title` - Stelt een eigen titel voor de kaart in Default:  `<username> GitHub Stats`.
-   `text_bold` - Gebruik vette tekst _(boolean)_. Standaard: `waar`.
-   `disable_animations` - Schakelt alle animaties in de kaart uit _(boolean)_. Standaard: `false`.
-   `ring_color` - Kleur van de rang cirkel _(hex kleur)_. Standaard de thema ring kleur als deze bestaat en anders de titel kleur heeft.

> **Opmerking** Wanneer hide_rank=`true`, de minimale breedte van de kaart is 270 px + de lengte van de titel en opvulling.

#### Exclusieve opties voor Repo Kaart:

-   `show_owner` - Toon de eigenaar naam van de repo's _(boolean)_. Standaard: `false`.

#### Taalkaart Exclusieve Opties

-   `Verberg` - Verberg de talen van de kaart _(door komma's gescheiden waarden)_. Standaard: `[] (lege array)`.
-   `hide_title` - _(boolean)_. Standaard: `false`.
-   `lay-out` - Schakel tussen twee beschikbare lay-outs `standaard` & `compact`. Standaard: `standaard`.
-   `card_width` - Breedte van de kaart handmatig instellen _(nummer)_. Standaard `300`.
-   `langs_count` - Toon meer talen op de kaart, tussen 1-10 _(getal)_. Standaard `5`.
-   `exclude_repo` - Verbergt specifieke repositories _(komma gescheiden waardes)_ Standaard: `[] (lege array)`.
-   `custom_title` - stelt een aangepaste titel voor de kaart _(string)_. Standaard `Meest gebruikte talen`.
-   `disable_animations` - Schakelt alle animaties in de kaart uit _(boolean)_. Standaard: `false`.

> :Waarschuwing: **Belangrijk:** Namen van programmeertalen moeten worden geuri-escaped, zoals gespecificeerd in [Percent Encoding](https://en.wikipedia.org/wiki/Percent-encoding) (Oftewel: `c++` moet `c%2B%2B` worden, `jupyter notebook` moet `jupyter%20notebook` worden, enzovoort...) Zie [urlencoder.org](https://www.urlencoder.org/) om dit automatisch te doen.

#### Exclusieve opties voor Programmeertaal Kaart:

-   `hide` - Verbergt specifieke talen van de kaart _(komma gescheiden waardes)_ Standaard: `[] (lege array)`.
-   `hide_title` - _(boolean)_. Standaard `onwaar`.
-   `line_height` - Verandert de lijn hoogte tussen tekst _(nummer)_ Standaard `25`.
-   `hide_progress` - Verbergt de voortgangsbalk en percentage _(boolean)_. Standaard `onwaar`.
-   `custom_title` - stelt een aangepaste titel voor de kaart _(string)_. Default `Wakatime Stats`.
-   `layout` - Keuze voor de twee beschikbare layouts `default` & `compact`  Standaard `standaard`.
-   `langs_count` - Laat meer talen op de kaart zien, waarde tussen 1-10, staat standaard op to 5 _(nummer)_
-   `api_domain` - Stel een aangepast API domein in voor de kaart, bv. om diensten te gebruiken zoals [Hakatime](https://github.com/mujx/hakatime) of [Wakapi](https://github.com/muety/wakapi) _(string)_. Standaard `Waka API`.
-   `bereik` – Vraag een bereik aan dat afwijkt van de standaard WakaTime , bijvoorbeeld `last_7_days`. Zie [WakaTime API docs](https://wakatime.com/developers#stats) voor een lijst met beschikbare opties. _(YYYY-MM, last_7_dagen, last_30_dagen, last_6_maanden, last_year, of all_time)_. Standaard `alle_time`.

* * *

# GitHub Extra Pins

GitHub extra pins geven je de mogelijkheid om meer dan 6 repositories op je profiel te pinnen, doormiddel van een GitHub readme profile.

Joepie! Je bent niet langer aan 6 pins gelimiteerd!

### Gebruik

Kopieer en plak deze code in je readme en verander de links.

Eindpunt: `api/pin?username=anuraghazra&repo=github-readme-stats`

```md
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)
```

### Demo

[![Leesmij-kaart](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)

Gebruikt [show_owner](#customization) variabele om de repo\'s eigenaar toe te voegen

[![Leesmij-kaart](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats&show_owner=true)](https://github.com/anuraghazra/github-readme-stats)

# Top Programmeertalen Kaart

De top programmeertalen kaart laat zien welke talen een GitHub gebruiker het meest gebruikt.

> Notitie: Top programmeertalen wijzen niet op een vaardigheids niveau, het is puur een GitHub metriek over welke talen de meeste code op GitHub hebben. Het is een nieuwe funktie van github-readme-stats.

### Gebruik

Kopieer en plak deze code in je readme en verander de links.

Eindpunt: `api/top-langs?username=anuraghazra`

```md
<code>line_height</code> - Stel de lijn-hoogte tussen text in <em x-id="4">(nummer)</em>
```
 - Stel de lijn-hoogte tussen text in _(nummer)_
</code>

### Verberg individueele repositories

Je kan de parameter `?exclude_repo=repo1,repo2` gebruiken om individueele repositories te verbergen.

```md
[![willianrod's Wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)
```

### Verberg individueele talen

Je kan de `?hide=taal1,taal2` parameter gebruiken om individuele programmeer talen te verbergen.

```md
[![Top Talen](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&hide=javascript,html)](https://github.com/anuraghazra/github-readme-stats)
```

### Laat meer programmeertalen zien

Je kan de `&langs_count=` optie gebruiken om de hoeveelheid talen op je kaart groter en kleiner te maken. Geldige waardes zijn tussen de 1 en 10 (inclusief), en de standaard waarde is 5.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&langs_count=8)](https://github.com/anuraghazra/github-readme-stats)
```

### Compacte Talen Kaart opmaak

Je kan de `&layout=compact` optie gebruiken om het kaart ontwerp aan te passen.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
```

### Demo

[![Top Programmeertalen](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   Compacte opmaak

[![Top programmeertalen](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

# Wekelijkse Wakatime Statistieken

Verander de `?username=` waarde naar je [Wakatime](https://wakatime.com) gebruikersnaam.

```md
<code>include_all_commits</code> - Tel alle commits inplaats van alleen de commits van het huidige jaar <em x-id="4">(boolean)</em>
```
 - Tel alle commits inplaats van alleen de commits van het huidige jaar _(boolean)_
</code>

> **Opmerking:**: Houd er rekening mee dat we momenteel alleen gegevens uit Wakatime profielen tonen die openbaar zijn.

### Demo

[![willianrod's Wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

[![Verberg specifieke statestieken](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&hide_progress=true)](https://github.com/anuraghazra/github-readme-stats)

-   Compacte lay-out

[![willianrod's Wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

* * *

### Alle demos

-   Standaard

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)

-   Verberg specifieke statistieken

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,issues)

-   Weergeef icoontjes

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=issues&show_icons=true)

-   Randkleur aanpassen

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&border_color=2e4058)

-   Voeg alle commits toe

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&include_all_commits=true)

-   Thema\'s

Kies uit de [standaard thema\'s](#themes)

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)

-   Kleurovergang

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

-   `custom_title` - Stel een aangepaste titel voor je kaart in

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)

-   Stel je kaart locale (taal) in

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&locale=es)

-   Kleine tip (Verstel de repo kaart z\'n positie)

![Aangepaste kaart](https://github-readme-stats.vercel.app/api/pin?username=anuraghazra&repo=github-readme-stats&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)

-   Top programmeertalen

[![Top programmeertalen](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   Wakatime kaart

[![willianrod's Wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

* * *

### Quick Tip (Uitlijnen van de Repo Kaarten)

GitHub staat standaard niet op de kaart naast elkaar. Om dat te doen, kunt u gebruik maken van deze benadering:

```html
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=convoychat" />
</a>
```

## Deploy je eigen Vercel instatie

#### Check de stapsgewijze video tutorial door @codeSTACKr (In het Engels)

> **Waarschuwing** Als je in het [hobby zit (d.w.z. gratis)](https://vercel.com/pricing) Vercel-abonnement, zorg ervoor dat u de `maxDuration` parameter in de [vercel wijzigt. zoon](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json) bestand van `30` tot `10` (zie [#1416](https://github.com/anuraghazra/github-readme-stats/issues/1416#issuecomment-950275476) voor meer informatie).

Sinds de GitHub API alleen maar 5k verzoeken per uur toestaat, zou mijn `https://github-readme-stats.vercel.app/api` mogelijk de rate limiet behalen. Als je het op je eigen Vercel server host, dan hoef je je nergens zorgen om te maken. Klik op de deploy knop om te beginnen!

> NOTITIE: Sinds [#58](https://github.com/anuraghazra/github-readme-stats/pull/58) zouden we geen problemen meer moeten hebben de 5k verzoeken per uur, en verdere downtime :D

[![Deploy naar Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/anuraghazra/github-readme-stats)

<details>
 <summary><b>:hammer_and_wrench: Stap-voor-stap gids over het instellen van uw eigen Vercel-instantie</b></summary>

1.  Ga naar [vercel.com](https://vercel.com/)
2.  Klik op `Log in` ![](https://files.catbox.moe/pcxk33.png)
3.  Meld je aan met GitHub door op `Continue with GitHub` te klikken. ![](https://files.catbox.moe/b9oxey.png)
4.  Log in op GitHub en sta toegang tot alle repositories toe, wanneer dat gevraagt wordt.
5.  Fork deze repo
6.  Na het forkeren van de repo, open het [`vercel.json`](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json#L5) bestand en verander het `maxDuration` veld naar `10`.
7.  Ga terug naar je [Vercel dashboard](https://vercel.com/dashboard)
8.  Selecteer `Import Project` ![](https://files.catbox.moe/3n76fh.png)
9.  Klik op de `Doorgaan met GitHub` knop, zoek naar de vereiste Git Repository en importeer deze door te klikken op de `Importeer` knop. Als alternatief kunt u een derde partij Git Repository importeren met behulp van de `Importeer Git Repository van derden ->` link onderaan de pagina. ![](https://files.catbox.moe/mg5p04.png)
10. Selecteer root en hou alles zoals het is, voeg alleen je environment variable genaamd PAT_1 toe (Zoals hier late zien word), die beheert over een persoonlijke toegangs token (PAT), die je gemakklijk [hier](https://github.com/settings/tokens/new) gemakkelijk kan creeëren. (Laat alles zoals het is, noem het maar iets, mag alles zijn.)
11. Voeg de PAT toe als een omgevingsvariabele met de naam `PAT_1` (zoals getoond). ![](https://files.catbox.moe/0yclio.png)
12. Klik deploy, en alles zou moeten werken. Zie je domein om de api te gebruiken!

</details>

### Houd je vork up-to-date

U kunt uw vork en dus uw privé Vercel-instantie up-to-date houden met de upstream via GitHubs' [Sync Fork knop](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork). Je kunt ook het [pull](https://github.com/wei/pull) pakket gebruiken dat door [@wei](https://github.com/wei) is gemaakt om dit proces te automatiseren.

## :sparkling_heart: Ondersteun het project

Ik maak bijna alles open-source wat ik kan, en ik probeer iedereen te helpen die deze projecten gebruiken. Natuurlijk, dit kost tijd. Natuurlijk kost dit tijd, je mag deze services gratis gebruiken.

Hoe dan ook, als je dit project gebruikt en er blij mee bent, of mij wilt aanmoedigen om dingen te blijven maken, zijn er een paar manieren om dit te doen; -

-   Credits geven aan github-readme-stats op je readme, die terug naar het project linkt :D
-   Sterren en delen van het project :rocket:
-   [![paypal.me/anuraghazra](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/anuraghazra) - U kunt eenmalige donaties doen via PayPal. Ik koop waarschijnlijk een ~ ~ koffie~~ thee. :tea:

Bedankt! :heart:

* * *

[![https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss](./powered-by-vercel.svg)](https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss)

Contributies zijn welkom! <3

Gemaakt met :heart: en JavaScript.
