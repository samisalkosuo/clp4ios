# clp4ios
Command Line Program for iOS is a command line program for iOS. It's not a shell but a collection of various commands using the greatest user interface of all time: the command-line interface.
 
[Command Line Program is available at App Store](https://itunes.apple.com/app/command-line-program/id1144342705?ls=1&mt=8).

A blog post about this: http://sami.salkosuo.net/command-line-program-for-ios.

# Contributing

Contributors welcome!

Do you have a comment/feedback/etc. or a wish for a command? See [CONTRIBUTING.md](./CONTRIBUTING.md) and open an issue or a pull request.

# 3rd party

Without many [great open source libraries](./3RD_PARTY.md), Command Line Program would not exist.
Thank You to them all!

# Commands

Following commands have been implemented:

- **Premium**, Info about Premium features.
- **apod**, Astronomy Picture of the Day by NASA.
  - date &lt;yyyy-mm-dd>, Astronomy Picture of the given Day.
  - random, Random Astronomy Picture of the Day.
  - today, Astronomy Picture of the Day.
- **ascii**, ASCII and extended ASCII, chars 0 - 255.
  - chr &lt;str or chr>, ASCII code of character(s) or string.
  - code &lt;dec or hex>, Character from the code(s).
  - control, Control characters.
  - ext, Extended ASCII characters.
  - print, Printable characters.
- **cls**, Clear console screen.
- **cowsay**, Cow says.
  - text &lt;text>, Text for cow to say.
- **curl**, Get URL content (text/plain & application/json).
  - get &lt;url> [LATLON || LL], GET request URL, LATLON or LL adds lat,lon params.
- **help**, List of available commands.
- **httpheaders**, Retrieve and list HTTP headers.
  - url &lt;http.url.to.web.site>, Web site address.
- **info**, Information about this program.
  - 3rdparty, Show 3rd party lib info.
- **location**, Current location.
  - nearby &lt;query>, Find nearby &lt;query>.
  - reverse, Current location address.
- **menu**, Add/delete custom command to/from menu.
  - add &lt;menu name> &lt;command>, Add new item to menu.
  - del &lt;menu name>, Delete item from menu.
- **network**, Device network info.
- **proverb**, Collection of proverbs around the globe.
  - cowsay, Random proverb by the cow.
  - random, Random proverb.
  - rev, Random proverb, but reversed.
  - revsay [locale], Speak reversed proverb.
  - say [locale], Speak proverb.
- **pwd**, Generate random passwords.
  - length &lt;length>, Password length.
  - symbols &lt;length>, Password with symbols.
- **quakes**, Show latest earthquakes.
  - dist, Order by distance from here.
  - mag, Order by magnitude.
- **quote**, Collection of various quotes.
  - cowsay, Random quote by the cow.
  - random, Random quote.
  - rev, Random quote, but reversed.
  - revsay [locale], Speak reversed quote.
  - say [locale], Speak quote.
- **roman**, Roman numeral converter and calculator.
  - ToInt &lt;Roman number>, Convert Roman number to integer.
  - ToRoman &lt;Integer>, Convert integer to Roman number.
  - add &lt;2+ Roman numbers>, Add Roman numbers
  - div &lt;2 Roman numbers>, Divide two Roman numbers
  - mul &lt;2+ Roman numbers>, Multiply Roman numbers
  - sub &lt;2 Roman numbers>, Subtract two Roman numbers
- **rss**, Read RSS feeds.
  - all &lt;no param>, Read all Settings-page RSS feeds.
  - feed &lt;url>, RSS feed URL.
- **sun**, Sunrise/sunset time in current location.
- **system**, Show various system info.
  - battery, Show battery info.
  - disk, Show disk info.
  - hardware, Show hardware info.
  - locale, Show locale info.
  - screen, Show screen info.
- **uname**, Generate random usernames.
  - format &lt;format>, Format: C=cons., V=vow., N=nr, +=space.

Note that some of the features require purchase of Premium features.

# Other stuff

Here in GitHub: https://github.com/samisalkosuo

iOS:
- [ttmsg](https://itunes.apple.com/us/app/ttmsg/id1225668824?ls=1&mt=8)
- [Gravity One](https://itunes.apple.com/app/gravity-one/id820432275?ls=1&mt=8)
- [Tycoon One](https://itunes.apple.com/app/tycoon-one/id982539073?ls=1&mt=8)

And if you are into scifi, see stories from the Strangers' Universe:
- [The Kaitian War](https://www.smashwords.com/books/view/409235?ref=samsal)
- [Truths, Half-Truths and Lies](https://www.smashwords.com/books/view/110000?ref=samsal)
- [Stories from the Strangers' Universe](https://www.smashwords.com/books/view/32121?ref=samsal)

Stories are available at Smashwords and other retailers including Apple iBooks.

