<p align="center">
 <img width="100px" src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">Mostra nei tuoi README file le statistiche GitHub generate dinamicamente!</p>
</p>
  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats/actions">
      <img alt="Superamento Delle Prove" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/graphs/contributors">
      <img alt="GitHub Extra Pin" src="https://img.shields.io/github/contributors/anuraghazra/github-readme-stats" />
    </a>
    <a href="https://codecov.io/gh/anuraghazra/github-readme-stats">
      <img src="https://codecov.io/gh/anuraghazra/github-readme-stats/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/issues">
      <img alt="Problemi" src="https://img.shields.io/github/issues/anuraghazra/github-readme-stats?color=0088ff" />
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
    <a href="#demo">Anteprima</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Segnala un errore</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Richiedi una nuova funzionalità</a>
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
    <a href="/docs/readme_tr.md">Tu<unk> rkc<unk> e</a>
  </p>
</p>

<p align="center">Ti piace il progetto? Se ti piace questo progetto, considera la possibilità di <a href="https://www.paypal.me/anuraghazra">donare</a> per aiutare a renderlo migliore!</p>

<a href="https://indiafightscorona.giveindia.org">
  <img src="https://indiaspora.org/wp-content/uploads/2021/04/give-India-logo.png" alt="Dare logo india" width="200" />
</a>

Stai pensando di sostenere il progetto donando? Si prega di non farlo!!

Aiuta invece l'India a combattere la seconda ondata mortale di COVID-19. Migliaia di persone muoiono in India a causa della mancanza di ossigeno & anche di infrastrutture legate al COVID.

Visita <https://indiafightscorona.giveindia.org> e fai una piccola donazione per aiutarci a combattere COVID e superare questa crisi. Una piccola donazione è lunga. :heart:

</p>

# Caratteristiche

