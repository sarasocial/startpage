# startpage

this is a startpage i made for myself. you can fork it and do whatever you want with it. it uses catppuccin colors.

inspo is random stuff from the [startpages subreddit](https://reddit.com/r/startpages) and from [catppuccin-startpage](https://github.com/pivoshenko/catppuccin-startpage).

**note:** i will completely fuck up this repo at a moments notice!!! you can download it, fork it, whatever you'd like, but do not rely on me to do anything but mess it up!!!! :)

## setting it up

### running locally

to play with the startpage locally, run:

```
git clone https://github.com/sarasoci.al/startpage && cd startpage
npm init -y && npm pkg set type="module"
npm install @11ty-eleventy npm-run-all sass @catppuccin/palette --save-dev
```

you can build with `npm run build`. you can also use `npm run serve` to build and host locally at [localhost:7272](http://localhost:7272). the port can be changed in the [eleventy config](/eleventy.config.js).

### using github pages

??? idk should work fine lmao

## configuration options

you can literally do whatever the hell you want with this but it's been optimized for quick configuration.

### customizing content

in [index.md](/_site/index.md) you can edit the content that appears on the startpage, including bookmarks and the "terminal" user/host names

### customizing look

you can edit [_startpage-theme.scss](/_resources/scss/themes/_startpage-theme.scss) to change visual aspects of the startpage, such as background and colors. it uses the `mocha` palette by default; this can be changed to any of the other catppuccin palettes with ease. you can also just like fuck around and use your own or bring in another theme (i will add [everforest](https://github.com/sainnhe/everforest) soon!)