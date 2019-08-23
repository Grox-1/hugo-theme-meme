# <div align="center">MemE</div>

<div align="center"><img src="https://raw.githubusercontent.com/reuixiy/hugo-theme-meme/master/static/icons/apple-touch-icon.png" /></div>

## Description

MemE is a powerful and highly customizable [GoHugo](https://github.com/gohugoio/hugo) *blog* theme. Moreover, MemE focus on elegance, code correctness, minimalist theme and simplicity. <sup id="fnref:1"><a href="#user-content-fn:1">[1]</a></sup>

Also, I hope you would enjoy MemE like a meme and share MemE like a meme! Just like what your blog and articles do! :stuck_out_tongue_closed_eyes:

Live demo: https://meme-test.netlify.com/

## Features

- InstantClick
- Dark Mode
- JSON-LD
- Multilingual
- Atom / RSS
- TOC
- Drop Cap & Small Cap
- KaTeX
- Google Analytics
- Disqus
- ...

## Details

### Home page layout

For home page layout, MemE has three different kinds: posts, poetry, footage.

1) Posts

![home-layout-posts.png](https://raw.githubusercontent.com/reuixiy/hugo-theme-meme/master/images/home-layout-posts.png)

2) Poetry

![home-layout-poetry.png](https://raw.githubusercontent.com/reuixiy/hugo-theme-meme/master/images/home-layout-poetry.png)

3) Footage

![home-layout-footage.png](https://raw.githubusercontent.com/reuixiy/hugo-theme-meme/master/images/home-layout-footage.png)

### Good for lazy bloggers

MemE has some special features for lazy bloggers. Such as:

1. Auto detect images for JSON-LD and Open Graph
2. Use posts’ taxonomies — such as categories and tags — or sections as keywords
3. Use GitHub flavored code fences instead of highlight shortcode for Syntax Highlighting
4. Use images’ title for caption instead of shortcode
5. Insert videos like images in Markdown
6. Use Hugo’s default Markdown engine for mathematical notation rendering instead of Mmark
7. ...

### Typography

MemE is highly customizable in Typography. You can customize font family, font size, line height, and even content width by yourself.

Moreover, MemE has Drop Cap & Small Cap features. You can set drop cap or enable drop cap after every horizontal rule tag (`<hr />`) — behaved like [The New Yorker](https://www.newyorker.com/) — for your posts. You can also set Small Cap for your posts’ headings.

MemE has two different paragraph style: margin and indent. You would get a paragraph style like a book if you set paragraph style to `indent`. Also, MemE has a special layout for poetry.

## Documentation

This theme’s documentation is still under development, you can *watch* MemE if you are interested.

### Installation

https://gohugo.io/getting-started/quick-start/

#### Hugo

For Arch Linux users:

```
$ sudo pacman -S hugo
$ hugo new site blog
```

For users of other systems, see: https://gohugo.io/getting-started/installing/

#### MemE

```
$ cd blog
$ git init
$ git submodule add https://github.com/reuixiy/hugo-theme-meme.git themes/meme
```

### Configuration

#### Basic

See [config.toml](https://github.com/reuixiy/meme-test/blob/master/config.toml).

#### Service Worker

MemE use gulp to generate sw.js, see: https://github.com/reuixiy/meme-test

### More

I will write an easy-to-understand tutorial about how to migrate from Hexo to Hugo and the differences of them.

## Awesome MemE

See [#2](https://github.com/reuixiy/hugo-theme-meme/issues/2).

## Footnotes

Actually, the reason I developed MemE is simply because I want to migrate [my blog](https://io-oi.me/) from [Hexo](https://hexo.io/) to Hugo smoothly. So I started to research Hugo’s documentation and google everything. In the end, I did it!

Since my previous Hexo blog theme is based on [NexT](https://github.com/theme-next/hexo-theme-next), MemE inherits some of NexT’s layout and style.

For the code I have referenced, I have indicated the source in the code. And I will add a full list here later.

---

<ol><li id="fn:1"><a href="https://itsfoss.com/install-arch-linux/">https://itsfoss.com/install-arch-linux/</a> <a href="#user-content-fnref:1">↩</a></li></ol>