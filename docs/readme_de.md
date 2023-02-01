<p align="center">
 <img width="100px" src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">Zeige dynamisch generierte GitHub-Statistiken in deinen Readmes!</p>
</p>
  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats/actions">
      <img alt="Tests bestehen" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/graphs/contributors">
      <img alt="GitHub Extra-Pins" src="https://img.shields.io/github/contributors/anuraghazra/github-readme-stats" />
    </a>
    <a href="https://codecov.io/gh/anuraghazra/github-readme-stats">
      <img src="https://codecov.io/gh/anuraghazra/github-readme-stats/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/issues">
      <img alt="Probleme" src="https://img.shields.io/github/issues/anuraghazra/github-readme-stats?color=0088ff" />
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
    <a href="#demo">Beispiele ansehen</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Fehler melden</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Funktion wünschen</a>
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
    .
    <a href="/docs/readme_tr.md">Türkc<unk> e</a>
  </p>
</p>

<p align="center">Du magst das Projekt? Wie wäre es mit einer kleinen <a href="https://www.paypal.me/anuraghazra">Spende</a> um es weiterhin am Leben zu erhalten?</p>

<a href="https://indiafightscorona.giveindia.org">
  <img src="https://indiaspora.org/wp-content/uploads/2021/04/give-India-logo.png" alt="India-Logo angeben" width="200" />
</a>

Beabsichtigen Sie, das Projekt durch Spenden zu unterstützen? Bitte NICHT!!

Hilf Indien stattdessen bei der Bekämpfung der zweiten tödlichen Welle von COVID-19. Tausende von Menschen sterben in Indien aufgrund eines Mangels an Sauerstoff & ebenfalls COVID-bezogene Infrastruktur.

Besuche <https://indiafightscorona.giveindia.org> und spende eine kleine Spende, um uns beim Kampf gegen COVID zu helfen und diese Krise zu überwinden. Eine kleine Spende geht weit weg. :heart:

</p>

# Funktionen

