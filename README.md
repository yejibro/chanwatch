# chanwatch
A script for monitoring /kpg/

It will notify you about specified keywords appearing on the forum

Move it to your dotyeji/bin folder, chmod it and add to your cron tab:

    @reboot	screen -dmS chanwatch ~/.yeji/bin/chanwatch

If you're not running Mac OS X you probably will want to tune this script
a bit, so it will notify you properly about new posts
