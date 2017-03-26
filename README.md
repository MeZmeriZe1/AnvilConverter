# AnvilConverter

A tool to convert .mcr mcregion worlds to .mca anvil format

Usage:

```java -jar "/Users/jazzwhistle/NetBeansProjects/dist/AnvilConverter.jar" /PathTo/PocketMine/worlds worldtoconvert```


The original .mcr files will be untouched, and the original level.dat renamed to level.dat_mcr
An new anvil level.dat is automatically generated to replace the mcregion version, so the server is ready to run after converion.
You can remove all the old .mcr files and level.dat_mcr if successfull, or revert by renaming level.dat_mcr to level.dat and deleting the .mca files


Code from https://www.mojang.com/2012/02/new-minecraft-map-format-anvil/
Copyright Mojang AB.
Don't do evil.
