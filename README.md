# Cop-It-Supreme-Bot
Supreme bot extension for Google Chrome. With this bot you can cop any item you want. Make with JavaScript, jQuery and Bootstrap 4.

### New in v1.1.3

__Replaced `If no items found with keywords, retry in X ms` by `Automatic start when items list is updated`.__
You must enable the countdown to use this option.
It works like this: 5 seconds before the start time (hour of the drop usually), the bot will check every seconds when the item list is updated. When it's done, bot will start instantly.

## Features

* You can run the bot in background, just open tab on "supremenewyork.com" page and start the bot on other tab.
* All sizes available (pants, top, shoes)
* USA, CANADA and EUROPE are supported.
* Multi keywords management, choose color and size
* Instant buy button on every item page
* Start at wanted time
* Bypass reCaptcha
* Auto-fill checkout page
* Retry when checkout failed
* Retry when keywords search failed

## Installation
Go to [chrome://extensions](chrome://extensions), then enable "Developer Mode" and drag the file `CopIt.crx` (you can find it in `bin` folder) on the page.

So if you want to build yourself with your modifications, just run `npm install`, then `gulp` and finally `gulp build`

Go to the settings page and fill it with all settings you want.

## Documentation
You can find all information on the settings page, you can contact me at support@copit.fr if you wanna know something.

