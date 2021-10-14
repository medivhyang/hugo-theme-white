# White

A clean Hugo theme. Inspired by [Paper](https://github.com/nanxiaobei/hugo-paper).

[Demo](https://medivhyang.com) 

## Install

Inside the folder of your Hugo project, run:

```bash
git submodule add https://github.com/medivhyang/hugo-theme-white themes/white
```

Open config.toml, change theme to "white":

```toml
theme = "white"
```

For more information, please read the [official guide](https://gohugo.io/getting-started/quick-start/#step-3-add-a-theme) of Hugo.

## Options

Available options to config.toml:


```toml
[params]
  disableHLJS = true                         # don't use highlight.js
  twitter = 'YOUR_TWITTER_ID'                # twitter.com/YOUR_TWITTER_ID
  github = 'YOUR_GITHUB_ID'                  # github.com/YOUR_GITHUB_ID
  instagram = 'YOUR_INSTAGRAM_ID'            # instagram.com/YOUR_INSTAGRAM_ID

[params.utteranc]
  enable = true
  repo = "medivhyang/medivhyang.github.io"
  issueTerm = "title"
  theme = "github-light"
```