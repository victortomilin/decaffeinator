# decaffeinator
> No more tears, no more pain, no more coffeescript...

## Features

This tool can convert your CoffeeScript file to es6 and will convert markup based on React DOM fabricator to JSX. No routine. Save your time and be happy.

## Installation

Just do the following bunch of commands:

```sh
git clone git@github.com:victortomilin/decaffeinator.git
cd decaffeinator
sh install
```

The script will automatically set up dependencies and add an own bin folder to the `PATH` variable to your `.bashrc` or `.zshrc` files to make you able to use "decoffeinator" as a command in your terminal.

## How to use

If you are ready and have a target to get rid of coffee in some file then just type the following command in your terminal:

```sh
grind <file_name>
```

For example:

```sh
grind UglyComponent.coffee
```

In the end, you should get a new one file with the name `UglyComponent.js`. 

## Requirements

You need to have:
- git
- nodejs
- npm
