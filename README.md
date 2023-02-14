# FuzzyDict

FuzzyDict is a live spellchecker integrated with the fzf command-line fuzzy
finder. The tool uses the hunspell utility for spellchecking.

## Requirements

In order to run FuzzyDict, you'll need to have the following utilities installed:

* fzf: A command-line fuzzy finder.
* hunspell: A spellchecking utility.

## Installation

To install FuzzyDict, you can either install fzf and hunspell from your package
manager or download them from their respective GitHub repositories:

* [fzf](https://github.com/junegunn/fzf)
* [hunspell](https://github.com/hunspell/hunspell)

## Usage

To run FuzzyDict, simply execute the fuzzydict script. The script will check if
the required utilities are installed, and exit if any are missing.

While FuzzyDict is running, you can type any word and see its spellchecking
results. The results are displayed using the dict_view script, which shows the
spellchecking results in both English and Greek.

## Plan for future development

There is a plan to include an install script in a future release to make it
easier for users to get up and running with fuzzydict.
