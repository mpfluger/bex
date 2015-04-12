## bex

Ever forget the sed one-liner to remove double newlines? Or the parameters to create an SSH tunnel? Bex is a very simple tool to remember your favorite commands and the command line switches you like to call them with. It comes with a small set of sane defaults and the rest is up to you. Enjoy ;)

## Install

Move `bex` to some folder in your `$PATH`:

```sh
cp bex /usr/local/bin
```

Configure the default directory to keep bex files (bexs) and optionally move the default bexs there. The default directory for bexs is set to `~/.bexs` in `bex`.

```sh
cp -R ./bexs ~/.bexs
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

You can set your favorite editor and the location of bexs in the top part of `bex`. Just change the relevant variables.

