# EACS - Equalizer APO Config Switcher

[![Build status](https://github.com/psidex/EACS/workflows/Go%20Build/badge.svg)](https://github.com/psidex/EACS/actions)
[![Go Report Card](https://goreportcard.com/badge/github.com/psidex/EACS)](https://goreportcard.com/report/github.com/psidex/EACS)
[![Ko-fi donate link](https://img.shields.io/badge/Donate-Coffee-orange.svg?style=flat&colorA=35383d)](https://ko-fi.com/M4M18XB1)
[![Ethereum donate link](https://img.shields.io/badge/Donate-Ether-5965a2.svg?style=flat&colorA=35383d)](https://etherscan.io/address/0x54A8Fe0C28B9DD4940266A78d70f11B621735A97)

A small Windows tray app that allows you to quickly switch between using different [Equalizer APO](https://sourceforge.net/projects/equalizerapo/) configuration files.

Inspired by [Peace](https://sourceforge.net/projects/peace-equalizer-apo-extension/).

![screenshot](screenshot.png)

## Features

- Right click on the tray icon to bring up the menu.
- The tray icon is dimmed when there are no active configurations.
- Enable and disable configurations by clicking them (you can have as many enabled as you want).
- Edit, add, and remove configurations just by changing `.txt` files.
- Everything happens in the system tray, keeping things simple.
- You can choose to have only one or many configurations active at the same time.

## Warnings

- This won't work alongside other configuration programs such as Peace or the default configuration program that comes with Equalizer APO.
- This will overwrite Equalizer APO's `config.txt`. Make a backup if you need to!.

## Install

- Create a directory called "EACS" in `<Equalizer APO install location>\EqualizerAPO\config`.
- Download the latest `EACS.zip` from [releases](https://github.com/psidex/EACS/releases/latest).
- Extract the zip to the directory you just created.
  - If you did this correctly, the exe should be at `EqualizerAPO\config\EACS\EACS.exe`
- Run `EACS.exe`.
- You should now have the icon in your system tray, you can now left/right click on it to switch configurations.
- If you want it to run on system startup, create a shortcut to the exe and move it to the Windows startup directory (`%USERPROFILE%\Start Menu\Programs\Startup`).

## Edit / Add / Remove Configurations

The folder that contains all the configuration files will be located at `EqualizerAPO\config\EACS\config-files`.

See [the user guide](./GUIDE.md) for more detailed information.

## Credit

Icon is the [Control Knobs](https://emojipedia.org/control-knobs/) emoji from [Twitter](https://twemoji.twitter.com/).
