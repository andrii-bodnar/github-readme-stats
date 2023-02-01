<p align="center">
 <img width="100px" src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">Readme'lerinizde dinamik olarak oluşturulmuş GitHub istatistikleri alın!</p>
</p>
  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats/actions">
      <img alt="Tests Passing" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/graphs/contributors">
      <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/anuraghazra/github-readme-stats" />
    </a>
    <a href="https://codecov.io/gh/anuraghazra/github-readme-stats">
      <img src="https://codecov.io/gh/anuraghazra/github-readme-stats/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/anuraghazra/github-readme-stats?color=0088ff" />
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
    <a href="#demo">Demo</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Hata İlet</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Özellik Talep Et</a>
  </p>
  <p align="center">
    <a href="/docs/readme_fr.md">Français </a>
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
    .
    <a href="/docs/readme_tr.md">Türkçe</a>
  </p>
</p>

<p align="center">Projeyi sevdiniz mi? Daha da gelişmesi için lütfen <a href="https://www.paypal.me/anuraghazra">bağış</a> yapın!</p>

<a href="https://indiafightscorona.giveindia.org">
  <img src="https://indiaspora.org/wp-content/uploads/2021/04/give-India-logo.png" alt="Give india logo" width="200" />
</a>

Are you considering supporting the project by donating? Please DO NOT!!

Instead, Help India fight the second deadly wave of COVID-19. Thousands of people are dying in India because of a lack of Oxygen & also COVID-related infrastructure.

Visit <https://indiafightscorona.giveindia.org> and make a small donation to help us fight COVID and overcome this crisis. A small donation goes a long way. :heart:

</p>

# Features

