# Leekwars Tampermonkey

This is a tampermonkey script to export a json build directly from a leek page from [Leekwars](https://leekwars.com/)

You can install it through Greasy Fork [here](https://greasyfork.org/en/scripts/561259-leekwars-tools) (or use the code from script.js directly)

Once the script is added to tampermonkey, go to any leek page (the url must start with https://leekwars.com/leek/).

A button named "Export Leek JSON" should appear on the page

![alt text](https://i.imgur.com/psTphQJ.png "Title")

When clicking it, it will extract the leek build (stats, weapons, chips, components, capital etc) from the dom, and make a downloadable json file.

The json build can then be imported in [Restator](https://leek-wars-restator.vercel.app/)
