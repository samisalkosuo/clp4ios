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

- **Premium**, Premium features.
  - info, Info about Premium features.
  - purchase, Purchase Premium features immediately.
  - restore, Restore Premium features.
- **apod**, Astronomy Picture of the Day by NASA.
  - apikey [&lt;your API key>], View or set NASA API key.
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
  - reverse, Current location address.
- **menu**, Add/delete custom command to/from menu.
  - add &lt;menu name> &lt;command>, Add new item to menu.
  - del &lt;menu name>, Delete item from menu.
- **network**, Device network info.
- **proverb**, Collection of proverbs around the globe.
  - cowsay, Random proverb by the cow.
  - random, Random proverb.
  - say [locale], Speak proverb. Default locale en-GB.
- **pwd**, Generate random passwords.
  - length &lt;length>, Password length.
  - symbols &lt;length>, Password with symbols.
- **quakes**, Show latest earthquakes.
  - dist, Order by distance from here.
  - mag, Order by magnitude.
- **quote**, Collection of various quotes.
  - cowsay, Random quote by the cow.
  - random, Random quote.
  - say [locale], Speak quote. Default locale is en-GB.
- **roman**, Roman numeral converter and calculator.
  - ToInt &lt;Roman number>, Convert Roman number to integer.
  - ToRoman &lt;Integer>, Convert integer to Roman number.
  - add &lt;2+ Roman numbers>, Add Roman numbers
  - div &lt;2 Roman numbers>, Divide two Roman numbers
  - mul &lt;2+ Roman numbers>, Multiply Roman numbers
  - sub &lt;2 Roman numbers>, Subtract two Roman numbers
- **settings**, View/set/reset settings.
  - locales, List available locales.
  - maxQuakes &lt;nr of quakes to display>, Max quakes results in quakes-cmd.
- **sun**, Sunrise/sunset time in current location.
- **uname**, Generate random usernames.
  - format &lt;format>, Format: C=cons., V=vow., N=nr, +=space.
Note that some of the features require purchase of Premium features.

# Other stuff

Here in GitHub: https://github.com/samisalkosuo

iOS games:
- [Gravity One](https://itunes.apple.com/app/gravity-one/id820432275?ls=1&mt=8)
- [Tycoon One](https://itunes.apple.com/app/tycoon-one/id982539073?ls=1&mt=8)

And if you are into scifi, see stories from the Strangers' Universe:
- [The Kaitian War](https://www.smashwords.com/books/view/409235?ref=samsal)
- [Truths, Half-Truths and Lies](https://www.smashwords.com/books/view/110000?ref=samsal)
- [Stories from the Strangers' Universe](https://www.smashwords.com/books/view/32121?ref=samsal)

Stories are available at Smashwords and other retailers including Apple iBooks.