-   [GitHub Statistiken-Karte](#github-stats-card)
-   [GitHub Extra Pins](#github-extra-pins)
-   [Top Programmiersprachen-Karte](#top-languages-card)
-   [Wakatime Wochen-Statistik](#wakatime-week-stats)
-   [Erscheinungsbild/Themes](#themes)
    -   [Responsive-Kartenthema](#responsive-card-theme)
-   [Anpassungen/Personalisierung](#customization)
    -   [Gemeinsame Optionen](#common-options)
    -   [Exklusive Optionen der Statistiken-Karte:](#stats-card-exclusive-options)
    -   [Verbreitete Optionen:](#repo-card-exclusive-options)
    -   [Exklusive Optionen der Sprachen-Karte:](#language-card-exclusive-options)
    -   [Exklusive Optionen der WakaTime-Karte:](#wakatime-card-exclusive-options)
-   [Selber betreiben](#deploy-on-your-own-vercel-instance)
    -   [Fork aktuell halten](#keep-your-fork-up-to-date)

# GitHub Statistiken-Karte

Kopieren Sie dies in Ihren Markdown-Inhalt, und das ist es. Einfach!

Passe den Wert des URL-Parameters `?username=` so an, dass dort dein GitHub-Nutzername steht.

```md
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

> **Notiz** Verfügbare Ränge sind S+ (Top 1%), S (Top 25%), A++ (Top 45%), A+ (Top 60%), und B+ (alle). Die Werte werden mit der [kumulativen Verteilungsfunktion](https://en.wikipedia.org/wiki/Cumulative_distribution_function) errechnet, die Commits, Beiträge, Probleme, Stars, Pull-Requests, Followers und eigene Repositories verwendet. Die Implementierung kann unter [src/calculateRank.js](./src/calculateRank.js) untersucht werden.

### Verbergen individueller Statistiken

Um eine spezifische Statistik auszublenden, kann dem Query-Parameter `?hide=` ein Array an Optionen, die nicht angezeigt werden sollen, übergeben werden.

> Optionen: `&hide=stars,commits,prs,issues,contribs`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=["contribs","prs"])
```

### Anzahl der privaten Beiträge zur Gesamtzahl der Commits hinzufügen

Sie können die Anzahl aller Ihrer privaten Beiträge zur Gesamtzahl der Commits hinzufügen, indem Sie den Abfrageparameter `&count_private=true` verwenden.

> **Notiz** Wenn Sie dieses Projekt selbst bereitstellen, werden die privaten Beiträge standardmäßig gezählt. Wenn Sie die öffentliche Vercel Instanz verwenden, müssen Sie [Ihre privaten Beiträge teilen](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/managing-contribution-settings-on-your-profile/showing-your-private-contributions-and-achievements-on-your-profile).

> `count_private` - Zähle private Beiträge _(Boolean)_

```md
<code>api_domain</code> - Legt eine benutzerdefinierte API Domain fest, z.B. für <a href="https://github.com/mujx/hakatime">Hakatime</a> oder <a href="https://github.com/muety/wakapi">Wakapi</a>
```
 - Legt eine benutzerdefinierte API Domain fest, z.B. für [Hakatime](https://github.com/mujx/hakatime) oder [Wakapi](https://github.com/muety/wakapi)
</code>

### Symbole anzeigen

Um Symbole anzuzeigen kann der URL-Parameter `show_icons=true` wie folgt verwendet werden:

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true)
```

### Erscheinungsbild/Themes

Mithilfe der eingebauten Themes kann das Aussehen der Karten verändern werden, ohne manuelle Anpassungen vornehmen zu müssen.

Benutze den `?theme=THEME_NAME`-Parameter wie folgt :-

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
```

#### Alle eingebauten Themes :-

`theme` - Name des Erscheinungsbildes/Themes [alle verfügbaren Themes](../themes/README.md)

<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stat Themes" width="600px" />

Du kannst dir eine Vorschau [aller verfügbaren Themes](../themes/README.md) ansehen oder die [theme config Datei](../themes/index.js) ansehen. Außerdem **kannst du neue Themes erstellen**, Beiträge an diesem Projekt sind gerne gesehen!

#### Responsive-Kartenthema

[![HINWEIS: Die Top Programmiersprachen treffen keine Aussage über persönliche Fähigkeiten oder dergleichen, es ist lediglich eine auf den GitHub-Statistiken des Nutzers basierende Kennzahl, welche Programmiersprache wie häufig verwendet wurde.](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![Klick <code>Import Git Repository</code>](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

Da GitHub die Karten erneut hochladen und sie von ihrem [CDN](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-anonymized-urls)bedienen wird, können wir das Browser/GitHub Theme nicht auf der Serverseite einfügen. Es gibt jedoch vier Methoden, die Sie verwenden können, um dynamische Themen auf der Client-Seite zu erstellen.

##### Benutze das transparente Theme

Wir haben ein `transparentes` Theme mit einem transparenten Hintergrund hinzugefügt. Dieses Theme ist so optimiert, dass es auf GitHubs dunklen und hellen Standardthemen gut aussieht. Sie können dieses Theme unter Verwendung des `&theme=transparent` Parameters aktivieren:

```md
<code>icon_color</code> - Symbolfarbe (falls verfügbar) <em x-id="4">(hex color)</em>
```
 - Symbolfarbe (falls verfügbar) _(hex color)_
</code>

<details>
<summary>:eyes: Beispiel anzeigen</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=transparent)

</details>

##### Fügen Sie transparenten Alpha-Kanal zu einem Thema bg_color hinzu

Sie können den `bg_color` Parameter verwenden, um eines der [verfügbaren Themes](./themes/README.md) transparent zu machen. Dies geschieht durch Setzen des `bg_color` auf eine Farbe mit einem transparenten Alphakanal (z.B. `bg_color=000000`):

```md
:warning: <strong x-id="1">Wichtig:</strong>
  Sprachennamen sollten uri-escaped sein, wie hier angegeben: <a href="https://en.wikipedia.org/wiki/Percent-encoding">Percent Encoding</a>
  (z.B.: <code>c++</code> sollte zu <code>c%2B%2B</code> werden, <code>jupyter notebook</code> sollte zu <code>jupyter%20notebook</code> werden, usw.)
```
 sollte zu c%2B%2B werden, jupyter notebook sollte zu jupyter%20notebook werden, usw.)
</code>

<details>
<summary>:eyes: Beispiel anzeigen</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)

</details>

##### `custom_title` - Legt einen benutzerdefinierten Titel fest

Sie können [GitHubs Theme-Kontext](https://github.blog/changelog/2021-11-24-specify-theme-context-for-images-in-markdown/) verwenden, um das Theme basierend auf dem GitHub Theme automatisch zu wechseln. Dies geschieht durch Anhängen von `#gh-dark-mode-only` oder `#gh-light-mode-only` an das Ende einer Bild-URL. Dieser Tag legt fest, ob das im Markdown angegebene Bild nur den Betrachtern mit einem hellen oder einem dunklen GitHub Theme angezeigt wird:

```md
<code>layout</code> - Wechsel zwischen den zwei verfügbaren Layouts <code>default</code> & <code>compact</code>
```
 - Wechsel zwischen den zwei verfügbaren Layouts default & compact
</code>

<details>
<summary>:eyes: Beispiel anzeigen</summary>

[![Farbverlauf](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![GitHub Readme Statistiken](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

</details>

##### Neue Medienfunktion von GitHub verwenden

Sie können [GitHubs neue Medienfunktion](https://github.blog/changelog/2022-05-19-specify-theme-context-for-images-in-markdown-beta/) in HTML verwenden, um festzulegen, ob Bilder für helle oder dunkle Themen angezeigt werden sollen. This is done using the HTML `<picture>` element in combination with the `prefers-color-scheme` media feature.

```html
<code>title_color</code> - Titelfarbe <em x-id="4">(hex color)</em>
```
 - Titelfarbe _(hex color)_
</code>

<details>
<summary>:eyes: Beispiel anzeigen</summary>

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

### Anpassungen/Personalisierung

Du kannst das Erscheinungsbild deiner `Stats Card` oder `Repo Card`, mithilfe von URL-Parametern, nach deinen Vorlieben anpassen.

#### Gemeinsame Optionen

-   `title_color` - Titelfarbe der Karte _(hex color)_. Default: `2f80ed`.
-   `text_color` - Textfarbe _(hex color)_. Standard: `434d58`.
-   `icon_color` - Icons Farbe falls verfügbar _(hex color)_. Standard: `4c71f2`.
-   `border_color` - Kartenrandfarbe _(hex color)_. Standard: `e4e2e2` (Wird nicht angewendet wenn `hide_border` aktiviert ist).
-   `bg_color` - Hintergrundfarbe der Karte _(hex color)_ **oder** einen Farbverlauf in Form von _Winkel,Anfang,Ende_. Standard: `fffefe`
-   `hide_border` - Versteckt den Rand der Karte _(boolean)_. Standard: `false`
-   `Theme` - Name des Themes, wählen Sie unter [allen verfügbaren Themes](./themes/README.md). Standard: `Standard-Template`
-   `cache_seconds` - Legen Sie den Cache-Header manuell _(min: 14400, max: 86400)_ fest. Standard: `14400 Sekunden (4 Stunden)`.
-   `Gebietsschema` - Setzen Sie die Sprache in der Karte _(z.B. cn, de, es, etc.)_. Standard: `de`.
-   `border_radius` - Ecke rundet die Karte ab. Standard: `4.5`.

> **Warnung** Wir verwenden Cache, um die Last auf unseren Servern zu reduzieren (siehe <https://github.com/anuraghazra/github-readme-stats/issues/1471#issuecomment-1271551425>). Unsere Karten haben einen Standardcache von 4 Stunden (14400 Sekunden). Außerdem ist der Cache auf ein Minimum von 30 Minuten und ein Maximum von 24 Stunden begrenzt.

##### Farbverlauf in bg_color

Du kannst mehrere, mit Kommas separierte, Werte in der bg_color Option angeben, um einen Farbverlauf anzuzeigen. Das Format ist:-

    &bg_color=WINKEL,FARBE1,FARBE2,FARBE3...FARBE10

#### Exklusive Optionen der Repo-Karte:

-   `Verstecke` - Versteckt die [angegebenen Elemente](#hiding-individual-stats) aus Statistiken _(durch Kommas getrennte Werte)_. Standard: `[] (leeres Array)`.
-   `hide_title` - _(boolean)_. Standard: `false`.
-   `card_width` - Legen Sie die Breite der Karte manuell _(Zahl)_ fest. Standard: `500px (ungefähr)`.
-   `hide_rank` - _(boolean)_ versteckt den Rang und verkleinert automatisch die Größe der Karte. Standard: `false`.
-   `show_icons` - _(boolean)_. Standard: `false`.
-   `include_all_commits` - Gesamtzahl der Commits statt nur des aktuellen Jahres Commits _(boolean)_. Standard: `false`.
-   `count_private` - Anzahl privater Commits _(boolean)_. Standard: `false`.
-   `Zeilen_Höhe` - Legt die Zeilenhöhe zwischen Text _(Zahl)_ fest. Standard: `25`.
-   `exclude_repo` - Sterne von angegebenen Repositories ausschließen _(durch Kommas getrennte Werte)_. Standard: `[] (leeres Array)`.
-   `custom_title` - Legt einen eigenen Titel für die Karte fest. Kopiere folgendes in deine Readme um die Statistiken zu benutzen. Passe den Wert des URL-Parameters `?username=` so an, dass dort dein GitHub-Nutzername steht.
-   `text_bold` - Fett Text _(boolean)_ verwenden. Standard: `true`.
-   `deaktivierte Animationen` - Deaktiviert alle Animationen in der Karte _(boolean)_. Standard: `false`.
-   `ring_color` - Farbe des Rankings _(hex color)_. Standardmäßig wird die Farbe des Theme-Ringes verwendet, wenn es existiert, und andernfalls die Titelfarbe.

> **Notiz** Wenn hide_rank=`true`ist, beträgt die minimale Kartenbreite 270 px + die Titellänge und das Padding.

#### Repo-Karte(Extra-Pin) anpassen

-   `show_owner` - Zeige den Namen des Repo-Besitzers _(boolean)_. Standard: `false`.

#### `hide` - Verbirgt die angegebenen Sprachen von der Karte _(Komma separierte Werte)_

-   `Hide` - Verstecke die auf der Karte angegebenen Sprachen _(durch Kommas getrennte Werte)_. Standard: `[] (leeres Array)`.
-   `hide_title` - _(Boolean)_ Standard: `false`.
-   `Layout` - Wechseln Sie zwischen zwei verfügbaren Layouts `Standard` & `kompakt`. Standard: `Standard`.
-   `card_width` - Legen Sie die Breite der Karte manuell _(Zahl)_ fest. Standard `300`.
-   `langs_count` - Zeige mehr Sprachen auf der Karte zwischen 1-10 _(Zahl)_. Standard `5`.
-   `exclude_repo` - angegebene Repositories ausschließen _(durch Kommas getrennte Werte)_. Standard: `[] (leeres Array)`.
-   `custom_title` - Legt einen eigenen Titel für die Karte _(String)_ fest. Standard `Meistbenutzte Sprachen`.
-   `deaktivierte Animationen` - Deaktiviert alle Animationen in der Karte _(boolean)_. Standard: `false`.

> **Warnung:** Sprachnamen sollten URI entschlüsselt werden, wie in [Prozent Encoding](https://en.wikipedia.org/wiki/Percent-encoding) angegeben (i. : `c++` sollte `c%2B%2B`werden, `Jupyter Notebook` sollte `Jupyter%20nÖtebook`werden, etc.) Du kannst [urlencoder.org](https://www.urlencoder.org/) benutzen, um dies automatisch zu tun.

#### Alle Beispiele

-   `Hide` - Verstecke die auf der Karte angegebenen Sprachen _(durch Kommas getrennte Werte)_. Standard: `[] (leeres Array)`.
-   `hide_title` - _(Boolean)_ Standard `false`.
-   `Zeilen_Höhe` - Legt die Zeilenhöhe zwischen Text _(Zahl)_ fest. Standard `25`.
-   `hide_progress` - Versteckt die Fortschrittsleiste und den Prozentsatz _(boolean)_. Standard `false`.
-   `custom_title` - Legt einen eigenen Titel für die Karte _(String)_ fest. Default `Wakatime Stats`.
-   `Layout` - Wechseln Sie zwischen zwei verfügbaren Layouts `Standard` & `kompakt`.  Standard ``.
-   `langs_count` - Begrenzt die Anzahl der angezeigten Sprachen auf der Karte
-   `api_domain` - Legen Sie eine eigene API-Domain für die Karte fest, z. um Dienste wie [Hakatime](https://github.com/mujx/hakatime) oder [Wakapi](https://github.com/muety/wakapi) _(string)_ zu verwenden. Standard `Waka API`.
-   `range` – Fragt eine andere Zeitspanne an, als jene, welche standardmäßig in Wakatime hinterlegt ist. Zum Beispiel `last_7_days`. Siehe [WakaTime API Dokumentation](https://wakatime.com/developers#stats). _(JJJJ-MM, last_7_days, last_30_days, last_6_months, last _year or all_time)_. Standard `all_time`.

* * *

# GitHub Extra Pins

GitHub Extra-Pins ermöglicht es mit Hilfe einer Readme auf deinem Profil mehr als 6 Repositories anzuzeigen.

Und Bääm! Du bist nicht mehr auf 6 angeheftete Repositories limitiert.

### Benutzung

Füge diesen Code in deine Readme-Datei ein und passe die Links an.

Endpunkt: `api/pin?username=anuraghazra&repo=github-readme-stats`

```md
[![Readme Karte](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)
```

### Demo

[![Lesekarte](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)

Benutze die [show_owner](#anpassungenpersonalisierung) Variable, um den Nutzernamen des Repository-Eigentümers anzuzeigen.

[![Lesekarte](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats&show_owner=true)](https://github.com/anuraghazra/github-readme-stats)

# Top Programmiersprachen-Karte

Die Top Programmiersprachen-Karte visualisiert die am meisten benutzten Programmiersprachen eines GitHub-Nutzers.

> **Notiz** Die Top-Sprachen zeigen nicht mein Fähigkeitsniveau oder ähnliches an; es ist eine GitHub Metrik, um festzustellen, welche Sprachen den meisten Code auf GitHub haben. Es ist ein neues Merkmal von github-readme-stats.

### Benutzung

Füge diesen Code in deine Readme-Datei ein und passe die Links an.

Endpunkt: `api/top-langs?username=anuraghazra`

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

### Einzelne Repositories ausschließen

Sie können den `&exclude_repo=repo1,repo2` Parameter verwenden, um einzelne Repositories auszuschließen.

```md
Hinweis: Seit <a href="https://github.com/anuraghazra/github-readme-stats/pull/58">#58</a> sollte es möglich sein, mehr als 5 Tsd Aufrufe pro Stunde ohne Downtimes zu verkraften :D
```

### Verbirg einzelne Sprachen

Du kannst den `?hide=language1,language2` URL-Parameter benutzen, um einzelne Sprachen auszublenden.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&hide=javascript,html)](https://github.com/anuraghazra/github-readme-stats)
```

### Alle Beiträge anzeigen

Sie können die Option `&langs_count=` verwenden, um die Anzahl der auf der Karte angezeigten Sprachen zu erhöhen oder zu verringern. Gültige Werte sind ganze Zahlen zwischen 1 und 10 (inklusive), und die Voreinstellung ist 5.

```md
<code>line_height</code> - Legt die Zeilenhöhe des Texts fest <em x-id="4">(Zahl)</em>
```
 - Legt die Zeilenhöhe des Texts fest _(Zahl)_
</code>

### Kompaktes Sprachen-Karte Layout

Du kannst die `&layout=compact` Option nutzen, um das Kartendesign zu ändern.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
```

### Demo

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   Kompaktes Layout

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

# Wakatime Wochen-Statistik

Ändere `?username=` in den eigenen [Wakatime](https://wakatime.com)-Benutzernamen.

```md
[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)
```

> **Hinweis**: Bitte beachten Sie, dass wir derzeit nur öffentliche Daten von Wakatime-Profilen anzeigen.

### Demo

[![willianrods Wakatime Statistiken](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

[![willianrods Wakatime Statistiken](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&hide_progress=true)](https://github.com/anuraghazra/github-readme-stats)

-   Kompaktes Layout

[![willianrods Wakatime Statistiken](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

* * *

### Alle Demos

-   Standard

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)

-   Ausblenden bestimmter Statistiken

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,issues)

-   Symbole anzeigen

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=issues&show_icons=true)

-   Rahmenfarbe anpassen

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&border_color=2e4058)

-   Alle Commits einbeziehen

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&include_all_commits=true)

-   Erscheinungsbild/Themes

Wähle Eines von den [Standard-Themes](#themes)

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)

-   Farbverlauf

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

-   Statistiken-Karte anpassen

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)

-   Gebietsschema festlegen

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&locale=es)

-   Forke dieses Repository

![Angepasste Karte](https://github-readme-stats.vercel.app/api/pin?username=anuraghazra&repo=github-readme-stats&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)

-   Top Programmiersprachen

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   Beispiel

[![willianrods Wakatime Statistiken](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

* * *

### Kleiner Tipp (Ausrichten der Repo-Karte)

Standardmäßig legt GitHub die Karten nicht nebeneinander aus. Dazu können Sie diesen Ansatz verwenden:

```html
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=convoychat" />
</a>
```

## Betreibe es auf deiner eigenen Vercel-Instanz

#### Schritt für Schritt YouTube Tutorial by @codeSTACKr

> **Warnung** Wenn Sie im [Hobby sind (z. kostenlos)](https://vercel.com/pricing) Vercel Plan, bitte stellen Sie sicher, dass Sie den `MaxDuration` Parameter im [Verzel ändern. Sohn](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json) Datei von `30` bis `10` (siehe [#1416](https://github.com/anuraghazra/github-readme-stats/issues/1416#issuecomment-950275476) für weitere Informationen).

Da die GitHub API nur 5 Tsd. Aufrufe pro Stunde zulässt, kann es passieren, dass meine `https://github-readme-stats.vercel.app/api` dieses Limit erreicht. Wenn du es auf deinem eigenen Vercel-Server hostest, brauchst du dich darum nicht zu kümmern. Klicke auf den Deploy-Knopf um loszulegen!

> `cache_seconds` - manuelles festlegen der Cachezeiten _(min: 1800, max: 86400)_

[![Auf Vercel verteilen](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/anuraghazra/github-readme-stats)

<details>
 <summary><b>:hammer_and_wrench: Schritt-für-Schritt Anleitung zum Einrichten Ihrer eigenen Vercel-Instanz</b></summary>

1.  Gehe zu [vercel.com](https://vercel.com/)
2.  Klicke auf `Log in` ![](https://files.catbox.moe/pcxk33.png)
3.  Melde dich mit deinem GitHub-account an, indem du `Continue with GitHub` klickst ![](https://files.catbox.moe/b9oxey.png)
4.  Verbinde dich mit GitHub und erlaube den Zugriff auf alle Repositories (falls gefordert)
5.  Fork diese Repo.
6.  Nach dem Forken des Repos öffnen Sie die [`vercel.json`](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json#L5) Datei und ändern Sie das Feld `maxDuration` auf `10`.
7.  Gehe zurück zu deinem [Vercel Dashboard](https://vercel.com/dashboard)
8.  Klick `Import Project` ![](https://files.catbox.moe/3n76fh.png)
9.  Klicken Sie auf den `Weiter mit der Schaltfläche GitHub` und suchen Sie nach dem benötigten Git Repository und importieren Sie es, indem Sie auf `Importieren` klicken. Alternativ können Sie ein Git Repository von Drittanbietern importieren, indem Sie das `Git Repository von Drittanbietern importieren ->` Link unten auf der Seite. ![](https://files.catbox.moe/mg5p04.png)
10. Wähle root und füge eine Umgebungsvariable namens PAT_1 (siehe Abbildung) die als Wert deinen persönlichen Access Token (PAT) hat hinzu, den du einfach [hier](https://github.com/settings/tokens/new) erzeugen kannst (lasse alles wie es ist, vergebe einen beliebigen Namen)
11. Fügen Sie den PAT als Umgebungsvariable namens `PAT_1` (wie angezeigt) hinzu. ![](https://files.catbox.moe/0yclio.png)
12. Klicke auf `Deploy`, und das wars. Besuche deine Domains um die API zu benutzen!

</details>

### Fork aktuell halten

Sie können Ihre Abzweigung und damit Ihre private Vercel-Instanz mit dem Upstream auf dem Laufenden halten, indem Sie den Button [Sync Fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) verwenden. Sie können auch das [pull](https://github.com/wei/pull) Paket verwenden, das von [@wei](https://github.com/wei) erstellt wurde, um diesen Prozess zu automatisieren.

## :sparkling_heart: Unterstütze das Projekt

Ich versuche alles was ich kann als Open-Source zur Verfügung zu stellen, als auch jedem der Hilfe bei der Benutzung dieses Projektes braucht zu antworten. Offensichtlich braucht seine Zeit. Sie können diesen Service kostenlos nutzen.

Wenn du dieses Projekt nutzt und zufrieden bist, kannst du dennoch Dinge tun um mich weiterhin zu motivieren am Projekt zu arbeiten:

-   Erwähne und verlinke das Projekt in deiner Readme wenn du es benutzt :D
-   Geb dem Projekt einen Stern hier auf GitHub und teile es :rocket:
-   [![paypal.me/anuraghazra](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/anuraghazra) - Du kannst einmalige Spenden via PayPal tätigen. Ich kaufe mir wahrscheinlich einen ~~Kaffee~~ Tee davon. :tea:

Vielen Dank! :heart:

* * *

[![https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss](./powered-by-vercel.svg)](https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss)

Mitarbeit an dem Projekt ist immer Willkommen! <3

Gemacht mit viel :heart: und JavaScript.
