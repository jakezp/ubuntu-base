# Base Ubuntu docker with cron and supervisor 

Run with:
```
docker run -d --name='base-test' --net='bridge' \
      -v '/tmp/base/cron':'/var/spool/cron/crontabs/' \
      jakezp/base-test
```
