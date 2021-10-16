<p align="center">
 <img width="100px" src="https://res.cloudinary.com/IAlzoriqi/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">Get dynamically generated GitHub stats on your readmes!</p>
</p>
  <p align="center">
    <a href="https://github.com/IAlzoriqi/IAlzoriqi/actions">
      <img alt="Tests Passing" src="https://github.com/IAlzoriqi/IAlzoriqi/workflows/Test/badge.svg" />
    </a>
    <a href="https://codecov.io/gh/IAlzoriqi/IAlzoriqi">
      <img src="https://codecov.io/gh/IAlzoriqi/IAlzoriqi/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/IAlzoriqi/IAlzoriqi/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/IAlzoriqi/IAlzoriqi?color=0088ff" />
    </a>
    <a href="https://github.com/IAlzoriqi/IAlzoriqi/pulls">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/IAlzoriqi/IAlzoriqi?color=0088ff" />
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
    <a href="https://github.com/IAlzoriqi/IAlzoriqi/issues/new/choose">Report Bug</a>
    ·
    <a href="https://github.com/IAlzoriqi/IAlzoriqi/issues/new/choose">Request Feature</a>
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
<p align="center">Love the project? Please consider <a href="https://www.paypal.me/IAlzoriqi">donating</a> to help it improve!

<p>
<a href="https://indiafightscorona.giveindia.org">
<img src="https://d2wvdrxmr8p0wf.cloudfront.net/static/giveindia.svg" alt="Give india logo" width="200" />
</a>

Are you considering to support the project by donating to me? Please DON'T!!

Instead, Help India fight 2nd deadly wave of COVID,  
Thousands of people are dying in India for lack of Oxygen & COVID related necessary infrastructure.