-   [GitHub İstatistikler Kartı](#github-stats-card)
-   [GitHub Ekstra Pinler](#github-extra-pins)
-   [En Çok Kullanılan Diller](#top-languages-card)
-   [Wakatime Haftalık İstatistikler](#wakatime-week-stats)
-   [Temalar](#themes)
    -   [Responsive Card Theme](#responsive-card-theme)
-   [Özelleştirmeler](#customization)
    -   [Common Options](#common-options)
    -   [İstatistik Karları Exclusive Özellikler:](#stats-card-exclusive-options)
    -   [Belirli Repoları Çıkartın](#repo-card-exclusive-options)
    -   [Belirli Dilleri Çıkartın](#language-card-exclusive-options)
    -   [`custom_title` - Kart için istediğiniz bir başlığı belirler](#wakatime-card-exclusive-options)
-   [Deploy Yourself](#deploy-on-your-own-vercel-instance)
    -   [Keep your fork up to date](#keep-your-fork-up-to-date)

# GitHub İstatistikler Kartı

Copy-paste this into your markdown content, and that is it. Çok basit!

`?username=` değerini kendi GitHub kullanıcı adınız ile değiştirin.

```md
[![Anurag'nın GitHub İstatistikleri](https://github-readme-stats.vercel.app/api?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

> Not: Şu sıralamalar mevcut: S+ (en üst 1%), S (en üst 25%), A++ (en üst 45%), A+ (en üst 60%), and B+ (herkes). Buradaki değerler [cumulative distribution function](https://en.wikipedia.org/wiki/Cumulative_distribution_function) ile hesaplanırken; commitler, katkılar, hatalar, yıldızlar, çekme istekleri, takipçiler ve sahip olunan depolar (repository) göz önünde bulundurulamaktadır. Uygulamanın yapısı [src/calculateRank.js](./src/calculateRank.js)'te daha detaylı incelenebilir.

### Hiding individual stats

`hide` - Belirli bir dili listede gizler _(Virgül ile ayırılmış değerlerle)_

> Örnek: `&hide=stars,commits,prs,issues,contribs`

```md
![mustafacagri's github stats](https://github-readme-stats.vercel.app/api?username=mustafacagri&hide=contribs,prs)
```

### Özel Katkı Sayısını Toplam Commit Sayısına Ekleme

Özel (private) olarak geliştirdiğiniz depolardaki commit sayınızı toplam commit sayınız içerisinde göstermek istiyorsanız `?count_private=true` parametresini gönderebilirsiniz.

> **Note** If you are deploying this project yourself, the private contributions will be counted by default. If you are using the public Vercel instance, you need to choose to [share your private contributions](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/managing-contribution-settings-on-your-profile/showing-your-private-contributions-and-achievements-on-your-profile).

> Örnek: `&count_private=true`

```md
![mustafacagri's github stats](https://github-readme-stats.vercel.app/api?username=mustafacagri&count_private=true)
```

### İkonları Göstermek

Eğer ikonları göstermek istiyorsanız, `show_icons=true` parametresini göndermeniz gerekmektedir. Örnek olarak:

```md
![mustafacagri's github stats](https://github-readme-stats.vercel.app/api?username=mustafacagri&show_icons=true)
```

### Temalar

Dahili olarak gelen temalarla, herhangi bir [manuel özelleştirme](#özelleştirmeler) yapmadan kartın görünümünü özelleştirebilirsiniz.

`?theme=THEME_NAME` parametresini kullanabilirsiniz:

```md
![mustafacagri's github stats](https://github-readme-stats.vercel.app/api?username=mustafacagri&show_icons=true&theme=radical)
```

#### Tüm Dahili Temalar :-

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stat Temaları" width="600px" />

Önizleme yapmak için şuralara göz atabilirsiniz: [tüm dahili temalar](./themes/README.md) veya [tema ayar dosyası](./themes/index.js) & **ayrıca siz de yeni bir tema oluşturarak katkı sağlayabilirsiniz** elbette isterseniz :D

#### Responsive Card Theme

[![En çok kullanılan diller](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![<code>Import Git Repository</code>'yi seçin.](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

Since GitHub will re-upload the cards and serve them from their [CDN](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-anonymized-urls), we can not infer the browser/GitHub theme on the server side. There are, however, four methods you can use to create dynamics themes on the client side.

##### Use the transparent theme

We have included a `transparent` theme that has a transparent background. This theme is optimized to look good on GitHub's dark and light default themes. You can enable this theme using the `&theme=transparent` parameter like so:

```md
<code>show_owner</code> - <em x-id="4">(boolean)</em> Reponun sahibinin ismini gösterir
```
 - _(boolean)_ Reponun sahibinin ismini gösterir
</code>

<details>
<summary>:eyes: Show example</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=transparent)

</details>

##### Add transparent alpha channel to a themes bg_color

You can use the `bg_color` parameter to make any of [the available themes](./themes/README.md) transparent. This is done by setting the `bg_color` to a colour with a transparent alpha channel (i.e. `bg_color=00000000`):

```md
[![ReadMe Kartı](https://github-readme-stats.vercel.app/api/pin/?username=mustafacagri&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)
```

<details>
<summary>:eyes: Show example</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)

</details>

##### `theme` - Temanın rengi [tüm temalar](./themes/README.md)

You can use [GitHub's theme context](https://github.blog/changelog/2021-11-24-specify-theme-context-for-images-in-markdown/) tags to switch the theme based on the user GitHub theme automatically. This is done by appending `#gh-dark-mode-only` or `#gh-light-mode-only` to the end of an image URL. This tag will define whether the image specified in the markdown is only shown to viewers using a light or a dark GitHub theme:

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mustafacagri)](https://github.com/anuraghazra/github-readme-stats)
```

<details>
<summary>:eyes: Show example</summary>

[![<code>include_all_commits</code> - <em x-id="4">(boolean)</em> Sadece bu yılın değil tüm zamanlarda yaptığınız commit sayısını gösterir](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![En Çok Kullanılan Diller](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

</details>

##### Use GitHub's new media feature

You can use [GitHub's new media feature](https://github.blog/changelog/2022-05-19-specify-theme-context-for-images-in-markdown-beta/) in HTML to specify whether to display images for light or dark themes. This is done using the HTML `<picture>` element in combination with the `prefers-color-scheme` media feature.

```html
<code>title_color</code> - Kart başlığı rengi <em x-id="4">(hex color / hex rengi)</em>
```
 - Kart başlığı rengi _(hex color / hex rengi)_
</code>

<details>
<summary>:eyes: Show example</summary>

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

### Özelleştirmeler

`Stats Card` ya da `Repo Card` görüntünüzü istediğiniz gibi şu parametreler ile değiştirebilirsiniz:

#### Common Options

-   `title_color` - Card's title color _(hex color)_. Default: `2f80ed`.
-   `text_color` - Body text color _(hex color)_. Default: `434d58`.
-   `icon_color` - Icons color if available _(hex color)_. Default: `4c71f2`.
-   `border_color` - Card's border color _(hex color)_. Default: `e4e2e2` (Does not apply when `hide_border` is enabled).
-   `bg_color` - Card's background color _(hex color)_ **or** a gradient in the form of _angle,start,end_. Default: `fffefe`
-   `hide_border` - Hides the card's border _(boolean)_. Default: `false`
-   `theme` - name of the theme, choose from [all available themes](./themes/README.md). Default: `default` theme.
-   `cache_seconds` - set the cache header manually _(min: 14400, max: 86400)_. Default: `14400 seconds (4 hours)`.
-   `locale` - set the language in the card _(e.g. cn, de, es, etc.)_. Default: `en`.
-   `border_radius` - Corner rounding on the card. Default: `4.5`.

> **Warning** We use caching to decrease the load on our servers (see <https://github.com/anuraghazra/github-readme-stats/issues/1471#issuecomment-1271551425>). Cache Hakkında: Repo kartında fork ve yıldız sayısı 1.000'den küçükse varsayılan cache süresi 4 saat yani 14400 saniyedir. Ayrıca, önbelleğin minimum 2 ve maksimum 24 saate sabitlendiğini unutmayın.

##### bg_color'da Gradient

bg_color içerisinde birden fazla rengi gradient olarak göstermek için virgülle ayırarak kullanabilirsiniz. Gradient kullanımı için örnek format:

    &bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10

#### Yaygın Seçenekler:

-   `hide` - Spesifik özellikleri istatistiklerden gizleyebilirsiniz. _(Virgül ile ayırılmış değerlerle)_ Default: `[] (blank array)`.
-   `hide_title` - _(boolean)_ Default: `false`.
-   `card_width` - Set the card's width manually _(number)_. Default: `500px  (approx.)`.
-   `hide_rank` - _(boolean)_ Sıralamayı gizler ve kartın genişliğini otomatik olarak tekrar düzenler Default: `false`.
-   `show_icons` - _(boolean)_. Default: `false`.
-   `include_all_commits` - Count total commits instead of just the current year commits _(boolean)_. Default: `false`.
-   `count_private` - Count private commits _(boolean)_. Default: `false`.
-   `line_height` - Sets the line height between text _(number)_. Default: `25`.
-   `exclude_repo` - Exclude stars from specified repositories _(Comma-separated values)_. Default: `[] (blank array)`.
-   `custom_title` - Kart için istediğiniz bir başlığı belirler Default:  `<username> GitHub Stats`.
-   `text_bold` - Use bold text _(boolean)_. Default: `true`.
-   `disable_animations` - Disables all animations in the card _(boolean)_. Default: `false`.
-   `ring_color` - Color of the rank circle _(hex color)_. Defaults to the theme ring color if it exists and otherwise the title color.

> **Note** When hide_rank=`true`, the minimum card width is 270 px + the title length and padding.

#### Repo Kartları Exclusive Özellikler:

-   `show_owner` - Show the repo's owner name _(boolean)_. Default: `false`.

#### Dil Kartları Exclusive Özellikler:

-   `hide` - Hide the languages specified from the card _(Comma-separated values)_. Default: `[] (blank array)`.
-   `hide_title` - _(boolean)_ Default: `false`.
-   `layout` - Switch between two available layouts `default` & `compact`. Default: `default`.
-   `card_width` - Kartın genişliğini manuel olarak belirler _(number)_ Default `300`.
-   `langs_count` - 1-10 arasında istediğiniz kadar dil gösterebilirsiniz. Varsayılan: 5 _(number)_
-   `exclude_repo` - Belirli repoları listeden çıkartır _(Virgül ile ayırılmış değerlerle)_ Default: `[] (blank array)`.
-   `custom_title` - Sets a custom title for the card _(string)_. Default `Most Used Languages`.
-   `disable_animations` - _(boolean)_ Kart içerisindeki tüm animasyonları kapatır Default: `false`.

> :warning: **Önemli:** Dİl isimleri [Percent Encoding](https://en.wikipedia.org/wiki/Percent-encoding)'te belirtildiği üzere uri-escaped olarak belirtilmelidir. (ör: `c++` yerine `c%2B%2B`, `jupyter notebook` yerine `jupyter%20notebook`, vb.) [urlencoder.org](https://www.urlencoder.org/) adresini kullanarak otomatik olarak değerleri bu şekle çevirebilirsiniz.

#### Wakatime Kart Exclusive Özellikler:

-   `hide` - Hide the languages specified from the card _(Comma-separated values)_. Default: `[] (blank array)`.
-   `hide_title` - _(boolean)_ Default `false`.
-   `line_height` - Sets the line height between text _(number)_. Default `25`.
-   `hide_progress` - Hides the progress bar and percentage _(boolean)_. Default `false`.
-   `custom_title` - Kart için istediğiniz bir başlığı belirler Default `Wakatime Stats`.
-   `layout` - Switch between two available layouts `default` & `compact`.  Default `default`.
-   `langs_count` - Limit the number of languages on the card, defaults to all reported languages _(number)_.
-   `api_domain` - Set a custom API domain for the card, e.g. to use services like [Hakatime](https://github.com/mujx/hakatime) or [Wakapi](https://github.com/muety/wakapi) _(string)_. Default `Waka API`.
-   `range` – Request a range different from your WakaTime default, e.g. `last_7_days`. See [WakaTime API docs](https://wakatime.com/developers#stats) for a list of available options. _(YYYY-MM, last_7_days, last_30_days, last_6_months, last_year, or all_time)_. Default `all_time`.

* * *

# GitHub Ekstra Pinler

GitHub ekstra pinler profilinize 6'dan fazla repoyu / depoyu profilinizde pinleyebilirsiniz.

Hey! Artık 6 pin ile kısıtlı kalmayacaksınız!

### Kullanım

Alttaki kodu kopyalayıp readme dosyanıza urlleri değiştirerek yapıştırın.

Endpoint: `api/pin?username=mustafacagri&repo=github-readme-stats`

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mustafacagri&langs_count=8)](https://github.com/anuraghazra/github-readme-stats)
```

### Demo

[![ReadMe Kartı](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)

[show_owner](#özelleştirmeler) ile reponun sahibini gösterebilirsiniz.

[![ReadMe Kartı](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats&show_owner=true)](https://github.com/anuraghazra/github-readme-stats)

# Kartın dilini seçin

En çok kullanılan diller kartı kullanıcının en çok kullandığı dilleri gösterir.

> **Note** Top Languages does not indicate my skill level or anything like that; it's a GitHub metric to determine which languages have the most code on GitHub. Ayrıca, github-readme-stats'ın yeni özelliğidir.

### Kullanım

Alttaki kodu kopyalayıp readme dosyanıza urlleri değiştirerek yapıştırın.

Endpoint: `api/top-langs?username=mustafacagri`

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mustafacagri&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
```

### Exclude individual repositories

`?exclude_repo=repo1,repo2` parametresini kullanarak istediğiniz repoları çıkartabilirsiniz.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&exclude_repo=github-readme-stats,anuraghazra.github.io)](https://github.com/anuraghazra/github-readme-stats)
```

### Hide individual languages

`?hide=language1,language2` parametresini kullanarak istediğiniz dilleri çıkartabilirsiniz.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mustafacagri&hide=javascript,html)](https://github.com/anuraghazra/github-readme-stats)
```

### Daha Fazla Dil Gösterin

`&langs_count=` parametresini kullanarak kartınızda gösterilen dil sayısını azaltabilir ya da artırabilirsiniz. Varsayılan değeri 5, kullanılabilir sayı aralığı ise 1-10'dur.

```md
https://github-readme-stats.vercel.app/api/top-langs/?username=mustafacagri
```

### Kompakt Dil Kartı Düzeni

`&layout=compact` parametresiyle kart tasarımınızı değiştirebilirsiniz.

```md
<code>line_height</code> - <em x-id="4">(number)</em> Satır arası yüksekliği belirler
```
 - _(number)_ Satır arası yüksekliği belirler
</code>

### Demo

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   Kompakt Düzen / Layout

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

# Wakatime Haftalık İstatistikler

`?username=` değerini [Wakatime](https://wakatime.com)'daki kullanıcı adınızla değiştirin.

```md
[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)
```

> **Note**: Please be aware that we currently only show data from Wakatime profiles that are public.

### Demo

[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&hide_progress=true)](https://github.com/anuraghazra/github-readme-stats)

-   Kompakt Düzen

[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

* * *

### Tüm Demolar

-   Varsayılan

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)

-   Belirli istatistikler gizli

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,issues)

-   İkonlar gösteriliyor

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=issues&show_icons=true)

-   Customize Border Color

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&border_color=2e4058)

-   Tüm commitler dahil

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&include_all_commits=true)

-   Temalar

[default themes](#themes) adresinden istediğiniz temayı seçin.

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)

-   Gradient

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

-   İstatistik Kartını Düzenleyin

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)

-   Setting card locale

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&locale=es)

-   Repo kartı düzenleyin

![Customized Card](https://github-readme-stats.vercel.app/api/pin?username=anuraghazra&repo=github-readme-stats&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)

-   Top languages

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   Wakatime kart

[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

* * *

### Hızlı İpucu (Repo Kartları Hizlayın)

Genellikle resimleri yan yana düzenleyemezsiniz. Bunu yapmak için şu yaklaşımı kullanabilirsiniz:

```html
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=convoychat" />
</a>
```

## Kendi Vercel Örneğinizde Yayınlayın

#### :film_projector: [Check Out Step By Step Video Tutorial By @codeSTACKr](https://youtu.be/n6d4KHSKqGk?t=107)

> **Warning** If you are on the [hobby (i.e. free)](https://vercel.com/pricing) Vercel plan, please make sure you change the `maxDuration` parameter in the [vercel.json](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json) file from `30` to `10` (see [#1416](https://github.com/anuraghazra/github-readme-stats/issues/1416#issuecomment-950275476) for more information).

GitHub API saatte sadece 5.000 isteğe izin verdiği için `https://github-readme-stats.vercel.app/api` adresindeki API'm bu limite muhtemelen takılmış olabilir. Eğer projeyi kendi Vercel sunucunuzda yayınlarsanız, böyle bir sorun yaşamayabilirsiniz. Deploy butonuna tıkla ve deploy başlasın!

> `cache_seconds` - Manuel olarak cache'i belirleyebilirsiniz _(en az: 1800, en fazla: 86400)_

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/anuraghazra/github-readme-stats)

<details>
 <summary><b>:hammer_and_wrench: Step-by-step guide on setting up your own Vercel instance</b></summary>

1.  [vercel.com](https://vercel.com/) adresine gidin
2.  `Log in`'e tıklayın ![](https://files.catbox.moe/pcxk33.png)
3.  `Continue with GitHub`'e basarak GitHub ile giriş yapın ![](https://files.catbox.moe/b9oxey.png)
4.  GitHub'a giriş yapın ve eğer çıkarsa tüm repolara izin verin.
5.  Bu repoyu fork'layın
6.  After forking the repo, open the [`vercel.json`](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json#L5) file and change the `maxDuration` field to `10`.
7.  [Vercel dashboard](https://vercel.com/dashboard)'unuza geri dönün.
8.  `Import Project`'i seçin. ![](https://files.catbox.moe/3n76fh.png)
9.  Click the `Continue with GitHub` button, search for the required Git Repository and import it by clicking the `Import` button. Alternatively, you can import a Third-Party Git Repository using the `Import Third-Party Git Repository ->` link at the bottom of the page. ![](https://files.catbox.moe/mg5p04.png)
10. Root'u seçin ve her şeyi olduğu gibi bırakın, [burada](https://github.com/settings/tokens/new) kolayca oluşturabileceğiniz kişisel bir erişim belirteci (personal access token) (PAT) içerecek olan PAT_1 adlı ortam değişkeninizi (gösterildiği gibi) ekleyin.
11. Add the PAT as an environment variable named `PAT_1` (as shown). ![](https://files.catbox.moe/0yclio.png)
12. Click deploy, and you're good to go. API'ı kullanmak için alanlarınızı (domainlerinizi) görün!

</details>

### Keep your fork up to date

You can keep your fork, and thus your private Vercel instance up to date with the upstream using GitHubs' [Sync Fork button](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork). You can also use the [pull](https://github.com/wei/pull) package created by [@wei](https://github.com/wei) to automate this process.

## :sparkling_heart: Projeyi Destekleyin

Neredeyse yapabildiğim her şeyi açık kaynak yapıyorum ve bu projeleri kullanırken yardıma ihtiyacı olan herkese cevap vermeye çalışıyorum. Açıkçası, bu zaman alıyor. Destekleriniz sayesinde bu hizmeti ücretsiz olarak kullanabilirsiniz.

Ayrıca, bu projeyi kullanıyor ve memnunsanız veya sadece bir şeyler yaratmaya devam etmem için beni teşvik etmek istiyorsanız, bunu yapmanın birkaç yolu var: -

-   Readme'nizde github-readme-stats'ı kullanırken bu projeye uygun bir link verebilirsiniz.
-   Projeye yıldız verebilir ve paylaşabilirsiniz :rocket:
-   [![paypal.me/anuraghazra](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/anuraghazra) - PayPal ile tek seferlik bağış yapabilirsiniz. Muhtemelen bir ~~kahve~~ ya da çay :tea: alacağım. :tea:

Teşekkürler! :heart:

* * *

[![https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss](./powered-by-vercel.svg)](https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss)

Contributions are welcome! &lt;3

:heart: ve JavaScript ile hazırlandı.
