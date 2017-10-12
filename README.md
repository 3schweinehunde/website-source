

* Create goaccess report only for Episodes
  `zcat other_vhosts_access.log.*.gz | grep schweinehun | grep 3sh00 | goaccess - > report_episodes.html`

* Create goaccess report
  `zcat other_vhosts_access.log.*.gz | grep schweinehun | goaccess - > report.html`

