# Safari Omnibar Extension

This extension support search from location bar without installing any native plugins into your system. It simple
javascript extension based on Safari 5 API.

To use it check settings in Safari Preferences. Chose you favorite search engine. This is Default Search Engine, it will be used in any time you typed simple text into Location Bar.

But sometimes you need to search over Facebook, Wikipedia or WolframAlpha, not by your selected Default Search Engine.
To do this just prefix search query by shortcut:

  * `?'` is your Default Search Engine
  * `g`' is 'Google'
  * `y`, `ya` is 'Yandex'
  * `!`, `y!` is 'Yahoo!'
  * `b`' is 'Bing'
  * `d`, `dd` is 'DuckDuckGo'
  * `wa` is 'WolframAlpha'
  * `f`, `fb` is 'Facebook'
  * `w`, `wp`, `wi` is 'Wikipedia'

For example, if your Default Engine it not Wikipedia, then you can type 'w Antoine de Saint-Exupéry' in Location Bar
and Safari open Wikipedia page about one greatest writer from Marseille.

If you using shortcut, then OmniBar will think what you not needed to use your default engine, so, it will exclude
Default Engine and will search for shortcut in all other.
