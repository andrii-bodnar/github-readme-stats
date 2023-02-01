<p align="center">
 <img width="100px" src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">あなたの README に自動生成された GitHub の統計情報を載せましょう！</p>
</p>
  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats/actions">
      <img alt="合格テスト" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/graphs/contributors">
      <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/anuraghazra/github-readme-stats" />
    </a>
    <a href="https://codecov.io/gh/anuraghazra/github-readme-stats">
      <img src="https://codecov.io/gh/anuraghazra/github-readme-stats/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/issues">
      <img alt="課題" src="https://img.shields.io/github/issues/anuraghazra/github-readme-stats?color=0088ff" />
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
    <a href="#demo">View Demo</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Report Bug</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Request Feature</a>
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
    <a href="/docs/readme_tr.md">TUR<unk> rkcブドウ</a>
  </p>
</p>

<p align="center">このプロジェクトを気に入っていただけましたか？ <br>もしよろしければ、プロジェクトのさらなる改善のために<a href="https://www.paypal.me/anuraghazra">寄付</a>を検討して頂けると嬉しいです！</p>

<a href="https://indiafightscorona.giveindia.org">
  <img src="https://indiaspora.org/wp-content/uploads/2021/04/give-India-logo.png" alt="インドのロゴを与える" width="200" />
</a>

あなたは寄付でプロジェクトを支援することを考えていますか? やめてください!!

代わりに、COVID-19の第二の致命的な波と戦うインドを助けます。 インドでは酸素 & COVID関連のインフラが不足しているため、何千人もの人々が亡くなっています。

<https://indiafightscorona.giveindia.org> を訪問し、COVIDと戦い、この危機を克服するために少額の寄付を行ってください。 小さな寄付は長い道のりです。 :heart:

</p>

# 主な機能

