# ShopChest
ShopChest - Spigot/Bukkit Plugin

This guide for ShopChest 1.18.
Repository is forked from Flowsqy_ShotChest.

## API
To use the API, you need to add the following repository and dependency in your maven project:

```xml
<repositories>
  <repository>
    <id>shopchest-repo</id>
    <url>https://epicericee.github.io/ShopChest/maven/</url>
  </repository>
</repositories>

<dependencies>
  <dependency>
    <groupId>de.epiceric</groupId>
    <artifactId>ShopChest</artifactId>
    <version>1.14-SNAPSHOT</version>
    <scope>system</scope>
    <systemPath>YOUR LIB FOLDER</systemPath>
  </dependency>
</dependencies>
```

You can find the javadoc here: https://epicericee.github.io/ShopChest/javadoc/

## Build
Clone this repository and use ``sh lib/install_local_depedencies.sh`` to import local dependencies.

Use BuildTools.jar with rev 1.17, 1.17.1 and 1.18 revision and remapped parameter.
Delibverables should be copied to lib-spigot.
- https://www.spigotmc.org/wiki/buildtools/
- https://blog.jeff-media.com/nms-use-mojang-mappings-for-your-spigot-plugins/

After importation, use ``mvn clean package`` or ``mvn clean install`` to build the project.
After the build succeeded, the ShopChest.jar is found in the ``/plugin/target/`` folder.

## Issues
If you find any issues, please provide them in the [Issues Section](https://github.com/EpicEricEE/ShopChest/issues) with a good description of how to reproduce it. If you get any error messages in the console, please also provide them.

## Download
This resource/plugin is found on the official spigot page [here](https://www.spigotmc.org/resources/shopchest.11431/).
You can also download the latest unstable builds on [this page](https://ci.codemc.io/job/EpicEricEE/job/ShopChest/).

