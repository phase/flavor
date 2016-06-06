# flavor
A Minecraft Server patching framework.

## Setting up the workspace
```
$ ./scripts/decompile.sh
# This will download a jar from Mojang's AWS and decompile it using the mappings in mappings/
# It will also extract the needed assets, like language files and the log4j config.
$ ./scripts/setupWorkspace.sh
# This will move the source files to src/main/java/ and patch them.
# The patches are needed because FernFlower isn't perfect.
```

## Recompiling
Running `mvn clean install` will create a runnable jar.
You can change the _pom.xml_ to set the main class.

## Credit
Thanks to...

* [MinecraftForge](https://github.com/MinecraftForge/FernFlower) for it's amazing fork of FernFlower.
* [md_5](https://github.com/md-5/SpecialSource) for SpecialSource and his work on CraftBukkit & Spigot.
* [Techcable](https://github.com/Techcable) & [Z750](https://github.com/Zbob750) for help along the way.