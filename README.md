# Metro

A digital signage app that shows realtime Washington Metro train arrivals.

You can select items using the up and down arrows. Press OK (enter) to select an item, and back (escape) to go back.

The home page shows a list of lines. Select a line to see the stations on the line, then select a station to see the next trains.

The app loads data from the [WMATA API](https://developer.wmata.com). The lists of lines and stations are cached since they don't change frequently. The next trains are loaded dynamically from the API and are refreshed every 15 seconds. 
 
### Config

Get an API key from the [WMATA API](https://developer.wmata.com) and enter it in `config.js`. 
 
### Navigation

The `typeahead.js` script is designed to let you select and follow links on any website. All you need to do is import the script and define a `selected` class in the CSS. In a desktop browser, you can also start typing the name of a link to select it.

