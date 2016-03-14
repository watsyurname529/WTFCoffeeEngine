# WTF Engine

Inspired by [WhatTheFuckShouldIMakeForDinner.com](http://whatthefuckshouldimakefordinner.com/), in 2011 [soulwire](https://github.com/soulwire) made [WhatTheFuckIsMyMashup.com](http://whatthefuckismymashup.com/) and released this simple tool, the [WTFEngine](https://github.com/soulwire/WTFEngine/), for generating similar websites.

# WTF Coffee

In creating my WTFEngine site I wanted to extend the functionality of the engine, and in doing so I rewrote the engine using CoffeeScript. So here it is.
The implementation so far covers the basic functionality of the original WTFEngine, but is still is missing some features from the original, such as Google spreadsheet compatibility.

Currently the WTFCoffeeEngine supports initialization using an object inside the main.coffee file using the same format as the original WTFEngine.

Plans are to include the ability to read data from a JSON formatted file, and possibly include the Google spreadsheet capability.
