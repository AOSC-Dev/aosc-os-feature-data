aosc-os-feature-data
===

This repository contains the feature metadata defined in
[AOSC OS Feature Marking Guidelines](https://wiki.aosc.io/developer/packaging/feature-marking-guidelines)
and are used in package management frontends such as
[oma](https://github.com/AOSC-Dev/oma) to inform users of system feature
installation and removal.

Format
---

The feature metadata is written in TOML, with support for localisation:

### Example

```
[kde-graphical-environment]
zh_CN = "KDE 图形界面"
en_US = "KDE graphical environment"

[multimedia-playback]
zh_CN = "多媒体播放"
en_US = "Multimedia playback"
```
