# cloudera
<div align="center">
<img src="https://github.com/paulvid/emr_to_cdp/raw/master/data/cloudera_logo_darkorange.png" width="820" height="100" align="middle">
</div>

# Schedule the script
## Cron Job

You may have to set the Execute permission on your script first:
```
chmod +x /home/govind/db_backup.sh
```
Yes, this has to be run by a cron job (or manually but what would be the point?)
If you have SSH access to your server:
```
crontab -e
0 0 * * * /home/govind/cron/db_backup.sh > /dev/null 2>&1
```
