## bex

Ever forget the sed one-liner to remove double newlines? Or the parameters to create an SSH tunnel? Bex is a very simple tool to remember your favorite commands and the command line switches you like to call them with. It comes with a small set of sane defaults and the rest is up to you. Enjoy ;)

## Install

Create a symbolic link to `bex` in some folder in your `$PATH`:

```sh
ln -s $(pwd)/bex /usr/local/bin/bex
```

## Run

Lookup a command:

```sh
bex command
```

Edit/create the bex file for command:

```sh
bex -e command
```

List all bexs:

```sh
bex -l
```

## Help

```sh
bex -h
```

## Configure

You can set your favorite editor in the top part of `bex`. Just change the EDITOR variable.
