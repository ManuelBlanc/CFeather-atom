[CFeather][homepage] is a package to provide C support for [Sublime Text 2]
[st2].

I created it because I'm not keen on Sublime's stock C package for the
following reasons:

1. It's conflated with supporting C++ at the same time.
2. It's scope taxonomy doesn't [KISS][kiss].

This package is targeted at [ISO C90 aka ANSI C89][lang]. For it to be picked
up by Sublime, you must first add the aforementioned stock package ("C++") to
the `ignored_packages` array in your settings file.

***

Licensed under [Creative Commons BY-SA 3.0][license].

[homepage]: https://github.com/frou/CFeather
[st2]: http://www.sublimetext.com/
[kiss]: http://en.wikipedia.org/wiki/KISS_principle
[lang]: http://en.wikipedia.org/wiki/C_(programming_language)#ANSI_C_and_ISO_C
[license]: http://creativecommons.org/licenses/by-sa/3.0/