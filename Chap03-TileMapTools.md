# Tile Map GameObject Components

So, Tile Map Editor basically lets you work on the parts of the Tile Map GameObject which are:

## Grid

The Grid component is a guide which helps to align GameObjects, such as Tiles, based on a selected layout. The component transforms Grid cell positions to the corresponding local coordinates of the GameObject. The Transform component then converts these local coordinates to world space or global coordinates.

## Tilemap Renderer

The Tilemap Renderer component is part of the Tilemap GameObject. It determines how Tiles set on the Tilemap are rendered.

## Tile Assets

Tiles are Assets that are arranged on Tilemaps to construct a 2D environment. Each Tile references a selected Sprite, which is then rendered at the Tile’s location on the Tilemap Grid. Refer to the Creating Tiles documentation for information about preparing and importing Sprites for your Tiles, and the different methods for creating the Assets in the Editor.

