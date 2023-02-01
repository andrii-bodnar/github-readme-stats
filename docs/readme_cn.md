<p align="center">
 <img width="100px" src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">在你的 README 中获取动态生成的 GitHub 统计信息！</p>
</p>
  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats/actions">
      <img alt="测试通过" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/graphs/contributors">
      <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/anuraghazra/github-readme-stats" />
    </a>
    <a href="https://codecov.io/gh/anuraghazra/github-readme-stats">
      <img src="https://codecov.io/gh/anuraghazra/github-readme-stats/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/issues">
      <img alt="议 题" src="https://img.shields.io/github/issues/anuraghazra/github-readme-stats?color=0088ff" />
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
    <a href="#demo">查看 Demo</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">报告 Bug</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">请求增加功能</a>
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
    <a href="/docs/readme_nl.md">Nederland</a>

    <a href="/docs/readme_np.md">नेपाली</a>
    .
    <a href="/docs/readme_tr.md">utilisé rkcconse</a>
  </p>
</p>

<p align="center">喜欢这个项目？ 请考虑<a href="https://www.paypal.me/anuraghazra">捐赠</a>来帮助它完善！</p>

<a href="https://indiafightscorona.giveindia.org">
  <img src="https://indiaspora.org/wp-content/uploads/2021/04/give-India-logo.png" alt="给india 徽标" width="200" />
</a>

您是否考虑通过捐赠来支持该项目？ 请不要！！

相反，帮助印度与COVID-19的第二个致命浪潮作斗争。 在印度，由于缺少Oxygen & 也缺少与COVID有关的基础设施，数以千计的人正在死亡。

Visit <https://indiafightscorona.giveindia.org> and make a small donation to help us fight COVID and overcome this crisis. 一笔小笔捐款取得了很大进展。 :heart:

</p>

# 特性