-   [GitHub 統計カード](#github-stats-card)
-   [GitHub Extra Pins](#github-extra-pins)
-   [トップ言語カード](#top-languages-card)
-   [Wakatime Weekの統計](#wakatime-week-stats)
-   [テーマ](#themes)
    -   [レスポンシブカードのテーマ](#responsive-card-theme)
-   [カスタマイズ](#customization)
    -   [共通のオプション](#common-options)
    -   [Stats Card だけに存在するオプション](#stats-card-exclusive-options)
    -   [`disable_animations` - カードのアニメーションを無効にする _(boolean)_](#repo-card-exclusive-options)
    -   [`locale` - カードに言語を設定する _(例えば cn, de, es, 等)_](#language-card-exclusive-options)
    -   [Wakatime Card Exclusive Option](#wakatime-card-exclusive-options)
-   [配置する](#deploy-on-your-own-vercel-instance)
    -   [フォークを最新の状態に保ちましょう](#keep-your-fork-up-to-date)

# GitHub 統計カード

これをマークダウンの内容にコピー&ペーストします。 シンプル！

`?username=` の値は、あなたの GitHub アカウントのユーザー名に変更してください。

```md
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

> **** 利用可能なランクはS+(上位1%)、S(上位25%)、A++(上位45%)、A+(上位60%)、B+(上位60%)です。 値はコミット、貢献、課題、スター、プルリクエスト、フォロワー、所有リポジトリを使用して、 [累積配布関数](https://en.wikipedia.org/wiki/Cumulative_distribution_function) を使用して計算されます。 詳しくは、[src/calculateRank.js](../src/calculateRank.js)をご覧ください。

### 特定の統計情報を隠す

クエリパラメータ `?hide=` に値をカンマ区切りで渡すことで、特定の統計情報を隠すことができます。

> Options: `&hide=stars,commits,prs,issues,contribs`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,prs)
```

### プライベートリポジトリへのコミットをカウントする

クエリパラメータ `?count_private=true` を使用することで、プライベートリポジトリへのコミット数を総数に追加することができます。

> **メモ** このプロジェクトを自分でデプロイする場合、非公開の貢献はデフォルトでカウントされます。 公開Vercelインスタンスを使用している場合は、 [プライベート貢献](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/managing-contribution-settings-on-your-profile/showing-your-private-contributions-and-achievements-on-your-profile)を共有することを選択する必要があります。

> Options: `&count_private=true`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&count_private=true)
```

### アイコンを表示する

クエリパラメータ `?show_icons=true` を使用することで、アイコンの表示が有効になります。

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true)
```

### テーマ

内蔵されているテーマを使用すれば、[手動のカスタマイズ](#customization)を行うことなくカードの外観を変更することができます。

`?theme=THEME_NAME` は以下のように使います。

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
```

#### 内蔵テーマの一覧

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stat Themes" width="600px" />

`theme` - [使用可能なテーマ一覧](../themes/README.md) から選んだテーマ名

#### レスポンシブカードのテーマ

[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![@codeSTACKr によるチュートリアルはこちら](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

GitHub はカードを再アップロードし、彼らの [CDN](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-anonymized-urls)から提供するため。 サーバー側でブラウザ/GitHubのテーマを推測することはできません。 ただし、クライアント側でダイナミクステーマを作成するために使用できる4つの方法があります。

##### 透明なテーマを使用する

透明な背景を持つ `透明な` テーマが含まれています。 このテーマはGitHubのデフォルトのテーマが暗く明るく見えるように最適化されています。 You can enable this theme using the `&theme=transparent` parameter like so:

```md
<code>show_owner</code> - リポジトリのオーナーを表示する <em x-id="4">(boolean)</em>
```
 - リポジトリのオーナーを表示する _(boolean)_
</code>

<details>
<summary>:eyes: サンプルを表示</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=transparent)

</details>

##### テーマbg_colorに透過アルファチャンネルを追加

その他の使用可能なテーマの[プレビュー](../themes/README.md)や[設定ファイル](../themes/index.js)もご覧ください。 もしよろしければ、**新しいテーマを投稿してみてください** :smile: これは `bg_color` を透明なアルファチャンネルを持つ色に設定することで行われます(例: `bg_color=000000000000`)。

```md
<code>title_color</code> - タイトルの色 <em x-id="4">(16 進数カラーコード)</em>
```
 - タイトルの色 _(16 進数カラーコード)_
</code>

<details>
<summary>:eyes: サンプルを表示</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)

</details>

##### テーマを自分でカスタマイズする

[GitHubのテーマ コンテキスト](https://github.blog/changelog/2021-11-24-specify-theme-context-for-images-in-markdown/) タグを使用して、ユーザー GitHub テーマに基づいてテーマを自動的に切り替えることができます。 これは画像URLの末尾に `#gh-dark-mode-only` または `#gh-light-mode-only` を追加することによって行われます。 このタグは、マークダウンで指定された画像が、暗いGitHubのテーマを使用して視聴者にのみ表示されるかどうかを定義します。

```md
[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only)
[![Anurag's GitHub stats-Light](https://github-readme-stats.vercel.app/api?username=anuraghazra&showicons=true&theme=default#gh
```

<details>
<summary>:eyes: サンプルを表示</summary>

[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![<code>Import Git Repository</code> を選択します。](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

</details>

##### GitHub の新しいメディア機能を使用する

HTML で [GitHubの新しいメディア機能](https://github.blog/changelog/2022-05-19-specify-theme-context-for-images-in-markdown-beta/) を使用して、明るいテーマでも暗いテーマでも画像を表示するかどうかを指定できます。 これは HTML の `<picture>` 要素と `prefers-color-scheme` メディア機能を組み合わせて使用します。

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
<summary>:eyes: サンプルを表示</summary>

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

### カスタマイズ

`Stats Card` や `Repo Card` の外観を URL パラメータを使って好きなようにカスタマイズすることができます。

#### Vercelの設定ガイド

-   `title_color` - カードのタイトル色 _(hex色)_. Default: `2f80ed`.
-   `text_color` - 本文の色 _(hex色)_. デフォルト: `434d58`.
-   `icon_color` - 利用可能な場合のアイコンの色 _(hex色)_. デフォルト: `4c71f2`.
-   `border_color` - カードの境界色 _(16 進色)_. デフォルト: `e4e2e2` ( `hide_border` が有効な場合は適用されません)。
-   `bg_color` - 背景の色 _(16 進数カラーコード)_ **または** _angle,start,end_ の形式でグラデーションを指定することも可 デフォルト: `fffefe`
-   `hide_border` - カードの枠を非表示にする _(boolean)_. デフォルト: `false`
-   `テーマ` - テーマの名前、 [利用可能なすべてのテーマ](./themes/README.md) から選択します。 デフォルト: `デフォルト` テーマ。
-   `cache_seconds` - キャッシュヘッダーを手動で設定 _(min: 14400, max: 86400)_. デフォルト: `14400 秒 (4 時間)`.
-   `locale` - カード _(例: cn, de, es, etc.)_ で言語を設定する。 デフォルト: `en`.
-   `border_radius` - カード上で角を丸める。 デフォルト: `4.5`.

> **Warning** We use caching to decrease the load on our servers (see <https://github.com/anuraghazra/github-readme-stats/issues/1471#issuecomment-1271551425>). カードのデフォルトキャッシュは4時間(14400秒)です。 また、キャッシュは最低でも 30 分、最大でも 24 時間に制限されていることに注意してください。

##### bg_color の グラデーション指定

bg_color オプションで複数のカンマ区切りの値を指定してグラデーションをレンダリングすることができます。 フォーマットは以下の通りになります。

    &bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10

#### コミット数の総数をカウントする

-   `hide` - 統計情報 [(カンマ区切り値)](#hiding-individual-stats) から指定された _アイテム_ を非表示にします。 デフォルト: `[] (空白の配列)`.
-   `hide_title` - _(boolean)_. デフォルト: `false`.
-   `card_width` - カードの幅を手動で _(数値)_ に設定する。 デフォルト: `500px (approx.)`.
-   `hide_rank` - _(boolean)_ はランクを隠し、カードの幅を自動的にリサイズします。 デフォルト: `false`.
-   `show_icons` - _(boolean)_. デフォルト: `false`.
-   `include_all_commits` - 現在の年コミットの代わりに総コミット数を数える _(boolean)_. デフォルト: `false`.
-   `count_private` - プライベートコミットをカウント _(boolean)_. デフォルト: `false`.
-   `line_height` - テキスト _(数値)_ の行の高さを設定します。 デフォルト: `25`.
-   `exclude_repo` - 指定されたリポジトリから星を除外する _(カンマ区切り)_. デフォルト: `[] (空白の配列)`.
-   `custom_title` - カードのカスタムタイトルを設定します。 Default:  `<username> GitHub Stats`.
-   `text_bold` - Use bold text _(boolean)_. デフォルト: `true`.
-   `disable_animations` - カード _(boolean)_ 内のすべてのアニメーションを無効にします。 デフォルト: `false`.
-   `ring_color` - ランクサークルの色 _(16 進色)_. 既定ではテーマリングの色が存在し、それ以外の場合はタイトルの色になります。

> **メモ** hide_rank=`true`は、最小カード幅は 270 px + タイトル長さとパディングです。

#### Repo Card だけに存在するオプション

-   `show_owner` - リポジトリのオーナー名 _(boolean)_ を表示する。 デフォルト: `false`.

#### Language Card だけに存在するオプション

-   `hide` - カードから指定された言語を非表示にする _(カンマ区切り)_. デフォルト: `[] (空白の配列)`.
-   `hide_title` - _(boolean)_. デフォルト: `false`.
-   `layout` - 2つの使用可能なレイアウトを切り替える `default` & `compact`. デフォルト: `default`.
-   `card_width` - カードの幅を手動で _(数値)_ に設定する。 デフォルト `300`。
-   `langs_count` - カードに言語を表示します。1-10 _(数値)_。 デフォルト `5`.
-   `exclude_repo` - 指定されたリポジトリを除外 _(カンマ区切り)_. デフォルト: `[] (空白の配列)`.
-   `custom_title` - カードの _(string)_ のカスタムタイトルを設定します。 デフォルト `最も使用されている言語`。
-   `disable_animations` - カード _(boolean)_ 内のすべてのアニメーションを無効にします。 デフォルト: `false`.

> **Warning** Language names should be URI-escaped, as specified in [Percent Encoding](https://en.wikipedia.org/wiki/Percent-encoding) (i.e: `c++` should become `c%2B%2B`, `jupyter notebook` should become `jupyter%20notebook`, etc.) [urlencoder.org](https://www.urlencoder.org/) を使用して自動的にこれを行うことができます。

#### Wakatime Card Exclusive Options

-   `hide` - カードから指定された言語を非表示にする _(カンマ区切り)_. デフォルト: `[] (空白の配列)`.
-   `hide_title` - _(boolean)_. デフォルト `false`。
-   `line_height` - テキスト _(数値)_ の行の高さを設定します。 デフォルト `25`.
-   `hide_progress` - プログレスバーとパーセンテージ _(ブール値)_ を非表示にします。 デフォルト `false`。
-   `custom_title` - カードの _(string)_ のカスタムタイトルを設定します。 Default `Wakatime Stats`.
-   `layout` - 2つの使用可能なレイアウトを切り替える `default` & `compact`.  デフォルト `デフォルト`。
-   `langs_count` - 表示される言語の数　_(1 ~ 10, 初期値 5)_
-   `api_domain` - Set a custom API domain for the card, e.g. to use services like [Hakatime](https://github.com/mujx/hakatime) or [Wakapi](https://github.com/muety/wakapi) _(string)_. デフォルト `Waka API`.
-   `range` – WakaTime デフォルトとは異なる範囲を要求する。例: `last_7_days`. 利用可能なオプションの一覧については、 [WakaTime API ドキュメント](https://wakatime.com/developers#stats) を参照してください。 _(YYYY-MM, last_7_days, last_30_days, last_6_months, last_year, all_time)_. デフォルト `all_time`.

* * *

# GitHub Extra Pins

GitHub extra pins を使うと、GitHub の readme プロフィールを使って、自分のプロフィールに 6 つ以上のリポジトリをピン留めすることができます。

やったー! もはや、リポジトリをピン留めできる数が 6 つに制限されることはありません。

### 使い方

以下のコードをあなたの readme にコピー & ペーストし、リンクを変更してください。

エンドポイント: `api/pin?username=anuraghazra&repo=github-readme-stats`

```md
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)
```

### デモ

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)

リポジトリのオーナーのユーザー名を含める場合は、show_owner 変数を使用します。

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats&show_owner=true)](https://github.com/anuraghazra/github-readme-stats)

# トップ言語カード

Top languages card には、その GitHub ユーザーが最も利用している Top languages が表示されます。

> **メモ** 上位言語は私のスキルレベルやそのようなことを示していません。 GitHubで最もコードの多い言語を決定するためのGitHubメトリックです。 github-readme-statsの新機能です。

### 使い方

以下のコードをあなたの readme にコピー & ペーストし、リンクを変更してください。

エンドポイント: `api/top-langs?username=anuraghazra`

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

### 個々のリポジトリを除外

`exclude_repo` - 指定されたリポジトリを除外する _(カンマ区切りで指定)_

```md
<code>count_private</code> - プライベートリポジトリへのコミットをカウントする <em x-id="4">(boolean)</em>
```
 - プライベートリポジトリへのコミットをカウントする _(boolean)_
</code>

### 特定の言語を隠す

クエリパラメータ `?hide=language1,language2` 使用することで、特定の言語を非表示にすることができます。

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langss/?username=anuraghazra&hide=javascript,html)](https://github.com/anuraghazra/github-readme-stats)
```

### 他の言語を表示する

`&langs_count=` オプションを使用して、カードに表示される言語の数を増減できます。 有効な値は 1 から 10 までの整数で、デフォルトは 5 です。

```md
<code>line_height</code> - テキストの行の高さ <em x-id="4">(number)</em>
```
 - テキストの行の高さ _(number)_
</code>

### コンパクト言語カードのレイアウト

クエリパラメータ `&layout=compact` を使用することで、カードのデザインを変更することができます。

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langss/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
```

### テーマの変更

[![トップ言語](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   レイアウトをコンパクトにする

[![トップ言語](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

# Wakatime Weekの統計

`custom_title` - タイトル文字列を変更する

```md
Note: このプロジェクトを自分でデプロイしている場合、デフォルトではプライベートリポジトリへのコミットがカウントされます。
```

> **メモ**: 現在、弊社は公開されているWakatimeプロファイルのデータのみを表示していることにご注意ください。

### デモ

[![ウィリアムロッドのワカティムの統計は](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

[![ウィリアムロッドのワカティムの統計は](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&hide_progress=true)](https://github.com/anuraghazra/github-readme-stats)

-   Compact layout の場合

[![ウィリアムロッドのワカティムの統計は](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

* * *

### 全てのデモ

-   デフォルト

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)

-   特定の統計情報を隠す

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,issues)

-   アイコンを表示する

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=issues&show_icons=true)

-   境界線の色をカスタマイズ

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&border_color=2e4058)

-   すべてのコミットを含める

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&include_all_commits=true)

-   テーマ

任意の[テーマ](#themes)を選択できます。

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)

-   グラデーション

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

-   stats card のカスタマイズ

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)

-   カードのロケールの設定

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&locale=es)

-   repo card のカスタマイズ

![カスタマイズしたカード](https://github-readme-stats.vercel.app/api/pin?username=anuraghazra&repo=github-readme-stats&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)

-   トップ言語

[![トップ言語](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   WakaTime カード

[![ウィリアムロッドのワカティムの統計は](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

* * *

### クイックヒント (カードを並べる)

デフォルトでは、GitHubはカードを並べて配置しません。 これを行うには、次のアプローチを使用できます。

```html
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=convoychat" />
</a>
```

## 自分の Vercel インスタンスにデプロイする

#### :film_projector: [@codeSTACKr によるステップバイステップビデオチュートリアルをチェックアウト](https://youtu.be/n6d4KHSKqGk?t=107)

> **Warning** If you are on the [hobby (i.e. free)](https://vercel.com/pricing) Vercel plan, please make sure you change the `maxDuration` parameter in the [vercel.json](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json) file from `30` to `10` (see [#1416](https://github.com/anuraghazra/github-readme-stats/issues/1416#issuecomment-950275476) for more information).

GitHub API は 1 時間あたり 5k リクエストしか受け付けていないので、私の `https://github-readme-stats.vercel.app/api` がレートリミッターを超えてしまう可能性があります。 自分の Vercel サーバーでホストしているのであれば、何も心配する必要はありません。 デプロイボタンをクリックして始めましょう！

> NOTE: [#58](https://github.com/anuraghazra/github-readme-stats/pull/58) 以降は 5k 以上のリクエストに対応できるようになり、ダウンタイムの問題もなくなりました :smile:

[![Vercel にデプロイする](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/anuraghazra/github-readme-stats)

<details>
 <summary><b>あなた自身のVercelインスタンスを設定する際の:hammer_and_wrench: ステップバイステップガイド</b></summary>

1.  [vercel.com](https://vercel.com/)に行きます。
2.  `Log in`をクリックします。 ![](https://files.catbox.moe/pcxk33.png)
3.  `Continue with GitHub` を押して GitHub にサインインします。 ![](https://files.catbox.moe/b9oxey.png)
4.  GitHub にサインインし、すべてのリポジトリへのアクセスを許可します。
5.  このリポジトリをフォークします。
6.  リポジトリをフォークした後、 [`vercel.json`](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json#L5) ファイルを開き、 `maxDuration` フィールドを `10` に変更します。
7.  [Vercel dashboard](https://vercel.com/dashboard)に戻ります。
8.  `Import Project` を選択します。 ![](https://files.catbox.moe/3n76fh.png)
9.  `` ボタンをクリックし、必要な Git リポジトリを検索し、 `Import` ボタンをクリックしてインポートします。 または、ページの下部にある `サードパーティーのGitリポジトリのインポート ->` リンクを使用して、サードパーティのGitリポジトリをインポートすることもできます。 ![](https://files.catbox.moe/mg5p04.png)
10. これには個人アクセストークン (PAT) が含まれており、[ここ](https://github.com/settings/tokens/new)で簡単に作成することができます (すべてをそのままにしておいて、何かに名前を付けてください。 )
11. root を選択して、すべてをそのままにしておき、PAT_1 という名前の環境変数を（下図のように）追加します。 ![](https://files.catbox.moe/0yclio.png)
12. デプロイをクリックすれば完了です。 API を使用するためにあなたのドメインを参照してください!

</details>

### フォークを最新の状態に保ちましょう

GitHubの [フォークを同期するボタン](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork)を使用して、あなたのプライベートなVercelインスタンスをアップストリームで最新の状態に保つことができます。 [@wei](https://github.com/wei/pull) によって作成された [pull](https://github.com/wei) パッケージを使用して、このプロセスを自動化することもできます。

## :sparkling_heart: このプロジェクトを支援する

私はできる限りのことをオープンソースで行い、また、このプロジェクトを利用する上で困っている皆さん全員に返信するようにしています。 明らかに、 には時間がかかります。 このサービスは無料で利用できます。

しかしながら、もしあなたがこのプロジェクトに満足しているのであれば、あるいはただ、私がソフトウェアを作り続けるよう励ましたいのであれば、いくつかの方法があります。

-   あなたの readme で github-readme-stats を使用して適切なクレジットを付与し、それにリンクします :smile:
-   このプロジェクトにスターを贈り、他の人達にもシェアしてください :rocket:
-   [![paypal.me/anuraghazra](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/anuraghazra) - PayPal を介して 1 回限りの寄付を行うことができます。 私はおそらく ~~コーヒー~~ お茶を買うでしょう。 :tea:

ありがとう！ :heart:

* * *

[![https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss](./powered-by-vercel.svg)](https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss)

コントリビュートは大歓迎です！ :heart_eyes:

このプロジェクトは :heart: と JavaScript で作られています。
