#### Version 18.1

- Added tweet-command. Search tweets, send tweets and send latest APOD, quote or proverb.
- Removed unavailable System-cmd info.
- Minor changes.

#### Version 17.8

- Added index-argument to RSS-command. Read RSS of specified index.
- Added list-argument to RSS-command. Lists all feeds set in Settings-page.


#### Version 17.7

- Added RSS-command. Use settings page to set feeds to read and use rss-command to read the feeds

#### Version 17.6

- Added startup-commands. Use Settings-page to set one or more commands to execute when app starts.

#### Version 17.5

- Added Settings-page and several settings for commands. Access: Menu->Settings.
- Premium-purchase now in Settings-page.
- Added Help-command to Menu.
- Internal updates.

#### Version 17.4

- Readded quakes-command. Uses now USGS earthquake feed to show latest quakes.

#### Version 17.3

- Added link to new ttmsg-app to info-command. ttmsg is messaging app based on MQTT.
- Changed versioning to YEAR.RELEASE
- Removed quakes-command since data source, kuakes.com, doesn't exist. Will be
  replaced in the future by data from USGS.
- Added civil, nautical and astronomical sunrise/sunset times to sun-command (when applicable).
- Internal updates.

#### Version 1.6 (11.02.2017)

- Arrow up is now showing more than just latest command in command history.
- Added M (Memory)and R (Restore) buttons. Use M to add text from textfield to memory and R to restore text to textfield.
- Updated 3rd party libraries.
- Bug fix. Nearby command now has URL to placemark (if available).
- Added system-command to show information about the device including hardware, locale and screen.

#### Version 1.5 (06.02.2017)

- Results of "location nearby" command are now sorted by distance from nearest to farthest.

#### Version 1.4 (06.01.2017)

- Added nearby-parameter to location-command. Search nearby points-of-interest.

#### v1.3 (08.12.2016)

- Added rev and revsay options to proverb and quote commands. Rev reverses text and revsay speaks reversed text (it can be quite funny).

#### v1.2 (23.10.2016)

- Changed APOD start date from 1.6.1995 to 16.6.1995.
- Does not stop music when saying quote or proverb.
- Added URL schemes clp:// and clp4ios:// to execute commands.
- Added N=number and +=space to username format in uname-command.
- Added quakes-command to show latest earthquakes.
- Added cls-command.
- Updated code to Swift 3.

#### v1.1 (01.09.2016)

- Added say-parameter to proverb and quote commands. Speaks the quote/proverb using given locale or default en-GB locale.
- Added link to Bing maps in location-command.
- Added Settings-command.
- Added check for new version when starting the app.

#### v1.0 (24.08.2016)

- Initial version.

