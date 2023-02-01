<p align="center">
 <img width="100px" src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">Obtenez des statistiques GitHub générées dynamiquement sur vos Readme !</p>
</p>
  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats/actions">
      <img alt="Tests réussis" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/graphs/contributors">
      <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/anuraghazra/github-readme-stats" />
    </a>
    <a href="https://codecov.io/gh/anuraghazra/github-readme-stats">
      <img src="https://codecov.io/gh/anuraghazra/github-readme-stats/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/issues">
      <img alt="Problèmes" src="https://img.shields.io/github/issues/anuraghazra/github-readme-stats?color=0088ff" />
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
    <a href="#démo">Voir la démo</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Soumettre un bug</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Demander une nouveauté</a>
  </p>
  <p align="center">
    <a href="/docs/readme_fr.md">Français</a>
    ·
    <a href="/docs/readme_cn.md">简体中文</a>
    ·
    <a href="/docs/readme_es.md">Español</a>
    ·
    <a href="/docs/readme_de.md">Deutsch</a>
    ·
    <a href="/docs/readme_ja.md">日本語</a>
    ·
    <a href="/docs/readme_pt-BR.md">Português Brasileiro</a>
    ·
    <a href="/docs/readme_it.md">Italiano</a>
    ·
    <a href="/docs/readme_kr.md">한국어</a>
    .
    <a href="/docs/readme_nl.md">Nederlands</a>
.
    <a href="/docs/readme_np.md">नेपाली</a>
    <a href="/docs/readme_tr.md">Tu<unk> rkc<unk> e</a>
  </p>
</p>

<p align="center">Vous aimez ce projet? Pensez <a href="https://www.paypal.me/anuraghazra">à faire un don</a> pour l'améliorer!</p>

<a href="https://indiafightscorona.giveindia.org">
  <img src="https://indiaspora.org/wp-content/uploads/2021/04/give-India-logo.png" alt="Donner le logo india" width="200" />
</a>

Envisagez-vous de soutenir le projet en faisant un don? NE FAITES PAS !!

Au lieu de cela, aidez l’Inde à combattre la deuxième vague mortelle du COVID-19. Des milliers de personnes meurent en Inde en raison d’un manque d’oxygène & aussi d’infrastructures liées au COVID.

Visitez <https://indiafightscorona.giveindia.org> et faites un petit don pour nous aider à combattre la COVID et à surmonter cette crise. Un petit don va très loin. :heart:

</p>

# Fonctionnalités

