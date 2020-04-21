<p align="center">
    <h2 align="center">Cedric Chee's Website - <a href="https://cedricchee.com">Check it out!</a> · <a href="https://travis-ci.org/cedrickchee/personal-website"><img src="https://camo.githubusercontent.com/5393485b732749b3499264168fa8af60166071e8/68747470733a2f2f7472617669732d63692e6f72672f73657267696f6b6f70706c696e2f696e6469676f2e7376673f6272616e63683d67682d7061676573" alt="Build Status" data-canonical-src="https://travis-ci.org/cedrickchee/personal-website.svg?branch=gh-pages" style="max-width:100%;"></a></h2>
</p>

<p align="center">Source code for my personal website and blog. Crafted with ♥</p>

***

<p align="center">
    <b><a href="README.md#what-is-under-the-hood">What is under the hood</a></b>
    |
    <b><a href="README.md#setup">Setup</a></b>
    |
    <b><a href="README.md#settings">Settings</a></b>
    |
    <b><a href="README.md#how-to">How to</a></b>
</p>

<!--<p align="center">
    <img src="https://raw.githubusercontent.com/cedrickchee/personal-website/gh-pages/assets/screen-shot.png" />
</p>-->

## What is under the hood

Built using:

- [Jekyll](https://jekyllrb.com/), [Sass](http://sass-lang.com/) and [SVG](https://www.w3.org/Graphics/SVG/)
- [Indigo theme](https://github.com/sergiokopplin/indigo). A simple and minimalist template for Jekyll
- Tests with [Travis CI](https://travis-ci.org/)
- Google PageSpeed: [98/100](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fcedricchee.com);
- No JS. :sunglasses:

## Setup

0. :star: to the project. :metal:
1. Fork the project [personal-website](https://github.com/cedrickchee/personal-website/fork)
2. Edit `_config.yml` with your data (check <a href="README.md#settings">settings</a> section)
3. Write some posts :bowtie:

If you want to test locally on your machine, do the following steps also:

1. Install [Jekyll](http://jekyllrb.com), [Node.js](https://nodejs.org/) and [Bundler](http://bundler.io/)
2. Clone the forked repo on your machine
3. Enter the cloned folder via terminal and run `bundle install`
4. Then run `bundle exec jekyll serve --config _config.yml,_config-dev.yml`
5. Open it in your browser: `http://localhost:4000`
6. Test your app with `bundle exec htmlproofer ./_site`

## Settings

Edit Jekyll site settings in `_config.yml` to customize your site.

```
name: John Doe
bio: 'The man behind the code'
picture: 'assets/images/my-profile-pic.jpg'
...

and lot of other options, like width, projects, pages, read-time, tags, related posts, animations, multiple-authors, etc.
```

## How To?

Check the [FAQ](./FAQ.md) if you have any question or problem.

---

## License

* Code: [MIT](https://cedrickchee.mit-license.org/) © Cedric Chee
* Content: [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/)
