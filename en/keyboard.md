---
title: Beringin Keyboard
description: Information on Writing Beringin
lang: en
---


# Beringin Keyboard

There are two major ways to write Beringin, one is using normal keyboard and the other is using special keyboard. This page shows you the differences between them and which one you should use.


## Table of Contents

- [Normal Keyboard](#normal-keyboard)
- [Special Keyboard](#special-keyboard)
- [Recommendation](#recommendation)


## Normal Keyboard

You can write Beringin by using normal Latin-based keyboard. This is done by assigning specific Latin letter to specific Beringin letter based on the [table here](latin-table) and by using the specified font from [here](../mnh48-beringin/en) that will display Beringin letters in place of Latin letters.

Pros:
- Easy to use
- Don't need to memorize that much of custom binding

Cons:
- Need to mix different fonts if you want to display both Beringin and Latin in the same sentence, this poses problem for certain software where only one font is allowed to be used on the whole instance

You could see the [table](latin-table) for all of the assigned keys for each Beringin letters, or you can read [this page](normal-keyboard) first to see the different types of assignment that were done for those letters.


## Special Keyboard

You can write Beringin by using special keyboard that access Unicode Private Use Area (PUA). This is done by assigning certain codepoints in PUA to specific Beringin letter as specified on this [table](unicode-table) and use the specified font from [here](../mnh48-beringin/en) that will display Beringin letters independent of Latin letters.

Pros:
- Don't need to mix fonts if you want to display both Beringin and Latin in the same sentence, this helps in certain software where only one font is allowed to be used on the whole instance as most operating system will just substitute Latin letters from other font if Beringin font is used

Cons:
- Need the font to be installed

You could see the [this page](special-keyboard) for more details on what types of keyboard software are available to write Beringin and how to write the letters out on those keyboards.


## Recommendation

For now, use the normal keyboard method unless you are using software that would require you to use the special keyboard method.

An enquiry has been sent to [Kreative Korporation](https://www.kreativekorp.com) who maintain the list of [Under-ConScript Unicode Registry](https://www.kreativekorp.com/ucsur/) (UCSUR) to add the codepoints used by Beringin to their registry but there has been no reply yet as of now. As such, please avoid using special keyboard method until they add it to the registry to avoid unnecessary re-assignment.

The registration is necessary to avoid other scripts from being assigned to the same codepoint, so that Beringin script will be displayed consistently across all systems in the world. Furthermore, non-Beringin font makers can also include Beringin script in their fonts alongside all other scripts if the codepoint are reserved for Beringin script.

Once Beringin script is added to UCSUR, then the special keyboard method would become the recommended way.

