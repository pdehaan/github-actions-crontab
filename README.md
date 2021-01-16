# github-actions-crontab

Running GitHub Actions on a schedule.

https://github.com/pdehaan/github-actions-crontab/blob/master/.github/workflows/timer.yaml 
A simple task which runs an `echo` command on a simple schedule.

Oddly, even though I thought this would run roughly every 30 minutes, per https://github.com/pdehaan/github-actions-crontab/blob/75a093b7d2aa9caf35bfebb9ac41305a0c77092f/.github/workflows/timer.yaml#L6 and <https://crontab.guru/#*/30_*_*_*_*>.
Looking at the https://github.com/pdehaan/github-actions-crontab/actions output it only seems to run once per hour. Not sure if GitHub is throttling me, or something else is funny. 
