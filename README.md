# Hello Minecraft! Server Manager
开源协议为GPL v3, 详情参见http://www.gnu.org/licenses/gpl.html

## Introduction

HMCSM is a Minecraft server manager which supports Mod/Bukkit plugin management, logs/maps/worlds backup, auto installing(Cauldron, Spigot, Bukkit), UI customizing and so on.

## Contribution
If you want to submit a pull request, there're some requirements:
* IDE: Netbeans 8.1
* Compiler: Java 1.8 and libraries only supports Java 1.7(because of retrolambda).
* Do NOT modify `gradle` files.

## Code
* package `org.jackhuang.hellominecraft.util`: HMC development utilities.
* package `org.jackhuang.hellominecraft.svrmgr`: All HMCSM codes.
* Folder `HMCUtils/src/main/resources/org/jackhuang/hellominecraft/lang` contains language files.

## Pay Attention
* package `org.jackhuang.hellominecraft.util.logging`: repackaged Apache Log4j, Apache License 2.0.
* package `com.google.gson`: Apache License 2.0
* package `org.jackhuang.hellominecraft.lookandfeel.ui`: contains some NimbusLAF's code belonging to Sun Microsystems under LGPL.