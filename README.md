

* Create goaccess report only for Episodes<br/>
  `zcat other_vhosts_access.log.*.gz | grep schweinehun | grep 3sh00 | goaccess - > report_episodes.html`

* Create goaccess report<br/>
  `zcat other_vhosts_access.log.*.gz | grep schweinehun | goaccess - > report.html`

* Test locally<br/>
  `jekyll serve --config _config.yml,_config.dev.yml --future`

* Upload to server<br/>
 `jekyll build && rsync -vr _site/ username@mittenin.at:/var/www/3schweinehunde`