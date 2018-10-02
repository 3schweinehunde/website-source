
* Test locally<br/>
  `jekyll serve --config _config.yml,_config.dev.yml --future`

* Upload to server<br/>
 `jekyll build && rsync -vr _site/ username@mittenin.at:/var/www/3schweinehunde`