# HELP

## Ruby

+ [custom Ruby version installation](https://www.moncefbelyamani.com/how-to-install-xcode-homebrew-git-rvm-ruby-on-mac/)
+ **set** the **local** version with `echo "3.2.2" > .ruby-version`
+ **set** the **"global"** version with `echo "chruby ruby-3.2.2" >> ~/.zshrc`
+ check Ruby version and binary with `which ruby` that should output e.g. `/Users/kalamita/.rubies/ruby-3.2.2/bin/ruby`, it should never be `usr/local/bin` - that's the OS Ruby! 

+ `jekyll serve --open-url --livereload --disable-disk-cache --incremental` **rebuild** and **reload** the site **automatically** without cache
  + `--open-url` opens in browser
  + `--detach` runs the server in background
  + `--disable-disk-cache` disables caching to disk in non-safe mode
  + `--incremental` enables incremental rebuild (disables `Auto-regeneration`)
  + `--no-watch` disables rebuild of changes
  + `--livereload` uses _LiveReload_ to **automatically** refresh browsers
  + `--port <PORT>` listens to a specified port (default `4000`)
  + `--baseurl </URL>`  Serve the website from the given base URL

## Font awesome

one of the following
+ add `<link rel="stylesheet" href="https://use.fontawesome.com/releases/v6.2.1/css/all.css" crossorigin="anonymous">` to `cv.html`
+ download `.css` files following [fontawesome.com/docs](https://fontawesome.com/docs/web/setup/host-yourself/webfonts)
+ [//github.com/drewish](https://github.com/drewish/jekyll-font-awesome-sass)

## Exclude files from build

add `exclude: [<filename>,...]` in `_config.yml`

## Layout

Should I style `body` and `main` or just `div#main` and `div#content`?
