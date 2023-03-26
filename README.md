# site-stuff
Personal blog/site wip :)

## To-do:
* [ ] Improve about.. add projects and such
* [ ] CI/CD
* [ ] Pull requests

## Done:
* [x] change theme
  * Theme used was [hello-friend-ng](https://github.com/rhazdon/hugo-theme-hello-friend-ng)
* [x] Fix dark theme
  * ~~This kinda works, depending on your OS settings~~
  * ~~Need to add a button tho?~~
  * Just `.Site.Params.EnableThemeToggle = true` :o
* [x] custom URL
  * Go to [abhigyankishor.ga](https://www.abhigyankishor.ga)
  * Go to [this](https://www.abhigyankishor.ga/posts/2022/05/how-to-custom-domain/) blog post to see how I did it :)

* [x] Heading font size.. kinda small :(
  * edit `main.css`
* [x] Figure out emojis :)
  * `enableEmoji = true` for rendering emojis in markdown
  * [emoji cheatsheet](https://www.webfx.com/tools/emoji-cheat-sheet/)
  * However, if you are passing something in the config.toml and want emojis then use `emojify` as shown in [here](https://stackoverflow.com/questions/60161106/how-can-i-insert-an-emoji-on-config-toml-in-hugo-rendered-website)
* [x] Maybe google analytics?
  * ~~All done! check out [this](https://www.abhigyankishor.ga/posts/2022/05/google-analytics-and-hugo/) blog post to see how I did it :)~~
  * Turns out hugo already has a good [template](https://gohugo.io/templates/internal/) for it.
  * Best to use with (hugo.IsProduction) to avoid google_analytics in localhost.
* [x] Google Site Verification
  * I think this is a by-product of google analytics
  * The crawl request was successful and google is aware of my webpage :) 
* [x] Improved twitter card :)
  * will slowly update the other posts as well.
  * updated fronmatter so it looks much better now.

* [x] Improve the tags system
  * Tags now show on all list pages. For now it works.
  * Media query added so phone gets a slightly different layout :)