-   [Scheda Statistiche GitHub](#github-stats-card)
-   [GitHub Extra Pins](#github-extra-pins)
-   [Top Languages Card](#top-languages-card)
-   [Statistiche Settimana Wakatime](#wakatime-week-stats)
-   [Temi](#themes)
    -   [Tema Scheda Responsive](#responsive-card-theme)
-   [Personalizzazione](#customization)
    -   [Opzioni comuni:](#common-options)
    -   [Nota sulla cache: le card hanno un valore di cache di 4 ore (14400 seconds) di default se il numero di fork & il numero di stelle è inferiore a 1000; altrimenti è pari a 2 ore (7200).](#stats-card-exclusive-options)
    -   [Per allineare le card una accanto all'altra, puoi adottare questo approccio:](#repo-card-exclusive-options)
    -   [Opzioni valide solo per le card dei linguaggi:](#language-card-exclusive-options)
    -   [Opzione Esclusiva Carta Wakatime](#wakatime-card-exclusive-options)
-   [Effettua il Deploy](#deploy-on-your-own-vercel-instance)
    -   [Mantieni aggiornato il tuo fork](#keep-your-fork-up-to-date)

# Scheda Statistiche GitHub

Copia-incolla questo nel tuo contenuto di markdown, e questo è questo. Semplice!

Ricorda di cambiare il valore `?username=` con il tuo nome utente GitHub.

```md
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

> **Nota** I ranghi disponibili sono S+ (top 1%), S (top 25%), A++ (top 45%), A+ (top 60%) e B+ (tutti). I valori sono calcolati utilizzando la funzione di distribuzione cumulativa [](https://en.wikipedia.org/wiki/Cumulative_distribution_function) utilizzando commit, contributi, problemi, stelle, richieste di pull, follower e repository di proprietà. L'implementazione può essere indagata su [src/calculateRank.js](./src/calculateRank.js).

### Nascondere statistiche individuali

Per nascondere qualche dato, puoi aggiungere i parametri `?hide=`, separando i valori con una virgola.

> Opzioni: `&hide=stars,commits,prs,issues,contribs`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,prs)
```

### Includere i contributi privati nel computo totale

Puoi aggiungere i tuoi contributi privati al totale dei commit, utilizzando il parametro `?count_private=true`.

> **Nota** Se si sta distribuendo questo progetto da solo, i contributi privati saranno contati per impostazione predefinita. Se stai usando l'istanza pubblica di Vercel, devi scegliere di [condividere i tuoi contributi privati](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/managing-contribution-settings-on-your-profile/showing-your-private-contributions-and-achievements-on-your-profile).

> Opzioni: `&count_private=true`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&count_private=true)
```

### Mostrare le icone

Per abilitare le icone, puoi specificare `show_icons=true`, ad esempio:

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true)
```

### Temi

Esistono alcuni temi predefiniti coi quali è possibile personalizzare l'aspetto delle card. In alternativa, è possibile effettuare una [personalizzazione manuale](#personalizzazione).

Usa il parametro `?theme=NOME_TEMA` in questo modo:-

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
```

#### Tutti i temi incorporati

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stat Themes" width="600px" />

Puoi avere un'anteprima di [tutti i temi supportati](../themes/README.md) o controllare il [file di configurazione dei temi](../themes/index.js) e **puoi anche contribuire creando un nuovo tema** se vuoi :D

#### Tema Scheda Responsive

[![Guarda questo Video Tutorial, realizzato da @codeSTACKr](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![Per creare una Card con le statistiche GitHub, copia e incolla nel tuo file markdown, tutto qua: è semplice!](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

Dal momento che GitHub ri-caricare le carte e servirle dal loro [CDN](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-anonymized-urls), non possiamo dedurre il tema browser/GitHub sul lato server. Ci sono, tuttavia, quattro metodi che è possibile utilizzare per creare temi dinamici sul lato client.

##### Usa il tema trasparente

Abbiamo incluso un tema `trasparente` che ha uno sfondo trasparente. Questo tema è ottimizzato per guardare bene sui temi di default scuro e chiaro di GitHub. Puoi abilitare questo tema usando il parametro `&theme=transparent` , così:

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=transparent)
```

<details>
<summary>:eyes: Mostra esempio</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=transparent)

</details>

##### Aggiunge un canale alfa trasparente a un tema bg_color

È possibile utilizzare il parametro `bg_color` per rendere trasparente uno qualsiasi dei [temi disponibili.](./themes/README.md) Questo viene fatto impostando il `bg_color` su un colore con un canale alfa trasparente (es. `bg_color=00000000`):

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)
```

<details>
<summary>:eyes: Mostra esempio</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)

</details>

##### `theme` - Nome del tema, dai un'occhiata a [tutti i temi disponibili](../themes/README.md)

È possibile utilizzare [GitHub's theme context](https://github.blog/changelog/2021-11-24-specify-theme-context-for-images-in-markdown/) tags per cambiare automaticamente il tema in base al tema GitHub utente. Questo viene fatto aggiungendo `#gh-dark-mode-only` o `#gh-light-mode-only` alla fine di un URL di immagine. Questo tag definirà se l'immagine specificata nel markdown viene mostrata solo agli spettatori usando una luce o un tema GitHub scuro:

```md
[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only)
[![Anurag's GitHub stats-Light](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/github.com/github-readme-stats#gh-mode-only)
```

<details>
<summary>:eyes: Mostra esempio</summary>

[![Select <code>Import Git Repository</code>](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![Statistiche GitHub (GitHub Stats Card)](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

</details>

##### Usa la nuova funzionalità multimediale di GitHub

È possibile utilizzare [la nuova funzione multimediale](https://github.blog/changelog/2022-05-19-specify-theme-context-for-images-in-markdown-beta/) di GitHub in HTML per specificare se visualizzare immagini per temi chiari o scuri. Questo viene fatto utilizzando l'elemento HTML `<picture>` in combinazione con la funzione `prefers-color-schema` multimediale.

```html
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
```

<details>
<summary>:eyes: Mostra esempio</summary>

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

### Personalizzazione

Puoi personalizzare l'aspetto delle tue `Stats Card` o delle `Repo Card` in qualsiasi modo, semplicemente modificando i parametri dell'URL.

#### Temi

-   `title_color` - Colore del titolo _(in esadecimale)_ Default: `2f80ed`.
-   `text_color` - Colore del testo _(in esadecimale)_ Predefinito: `434d58`.
-   `icon_color` - Colore delle icone, se disponibili _(in esadecimale)_ Predefinito: `4c71f2`.
-   `border_color` - Colore bordo della carta _(colore esadecimale)_. Predefinito: `e4e2e2` (Non si applica quando `hide_border` è abilitato).
-   `bg_color` - Colore dello sfondo _(in esadecimale)_ **oppure** un gradiente nella forma _angolo,inizio,fine_ Predefinito: `fffefe`
-   `hide_border` - Nasconde il bordo della carta _(booleano)_ Predefinito: `false`
-   `tema` - nome del tema, scegli tra [tutti i temi disponibili](./themes/README.md). Predefinito: `tema predefinito`.
-   `cache_seconds` - Specifica manualmente il valore di cache, in secondi _(min: 1800, max: 86400)_ Predefinito: `14400 secondi (4 ore)`.
-   `locale` - Impostare la lingua nella scheda _(per esempio. cn, de, es, eccetera.)_
-   `border_radius` - Arrotondamento ad angolo sulla carta. Predefinito: `4.5`.

> **Avviso** Utilizziamo la cache per diminuire il carico sui nostri server (vedi <https://github.com/anuraghazra/github-readme-stats/issues/1471#issuecomment-1271551425>). Le nostre carte hanno una cache predefinita di 4 ore (14400 secondi). Inoltre, notare che la cache è fissata ad un minimo di 4 ore e ad un massimo di 24 ore.

##### Gradiente nello sfondo

Puoi fornire valori separati da virgola nel parametro bg_color per creare un gradiente, il cui formato è:-

    &bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10

#### Opzioni valide solo per le card delle statistiche:

-   `hide` - Nasconde gli oggetti selezionati _(valori separati da virgola)_ Predefinito: `[] (vettore vuoto)`.
-   `hide_title` - _(boolean)_. Predefinito: `false`.
-   `card_width` - Imposta manualmente la larghezza della carta _(numero)_. Predefinito: `500px (circa.)`.
-   `hide_rank` - _(boolean)_ nasconde il rango e ridimensiona automaticamente la larghezza della carta. Predefinito: `false`.
-   `show_icons` - Mostra le icone _(booleano)_ Predefinito: `false`.
-   `include_all_commits` - Mostra tutti i commit e non solo quelli dell'anno corrente _(booleano)_ Predefinito: `false`.
-   `count_private` - Include i contributi privati _(booleano)_ Predefinito: `false`.
-   `line_height` - Imposta l'altezza della linea tra il testo _(numero)_. Predefinito: `25`.
-   `exclude_repo` - Escludi le stelle dai repository specificati _(valori separati da virgole)_. Predefinito: `[] (vettore vuoto)`.
-   `custom_title` - Imposta un titolo personalizzato per la carta. Default:  `<username> GitHub Stats`.
-   `text_bold` - Usa testo in grassetto _(boolean)_. Predefinito: `true`.
-   `disable_animations` - Disabilita tutte le animazioni nella carta _(boolean)_. Predefinito: `false`.
-   `ring_color` - Colore del cerchio di rango _(colore esadecimale)_. Predefinito al colore dell'anello del tema se esiste e altrimenti il colore del titolo.

> **Nota** When hide_rank=`true`, the minimum card width is 270 px + the title length and padding.

#### Opzioni valide solo per le Repo Card:

-   `show_owner` - Mostra il nome proprietario del repo's _(boolean)_. Predefinito: `false`.

#### NOTA: questa card non indica il livello di abilità, ma piuttosto quanto codice hai scritto in un determinato linguaggio

-   `hide` - Hide the languages specified from the card _(Comma-separated values)_. Predefinito: `[] (vettore vuoto)`.
-   `hide_title` - Nasconde il titolo _(booleano)_ Predefinito: `false`.
-   `layout` - Specifica il tipo di layout, `default` (esteso) o `compact` (compatto) Predefinito: `default`.
-   `card_width` - Specifica il valore della larghezza _(numero)_ Predefinito `300`.
-   `langs_count` - Mostra più lingue sulla carta, tra 1-10 _(numero)_. Predefinito `5`.
-   `exclude_repo` - Escludi i repository specificati _(valori separati da virgole)_. Predefinito: `[] (vettore vuoto)`.
-   `custom_title` - Imposta un titolo personalizzato per la carta _(stringa)_. Predefinito `Lingue più usate`.
-   `disable_animations` - Disabilita tutte le animazioni nella carta _(boolean)_. Predefinito: `false`.

> **Attenzione** I nomi delle lingue dovrebbero essere URI-escaped, come specificato in [Codifica per cento](https://en.wikipedia.org/wiki/Percent-encoding) (i. : `c++` dovrebbe diventare `c%2B%2B`, `jupyter notebook` dovrebbe diventare `jupyter%20notebook`, ecc.) Puoi usare [urlencoder.org](https://www.urlencoder.org/) per aiutarti a farlo automaticamente.

#### Opzioni Esclusive Carta Wakatime

-   `hide` - Hide the languages specified from the card _(Comma-separated values)_. Predefinito: `[] (vettore vuoto)`.
-   `hide_title` - Nasconde il titolo _(booleano)_ Predefinito `falso`.
-   `line_height` - Specifica il valore dell'altezza di riga _(numero)_ Predefinito `25`.
-   `hide_rank` - Nasconde il punteggio _(booleano)_ Predefinito `falso`.
-   `custom_title` - Imposta un titolo personalizzato per la carta _(stringa)_. Default `Wakatime Stats`.
-   `layout` - Specifica il tipo di layout, `default` (esteso) o `compact` (compatto)  Predefinito `predefinito`.
-   `langs_count` - Limita il numero di lingue sulla carta, valori predefiniti per tutte le lingue segnalate _(numero)_.
-   `api_domain` - Imposta un dominio API personalizzato per la scheda, ad es. per utilizzare servizi come [Hakatime](https://github.com/mujx/hakatime) o [Wakapi](https://github.com/muety/wakapi) _(stringa)_. API predefinita `Waka`.
-   `range` – Richiedi un intervallo diverso da quello predefinito per WakaTime, ad esempio `last_7_days`. Vedi [WakaTime API docs](https://wakatime.com/developers#stats) per un elenco di opzioni disponibili. _(YYY-MM, last_7_days, last_30_days, last_6_mesi, last_year, or all_time)_. Predefinito `all_time`.

* * *

# GitHub Extra Pins

GitHub Extra Pins ti permette di fissare in alto più di 6 repository nel tuo profilo, sfruttando il README del profilo.

Yay! Non sei più limitato a 6 repository fissati.

### Utilizzo

Copia e incolla il seguente codice, premurandoti di cambiare il link.

Endpoint: `api/pin?username=anuraghazra&repo=github-readme-stats`

```md
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anurhazra/github-readme-stats)
```

### Demo

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)

Usa la variabile [show_owner](#personalizzazione) per includere il nome utente del proprietario

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats&show_owner=true)](https://github.com/anuraghazra/github-readme-stats)

# Top Languages Card

La Top Languages Card mostra i linguaggi che utilizzi di più su GitHub.

> **Nota** Le migliori lingue non indicano il mio livello di abilità o qualcosa del genere; è una metrica di GitHub per determinare quali lingue hanno più codice su GitHub. Si tratta di una nuova caratteristica di github-readme-stats.

### Utilizzo

Copia e incolla nel tuo file README, cambiando i link.

Endpoint: `api/top-langs?username=anuraghazra`

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

### Escludi i singoli repository

È possibile utilizzare il parametro `&exclude_repo=repo1, repo2` per escludere i singoli repository.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&exclude_repo=github-readme-stats,anuraghazra.github.io)](https://github.com/anuraghazra/github-readme-stats)
```

### Nascondi linguaggi specifici

Puoi utilizzare il parametro `?hide=linguaggio1,linguaggio2` per nascondere alcuni linguaggi.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&hide=javascript,html)](https://github.com/anurhazra/github-readme-stats)
```

### Linguaggi più usati

È possibile utilizzare l'opzione `&langs_count=` per aumentare o diminuire il numero di lingue mostrate sulla carta. I valori validi sono interi tra 1 e 10 (inclusi) e il valore predefinito è 5.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&langs_count=8)](https://github.com/anuraghazra/github-readme-stats)
```

### Layout Della Scheda Lingua Compatta

Puoi utilizzare l'opzione `&layout=compact` per cambiare l'aspetto della card.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
```

### Demo

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   Layout compatto

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

# Statistiche Settimana Wakatime

`show_owner` - Mostra il nome utente del proprietario _(booleano)_

```md
[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)
```

> **Nota**: Si prega di essere consapevoli che al momento mostriamo solo i dati da profili Wakatime che sono pubblici.

### Demo

[![statistiche di risveglio di willianrod](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

[![statistiche di risveglio di willianrod](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&hide_progress=true)](https://github.com/anuraghazra/github-readme-stats)

-   Layout Compatto

[![statistiche di risveglio di willianrod](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

* * *

### Tutte Le Demo

-   Predefinito

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)

-   Nascondere dati specifici

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,issues)

-   Mostrare le icone

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=issues&show_icons=true)

-   Personalizza Colore Bordo

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&border_color=2e4058)

-   Includere tutti i commit

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&include_all_commits=true)

-   Temi

Scegli uno dei [temi di default](#themes)

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)

-   Gradiente

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

-   Personalizzare le Stats Card

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)

-   Impostazione locale scheda

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&locale=es)

-   Personalizzare le Repo Card

![Carta Personalizzata](https://github-readme-stats.vercel.app/api/pin?username=anuraghazra&repo=github-readme-stats&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)

-   Linguaggi più usati (Top Languages Card)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   Scheda WakaTime

[![statistiche di risveglio di willianrod](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

* * *

### Consiglio veloce (Allineare le Card)

Per impostazione predefinita, GitHub non espone le carte fianco a fianco. Per fare questo, è possibile utilizzare questo approccio:

```html
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=convoychat" />
</a>
```

## Deploy su Vercel

#### :film_projector: [Check Out Step By Step Video Tutorial di @codeSTACKr](https://youtu.be/n6d4KHSKqGk?t=107)

> **Attenzione** Se sei sul [hobby (es. gratuito)](https://vercel.com/pricing) Piano Vercel, assicurati di modificare il parametro `maxDuration` nel [vercel. son](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json) file da `30` a `10` (vedi [#1416](https://github.com/anuraghazra/github-readme-stats/issues/1416#issuecomment-950275476) per maggiori informazioni).

Since the GitHub API only allows 5k requests per hour, it is possible that my `https://github-readme-stats.vercel.app/api` could hit the rate limiter. If you host it on your own Vercel server, then you don't have to worry about anything. Clicca sul pulsante deploy per iniziare!

> NOTE: Since [#58](https://github.com/anuraghazra/github-readme-stats/pull/58) we should be able to handle more than 5k requests and have no issues with downtime :D

[![Distribuisci a Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/anuraghazra/github-readme-stats)

<details>
 <summary><b>:hammer_and_wrench: Guida passo passo per configurare la tua istanza di Vercel</b></summary>

1.  Go to [vercel.com](https://vercel.com/)
2.  Click on `Log in` ![](https://files.catbox.moe/pcxk33.png)
3.  Sign in with GitHub by pressing `Continue with GitHub` ![](https://files.catbox.moe/b9oxey.png)
4.  Sign into GitHub and allow access to all repositories, if prompted
5.  Fork this repo
6.  Dopo aver forgiato il repo, apri il file [`vercel.json`](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json#L5) e cambia il campo `maxDuration` in `10`.
7.  Go back to your [Vercel dashboard](https://vercel.com/dashboard)
8.  Select `Import Project` ![](https://files.catbox.moe/3n76fh.png)
9.  Fare clic sul pulsante `Continua con GitHub` , cercare il repository Git richiesto e importarlo facendo clic sul pulsante `Importa`. In alternativa, puoi importare un repository Git di terze parti usando il link `Importa repository Git di terze parti ->` in fondo alla pagina. ![](https://files.catbox.moe/mg5p04.png)
10. Crea un token di accesso personale (PAT) [qui](https://github.com/settings/tokens/new) e abilita i permessi `repo` (questo permette di accedere alle statistiche di repo private).
11. Aggiungere il PAT come variabile d'ambiente chiamata `PAT_1` (come mostrato). ![](https://files.catbox.moe/0yclio.png)
12. Fare clic su deploy, e sei bravo ad andare. Vedi i tuoi domini per usare l'API!

</details>

### Mantieni aggiornato il tuo fork

Puoi mantenere la tua forchetta, e quindi la tua istanza privata Vercel aggiornata con l'upstream utilizzando il pulsante [Sync Fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) di GitHubs. Puoi anche utilizzare il pacchetto [pull](https://github.com/wei/pull) creato da [@wei](https://github.com/wei) per automatizzare questo processo.

## :sparkling_heart: Supporta il progetto

Rendo open-source quasi tutto ciò che posso e provo a rispondere a chiunque sia in difficoltà nell'utilizzare questi progetti. Ovviamente, mi richiede del tempo. Puoi utilizzare questo servizio gratuitamente.

Tuttavia, se usi il progetto e ti piace e vuoi sostenermi, puoi:-

-   Dare il giusto riconoscimento quando usi github-readme-stats nei tuoi readme, includendo un link :D
-   Mettere una stella e condividere il progetto :rocket:
-   [![paypal.me/anuraghazra](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/anuraghazra) - Fare una donazione via PayPal. Probabilmente compreròun ~~caffè~~ tè. :tea:

Grazie! :heart:

* * *

[![https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss](./powered-by-vercel.svg)](https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss)

I contributi sono benvenuti! <3

Realizzato col :heart: e in JavaScript.
