**jq-wrappers: a set of handy [jq](https://stedolan.github.io/jq/) wrappers to manipulate minified JSON files.**

## jformat

Format and save a minified JSON file into another file.
This will create the file `<input file>_format.json`

Usage: `jformat <input JSON file>`

## jvim

Format and open a minified JSON file into `vim`. The original file won't be
modified, only a working version will be opened into `vim`.

Usage: `jvim <input JSON file>`

## jless

Format and open a minified JSON file into `less`. The original file won't be
modified, only a working version will be opened into `less`.

Usage: `jless <input JSON file>`

## jdiff / jmeld

Format then open two minified JSON files into `diff` / `meld`. The original
files won't be modified.

## Installation

This repo required `jq`, `less`, `meld`, and `vim`.
Clone this repository, and add it to your `$PATH` envvar.

If needed, `chmod +x` the scripts.
