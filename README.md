
# MyHome

- Fork from PiHome to support my Beaglebone Black :)

Original project at: [http://pihome.harkemedia.de](http://pihome.harkemedia.de)

#### MyHome 2.0 ####
User: `admin`
Pass: `pihome`


# Services

```
sudo crontab -e
```

Then, add:

```
#### PiHome CronJobs ####
*/5 * * * * php /home/www/cron/weather.php 
* * * * * php /home/www/cron/sunrise_sunset.php
* * * * * php /home/www/cron/gcal.php
* * * * * php /home/www/cron/caldav.php
```