Visit [https://indiafightscorona.giveindia.org](https://indiafightscorona.giveindia.org) and make a small donation to help us fight covid and overcome this crisis.  
Your small help goes a long way. :heart:

</p>

# Features

- [GitHub Stats Card](#github-stats-card)
- [GitHub Extra Pins](#github-extra-pins)
- [Top Languages Card](#top-languages-card)
- [Wakatime Week Stats](#wakatime-week-stats)
- [Themes](#themes)
- [Customization](#customization)
  - [Common Options](#common-options)
  - [Stats Card Exclusive Options](#stats-card-exclusive-options)
  - [Repo Card Exclusive Options](#repo-card-exclusive-options)
  - [Language Card Exclusive Options](#language-card-exclusive-options)
  - [Wakatime Card Exclusive Option](#wakatime-card-exclusive-options)
- [Deploy Yourself](#deploy-on-your-own-vercel-instance)

# GitHub Stats Card

Copy-paste this into your markdown content, and that's it. Simple!

Change the `?username=` value to your GitHub's username.

```md
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=IAlzoriqi)](https://github.com/IAlzoriqi/IAlzoriqi)
```

_Note: Available ranks are S+ (top 1%), S (top 25%), A++ (top 45%), A+ (top 60%), and B+ (everyone).
The values are calculated by using the [cumulative distribution function](https://en.wikipedia.org/wiki/Cumulative_distribution_function) using commits, contributions, issues, stars, pull requests, followers, and owned repositories.
The implementation can be investigated at [src/calculateRank.js](./src/calculateRank.js)_

### Hiding individual stats

To hide any specific stats, you can pass a query parameter `?hide=` with comma-separated values.

> Options: `&hide=stars,commits,prs,issues,contribs`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=IAlzoriqi)
```

### Adding private contributions count to total commits count

You can add the count of all your private contributions to the total commits count by using the query parameter `?count_private=true`.

_Note: If you are deploying this project yourself, the private contributions will be counted by default. Otherwise, you need to choose to share your private contribution counts._

> Options: `&count_private=true`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=IAlzoriqi&count_private=true)
```

### Showing icons

To enable icons, you can pass `show_icons=true` in the query param, like so:

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=IAlzoriqi&show_icons=true)
```

### Themes

With inbuilt themes, you can customize the look of the card without doing any [manual customization](#customization).

Use `&theme=THEME_NAME` parameter like so :-

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=IAlzoriqi&show_icons=true&theme=radical)
```

#### All inbuilt themes :-

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://res.cloudinary.com/IAlzoriqi/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stats Themes" width="600px"/>

You can look at a preview for [all available themes](./themes/README.md) or checkout the [theme config file](./themes/index.js) & **you can also contribute new themes** if you like :D

### Customization

You can customize the appearance of your `Stats Card` or `Repo Card` however you wish with URL params.

#### Common Options:

- `title_color` - Card's title color _(hex color)_
- `text_color` - Body text color _(hex color)_
- `icon_color` - Icons color if available _(hex color)_
- `border_color` - Card's border color _(hex color)_. (Does not apply when `hide_border` is enabled)
- `bg_color` - Card's background color _(hex color)_ **or** a gradient in the form of _angle,start,end_
- `hide_border` - Hides the card's border _(boolean)_
- `theme` - name of the theme, choose from [all available themes](./themes/README.md)
- `cache_seconds` - set the cache header manually _(min: 1800, max: 86400)_
- `locale` - set the language in the card _(e.g. cn, de, es, etc.)_
- `border_radius` - Corner rounding on the card\_

##### Gradient in bg_color

You can provide multiple comma-separated values in bg_color option to render a gradient, the format of the gradient is :-

```
&bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10
```

> Note on cache: Repo cards have a default cache of 4 hours (14400 seconds) if the fork count & star count is less than 1k, otherwise, it's 2 hours (7200 seconds). Also, note that the cache is clamped to a minimum of 2 hours and a maximum of 24 hours.

#### Stats Card Exclusive Options:

- `hide` - Hides the specified items from stats _(Comma-separated values)_
- `hide_title` - _(boolean)_
- `hide_rank` - _(boolean)_ hides the rank and automatically resizes the card width
- `show_icons` - _(boolean)_
- `include_all_commits` - Count total commits instead of just the current year commits _(boolean)_
- `count_private` - Count private commits _(boolean)_
- `line_height` - Sets the line-height between text _(number)_
- `custom_title` - Sets a custom title for the card
- `disable_animations` - Disables all animations in the card _(boolean)_

#### Repo Card Exclusive Options:

- `show_owner` - Show the repo's owner name _(boolean)_

#### Language Card Exclusive Options:

- `hide` - Hide the languages specified from the card _(Comma-separated values)_
- `hide_title` - _(boolean)_
- `layout` - Switch between two available layouts `default` & `compact`
- `card_width` - Set the card's width manually _(number)_
- `langs_count` - Show more languages on the card, between 1-10, defaults to 5 _(number)_
- `exclude_repo` - Exclude specified repositories _(Comma-separated values)_
- `custom_title` - Sets a custom title for the card

> :warning: **Important:**
> Language names should be uri-escaped, as specified in [Percent Encoding](https://en.wikipedia.org/wiki/Percent-encoding)
> (i.e: `c++` should become `c%2B%2B`, `jupyter notebook` should become `jupyter%20notebook`, etc.) You can use
> [urlencoder.org](https://www.urlencoder.org/) to help you do this automatically.

#### Wakatime Card Exclusive Options:

- `hide` - Hide the languages specified from the card _(Comma-separated values)_
- `hide_title` - _(boolean)_
- `line_height` - Sets the line-height between text _(number)_
- `hide_progress` - Hides the progress bar and percentage _(boolean)_
- `custom_title` - Sets a custom title for the card
- `layout` - Switch between two available layouts `default` & `compact`
- `langs_count` - Limit number of languages on the card, defaults to all reported langauges
- `api_domain` - Set a custom API domain for the card, e.g. to use services like [Hakatime](https://github.com/mujx/hakatime) or [Wakapi](https://github.com/muety/wakapi)
- `range` – Request a range different from your WakaTime default, e.g. `last_7_days`. See [WakaTime API docs](https://wakatime.com/developers#stats) for list of available options.

---

# GitHub Extra Pins

GitHub extra pins allow you to pin more than 6 repositories in your profile using a GitHub readme profile.

Yay! You are no longer limited to 6 pinned repositories.

### Usage

Copy-paste this code into your readme and change the links.

Endpoint: `api/pin?username=IAlzoriqi&repo=github-readme-stats`

```md
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=IAlzoriqi&repo=github-readme-stats)](https://github.com/IAlzoriqi/IAlzoriqi)
```

### Demo

[![Readme Card](https://IAlzoriqi.vercel.app/api/pin/?username=IAlzoriqi&repo=IAlzoriqi)](https://github.com/IAlzoriqi/IAlzoriqi)

Use [show_owner](#customization) variable to include the repo's owner username

[![Readme Card](https://IAlzoriqi.vercel.app/api/pin/?username=IAlzoriqi&repo=IAlzoriqi&show_owner=true)](https://github.com/IAlzoriqi/IAlzoriqi)

# Top Languages Card

The top languages card show a GitHub user's most frequently used top language.

_NOTE: Top Languages does not indicate my skill level or anything like that, it's a GitHub metric of which languages have the most code on GitHub. It's a new feature of IAlzoriqi._

### Usage

Copy-paste this code into your readme and change the links.

Endpoint: `api/top-langs?username=IAlzoriqi`

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=IAlzoriqi)](https://github.com/IAlzoriqi/IAlzoriqi)
```

### Exclude individual repositories

You can use `?exclude_repo=repo1,repo2` parameter to exclude individual repositories.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=IAlzoriqi&exclude_repo=MyGuideAtMyPhone,TestMyGuideAtMyPhone,my_guide_at_my_phone&langs_count=10&hide=C#)](https://github.com/IAlzoriqi/IAlzoriqi)
```

### Hide individual languages

You can use `?hide=language1,language2` parameter to hide individual languages.

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=IAlzoriqi)](https://github.com/IAlzoriqi/IAlzoriqi)

### Show more languages

You can use the `&langs_count=` option to increase or decrease the number of languages shown on the card. Valid values are integers between 1 and 10 (inclusive), and the default is 5.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=IAlzoriqi&langs_count=10)](https://github.com/IAlzoriqi/IAlzoriqi)
```

### Compact Language Card Layout

You can use the `&layout=compact` option to change the card design.

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=IAlzoriqi&layout=compact)](https://github.com/IAlzoriqi/IAlzoriqi)

### Demo
https://github-readme-stats.vercel.app/api/top-langs/?username=IAlzoriqi&exclude_repo=SalesManagementSoftware,IAlzoriqi.github.io&&langs_count=10&hide=HTML,JavaScript,PHP,Kotlin,Objective-C,CSS,Hack&show_private=true

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=IAlzoriqi&count-private=true&langs_count=10&exclude_repo=github-readme-stats,github.com/IAlzoriqi/IAlzoriqi&hide=CSS,html,Hack,kotlin,Swift,C#,JavaScript,Objective-C,Kotlin,C++)](https://github.com/IAlzoriqi/IAlzoriqi)


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=IAlzoriqi&count-private=true&langs_count=10&exclude_repo=github-readme-stats,github.com/IAlzoriqi/IAlzoriqi&hide=CSS,html,Hack,kotlin,Swift,C#,JavaScript,Objective-C,Kotlin,C++)](https://github.com/IAlzoriqi/IAlzoriqi)

- Compact layout

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=IAlzoriqi&layout=compact)](https://github.com/IAlzoriqi/IAlzoriqi)

# Wakatime Week Stats

Change the `?username=` value to your [Wakatime](https://wakatime.com) username.

```md
[![IAlzoriqi's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=IAlzoriqi)](https://github.com/IAlzoriqi/IAlzoriqi)
```

### Demo

[![IAlzoriqi wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=IAlzoriqi)](https://github.com/IAlzoriqi/IAlzoriqi)

[![IAlzoriqi's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=IAlzoriqi&hide_progress=true)](https://github.com/IAlzoriqi/IAlzoriqi)

- Compact layout

[![IAlzoriqi wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=IAlzoriqi&layout=compact)](https://github.com/IAlzoriqi/IAlzoriqi)

---

### All Demos

- Default

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=IAlzoriqi&langs_count=8&exclude_repo=github-readme-stats,IAlzoriqi.github.io&count-private=true))

- Hiding specific stats

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=IAlzoriqi&langs_count=8&&count-private=true))

- Showing icons

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=IAlzoriqi&show_icons=true&count-private=true)

- Customize Border Color

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=IAlzoriqi&border_color=2e4058&count-private=true)

- Include All Commits

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=IAlzoriqi&include_all_commits=true)

- Themes

Choose from any of the [default themes](#themes)

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=IAlzoriqi&show_icons=true&theme=radical)

- Gradient

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=IAlzoriqi&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

- Customizing stats card

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=IAlzoriqi&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)

- Setting card locale

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=IAlzoriqi&locale=es)

- Customizing repo card

![Customized Card](https://github-readme-stats.vercel.app/api/pin?username=IAlzoriqi&repo=github-readme-stats&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)

- Top languages

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=IAlzoriqi&count-private=true)](https://github.com/IAlzoriqi/IAlzoriqi)

- Wakatime card

[![IAlzoriqi wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=IAlzoriqi)](https://github.com/IAlzoriqi/IAlzoriqi)

---

### Quick Tip (Align The Repo Cards)

You usually won't be able to layout the images side by side. To do that you can use this approach:

```html
<a href="https://github.com/IAlzoriqi/IAlzoriqi">
  <img
    align="center"
    src="https://github-readme-stats.vercel.app/api/pin/?username=IAlzoriqi&repo=TestMyGuideAtMyPhone"
  />
</a>
<a href="https://github.com/IAlzoriqi/TestMyGuideAtMyPhone">
  <img
    align="center"
    src="https://github-readme-stats.vercel.app/api/pin/?username=IAlzoriqi&repo=TestMyGuideAtMyPhone"
  />
</a>
```

## Deploy on your own Vercel instance

#### [Check Out Step By Step Video Tutorial By @codeSTACKr](https://youtu.be/n6d4KHSKqGk?t=107)

Since the GitHub API only allows 5k requests per hour, my `https://github-readme-stats.vercel.app/api` could possibly hit the rate limiter. If you host it on your own Vercel server, then you don't have to worry about anything. Click on the deploy button to get started!

NOTE: Since [#58](https://github.com/IAlzoriqi/IAlzoriqi/pull/58) we should be able to handle more than 5k requests and have no issues with downtime :D

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/IAlzoriqi/IAlzoriqi)

<details>
 <summary><b> Guide on setting up Vercel  🔨 </b></summary>

1. Go to [vercel.com](https://vercel.com/)
1. Click on `Log in`
   ![](https://files.catbox.moe/tct1wg.png)
1. Sign in with GitHub by pressing `Continue with GitHub`
   ![](https://files.catbox.moe/btd78j.jpeg)
1. Sign into GitHub and allow access to all repositories, if prompted
1. Fork this repo
1. Go back to your [Vercel dashboard](https://vercel.com/dashboard)
1. Select `Import Project`
   ![](https://files.catbox.moe/qckos0.png)
1. Select `Import Git Repository`
   ![](https://files.catbox.moe/pqub9q.png)
1. Select root and keep everything as is, just add your environment variable named PAT_1 (as shown), which will contain a personal access token (PAT), which you can easily create [here](https://github.com/settings/tokens/new) (leave everything as is, just name it something, it can be anything you want)
   ![](https://files.catbox.moe/0ez4g7.png)
1. Click deploy, and you're good to go. See your domains to use the API!

</details>

## :sparkling_heart: Support the project

I open-source almost everything I can, and I try to reply to everyone needing help using these projects. Obviously,
this takes time. You can use this service for free.

However, if you are using this project and are happy with it or just want to encourage me to continue creating stuff, there are few ways you can do it :-

- Giving proper credit when you use github-readme-stats on your readme, linking back to it :D
- Starring and sharing the project :rocket:
- [![paypal.me/IAlzoriqi](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/IAlzoriqi) - You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:

Thanks! :heart:

---

[![https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss](./powered-by-vercel.svg)](https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss)

Contributions are welcome! <3

Made with :heart: and JavaScript.
