```text
========================================================================
NOTICE OF ARCHIVAL AND COMPLIANCE
========================================================================

STATUS: UNMAINTAINED ARCHIVE
This repository functions strictly as a public archive for the 
preservation of open-source software. Following the deletion of the 
original upstream account, this repository was automatically designated 
as the root node by the hosting platform.

LICENSING AND COMPLIANCE
This archive operates in accordance with the repository's original 
open-source license terms, if present. The current custodian did not 
author this software and provides no warranty, maintenance, or updates.

TAKEDOWN AND DELETION REQUESTS
If you are the original author, copyright owner, or an authorized 
representative with the legal authority to request the permanent 
removal of this software, please submit a request by contacting 
the repository owner or custodian. Valid deletion requests will be
processed immediately upon verification of rights.
========================================================================
```
---
# lazy-kotlin-tui

A kotlin terminal ui library inspired by [lazygit](https://github.com/jesseduffield/lazygit) and [osu!framework](https://github.com/ppy/osu-framework/)

This library is work in progress!!!!

```kotlin
val screen = screen {
    size = Vector2(terminal.width, terminal.height)
    hasBorder = true
    children = mutableListOf(
        drawableText {
            size = Vector2(20, 5)
            position = Vector2(5 ,5)
            text = "hello there!"
            hasBorder = true
        },
        drawableRectangle {
            size = Vector2(30, 10)
            position = Vector2(30, 20)
            hasBorder = true
            filling = '#'
        }
    )
}

screen.render()
```

![image](https://github.com/user-attachments/assets/ac483a78-ff0a-495c-8c8f-ad86ad5239c8)

