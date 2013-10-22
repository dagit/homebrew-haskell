# Homebrew-Haskell
Haskell related formulas for [Homebrew](http://brew.sh).

### Compatibility

*   These formulas should be compatible with **10.6 ≤ OS X ≤ 10.9**
*   They are _not_ heavily tested on versions prior to **OS X ≤ 10.6**

###### NOTE:
_I hope to address this by employing an automated testing system that includes older versions of OS X._

### How do I install these formulas?
Just `brew tap darinmorrison/haskell` then `brew install <formula>`.

_Read more about how Homebrew taps work [here](https://github.com/mxcl/homebrew/wiki/brew-tap)._

###### NOTE:
Some of these formulas may have name conflicts with existing formulas from other tapped repositories or from the main Homebrew repository at [mxcl/homebrew]. When that happens, you can still install the versions from this repository by using the fully qualified name `darinmorrison/haskell/<formula>`.

### Can I install these formulas without tapping the repository?
Of course! You can install any individual formula by specifying its URL:

    brew install https://raw.github.com/darinmorrison/homebrew-haskell/master/<formula>.rb

### Why the duplicates of  [mxcl/homebrew] formulas?
This repository exists to serve a few main purposes:

1. Provide a staging ground for new Haskell-related Homebrew developments: patches, new formulas, enhancements, etc.

2. Provide a collection of enhanced or niche Haskell-related formula—stuff that may not end up in [mxcl/homebrew] for whatever reason.

3. Provide a collection of formulas that favor Haskell conventions over Homebrew conventions whenever a choice along those lines must be made. 

### Docs
`brew help`, `man brew`, or the Homebrew [wiki][].

[mxcl/homebrew]:https://github.com/mxcl/homebrew
[wiki]:http://wiki.github.com/mxcl/homebrew
