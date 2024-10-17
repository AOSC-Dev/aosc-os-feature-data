aosc-os-feature-data
===

This repository contains the feature metadata defined in
[AOSC OS Feature Marking Guidelines](https://wiki.aosc.io/developer/packaging/feature-marking-guidelines)
and are used in package management frontends such as
[oma](https://github.com/AOSC-Dev/oma) to inform users of system feature
installation and removal.

Format
---

The feature metadata is written similarly to that of APT repository metadata:

- `Feature`: Name of the feature marker
- `Functionality`: A short description for the feature; this item may be
  localised with `-$LANG` suffixes.

### Example

```
Feature: kde-graphical-environment
Functionality: KDE graphical environment
Functionality-zh_CN: KDE 图形界面

Feature: multimedia-playback
Functionality: Multimedia playback support
Functionality-zh_CN: 多媒体播放
```
