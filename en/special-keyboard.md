---
title: Special Keyboard
description: Information on Writing Beringin on a special keyboard
lang: en
---

[← Back to Keyboard](keyboard.html)
{: .back}

There are two major ways to write Beringin, one is using [normal keyboard](normal-keyboard.html) and the other is using special keyboard. This page shows you the details on how to write Beringin using the special keyboard layout(s) specifically made for Beringin script.


## Table of Contents

- [Introduction](#introduction)
- [Unicode Registry](#unicode-registry)
- [Direct Input Keyboard](#direct-input-keyboard)
- [Input Method Editor Keyboard](#input-method-editor-keyboard)
- [Manual Input](#manual-input)
  - [Shortcut Keys](#shortcut-keys)
  - [Input Tools](#input-tools)
    - [Windows](#windows)
    - [Linux](#linux)
    - [macOS](#macos)
    - [Android](#android)
    - [Other Operating Systems](#other-operating-systems)
- [Unicode Table](#unicode-table)


## Introduction

You can write Beringin by using special keyboard that access Unicode Private Use Area (PUA). This is done by assigning certain codepoints in PUA to specific Beringin letter and use the specified font from [here](../mnh48-beringin/en) that will display Beringin letters independent of Latin letters.

Pros:
- Don't need to mix fonts if you want to display both Beringin and Latin in the same sentence, this helps in certain software where only one font is allowed to be used on the whole instance as most operating system will just substitute Latin letters from other font if Beringin font is used

Cons:
- Need the font to be installed

**Make sure you have installed the font for Beringin alphabet before attempting this, otherwise the alphabet will not appear in your system.** Any version of Beringin fonts provided [here](../mnh48-beringin/en) contains the characters needed to display Beringin, but the PUA version is recommended.


## Unicode Registry

Beringin script uses codepoints in the Unicode Private Use Area (PUA) which is maintained under private agreements between different parties. An enquiry has been sent to [Kreative Korporation](https://www.kreativekorp.com) who maintain the list of [Under-ConScript Unicode Registry](https://www.kreativekorp.com/ucsur/) (UCSUR) to add the codepoints used by Beringin to their registry but there has been no reply yet as of now. As such, please avoid using special keyboard method until they add it to the registry to avoid unnecessary re-assignment.

The registration is necessary to avoid other scripts from being assigned to the same codepoint, so that Beringin script will be displayed consistently across all systems in the world. Furthermore, non-Beringin font makers will also be able to include Beringin script in their fonts alongside all other scripts if the codepoint are reserved for Beringin script.

Once Beringin script is added to UCSUR, then the special keyboard method would become the recommended way.

There is no plan to propose for the independent encoding of the whole Beringin block in the normal (non-private) Unicode codepoint assignment yet because there are too many process involved and there is no formal entity that could back the assignment up yet. It is not impossible, there is just too many process involved and Unicode Consortium is too busy with assigning new encodings for much more important codepoint such as native scripts in other languages that is being used as the **only** writing system but still not in Unicode (unlike Beringin script where the languages using it (Malay and Indonesian) are already being written in Latin, Arabic and few other scripts that are already encoded in Unicode).


## Direct Input Keyboard

Direct input keyboard is the method where the keyboard layout is fixed and the characters are directly assigned to certain keypress. The keyboard you commonly used to write English, Arabic, Russian among others are direct input keyboard.

Currently, there is no direct input keyboard layout offered for Beringin script on any operating systems. Stay tuned.

There are plans for standalone keyboard application for Beringin alphabet and also extensions to support Beringin alphabet for certain existing keyboards on Android. No plan to support iOS since I don't have money to pay to Apple, all developers needs to pay them USD 99 per year just to release on iOS and that amount is a burden due to high currency change.


## Input Method Editor Keyboard

Input method editor (IME) keyboard is the method where there is no keyboard layout used. Instead, you type the Latin spelling of the word with Latin keyboard and the IME system will let you choose which letters, words or phrases you want to write, which will then convert to the characters you have chosen. The keyboard you commonly used to write Chinese, Japanese, Korean among others are IME keyboard.

Currently, Beringin alphabet is available to be used with the fcitx IME system on Linux operating systems. You can see the instruction to install it from [here](../fcitx-table-beringin/en).

There is no input method editor keyboard system offered for other operating systems yet. Stay tuned.


## Manual Input

It is possible to manually write the Beringin letters character if you know the exact codepoint of the letters and your operating system allows you to input Unicode characters using codepoint, or you have tool that gives you access to PUA or the whole Unicode.


### Shortcut Keys

A few operating systems allow you to write characters by its codepoint by the use of shortcut key, or third-party application. Please see [Unicode input](https://en.wikipedia.org/wiki/Unicode_input) on Wikipedia for more details. For example, typing `Ctrl+Shift+u` followed by the keys `e`, `b`, `a`, `4`, and `space` on Linux such as Ubuntu (and other Unix variants including ChromeOS) will gives you Beringin Letter Cheh (<span class="brgnpuachar"></span>) which is assigned to the codepoint U+EBA4 in PUA.

If your operating system does not support shortcut key, a third-party tools might exist to allow you enter the codepoint. For example, the application [Unicode Keyboard](https://play.google.com/store/apps/details?id=org.tiwu.unicodekeyboard&hl=en_US) allows you to do the same thing on Android.


### Input Tools

A few operating systems has tool that allow you to access, view and copy Unicode characters. In all of these tools, you need to go to the Private Use Area block out of the massive amount of Unicode blocks available. Beringin alphabet sits at the codepoint U+EBA0 to U+EBFF in that block.


#### Windows

On Windows, this tool is known as Character Map, but it is only limited to Basic Multilingual Plane (BMP) of the Unicode and not the whole Unicode. Fortunately, PUA is in BMP, so Beringin alphabet will be visible and selectable in Character Map. To access other characters outside of BMP, you will need to install third-party tools such as BabelMap.


#### Linux

On Linux, most of operating systems that has desktop environment will ship with this tool and the actual tool software and name varies from system to system. Most notable tools are Character Map (gucharmap) on GNOME desktop environment and Character Select (kcharselect) on KDE desktop environment. These tools usually has access to the whole Unicode but it depends on your configuration and settings.


#### macOS

On macOS, this tool is known as Character Viewer, but there is no details on the exact steps to access PUA, plus it will require different steps to configure between one mac version to the other, since macOS is a babysitter-type operating system who obscure all the technical stuff away from end user, their Character Viewer will only diplay what common users would usually access by default and not PUA. You might want a third party tool instead.


#### Android

On Android, you can install third party application to access Beringin alphabet.

1. [Character Pad](https://play.google.com/store/apps/details?id=com.husseinelfeky.characterpad&hl=en)
  - Tap on Menu button on top-left
  - Scroll the menu and tap on Private Use Area
  - Scroll down until you see the Beringin letter

2. [Unicode Pad](https://play.google.com/store/apps/details?id=jp.ddo.hotmist.unicodepad&hl=en)
  - Install Beringin font in the application as it has its own environment
  - Tap on the List tab if it was on other tab
  - Tap on the dropdown just under the tab
  - Select U+E000 Private Use Area
  - Scroll down until you see the Beringin letter


#### Other operating systems

Look for Unicode tools specific for your system, otherwise you're out of luck.


## Unicode Table

The Unicode table listing all assigned Beringin codepoints is [here](unicode-table.html).
