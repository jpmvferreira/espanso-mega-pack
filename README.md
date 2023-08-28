## About
A collection of curated home built packages for the cross-platform text expander [Espanso](https://espanso.org/).

## Packages Included
In this repository you will find the following packages:

- **greek-letters-improved**: A package containing most of the Greek alphabet and some common variatons using Latex based naming scheme
- **markdown-shortcuts**: A simple package to make writing Markdown easier
- **math-symbols**: Displays math symbols using Latex based naming scheme
- **combining-characters**: Modifies characters with a collection of symbols e.g.: à, â, a⃗, a̅, a⃜
- **super-sub-scripts**: A collection of subscripts and superscripts with Latex based naming scheme

## Available Triggers
Inside the folder for each package you will see a `README.md` file. This file will include all of the provided triggers provided by that package.

## Installation
There are two ways to install any of these packages, directly from this Git repository or from the [Espanso Hub](https://hub.espanso.org/). The difference between them is that by installing a package via this Git repository you will get the latest updates as soon as I publish them, whereas via the Espanso Hub you have to wait for the package to be approved and will be provided a version number.

To install any of the packages directly from this repository open up a terminal and write
```
espanso install <package name> https://github.com/jpmvferreira/espanso-packages-mega-pack.git --external
```

To install it via the Espanso Hub open up a terminal and write
```
espanso install <package name>
```

Where `<package name>` should be replaced by any of the previously mentioned packages.

## Contributing
There are still **a lot** of triggers that are missing here, when compared to all possible unicode symbols typically used in math/physics. If you find any trigger that you believe should be present in one of these packages, do not hesistate in opening up a pull request or an issue! The same applies if you happen to have a suggestion, improvement or discussion of any type.

## References
The main references I used to write these packages were:
- **[Compart.com/Unicode](https://www.compart.com/en/unicode):** An agregator of Unicode symbols that features organization into [categories](https://www.compart.com/en/unicode/category) (e.g.: modifier symbols, math symbols, etc.) and searching by name and by symbol.

- **[symbl.cc](https://unicode-table.com/en/):** Another agregator for Unicode symbols that features organization in [collections](https://unicode-table.com/en/sets/) (e.g.: arrows, math symbols, greek symbols, etc.) and searching by name and by symbol.

- **[Julia Manual - Unicode Input](https://docs.julialang.org/en/v1/manual/unicode-input/#Unicode-Input):** Lists Unicode characters that can be entered via tab completion of LaTeX-like abbreviations in the Julia REPL.

Other references which I have came about while searching around that were also useful:

- [Wikibooks - Unicode List of Useful Symbols](https://en.wikibooks.org/wiki/Unicode/List_of_useful_symbols): Smaller curated list of the most useful Unicode symbols.

- [joom/latex-unicoder.vim](https://github.com/joom/latex-unicoder.vim): Dump of Latex symbols available and their unicode counterpart.

- [Wikipedia - Combining Characters](https://en.wikipedia.org/wiki/Combining_character): List of combining characters.

- [Wikipedia - Mathematical Symbols by Subject](https://en.wikipedia.org/wiki/List_of_mathematical_symbols_by_subject): List of mathematical symbols.

- [Wikipedia - Greek Alphabet](https://en.wikipedia.org/wiki/Greek_alphabet): List of Greek alphabet letters.

- [Wikipedia - Unicode Subscripts and Superscripts](https://en.wikipedia.org/wiki/Unicode_subscripts_and_superscripts): List of subscripts, superscripts, overscripts and underscripts

## License
This package is licensed under the MIT license.

For further information refer to the [LICENSE.MD](./LICENSE.md) file available in this repository.
