# Espanso packages mega pack
A collection of curated and home built packages for the cross-platform text expander Espanso.

## Packages included
- **greek-letters**: A package containing most of the Greek alphabet and some common variatons using Latex based naming scheme
- **markdown-shortcuts**: A simple package to make writing Markdown easier
- **math-symbols**: Displays math symbols using Latex based naming scheme
- **combining-characters**: Modifies characters with a collection of symbols e.g.: à, â, a⃗, a̅, a⃜
- **super-sub-scripts**: A collection of subscripts and superscripts with Latex based naming scheme


## Installation
To install any of the packages available on this repository simply open up a terminal and write
```
espanso install <package name> https://github.com/JPUnD/espanso-packages-mega-pack.git --external
```

Where `<package name>` should be replaced by any of the previously mentioned packages.

## Available matches
To see the matches for each specific package simply go to the corresponding directory in this repository and the `README.md` will display all of the available matches.

## Contributions
There are still **a lot** of triggers that are missing here, when compared to all possible unicode symbols in math/physics, but I don't use any of them.

However the more the better, so if you would like to add a variation of a given greek letter, your favorite mathematical symbol or some modifier that you use often, feel free to submit a pull request or open up an issue!

Also, I might have added some symbol with the wrong name or that you would like to have an alias for (e.g.: :hslash: expands to ℏ but you might also would like to call this :reducedplanck:). You can also open up an issue for that and we can add multiple triggers for the same replace, as long as no conflicts are detected.

## References
- [Compart/Unicode](https://www.compart.com/en/unicode): Massive agregator for all Unicode symbols organized into categories that also allows you to search a symbol knowing it's name and vice-versa. This is the best place to look for specific symbols by name or by category giving you a full organized overview of the Unicode standard.

- [Wikibooks - Unicode List of Useful Symbols](https://en.wikibooks.org/wiki/Unicode/List_of_useful_symbols): Smaller curated list of the most useful Unicode symbols.

- [joom/latex-unicoder.vim](https://github.com/joom/latex-unicoder.vim): Dump of Latex symbols available and their unicode counterpart.

- [Metaxal/latex-math-chars.rkt](https://gist.github.com/Metaxal/86be1b733c0f5ad4a0cf6c58cf140436): Same as the previous, but with the symbols written in Unicode notation.

- [Wikipedia - Combining Characters](https://en.wikipedia.org/wiki/Combining_character): List of combining characters.

- [Wikipedia - Mathematical Symbols by Subject](https://en.wikipedia.org/wiki/List_of_mathematical_symbols_by_subject): List of mathematical symbols.

- [Wikipedia - Greek Alphabet](https://en.wikipedia.org/wiki/Greek_alphabet): List of Greek alphabet letters.

- [Wikipedia - Unicode Subscripts and Superscripts](https://en.wikipedia.org/wiki/Unicode_subscripts_and_superscripts): List of subscripts, superscripts, overscripts and underscripts

## License
This package is licensed under the MIT license.

For further information refer to the file `LICENSE` available on this repository.
