# 💬 Markov CLI
[![NPM version](https://img.shields.io/npm/v/markov-cli.svg?maxAge=3600)](https://www.npmjs.com/package/markov-cli)
[![NPM downloads](https://img.shields.io/npm/dt/markov-cli.svg?maxAge=3600)](https://www.npmjs.com/package/markov-cli)
[![Build status](https://travis-ci.com/lolPants/markov-cli.svg)](https://travis-ci.com/lolPants/markov-cli)
[![Dependencies](https://img.shields.io/david/lolpants/markov-cli.svg?maxAge=3600)](https://david-dm.org/lolpants/markov-cli)
[![Coverage Status](https://coveralls.io/repos/github/lolPants/markov-cli/badge.svg?branch=master)](https://coveralls.io/github/lolPants/markov-cli?branch=master)

##### CLI to analyze text into a Markov Chain and generate sentences from them.

## 💾 Installation
The package is on the NPM registry as `markov-cli`. Simply install it globally with your NPM client of choice.

## 🔧 Usage
Once installed globally, verify the command installed with `markov-cli --help`  
There are two subcommands you can use:

### `analyze`
Example usage: `markov-cli analyze input.txt`  
Where `input.txt` is a file containing input strings, separated by newlines.

This will output a file named `input.json` with markov chain data for use in the next subcommand.

### `generate`
Example usage: `markov-cli generate input.json`  
Where `input.json` is a markov chain file generated by the `analyze` command.

This will output a string generated using the markov chain.

## ❤ Thanks
* [weighted-random](https://www.npmjs.com/package/weighted-random)
* [This Article](https://hackernoon.com/automated-text-generator-using-markov-chain-de999a41e047)