-   [Carte des stats GitHub](#github-stats-card)
-   [GitHub Extra Pins](#github-extra-pins)
-   [Carte des meilleurs langages](#top-languages-card)
-   [Statistiques de la semaine Wakatime](#wakatime-week-stats)
-   [Thèmes](#themes)
    -   [Thème de carte adaptative](#responsive-card-theme)
-   [Personnalisation](#customization)
    -   [Options courantes](#common-options)
    -   [Stats Card Exclusive Options:](#stats-card-exclusive-options)
    -   [Options principales:](#repo-card-exclusive-options)
    -   [`hide` - Masquer les langages spécifiés sur la carte _(Comma seperated values)_](#language-card-exclusive-options)
    -   [Note: Si vous déployez vous-même ce projet, les contributions privées seront comptées par défaut ; sinon, vous devez choisir de partager les comptes de vos contributions privées.](#wakatime-card-exclusive-options)
-   [Deployer toi-même](#deploy-on-your-own-vercel-instance)
    -   [Gardez votre fork à jour](#keep-your-fork-up-to-date)

# Carte des Stats GitHub

Copiez-collez ceci dans votre Markdown, et c'est tout. C'est simple !

Remplacez la valeur `?username=` par le nom d'utilisateur de votre GitHub.

```md
[![Les Stats GitHub de Anurag](https://github-readme-stats.vercel.app/api?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

> **Note** Les rangs disponibles sont S+ (top 1%), S (top 25%), A++ (top 45%), A+ (top 60%), et B+ (everyone). Les valeurs sont calculées en utilisant la fonction [de distribution cumulée](https://en.wikipedia.org/wiki/Cumulative_distribution_function) en utilisant des commits, des contributions, des tickets, des étoiles, des pull requests, des suiveurs et des dépôts propriétaires. L'implémentation peut être étudiée sur [src/calculateRank.js](./src/calculateRank.js).

### Cacher les statistiques individuelles

Pour masquer des statistiques spécifiques, vous pouvez passer un paramètre de requête `?hide=` avec des valeurs séparées par des virgules.

> Options : `&hide=étoiles, commits,prs,issues,contribs`

```md
![Les Stats GitHub de Anurag](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,prs)
```

### Ajouter le compte des contributions privées au compte des commits totaux

Vous pouvez ajouter le compte de toutes vos contributions privées au compte total des engagements en utilisant le paramètre de requête `?count_private=true`.

> **Note** Si vous déployez ce projet vous-même, les contributions privées seront comptées par défaut. Si vous utilisez l'instance publique Vercel , vous devez choisir de [partager vos contributions privées](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/managing-contribution-settings-on-your-profile/showing-your-private-contributions-and-achievements-on-your-profile).

> Options : `&count_private=true`

```md
![Les Stats GitHub de Anurag](https://github-readme-stats.vercel.app/api?username=anuraghazra&count_private=true)
```

### Afficher les icônes

Pour activer les icônes, vous pouvez passer `show_icons=true` dans le paramètre de requête, comme ceci :

```md
![Les Stats GitHub de Anurag](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true)
```

### Thèmes

Avec les thèmes intégrés, vous pouvez personnaliser l'apparence de la carte sans faire de [personnalisation manuelle](#customization).

Use `?theme=THEME_NAME` parameter like so :-

```md
![Les Stats GitHub de Anurag](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
```

#### Tous les thèmes intégrés :-

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stat Themes" width="600px" />

Vous pouvez consulter un aperçu de [tous les thèmes disponibles](../themes/README.md) ou consulter le [fichier de configuration des thèmes](../themes/index.js) & **vous pouvez également ajouter de nouveaux thèmes** si vous le souhaitez :D

#### Thème de carte adaptative

[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![<code>include_all_commits</code> - Compter le total de commits au lieu de ne compter que les commits de l'année en cours <em x-id="4">(boolean)</em>](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

Puisque GitHub va re-télécharger les cartes et les servir depuis leur [CDN](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-anonymized-urls), nous ne pouvons pas inférer le thème navigateur/GitHub du côté serveur. Il y a toutefois quatre méthodes que vous pouvez utiliser pour créer des thèmes dynamiques du côté client.

##### Utiliser le thème transparent

Nous avons inclus un thème `transparent` qui a un arrière-plan transparent. Ce thème est optimisé pour avoir une bonne apparence sur les thèmes sombres et clairs de GitHub. Vous pouvez activer ce thème en utilisant le paramètre `&theme=transparent` comme suit:

```md
<code>show_owner</code> - Affiche le nom du propriétaire du dépôt <em x-id="4">(boolean)</em>
```
 - Affiche le nom du propriétaire du dépôt _(boolean)_
</code>

<details>
<summary>:eyes: Voir l'exemple</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=transparent)

</details>

##### Ajouter un canal alpha transparent à un thème bg_color

Vous pouvez utiliser le paramètre `bg_color` pour rendre transparents l'un des [thèmes disponibles](./themes/README.md). Ceci est fait en définissant la `bg_color` à une couleur avec un canal alpha transparent (i.e. `bg_color=00000000` ) :

```md
[![Carte ReadMe](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)
```

<details>
<summary>:eyes: Voir l'exemple</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)

</details>

##### Thèmes

Vous pouvez utiliser les balises [du thème contexte](https://github.blog/changelog/2021-11-24-specify-theme-context-for-images-in-markdown/) de GitHub pour basculer le thème en fonction du thème GitHub de l'utilisateur automatiquement. Ceci est fait en ajoutant `#gh-dark-mode-only` ou `#gh-light-mode-only` à la fin d'une URL d'image. Cette balise définira si l'image spécifiée dans le markdown est affichée uniquement aux spectateurs en utilisant un thème clair ou sombre GitHub :

```md
[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only)
[![Anurag's GitHub stats-Light](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-reads#gh-light-mode-only)
```

<details>
<summary>:eyes: Voir l'exemple</summary>

[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![Sélectionnez <code>Import Git Repository</code>](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

</details>

##### Utiliser les nouveaux médias de GitHub

Vous pouvez utiliser la fonctionnalité [des nouveaux médias de GitHub](https://github.blog/changelog/2022-05-19-specify-theme-context-for-images-in-markdown-beta/) en HTML pour spécifier si vous voulez afficher des images pour des thèmes clairs ou sombres. Ceci est fait en utilisant l'élément HTML `<picture>` en combinaison avec la fonctionnalité média `prefers-color-scheme`.

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
<summary>:eyes: Voir l'exemple</summary>

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

### Personnalisation

Vous pouvez personnaliser l'apparence de votre `Carte des stats` ou `Carte de dépôt` comme vous le souhaitez avec les paramètres d'URL.

#### Options courantes

-   `title_color` - couleur titre de la carte _(couleur hexadécimale)_. Default: `2f80ed`.
-   `text_color` - Couleur du corps du texte _(couleur hexadécimale)_. Par défaut : `434d58`.
-   `icon_color` - Couleur des icônes si disponible _(couleur hexadécimale)_. Par défaut : `4c71f2`.
-   `border_color` - Couleur de bordure de la carte _(couleur hexadécimale)_. Par défaut : `e4e2e2` (Ne s'applique pas lorsque `hide_border` est activé).
-   `bg_color` - Couleur de fond de la carte _(couleur hexadécimale)_ **ou** un gradient sous la forme de _angle,démarrage,fin_. Par défaut : `fffefe`
-   `hide_bord` - Masque la bordure de la carte _(booléen)_. Par défaut : `faux`
-   `thème` - nom du thème, choisissez parmi [tous les thèmes disponibles](./themes/README.md). Par défaut : `thème` par défaut.
-   `cache_secondes` - définit l'en-tête de cache manuellement _(min: 14400, max: 86400)_. Par défaut : `14400 secondes (4 heures)`.
-   `locale` - définir la langue de la carte _(par exemple. cn, de, es, etc.)_
-   `border_radius` - Coin arrondi sur la carte. Par défaut : `4.5`.

> **Avertissement** Nous utilisons la mise en cache pour diminuer la charge de nos serveurs (voir <https://github.com/anuraghazra/github-readme-stats/issues/1471#issuecomment-1271551425>). Nos cartes ont une cache par défaut de 4 heures (14400 secondes). Notez également que la mémoire cache est limitée à 30 minutes au minimum et à 24 heures au maximum.

##### Dégradé dans bg_color

Vous pouvez fournir plusieurs valeurs (suivie d'une virgule) dans l'option bg_color pour rendre un degradé, le format du degradé est :-

    &bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10

#### Repo Card Exclusive Options:

-   `hide` - Masque les [éléments spécifiés](#hiding-individual-stats) des stats _(valeurs séparées par des virgules)_. Par défaut : `[] (tableau vide)`.
-   `hide_title` - _(boolean)_. Par défaut : `false`.
-   `card_width` - Définit la largeur de la carte manuellement _(nombre)_. Par défaut : `500px (approx.)`.
-   `masquer le rang` - _(booléen)_ masque le rang et redimensionne automatiquement la largeur de la carte. Par défaut : `false`.
-   `show_icons` - _(boolean)_. Par défaut : `false`.
-   `include_all_commits` - Comptez le nombre total de commits au lieu de l'année courante commite _(boolean)_. Par défaut : `false`.
-   `count_private` - Nombre de commits privés _(boolean)_. Par défaut : `false`.
-   `ligne_height` - Définit la hauteur de la ligne entre le texte _(nombre)_. Par défaut : `25`.
-   `exclude_repo` - Exclure les étoiles des dépôts spécifiés _(valeurs séparées par des virgules)_. Par défaut : `[] (tableau vide)`.
-   `custom_title` - Définit un titre personnalisé pour la carte. Default:  `<username> GitHub Stats`.
-   `text_bold` - Utilisez du texte en gras _(boolean)_. Par défaut : `true`.
-   `disable_animation` - Désactive toutes les animations de la carte _(boolean)_. Par défaut : `false`.
-   `anneau` - Couleur du cercle de rang _(couleur hexadécimale)_. Par défaut, la couleur de l'anneau du thème existe, sinon la couleur du titre.

> **Remarque** Lorsque hide_rank=`vrai`, la largeur minimale de la carte est de 270 px + la longueur du titre et le remplissage.

#### Language Card Exclusive Options:

-   `show_owner` - Afficher le nom du propriétaire du dépôt _(booléen)_. Par défaut : `false`.

#### Carte des langages les + utilisés

-   `masquer` - Cacher les langues spécifiées à partir de la carte _(valeurs séparées par des virgules)_. Par défaut : `[] (tableau vide)`.
-   `hide_title` - Masquer le titre _(boolean)_ Par défaut : `false`.
-   `layout` - Basculer entre deux mises en page disponibles `par défaut` & `compact`. Par défaut : `par défaut`.
-   `card_width` - Définit la largeur de la carte manuellement _(nombre)_. Par défaut `300`.
-   `langs_count` - Afficher plus de langues sur la carte, entre 1-10 _(nombre)_. Par défaut `5`.
-   `exclude_repo` - Exclure les dépôts spécifiés _(valeurs séparées par des virgules)_. Par défaut : `[] (tableau vide)`.
-   `custom_title` - Définit un titre personnalisé pour la carte _(chaîne)_. Par défaut `Langues les plus utilisées`.
-   `disable_animation` - Désactive toutes les animations de la carte _(boolean)_. Par défaut : `false`.

> **Avertissement** Les noms de langues doivent être protégés par des URI, comme spécifié dans [Pourcentage Encodage](https://en.wikipedia.org/wiki/Percent-encoding) (i. : `c++` devrait devenir `c%2B%2B`, `bloc-notes jupyter` devrait devenir `jupyter%20notebook`, etc.) Vous pouvez utiliser [urlencoder.org](https://www.urlencoder.org/) pour vous aider à le faire automatiquement.

#### Top Langages

-   `masquer` - Cacher les langues spécifiées à partir de la carte _(valeurs séparées par des virgules)_. Par défaut : `[] (tableau vide)`.
-   `hide_title` - Masquer le titre _(boolean)_ Par défaut `faux`.
-   `ligne_height` - Définit la hauteur de la ligne entre le texte _(nombre)_. Par défaut `25`.
-   `masque la progression` - masque la barre de progression et le pourcentage _(booléen)_. Par défaut `faux`.
-   `custom_title` - Définit un titre personnalisé pour la carte _(chaîne)_. Default `Wakatime Stats`.
-   `layout` - Basculer entre deux mises en page disponibles `par défaut` & `compact`.  Par défaut `par défaut`.
-   `langs_count` - Limite le nombre de langues sur la carte, par défaut à toutes les langues signalées _(nombre)_.
-   `api_domain` - Définit un domaine API personnalisé pour la carte, par ex. pour utiliser des services comme [Hakatime](https://github.com/mujx/hakatime) ou [Wakapi](https://github.com/muety/wakapi) _(chaîne)_. Par défaut `API Waka`.
-   `range` – Demande une plage différente de votre WakaTime par défaut, par exemple `last_7_days`. Voir [la documentation de l'API WakaTime](https://wakatime.com/developers#stats) pour une liste des options disponibles. _(YYYY-MM, last_7_days, last_30_days, last_6_months, last_year, or all_time)_. Par défaut `all_time`.

* * *

# GitHub Extra Pins

Les épingles supplémentaires GitHub vous permettent d'épingler plus de 6 dépôts dans votre profil en utilisant un profil GitHub readme.

Et OUI ! Vous n'êtes plus limité à 6 dépôts épinglés.

### Usage

Copiez-collez ce code dans votre readme et modifiez les liens.

Extrémité: `api/pin?username=anuraghazra&repo=github-readme-stats`

```md
<code>bg_color</code> - Couleur du fond de la carte <em x-id="4">(hex color)</em> <strong x-id="1">ou</strong> un gradiant de la forme <em x-id="4">angle,start,end</em>
```
 - Couleur du fond de la carte _(hex color)_ **ou** un gradiant de la forme _angle,start,end_
</code>

### Démo

[![Carte Readme](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)

Utiliser la variable [show_owner](#customization) pour inclure le nom d'utilisateur du propriétaire du dépôt.

[![Carte Readme](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats&show_owner=true)](https://github.com/anuraghazra/github-readme-stats)

# Carte des langues les plus populaires

La carte des langages principaux montre les langages les plus utilisés par les utilisateurs de GitHub.

> **Remarque** Les langues principales n'indiquent pas mon niveau de compétence ou quoi que ce soit de ce genre ; il s'agit d'une métrique GitHub pour déterminer quelles langues ont le plus de code sur GitHub. C'est une nouvelle fonctionnalité de github-readme-stats.

### Usage

Copiez-collez ce code dans votre readme et modifiez les liens.

Extrémité: `api/top-langs?username=anuraghazra`

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

### Exclure les dépôts individuels

Vous pouvez utiliser le paramètre `&exclude_repo=repo1,repo2` pour exclure les dépôts individuels.

```md
<code>count_private</code> - Compter les commits privés <em x-id="4">(boolean)</em>
```
 - Compter les commits privés _(boolean)_
</code>

### Cacher certaines langages

Vous pouvez utiliser le paramètre `?hide=language1,language2` pour masquer les langages individuels.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&hide=javascript,html)](https://github.com/anuraghazra/github-readme-stats)
```

### Afficher plus de langues

Vous pouvez utiliser l'option `&langs_count=` pour augmenter ou diminuer le nombre de langues affichées sur la carte. Les valeurs valides sont des entiers compris entre 1 et 10 (inclus), et la valeur par défaut est 5.

```md
<code>line_height</code> - Fixer la hauteur de la ligne entre les textes <em x-id="4">(number)</em>
```
 - Fixer la hauteur de la ligne entre les textes _(number)_
</code>

### Carte compacte des langages

Vous pouvez utiliser l'option `&layout=compact` pour changer le style de la carte.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
```

### Démo

[![Meilleurs langages](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   Forkez ce dépôt

[![Meilleurs langages](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

# Statistiques de la semaine Wakatime

`theme` - Nom du thème, parmis [tous les thèmes disponibles](../themes/README.md)

```md
:warning: <strong x-id="1">Important:</strong>
  Les noms des langages doivent être en format uri, comme spécifié dans <a href="https://fr.wikipedia.org/wiki/Percent-encoding">Percent Encoding</a>
  (c'est-à-dire que: <code>c++</code> devrait devenir <code>c%2B%2B</code>, <code>jupyter notebook</code> devrait devenir <code>jupyter%20notebook</code>, etc.)
```
 devrait devenir c%2B%2B, jupyter notebook devrait devenir jupyter%20notebook, etc.)
</code>

> **Note**: Veuillez noter que nous ne montrons actuellement que les données des profils Wakatime qui sont publics.

### Défaut

[![stats wakatime de willianrod](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

[![stats wakatime de willianrod](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&hide_progress=true)](https://github.com/anuraghazra/github-readme-stats)

-   Carte compacte

[![stats wakatime de willianrod](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

* * *

### Toutes les démos

-   Par défaut

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)

-   Ne pas afficher des stats spécifiques

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,issues)

-   Afficher les icônes

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=issues&show_icons=true)

-   Personnaliser la couleur de la bordure

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&border_color=2e4058)

-   Inclure tous les commits

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&include_all_commits=true)

-   Thèmes

Choisissez parmi l'un des [thèmes par défaut](#themes)

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)

-   Dégradé

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

-   Personnaliser la carte des stats

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)

-   `card_width` - Fixer la largeur de la carte manuellement _(number)_

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&locale=es)

-   Personnaliser la carte dépôt

![Carte personnalisée](https://github-readme-stats.vercel.app/api/pin?username=anuraghazra&repo=github-readme-stats&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)

-   Langues principales

[![Meilleurs langages](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   Carte WakaTime

[![stats wakatime de willianrod](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

* * *

### Conseil rapide (aligner les cartes des dépôts)

En général, vous ne pourrez pas mettre les images côte à côte. Pour ce faire, vous pouvez utiliser cette approche :

```html
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=convoychat" />
</a>
```

## Déployer sur votre propre instance Vercel

#### Check Out Step By Step Video Tutorial By @codeSTACKr

> **Avertissement** Si vous êtes sur le passe-temps [(i.e. libre)](https://vercel.com/pricing) Plan Vercel, assurez-vous de changer le paramètre `maxDuration` dans le vercel [. fichier fils](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json) de `30` à `10` (voir [#1416](https://github.com/anuraghazra/github-readme-stats/issues/1416#issuecomment-950275476) pour plus d'informations).

Comme l'API GitHub ne permet que 5k requêtes par heure, il est possible que mon `https://github-readme-stats.vercel.app/api` puisse atteindre le limiteur de débit. Si vous l'hébergez sur votre propre serveur Vercel, alors vous n'avez pas à vous soucier de quoi que ce soit. Cliquez sur le bouton de déploiement pour commencer !

> NOTE: Depuis [#58](https://github.com/anuraghazra/github-readme-stats/pull/58) nous devrions être en mesure de traiter plus de 5 000 demandes et ne pas avoir de problèmes de temps d'arrêt :D

[![Deployer avec Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/anuraghazra/github-readme-stats)

<details>
 <summary><b>Guide étape par étape :hammer_and_wrench: sur la configuration de votre propre instance Vercel</b></summary>

1.  Allez sur [vercel.com](https://vercel.com/)
2.  Cliquez sur `Log in` ![](https://files.catbox.moe/pcxk33.png)
3.  Connectez-vous avec GitHub en cliquant `Continue with GitHub` ![](https://files.catbox.moe/b9oxey.png)
4.  Connectez-vous à GitHub et autorisez l'accès à tous les dépôts, si vous y êtes invité
5.  Fork this repo.
6.  Après avoir bifurqué le dépôt, ouvrez le fichier [`vercel.json`](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json#L5) et changez le champ `maxDuration` à `10`.
7.  Retournez au [dashboard Vercel](https://vercel.com/dashboard)
8.  Sélectionnez `Import Project` ![](https://files.catbox.moe/3n76fh.png)
9.  Cliquez sur le bouton `Continuer avec GitHub` , recherchez le dépôt Git requis et importez-le en cliquant sur le bouton `Importer`. Vous pouvez également importer un dépôt Git tiers en utilisant le lien `Importer le dépôt Git tiers ->` en bas de la page. ![](https://files.catbox.moe/mg5p04.png)
10. Créez un jeton d'accès personnel (PAT) [ici](https://github.com/settings/tokens/new) et activez les permissions `dépôt` (cela permet d'accéder aux statistiques du dépôt privé).
11. Ajoute le PAT comme une variable d'environnement nommée `PAT_1` (comme indiqué). ![](https://files.catbox.moe/0yclio.png)
12. Cliquez sur "Deploy" et vous êtes prêt à partir. Regardez vos domaines pour utiliser l'API !

</details>

### Gardez votre fork à jour

Vous pouvez garder votre fork, et donc votre instance privée Vercel à jour avec le flux amont en utilisant le [bouton Sync Fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) de GitHubs. Vous pouvez également utiliser le package [pull](https://github.com/wei/pull) créé par [@wei](https://github.com/wei) pour automatiser ce processus.

## :sparkling_heart: Supporter le project

Je mets open-source presque tout ce que je peux, et j'essaie de répondre à tous ceux qui ont besoin d'aide en utilisant ces projets. Évidemment, cela prend du temps. Vous pouvez utiliser ce service gratuitement.

Cependant, si vous utilisez ce projet et que vous en êtes satisfait ou si vous voulez simplement m'encourager à continuer à créer, il y a quelques façons de le faire :-

-   Donner un crédit approprié lorsque vous utilisez github-readme-stats sur votre readme, avec un lien vers celui-ci :D
-   Mettre une étoile et partager le projet :rocket:
-   [![paypal.me/anuraghazra](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/anuraghazra) - Vous pouvez faire des dons uniques via PayPal. Je vais probablement acheter un ~~café~~ thé. :tea:

Merci ! :heart:

* * *

[![https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss](./powered-by-vercel.svg)](https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss)

Les contributions sont les bienvenues ! <3

Fait avec :heart: et JavaScript.
