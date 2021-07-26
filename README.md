# tiled-kaboom

This is a map-loader for [kaboom](https://kaboomjs.com/) to load [tiled](https://www.mapeditor.org/) JSON maps.

The terrain tiles came from [here](https://opengameart.org/content/tiled-terrains) and uses a terrain-set to make it really fast & easy to make cool maps in tiled.

You can see example-usage of the library [here](https://github.com/konsumer/tiled-kaboom/blob/main/index.html).

In your game, make sure the layer-format is "CSV" and compression is turned off. Embed your tilemaps.

You can test it out with this command:

```sh
npx serve
```