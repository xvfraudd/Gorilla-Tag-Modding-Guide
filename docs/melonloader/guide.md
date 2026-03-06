# MelonLoader Installation Guide

::: tip
If you do not know how to find your game path, refer to [Locating Your Game](/docs//extra//locating-your-game.md)
:::

## 0. Preface

If you are migrating from BepInEx, you need to delete it from your Gorilla Tag installation.
Find your Gorilla Tag folder, and delete the following files:

```
BepInEx/
changelog.txt
doorstop_config.ini
winhttp.dll
```

## 1. Download MelonLoader

To get mods up and running, you need MelonLoader..
Downloads are on the [MelonLoader GitHub Releases](https://github.com/LavaGang/MelonLoader/releases/tag/v0.7.2). Pick the installer which matches your platform.

Once you open the installer, select Gorilla Tag from the list.
Then, make sure the version is **0.7.2, or higher**, then hit `install`.

![screenshot of melonloader installer](/assets/ver.png)

::: tip HOLD UP!
If the installation fails, report the issue to the Gorilla Tag Modding Hub Discord!
:::

## 2. Download GorillaLibrary

Congratulations, you've now successfully modded Gorilla Tag!

To ensure all your mods work, you need GorillaLibrary
Go to [GorillaLibrary's GitHub Releases](https://github.com/GorillaTagModdingHub/GorillaLibrary/releases), and download Gorillalibrary.zip

Unzip the file that you download.

Next, find your Gorilla Tag folder, and copy the contents of the folder into it.

::: warning HOLD UP!
**DO NOT** copy the base GorillaLibrary folder into Gorilla Tag's folder.
Instead, copy the **contents** of it (Mods/).
:::

## Finishing up

You've successfully modded your game!

To find mods to install, refer to the [Gorilla Tag Mod Hub](https://discord.gg/t8AmU8YVcs), or the [Gorilla Tag GameBanana](https://gamebanana.com/games/9496).

::: tip
If you're using Linux, you need to do one more step.
refer to [Linux](/docs/extra/linux) for this.
:::
