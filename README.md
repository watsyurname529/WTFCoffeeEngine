# WTF CoffeeEngine

This is a new implementation of the [WTFEngine](https://github.com/soulwire/WTFEngine/) in [CoffeeScript](http://coffeescript.org/).

I wanted to extend the functionality of the original engine, and in doing so I rewrote the engine using CoffeeScript. So here it is.
The implementation so far covers the basic functionality of the original WTFEngine, but is still is missing some features from the original, such as Google spreadsheet compatibility.

Currently the WTFCoffeeEngine supports initialization using an object inside the main.coffee file using the same format as the original WTFEngine.

Plans are to include the ability to read data from a JSON formatted file, Google spreadsheet capability, and the ability to dynamically change the generation lists without having to change the source code.

Please note that the CoffeeScript is almost certainly not pure idiomatic CoffeeScript as this is my first project using CoffeeScript or JavaScript.

# WTF Engine

Inspired by [WhatTheFuckShouldIMakeForDinner.com](http://whatthefuckshouldimakefordinner.com/), in 2011 [soulwire](https://github.com/soulwire) made [WhatTheFuckIsMyMashup.com](http://whatthefuckismymashup.com/) and released this simple tool, the [WTFEngine](https://github.com/soulwire/WTFEngine/), for generating similar websites.
