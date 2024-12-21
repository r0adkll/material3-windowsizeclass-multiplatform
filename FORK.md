# Fork

This repo is forked from https://github.com/chrisbanes/material3-windowsizeclass-multiplatform, since both it and the now included implementation of the windowsizeclass in [Compose Multiplatform](https://www.jetbrains.com/help/kotlin-multiplatform-dev/whats-new-compose-170.html#material3-material3-window-size-class) do not offer support for [ALL Window size classes](https://m3.material.io/foundations/layout/applying-layout/window-size-classes#374861a7-92c0-4ba1-ae14-c7388cefefb7) notably the Large and Extra-large sizes which is critical for proper Web/Desktop support.

## Installing

Installing this will consist of changing the maven library targets

| From                     | To                    |
|--------------------------|-----------------------|
| dev.chrisbanes.material3 | com.r0adkll.material3 |

