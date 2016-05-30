# Whis Firefox autoconfig

Quick job to disable some of the things I don't like in firefox. Thanks to Cliqz for the initial project this is based on.

* sending messages to mozilla servers
* inability to run unsigned extensions ...

The mechanism to put those settings is called 'autoconfig'.

## Setup

Look here for autoconfig intro: http://pascal-mietlicki.fr/en/blog/post/work/firefox-autoconfig/

Enable global autoconfig by:
* copy `autoconfig.js` to `<FIREFOX INSTALLATION DIR>/default/pref`
* copy `firefox.cfg` to `<FIREFOX INSTALLATION DIR>`