-   [GitHub 统计卡片](#github-stats-card)
-   [GitHub 更多置顶](#github-extra-pins)
-   [热门语言卡片](#top-languages-card)
-   [唤醒周统计](#wakatime-week-stats)
-   [主题](#themes)
    -   [`bg_color` - 卡片背景颜色 _（十六进制色码）_ **或者** 以 _angle,start,end_ 的形式渐变](#responsive-card-theme)
-   [自定义](#customization)
    -   [常用选项：](#common-options)
    -   [统计卡片专属选项:](#stats-card-exclusive-options)
    -   [Fork 这个仓库](#repo-card-exclusive-options)
    -   [语言卡片专属选项:](#language-card-exclusive-options)
    -   [唤醒卡专用选项](#wakatime-card-exclusive-options)
-   [自己部署](#deploy-on-your-own-vercel-instance)
    -   [保持您的分叉更新](#keep-your-fork-up-to-date)

# GitHub 统计卡片

将此复制粘贴到您的Markdown内容中，那就是它。 简单！

更改 `?username=` 的值为你的 GitHub 用户名。

```md
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

> **注意** 可用等级为：S+(顶部1%)、S(顶部25%)、A++(顶部45%)、A+(顶部60%)和B+(所有人)。 值是通过使用 [累积分布函数](https://en.wikipedia.org/wiki/Cumulative_distribution_function) 计算的，使用的是提交、贡献、问题、星、拉取请求、追随者和拥有的资源库。 执行情况可以在 [src/calculateRank.js](./src/calculateRank.js) 中进行调查。

### 隐藏指定统计

您可以传递查询参数 `&hide=` 来隐藏任何具有逗号分隔值的特定统计信息。

> 选项：`&hide=stars,commits,prs,issues,contribs`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,prs)
```

### 将私人项目贡献添加到总提交计数中

您可以使用查询参数 `&count_private=true` 将您所有私人贡献的计数添加到提交计数。

> **注意** 如果您自己部署这个项目，私人捐款将被默认计数。 如果你正在使用公共Vercel实例, 你需要选择 [分享你的私人贡献](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/managing-contribution-settings-on-your-profile/showing-your-private-contributions-and-achievements-on-your-profile)。

> 选项: `&count_private=true`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&count_private=true)
```

### 显示图标

如果想要显示图标，你可以调用 `show_icons=true` 参数，像这样：

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true)
```

### 主题

你可以通过现有的主题进行卡片个性化，省去[手动自定义](#自定义)的麻烦。

像这样使用 `&theme=THEME_NAME` 参数：

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
```

#### 所有现有主题

GitHub readme statistics 带有几个内置主题(例如) `dark`, `radical`, `merko`, `gruvbox`, `tokyonight`, `onedark`, `cobalt`, `synthwave`, `highcontrast`, `dracula`)。

<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stat Themes" width="600px" />

您可以查看 [所有可用主题](./themes/README.md) 的预览或签出 [主题配置文件](./themes/index.js) & **如果您喜欢:D ，您也可以贡献新主题**

#### `bg_color` - 卡片背景颜色 _（十六进制色码）_ **或者** 以 _angle,start,end_ 的形式渐变

[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![选择 <code>Import Git Repository</code>](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

因为GitHub 将重新上传卡片并从他们的 [CDN](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-anonymized-urls)中为他们服务， 我们不能推断服务器端的浏览器/GitHub 主题。 然而，您可以使用四种方法在客户端创建动态主题。

##### 使用透明主题

我们包含了一个具有透明背景的 `transparent` 主题。 这个主题被优化以便在 GitHub 的黑暗和光暗的默认主题上看好。 您可以使用 `&theme=transparent` 参数来启用此主题：

```md
<code>hide</code> - 隐藏特定统计信息 <em x-id="4">(以逗号分隔)</em>
```
 - 隐藏特定统计信息 _(以逗号分隔)_
</code>

<details>
<summary>:eyes: 显示示例</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=transparent)

</details>

##### 将透明的 Alpha 通道添加到主题bg_颜色中

You can use the `bg_color` parameter to make any of [the available themes](./themes/README.md) transparent. This is done by setting the `bg_color` to a colour with a transparent alpha channel (i.e. `bg_color=00000000`):

```md
点击 deploy，这就完成了，查看你的域名就可使用 API 了！
```

<details>
<summary>:eyes: 显示示例</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)

</details>

##### `theme` - 主题名称，从[所有可用主题](../themes/README.md)中选择

您可以使用 [GitHub的主题上下文](https://github.blog/changelog/2021-11-24-specify-theme-context-for-images-in-markdown/) 标签自动切换基于用户 GitHub 主题的主题。 这是通过附加 `#gh-dark-mode-only` 或 `#gh-light-mode-only` 到图像URL的结尾。 此标签将定义Markdown中指定的图像是否只显示给使用光线或暗色GitHub 主题的观众：

```md
[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghhazra/github-readme-stats#gh-dark-mode-Light)
[![Anurag's GitHub stats-Light](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://
```

<details>
<summary>:eyes: 显示示例</summary>

[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![#GitHub-更多置顶](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

</details>

##### 使用 GitHub 的新媒体功能

您可以使用 [GitHub 在 HTML 中的新媒体功能](https://github.blog/changelog/2022-05-19-specify-theme-context-for-images-in-markdown-beta/) 来指定是否显示光标或暗色主题的图像。 这是使用 HTML `<picture>` 元素与 `prefers-color-scheme` 媒体特性结合完成的。

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
<summary>:eyes: 显示示例</summary>

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

### 自定义

你可以通过使用 URL 参数的方式，为你的 `Stats Card` 或 `Repo Card` 自定义样式。

#### 自己部署

-   `title_color` - 卡片标题颜色 _(十六进制颜色)_ Default: `2f80ed`.
-   `text_color` - Body text color _(hex color)_. 默认： `434d58`。
-   `icon_color` - 可用图标颜色 _(十六进制颜色)_. 默认： `4c71f2`。
-   `border_color` - 卡片边色 _(十六进制颜色)_ 默认： `e4e2e2` (当 `hide_border` 启用时不适用)。
-   `bg_color` - 卡片的背景颜色 _(十六进制颜色)_ **或** 形式为 _角度,开始,结束_ 的渐变. 默认： `fffefe`
-   `hide_border` - 隐藏卡片边框 _(布尔)_ 默认： `false`
-   `theme` - 主题名称，从 [所有可用主题](./themes/README.md) 中选择。 默认： `default` 主题。
-   `cache_seconds` - 手动设置缓存头 _(min: 14400, max: 86400)_ 默认： `14400 seconds (4 hours)`。
-   `locale` - 设置卡片 _中的语言(例如cn, de, es, 等)_ 默认： `en`.
-   `border_radius` - 四角环绕在卡上。 默认： `4.5`。

> **警告** 我们使用缓存来减少服务器上的负载(见 <https://github.com/anuraghazra/github-readme-stats/issues/1471#issuecomment-1271551425>)。 我们的卡片默认缓存为4小时(14400秒)。 另请注意缓存被限制为最短 2 小时，最长 24 小时。

##### bg_color 渐变

你可以在 bg_color 选项中提供多个逗号分隔的值来呈现渐变，渐变的格式是 :-

    &bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10

#### 设置 Vercel 的指导

-   `hide` - 从统计数据中隐藏 [个指定项目](#hiding-individual-stats) _(逗号分隔值)_. 默认： `[] (blank array)`。
-   `hide_title` - _(布尔)_ 默认： `false`。
-   `card_width` - 手动设置卡的宽度 _(数字)_。 默认： `500px  (approx.)`。
-   `hide_rank` - _(布尔)_ 隐藏排名并自动调整卡宽度。 默认： `false`。
-   `show_icons` - _(boolean)_. 默认： `false`。
-   `include_all_commits` - 计算提交总数，而不仅仅是当前年度提交 _(布尔)_。 默认： `false`。
-   `count_private` - 计数私人提交 _(布尔值)_. 默认： `false`。
-   `line_height` - 设置文本 _(数字)_ 之间的行高度。 默认： `25`。
-   `exclude_repo` - 从指定仓库排除星星 _(逗号分隔的值)_. 默认： `[] (blank array)`。
-   `custom_title` - 设置卡片的自定义标题。 Default:  `<username> GitHub Stats`.
-   `text_bold` - 使用粗体文本 _(布尔值)_. 默认： `true`。
-   `disable_animations` - 禁用卡片中的所有动画 _(布尔)_ 默认： `false`。
-   `ring_color` - 等级圈的颜色 _(十六进制颜色)_ 默认主题环颜色，如果它存在，则为标题颜色。

> **注意** 当hide_rank=`true`时，卡的最小宽度是 270 px + 标题长度和填充。

#### Repo 卡片专属选项:

-   `show_owner` - 显示仓库的所有者名称 _(布尔)_。 默认： `false`。

#### `hide` - 从卡片中隐藏指定语言 _(Comma seperated values)_

-   `hide` - 隐藏卡片中指定的语言 _(逗号分隔值)_。 默认： `[] (blank array)`。
-   `hide_title` - _(布尔)_ 默认： `false`。
-   `layout` - 在两个可用布局之间切换 `default` & `compact`。 默认： `default`。
-   `card_width` - 手动设置卡的宽度 _(数字)_。 默认 `300`。
-   `langs_count` - 在卡上显示更多语言，介于 1-10 _(号码)_ 默认 `5`。
-   `exclude_repo` - 排除指定的仓库 _(逗号分隔值)_. 默认： `[] (blank array)`。
-   `custom_title` - 设置卡片的自定义标题 _(字符串)_。 默认 `Most Used Languages`。
-   `disable_animations` - 禁用卡片中的所有动画 _(布尔)_ 默认： `false`。

> :warning: **重要:** 如 [Percent Encoding](https://en.wikipedia.org/wiki/Percent-encoding) 所指定，语言名称应使用 uri 转义。 (例: `c++` 应该是 `c%2B%2B`, `jupyter notebook` 应该是 `jupyter%20notebook`, 等.)

#### 唤醒卡专用选项

-   `hide` - 隐藏卡片中指定的语言 _(逗号分隔值)_。 默认： `[] (blank array)`。
-   `hide_title` - _(布尔)_ 默认 `false`。
-   `line_height` - 设置文本 _(数字)_ 之间的行高度。 默认 `25`。
-   `hide_progress` - 隐藏进度条和百分比 _(布尔)_。 默认 `false`。
-   `custom_title` - 设置卡片的自定义标题 _(字符串)_。 Default `Wakatime Stats`.
-   `layout` - 在两个可用布局之间切换 `default` & `compact`。  默认 `default`。
-   `card_width` - 手动设置卡片的宽度 _(number)_
-   `api_domain` - 设置一个自定义的 API 域名，例如： 使用诸如 [Hakatime](https://github.com/mujx/hakatime) 或 [Wakapi](https://github.com/muety/wakapi) _(字符串)_ 默认 `Waka API`。
-   `range` — 请求一个不同于您的 WakaTime 默认值的范围，例如： `last_7_days`。 查看 [WakaTime API 文档](https://wakatime.com/developers#stats) 查看可用选项列表。 _(YYY-MM, last_7_days, last_30_days, last_6_month, last_year, or all_time)_. 默认 `all_time`。

* * *

# GitHub 更多置顶

GitHub 更多置顶 允许你在使用 GitHub readme profile 时，在个人资料中置顶多于 6 个 repo 。

是的！ 你不再受限于置顶最多 6 个存储库了。

### 使用细则

将此代码复制粘贴到您的 `README.md` 文件中，并修改链接。

端点: `api/pin?username=anuraghazra&repo=github-readme-stats`

```md
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)
```

### 演示模式

[![阅读卡](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)

使用 [show_owner](#自定义) 变量将 Repo 所有者的用户名包含在内。

[![阅读卡](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats&show_owner=true)](https://github.com/anuraghazra/github-readme-stats)

# 热门语言卡片

热门语言卡片显示了 GitHub 用户常用的编程语言。

> **注意** 顶部语言没有显示我的技能水平或任何这样的东西； 它是一个 GitHub 公式来确定哪些语言在 GitHub 上拥有最多的代码。 它是Github读取状态的一个新特点。

### 使用细则

复制粘贴这段代码到你的 README 文件中，并更改链接。

端点: `api/top-langs?username=anuraghazra`

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

### 排除单个资源库

您可以使用 `&exclude repe_repo=repo1,repo2` 参数来排除单独的资源库。

```md
注: 等级基于用户的统计信息计算得出，详见 <a href="../src/calculateRank.js">src/calculateRank.js</a>
```

### 隐藏指定语言

可以使用 `?hide=language1,language2` 参数来隐藏指定的语言。

```md
[![Langs](https://github-readme-stats.vercel.app/api/to-langs/?username=anuraghazra&hide=javascript,html)](https://github.com/anuraghazra/github-readme-stats)
```

### 显示更多语言

您可以使用 `&langs_count=` 选项来增加或减少卡上显示的语言数量。 有效值是 1 和 10 之间的整数 (包括在内)，默认值是 5。

```md
<code>line_height</code> - 设置文本之间的行高 <em x-id="4">(number)</em>
```
 - 设置文本之间的行高 _(number)_
</code>

### 紧凑的语言卡片布局

你可以使用 `&layout=compact` 参数来改变卡片的样式。

```md
[![Langs](https://github-readme-stats.vercel.app/api/to-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
```

### 演示模式

[![顶部Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   紧凑布局

[![顶部Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

# 唤醒周统计

`hide_title` - _(boolean)_

```md
将这行代码复制到你的 markdown 文件中，就是如此简单！
```

> **注意**: 请知道我们目前只显示来自Wakatime公开的数据。

### 演示模式

[![willianrod 的唤醒状态](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

[![willianrod 的唤醒状态](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&hide_progress=true)](https://github.com/anuraghazra/github-readme-stats)

-   `layout` - 在两个可用布局 `default` & `compact` 间切换

[![willianrod 的唤醒状态](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

* * *

### 全部 Demos

-   默认

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)

-   隐藏指定统计

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,issues)

-   显示图标

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=issues&show_icons=true)

-   自定义边框颜色

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&border_color=2e4058)

-   包含全部提交

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&include_all_commits=true)

-   主题

从[默认主题](#主题)中进行选择

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)

-   渐变

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

-   自定义统计卡片

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)

-   设置卡片区域

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&locale=es)

-   自定义 repo 卡片

![自定义卡](https://github-readme-stats.vercel.app/api/pin?username=anuraghazra&repo=github-readme-stats&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)

-   热门语言

[![顶部Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   唤醒卡

[![willianrod 的唤醒状态](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

* * *

### 快速提示 (对齐 Repo 卡片)

你通常无法将图片靠边显示。 为此，您可以使用以下方法：

```html
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=convoychat" />
</a>
```

## 在您自己的 Vercel 实例上部署

#### Check Out Step By Step Video Tutorial By @codeSTACKr

> **Warning** If you are on the [hobby (i.e. free)](https://vercel.com/pricing) Vercel plan, please make sure you change the `maxDuration` parameter in the [vercel.json](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json) file from `30` to `10` (see [#1416](https://github.com/anuraghazra/github-readme-stats/issues/1416#issuecomment-950275476) for more information).

因为 GitHub 的 API 每个小时只允许 5 千次请求，我的 `https://github-readme-stats.vercel.app/api` 很有可能会触发限制。 如果你将其托管在自己的 Vercel 服务器上，那么你就不必为此担心。 点击 deploy 按钮来开始你的部署！

> 注意: 从 [#58](https://github.com/anuraghazra/github-readme-stats/pull/58) 开始，我们应该能够处理超过 5 千次的请求，并且不会出现宕机问题 :D

[![部署到Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/anuraghazra/github-readme-stats)

<details>
 <summary><b>:hammer_and_wrench: 步步进指南，用于设置您自己的Vercel 实例</b></summary>

1.  前往 [vercel.com](https://vercel.com/)
2.  点击 `Log in` ![](https://files.catbox.moe/pcxk33.png)
3.  点击 `Continue with GitHub` 通过 GitHub 进行登录 ![](https://files.catbox.moe/b9oxey.png)
4.  登录 GitHub 并允许访问所有存储库（如果系统这样提示）
5.  派遣这个仓库.
6.  After forking the repo, open the [`vercel.json`](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json#L5) file and change the `maxDuration` field to `10`.
7.  返回到你的 [Vercel dashboard](https://vercel.com/dashboard)
8.  选择 `Import Project` ![](https://files.catbox.moe/3n76fh.png)
9.  Click the `Continue with GitHub` button, search for the required Git Repository and import it by clicking the `Import` button. Alternatively, you can import a Third-Party Git Repository using the `Import Third-Party Git Repository ->` link at the bottom of the page. ![](https://files.catbox.moe/mg5p04.png)
10. Create a personal access token (PAT) [here](https://github.com/settings/tokens/new) and enable the `repo` permissions (this allows access to see private repo stats).
11. 添加 PAT 作为一个环境变量，名为 `PAT_1` (显示)。 ![](https://files.catbox.moe/0yclio.png)
12. 单击部署，你很好。 查看您的域名使用 API！

</details>

### 保持您的分叉更新

您可以使用GitHubs的 [Sync Fork 按钮](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) 来保持您的叉，从而使您的私有Vercel 实例与上游更新到最新。 您也可以使用 [@wei](https://github.com/wei) 创建的 [拉取](https://github.com/wei/pull) 软件包自动化此进程。

## :sparkling_heart: 支持这个项目

我尽己所能地进行开源，并且我尽量回复每个在使用项目时需要帮助的人。 很显然， 这需要时间。 您可以免费使用此服务。

然而, 如果你正在使用这个项目并感觉良好，或只是想要支持我继续开发，你可以通过如下方式：

-   在你的 readme 中使用 github-readme-stats 时，链接指向这里 :D
-   Star 并 分享这个项目 :rocket:
-   [![paypal.me/anuraghazra](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/anuraghazra) - 你可以通过 PayPal 一次性捐款. 我多半会买一杯 ~~咖啡~~ 茶. :tea: 我可能会购买一只~~咖啡~~ 茶叶。 :tea:

谢谢！ :heart:

* * *

[![https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=os](./powered-by-vercel.svg)](https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss)

欢迎贡献！ <3

用 :heart: 发电，用 JavaScript 制作。
