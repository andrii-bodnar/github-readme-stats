<p align="center">
 <img width="100px" src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">동적으로 생성되는 GitHub 사용량 통계를 여러분의 README 에 추가해보세요!</p>
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
    <a href="#미리보기">미리보기 확인</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">버그 제보하기</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">기능 추가 요청하기</a>
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
    <a href="/docs/readme_tr.md">Türkçe</a>
  </p>
</p>

<p align="center">Love the project? 괜찮으시다면, 서비스 개선을 위해 <a href="https://www.paypal.me/anuraghazra">기부</a>를 고려해주세요!</p>

<a href="https://indiafightscorona.giveindia.org">
  <img src="https://indiaspora.org/wp-content/uploads/2021/04/give-India-logo.png" alt="Give india logo" width="200" />
</a>

Are you considering supporting the project by donating? Please DO NOT!!

Instead, Help India fight the second deadly wave of COVID-19. Thousands of people are dying in India because of a lack of Oxygen & also COVID-related infrastructure.

Visit <https://indiafightscorona.giveindia.org> and make a small donation to help us fight COVID and overcome this crisis. A small donation goes a long way. :heart:

</p>

# 기능들

-   [GitHub 통계](#github-stats-card)
-   [GitHub 저장소 핀](#github-extra-pins)
-   [Top Languages Card](#top-languages-card)
-   [Wakatime 주간 통계](#wakatime-week-stats)
-   [테마](#themes)
    -   [Responsive Card Theme](#responsive-card-theme)
-   [Customization](#customization)
    -   [Common Options](#common-options)
    -   [언어 사용량 통계 카드의 표시 제한 옵션:](#stats-card-exclusive-options)
    -   [Repo Card Exclusive Options](#repo-card-exclusive-options)
    -   [Language Card Exclusive Options](#language-card-exclusive-options)
    -   [저장소 카드의 표시 제한 옵션:](#wakatime-card-exclusive-options)
-   [Deploy Yourself](#deploy-on-your-own-vercel-instance)
    -   [Keep your fork up to date](#keep-your-fork-up-to-date)

# GitHub 통계

Copy-paste this into your markdown content, and that is it. Simple!

`?username=` 속성의 값을 GitHub 계정의 사용자 명(닉네임)으로 바꿔주세요.

```md
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

> **Note** Available ranks are S+ (top 1%), S (top 25%), A++ (top 45%), A+ (top 60%), and B+ (everyone). 커밋의 수(commits), 기여도(contribution), 이슈의 수(issues), 즐겨찾기(star), 작업내용 반영 요청(Pull Request), 팔로워 수, 그리고 보유 중인 저장소 등의 항목들에 대해 [누적 분포 함수](https://ko.wikipedia.org/wiki/%EB%88%84%EC%A0%81_%EB%B6%84%ED%8F%AC_%ED%95%A8%EC%88%98) 를 이용해 계산됩니다. The implementation can be investigated at [src/calculateRank.js](./src/calculateRank.js).

### 개별 통계 숨기기

`hide` - 통계에서 특정한 값 제외 _(Comma-separated values)_

> 사용 가능한 항목들: `&hide=stars,commits,prs,issues,contribs`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,prs)
```

### 총 커밋 수에 비공개 기여도 (private contribs) 수 추가하기

You can add the count of all your private contributions to the total commits count by using the query parameter `&count_private=true`.

> **Note** If you are deploying this project yourself, the private contributions will be counted by default. If you are using the public Vercel instance, you need to choose to [share your private contributions](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/managing-contribution-settings-on-your-profile/showing-your-private-contributions-and-achievements-on-your-profile).

> 예시: `&count_private=true`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&count_private=true)
```

### 아이콘 표시하기

아이콘 항목을 활성화 하기 위해선, 다음과 같이 `show_icons=true` 속성을 추가해주세요.

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true)
```

### 테마 설정하기

원하신다면 [테마 설정하기](../themes/index.js) 항목에서  **새로운 테마를 직접 만드실수 있어요.** :D

다음과 같이 `?theme=THEME_NAME` 속성을 이용해주세요.

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
```

#### 지원하는 내장 테마 목록

내장 테마를 사용하시면, 별도의 [커스터마이징](#커스터마이징) 없이 GitHub 통계 카드를 꾸미실 수 있어요.

<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stat Themes" width="600px" />

[사용 가능한 모든 테마](../themes/README.md) 에서 미리보기를 확인하실 수 있어요.

#### Responsive Card Theme

[![Anurag 님의 GitHub 사용량 통계](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![GitHub 저장소 핀 카드](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

Since GitHub will re-upload the cards and serve them from their [CDN](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-anonymized-urls), we can not infer the browser/GitHub theme on the server side. There are, however, four methods you can use to create dynamics themes on the client side.

##### Use the transparent theme

We have included a `transparent` theme that has a transparent background. This theme is optimized to look good on GitHub's dark and light default themes. You can enable this theme using the `&theme=transparent` parameter like so:

```md
<code>?count_private=true</code> 속성을 추가하시면, 여러분의 모든 비공개 기여도까지 반영됩니다.
```
 속성을 추가하시면, 여러분의 모든 비공개 기여도까지 반영됩니다.
</code>

<details>
<summary>:eyes: Show example</summary>

![Anurag 님의 GitHub 사용량 통계](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=transparent)

</details>

##### Add transparent alpha channel to a themes bg_color

You can use the `bg_color` parameter to make any of [the available themes](./themes/README.md) transparent. This is done by setting the `bg_color` to a colour with a transparent alpha channel (i.e. `bg_color=00000000`):

```md
<a href="../src/calculateRank.js">src/calculateRank.js</a> 에서 수행되는 계산 작업의 내용을 확인할 수 있습니다.
```

<details>
<summary>:eyes: Show example</summary>

![Anurag 님의 GitHub 사용량 통계](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)

</details>

##### `theme` - 테마의 이름, [사용 가능한 모든 테마](../themes/README.md) 에서 선택

You can use [GitHub's theme context](https://github.blog/changelog/2021-11-24-specify-theme-context-for-images-in-markdown/) tags to switch the theme based on the user GitHub theme automatically. This is done by appending `#gh-dark-mode-only` or `#gh-light-mode-only` to the end of an image URL. This tag will define whether the image specified in the markdown is only shown to viewers using a light or a dark GitHub theme:

```md
<code>Import Git Repository</code> 항목 선택!
```
 항목 선택!
</code>

<details>
<summary>:eyes: Show example</summary>

[![Anurag 님의 GitHub 저장소 핀](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![GitHub 저장소 핀 카드](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

</details>

##### Use GitHub's new media feature

You can use [GitHub's new media feature](https://github.blog/changelog/2022-05-19-specify-theme-context-for-images-in-markdown-beta/) in HTML to specify whether to display images for light or dark themes. This is done using the HTML `<picture>` element in combination with the `prefers-color-scheme` media feature.

```html
<code>icon_color</code> - 아이콘 색상 (활성화된 경우) <em x-id="4">(hex color)</em>
```
 - 아이콘 색상 (활성화된 경우) _(hex color)_
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

### Customization

여러가지 추가 속성을 통해, 원하는대로 `Stats Card` 또는 `Repo Card` 모양을 커스터마이징할 수 있어요.

#### Common Options

-   `title_color` - 카드 타이틀 색상 _(hex color)_ Default: `2f80ed`.
-   `text_color` - Body text color _(hex color)_. Default: `434d58`.
-   `icon_color` - Icons color if available _(hex color)_. Default: `4c71f2`.
-   `border_color` - Card's border color _(hex color)_. Default: `e4e2e2` (Does not apply when `hide_border` is enabled).
-   `bg_color` - 카드의 배경 색상 _(hex color)_ **혹은** 다음 양식으로 그라데이션 주기 _angle,start,end_ Default: `fffefe`
-   `hide_border` - Hides the card's border _(boolean)_. Default: `false`
-   `theme` - name of the theme, choose from [all available themes](./themes/README.md). Default: `default` theme.
-   `cache_seconds` - 수동으로 캐시 헤더 설정 _(min: 1800, max: 86400)_ Default: `14400 seconds (4 hours)`.
-   `locale` - 카드에 표시할 언어 _(e.g. kr, cn, de, es, etc.)_
-   `border_radius` - Corner rounding on the card. Default: `4.5`.

> **Warning** We use caching to decrease the load on our servers (see <https://github.com/anuraghazra/github-readme-stats/issues/1471#issuecomment-1271551425>). Our cards have a default cache of 4 hours (14400 seconds). Also, note that the cache is clamped to a minimum of 4 hours and a maximum of 24 hours.

##### Gradient in bg_color

You can provide multiple comma-separated values in the bg_color option to render a gradient with the following format:

    &bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10

#### 통계 카드의 표시 제한 옵션:

-   `hide` - Hides the [specified items](#hiding-individual-stats) from stats _(Comma-separated values)_. Default: `[] (blank array)`.
-   `hide_title` - _(boolean)_. Default: `false`.
-   `card_width` - Set the card's width manually _(number)_. Default: `500px  (approx.)`.
-   `hide_rank` - _(boolean)_ hides the rank and automatically resizes the card width. Default: `false`.
-   `hide_title` - 타이틀 표시 여부 _(boolean)_ Default: `false`.
-   `include_all_commits` - 올해가 아닌 전체 연도에 대한 커밋 포함 여부 _(boolean)_ Default: `false`.
-   `count_private` - Count private commits _(boolean)_. Default: `false`.
-   `line_height` - 텍스트 간 줄 높이 설정(자간) _(number)_ Default: `25`.
-   `exclude_repo` - Exclude stars from specified repositories _(Comma-separated values)_. Default: `[] (blank array)`.
-   `custom_title` - 카드의 타이틀 값 설정 Default:  `<username> GitHub Stats`.
-   `text_bold` - Use bold text _(boolean)_. Default: `true`.
-   `disable_animations` - Disables all animations in the card _(boolean)_. Default: `false`.
-   `ring_color` - Color of the rank circle _(hex color)_. Defaults to the theme ring color if it exists and otherwise the title color.

> **Note** When hide_rank=`true`, the minimum card width is 270 px + the title length and padding.

#### Repo Card Exclusive Options

-   `show_owner` - 저장소 소유자 닉네임 표기 여부 _(boolean)_ Default: `false`.

#### Language Card Exclusive Options

-   `hide` - Hide the languages specified from the card _(Comma-separated values)_. Default: `[] (blank array)`.
-   `hide_title` - 타이틀 제외 _(boolean)_ Default: `false`.
-   `layout` - 사용 가능한 두 가지 값, `default` & `compact` 중 표시 형태 선택 Default: `default`.
-   `card_width` - 카드 너비 직접 설정 _(number)_ Default `300`.
-   `langs_count` - Show more languages on the card, between 1-10 _(number)_. Default `5`.
-   `exclude_repo` - Exclude specified repositories _(Comma-separated values)_. Default: `[] (blank array)`.
-   `custom_title` - 카드의 타이틀 값 설정 Default `Most Used Languages`.
-   `disable_animations` - 카드의 모든 에니메이션 활성 여부 _(boolean)_ Default: `false`.

> 언어의 이름은 [퍼센트 인코딩](https://ko.wikipedia.org/wiki/%ED%8D%BC%EC%84%BC%ED%8A%B8_%EC%9D%B8%EC%BD%94%EB%94%A9) 에 지정된 URI 방식으로 표기되어야 합니다. ( 예를 들면, `c++` 는 `c%2B%2B`, `jupyter notebook` 는 `jupyter%20notebook`, 등등. ) [urlencoder.org](https://www.urlencoder.org/) < 서비스를 이용하면 자동으로 생성할 수 있습니다.

#### Wakatime 카드의 표시 제한 옵션:

-   `hide` - 카드에서 특정 언어 제외 _(Comma-separated values)_ Default: `[] (blank array)`.
-   `hide_title` - 타이틀 제외 _(boolean)_ Default `false`.
-   `line_height` - 텍스트 간 줄 높이 설정(자간) _(number)_ Default `25`.
-   `hide_progress` - Hides the progress bar and percentage _(boolean)_. Default `false`.
-   `custom_title` - 카드의 타이틀 값 설정 Default `Wakatime Stats`.
-   `layout` - 사용 가능한 두 가지 값, `default` & `compact` 중 표시 형태 선택  Default `default`.
-   `langs_count` - 카드에 표시할 언어의 수 (1-10 사이, 기본 값 : 5) _(number)_
-   `api_domain` - Set a custom API domain for the card, e.g. to use services like [Hakatime](https://github.com/mujx/hakatime) or [Wakapi](https://github.com/muety/wakapi) _(string)_. Default `Waka API`.
-   `range` – Request a range different from your WakaTime default, e.g. `last_7_days`. See [WakaTime API docs](https://wakatime.com/developers#stats) for a list of available options. _(YYYY-MM, last_7_days, last_30_days, last_6_months, last_year, or all_time)_. Default `all_time`.

* * *

# GitHub 저장소 핀

GitHub 저장소 여분 핀을 이용하면, 6개 이상의 저장소 핀을 여러분의 프로필에 추가할 수 있어요.

맞아요! You are no longer limited to 6 pinned repositories.

### 사용법

이 코드를 복사해서 여러분의 README 에 넣고 링크를 변경해주세요.

엔드 포인트: `api/pin?username=anuraghazra&repo=github-readme-stats`

```md
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)
```

### Demo

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)

Use [show_owner](#customization) variable to include the repo's owner username

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats&show_owner=true)](https://github.com/anuraghazra/github-readme-stats)

# Top Languages Card

언어 사용량 통계 카드는 GitHub 사용자가 가장 많이 사용한 언어가 표시됩니다.

> **Note** Top Languages does not indicate my skill level or anything like that; it's a GitHub metric to determine which languages have the most code on GitHub. It is a new feature of github-readme-stats.

### 사용법

이 코드를 복사해서 여러분의 README 에 넣고 링크를 변경해주세요.

엔드 포인트: `api/top-langs?username=anuraghazra`

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

### Exclude individual repositories

`?exclude_repo=repo1,repo2` 속성을 통해 특정 저장소를 제외할 수 있어요.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&exclude_repo=github-readme-stats,anuraghazra.github.io)](https://github.com/anuraghazra/github-readme-stats)
```

### Hide individual languages

`?hide=language1,language2` 속성을 통해 특정 언어를 제외할 수 있어요.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&hide=javascript,html)](https://github.com/anuraghazra/github-readme-stats)
```

### 표시할 언어 수 지정하기

`&langs_count=` 속성을 통해 카드에 표시할 언어의 수를 지정할 수 있어요. (1-10 사이, 기본 값 : 5)

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&langs_count=8)](https://github.com/anuraghazra/github-readme-stats)
```

### 컴택트한 카드 레이아웃 설정하기

`&layout=compact` 속성을 통해 카드의 디자인을 변경할 수 있어요.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
```

### Demo

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   컴팩트한 레이아웃

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

# Wakatime 주간 통계

`?username=` 속성의 값을 [Wakatime](https://wakatime.com) 계정의 사용자 명(닉네임)으로 바꿔주세요.

```md
[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)
```

> **Note**: Please be aware that we currently only show data from Wakatime profiles that are public.

### Demo

[![willianrod 님의 wakatime 통계](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

[![willianrod 님의 wakatime 통계](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&hide_progress=true)](https://github.com/anuraghazra/github-readme-stats)

-   컴팩트한 레이아웃

[![willianrod 님의 Wakatime 카드](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

* * *

### All Demos

-   기본

![언어 사용량 통계](https://github-readme-stats.vercel.app/api?username=anuraghazra)

-   특정 통계 내용 숨김

![Anurag 님의 GitHub 사용량 통계](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,issues)

-   아이콘 표시

![Anurag 님의 GitHub 사용량 통계](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=issues&show_icons=true)

-   Customize Border Color

![Anurag 님의 GitHub 사용량 통계](https://github-readme-stats.vercel.app/api?username=anuraghazra&border_color=2e4058)

-   전체 커밋 포함 시

![언어 사용량 통계](https://github-readme-stats.vercel.app/api?username=anuraghazra&include_all_commits=true)

-   테마들

[내장 테마](#themes) 에서 직접 선택해보세요

![언어 사용량 통계](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)

-   그라데이션 주기

![Anurag 님의 GitHub 사용량 통계](https://github-readme-stats.vercel.app/api?username=anuraghazra&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

-   통계 카드 커스터마이징하기

![Anurag 님의 GitHub 사용량 통계](https://github-readme-stats.vercel.app/api/?username=anuraghazra&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)

-   Setting card locale

![언어 사용량 통계](https://github-readme-stats.vercel.app/api/?username=anuraghazra&locale=es)

-   Customizing repo card

![Customized Card](https://github-readme-stats.vercel.app/api/pin?username=anuraghazra&repo=github-readme-stats&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)

-   Top languages

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   Wakatime 카드

[![willianrod 님의 wakatime 통계](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

* * *

### Quick Tip (Align The Repo Cards)

By default, GitHub does not lay out the cards side by side. To do that, you can use this approach:

```html
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=convoychat" />
</a>
```

## 나만의 Vercel 인스턴스에 직접 배포하기

#### :film_projector: [Check Out Step By Step Video Tutorial By @codeSTACKr](https://youtu.be/n6d4KHSKqGk?t=107)

> **Warning** If you are on the [hobby (i.e. free)](https://vercel.com/pricing) Vercel plan, please make sure you change the `maxDuration` parameter in the [vercel.json](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json) file from `30` to `10` (see [#1416](https://github.com/anuraghazra/github-readme-stats/issues/1416#issuecomment-950275476) for more information).

Since the GitHub API only allows 5k requests per hour, my `https://github-readme-stats.vercel.app/api` could possibly hit the rate limiter. 만약, 여러분이 Vercel server 에서 직접 호스트 하신다면, 걱정하실 일은 없을거에요. Click on the deploy button to get started!

> 참고: [#58](https://github.com/anuraghazra/github-readme-stats/pull/58) 풀 리퀘스트 이후로, 저희는 5,000 개 이상의 요청을 처리할 수 있게 됐어요. 더이상 서버 다운에 대한 걱정은 노놉! :D

[![Vercel 에 배포하기](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/anuraghazra/github-readme-stats)

<details>
 <summary><b>:hammer_and_wrench: Step-by-step guide on setting up your own Vercel instance</b></summary>

1.  [vercel.com](https://vercel.com/) 으로 이동하기
2.  `Log in` 버튼 클릭! ![](https://files.catbox.moe/pcxk33.png)
3.  `Continue with GitHub` 버튼을 이용해 GitHub 계정으로 가입하기 ![](https://files.catbox.moe/b9oxey.png)
4.  GitHub 에 로그인한 뒤, (권한을 요청한다면) 모든 저장소에 대한 권한을 허용해주세요!
5.  Fork this repo.
6.  After forking the repo, open the [`vercel.json`](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json#L5) file and change the `maxDuration` field to `10`.
7.  [Vercel 대시보드](https://vercel.com/dashboard) 로 돌아가세요!
8.  `Import Project` 항목 선택! ![](https://files.catbox.moe/3n76fh.png)
9.  Click the `Continue with GitHub` button, search for the required Git Repository and import it by clicking the `Import` button. Alternatively, you can import a Third-Party Git Repository using the `Import Third-Party Git Repository ->` link at the bottom of the page. ![](https://files.catbox.moe/mg5p04.png)
10. Create a personal access token (PAT) [here](https://github.com/settings/tokens/new) and enable the `repo` permissions (this allows access to see private repo stats).
11. Add the PAT as an environment variable named `PAT_1` (as shown). ![](https://files.catbox.moe/0yclio.png)
12. 마지막으로 'Deploy' 버튼을 클릭하면, 끝! => API 를 사용하기 위한 도메인 주소를 확인하세요!

</details>

### Keep your fork up to date

You can keep your fork, and thus your private Vercel instance up to date with the upstream using GitHubs' [Sync Fork button](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork). You can also use the [pull](https://github.com/wei/pull) package created by [@wei](https://github.com/wei) to automate this process.

## :sparkling_heart: 프로젝트 지원하기!

저는 가능한 모든 요소들을 오픈소스로 공개하고, 이 서비스를 이용하는데 도움이 필요한 모두에게 도움을 드리려 노력하고 있어요. 솔직히 말하자면, 시간이 좀 걸린답니다... 물론, 여러분이 이 서비스를 사용하는건 무료에요 ㅎ

하지만, 만약 여러분이 이 서비스를 잘 이용하시고, 만족하시거나, 제가 이런 요소들을 만드는 데에 도움을 주고 싶으시다면, 여러분께서 도와주실 수 있는 것들이 있어요!

-   아래의 버튼을 이용해 직접 배포해보세요!
-   이 프로젝트를 많이 공유해주시고, 즐겨찾기 해주세요! :rocket:
-   [![paypal.me/anuraghazra](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/anuraghazra) - PayPal 을 이용해 1회성 도네이션을 해주실 수 있어요. 아마도 전 ~~커피, 아... 아니~~ 차를 사서 마시겠죠? ㅎ; :tea:

감사합니다! :heart:

* * *

[![https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss](./powered-by-vercel.svg)](https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss)

프로젝트에 대한 기여는 언제나 환영이에요! <3

Made with :heart: and JavaScript.
