# pytale

> Server-side Hytale scripting using Python.

This plugin is for everyone that wants to create [Hytale](https://hytale.com/) plugins, but don't know how to code in Java.

Truth is, **i suck** at Java programming. Yes, Java was my first programming language of all, and I've started coding doing Minecraft mods and plugins. But I don't feel like coding Java anymore, so I made this mod!

---

### Installation

Well, this couldn't be harder. Just drag the latest version of `Pytale.jar` either from the releases or Curseforge to the `/Mods` folder, start your it, and you're ready to go!

---

### Usage

First, when loading the server, run:

```
/py stubgen
```

This will generate a file called `hytale.pyi`, its a stub file containing all classes, their attributes and methods extracted from the `HytaleServer.jar`.

Inside of your save folder _(which must have Pytale enabled)_, you'll se a `mods\com.cabrix_Pytale` folder, that folder will contain your scripts.

Some variables are always exposed.

```py
logger: HytaleLogger
plugin: PytalePlugin
```
