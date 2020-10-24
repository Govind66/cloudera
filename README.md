# cloudera
<div align="center">
<img src="https://github.com/paulvid/emr_to_cdp/raw/master/data/cloudera_logo_darkorange.png" width="820" height="100" align="middle">
</div>

# Schedule the script
## Cron Job
```
crontab -e
0 0 * * * /home/centos/cron/backup-db.sh > /dev/null 2>&1
```
