# WIAI: Where I'm at Ideally

This is the place we love but cannot visit during the pandemic.
Visit us in our [online hideaway](https://play.workadventu.re/_/global/fs-wiai.github.io/wiai-home/maps/erba_inner_yard.json#entry_middle_staircases).

## Tools We Use
* The map is available via Github Pages and playable on [WorkAdventure](https://workadventu.re).
* It is built using the [Tiled editor](https://www.mapeditor.org/).
* Most of our Graphics are made using [Gimp](https://gimp.org).
* Some tiles and most of the tutorial section below came with the [starter kit](https://github.com/thecodingmachine/workadventure-map-starter-kit).

## How to Participate

### Cloning the map
Start by cloning the map. If you are used to Git and GitHub, simply clone the map
to your computer using your preferred tool and [jump to the next chapter](#loading-the-map-in-tiled).

If you are new to Git, cloning the map means downloading the map to your computer.
To do this, you will need Git, or a Git-compatible tool. Our advice is to use
[GitHub Desktop](https://desktop.github.com/).

### Loading the map in Tiled

All maps can be found in the maps folder (ending in `.json`).
The sample map is in the file `map_initial_example.json`.
You can load these files into [Tiled](https://www.mapeditor.org/).

Now, it's up to you to edit the map and write your own map.

Some resources regarding Tiled:

- [Tiled documentation](https://doc.mapeditor.org/en/stable/manual/introduction/)
- [Tiled video tutorials](https://www.gamefromscratch.com/post/2015/10/14/Tiled-Map-Editor-Tutorial-Series.aspx)

### Crafting Tiles

We keep the project files for all tiles in the folder `maps/tileset_saves`.
Be sure to work mainly in your own tile set to prohibit merge conflicts on binary files.
If you are new, just create your own file in the aforementioned folder and export a PNG file to be used with the maps into the `maps` folder.

### About WorkAdventu.re maps

In order to design a map that will be readable by WorkAdventure, you will have to respect some constraints.

In particular, you will need to:

- set a start position for the players
- configure the "floor layer" (so that WorkAdventure can correctly display characters above the floor, but under the ceiling)
- eventually, you can place exits that link to other maps

All this is described in the [WorkAdventure documentation](https://github.com/thecodingmachine/workadventure/#designing-a-map).
Please be sure to check it out. 

### Pushing the map

When your changes are ready, you need to "commit" and "push" the changes back to GitHub.
Just wait a few minutes, and your map will be propagated automatically to the GitHub pages web-server.