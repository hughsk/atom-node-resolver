# node-resolver [![stable](http://badges.github.io/stability-badges/dist/stable.svg)](http://github.com/badges/stability-badges)

Atom plugin to jump to a module's file from its require statement.

![node-resolver](http://imgur.com/1JW3Txg.gif)

## Usage

1. Move your cursor to a require statement.
2. Open the command palette and run the "Node Resolver: Open Selected Dependencies" command.
3. The selected file will open.

Note that you can also select a range of text and run the command to open up
*all* of the files required within that range.

If you'd like to add a shortcut for this, I'd recommend adding the following
to your `keymap.cson`:

``` cson
'.workspace':
  'ctrl-alt-o': 'node-resolver:open-selected-dependencies'
```

## License

MIT. See [LICENSE.md](http://github.com/hughsk/atom-node-resolver/blob/master/LICENSE.md) for details.
