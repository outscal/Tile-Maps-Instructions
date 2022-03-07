# Tile Map Workflow

Now that you are aware about the components, Can you take a guess on the steps on how to add tilemaps to your game?

![](https://media.giphy.com/media/BpadRS0HKJ7Irh150L/giphy.gif)

Here is a general workflow with steps that you should follow:

## Create a Tilemap that you will paint your Tiles on. A Grid GameObject is also automatically created as a parent to the Tilemap in the process.

![Grid](https://user-images.githubusercontent.com/44625252/156932095-f33ff45b-df0e-40b1-850a-6c927fa7f8d4.png)

## Create Tile Assets directly, or generate Tiles automatically by bringing Sprites into the Tile Palette window.

![](https://user-images.githubusercontent.com/44625252/156932124-d9ef09d3-2034-4ab8-a452-80d6a7dba210.png)

Once you have the tile assets ready, you can drag and drop:

![](https://user-images.githubusercontent.com/44625252/156932347-abbf8b96-3cfe-4625-abce-ed5900e07d5a.png)

## Create a Tile Palette that contains your Tile Assets and use a variety of painting Brushes to Paint onto Tilemaps.

![](https://user-images.githubusercontent.com/44625252/156932360-e9a86007-08b7-41e3-a6ff-0c2009be75c3.png)

## You can attach the Tilemap Collider 2D component to your Tilemaps to have them interact with Physics2D.

![TileMap_Coliider](https://user-images.githubusercontent.com/44625252/156932437-5942254a-1107-4099-8cfc-43781e696dc7.png)

## Use the select/erase tools or Brush to paint your tiles in the scene and make changes accordingly

![](https://user-images.githubusercontent.com/44625252/156932512-1e9e11b9-3a39-428c-a81c-0ab89e209ddb.png)

Some common tools are Select tool, Brush tool, Erase tool etc..., you can hover your mouse pointer over each to see what each does.

The below snippet shows a basic usage of brush and erase tool to add tiles to the grid and also remove if required.

![](https://user-images.githubusercontent.com/44625252/157039209-92f7cbb4-bb96-445c-ab5e-39bfa436b15e.gif)

Have you designed your level yet? With the above knowledge, go ahead and design your first level for any 2D platformer.

![](https://media.giphy.com/media/bDU40XiztDAiEPyxiN/giphy.gif)
