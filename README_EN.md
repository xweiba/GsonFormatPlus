GsonFormatPlus

This is a plugin you can generate Json model from Json String.
**This Plugin is only for IntelliJ IDEA**.
which is base on [GsonFormat](https://github.com/zzz40500/GsonFormat) 
and more flexible and convenient. Welcome to issue and PR.

## Install
- Using IDE built-in plugin system on Windows:
  - <kbd>File</kbd> > <kbd>Settings</kbd> > <kbd>Plugins</kbd> > <kbd>Browse repositories...</kbd> > <kbd>Search for "GsonFormatPlus"</kbd> > <kbd>Install Plugin</kbd>
- Using IDE built-in plugin system on MacOs:
  - <kbd>Preferences</kbd> > <kbd>Settings</kbd> > <kbd>Plugins</kbd> > <kbd>Browse repositories...</kbd> > <kbd>Search for "GsonFormatPlus"</kbd> > <kbd>Install Plugin</kbd>
- Manually:
  - Download the [latest release](https://github.com/mars-men/GsonFormatPlus/releases) and install it manually using <kbd>Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Install plugin from disk...</kbd>
  - From official jetbrains store from [download](https://plugins.jetbrains.com/plugin/14949-gsonformatplus/)
  

Restart IDE.

## Usage
### 1.Use IDE menu

![Generate.png](https://raw.githubusercontent.com/sun-men/Figurebed/master/2020/03/12-11-12-47-gsonformat-insert.png)

### 2.Use hotkey

Default **Option + s**(Mac), **Alt + s** (win)

You can change the hotkey via: 

![修改快捷键.png](https://raw.githubusercontent.com/sun-men/Figurebed/master/2020/03/12-11-13-43-gsonformat-keymap.png)

### 3.Use Demo

![gsonformatgeneratorgif](https://raw.githubusercontent.com/sun-men/Figurebed/master/2020/03/12-11-18-54-gsonformat-generator.gif)

### 4.Setting

![gsonformatsettingpng](https://raw.githubusercontent.com/sun-men/Figurebed/master/2020/03/12-11-18-09-gsonformat-setting.png)




SETTING

| module  | value  | default | description  |
| --- | --- | --- | --- |
| Convert Method | object/arrayFromData | false   | Gson convert method |
| Generate | virgo mode | true   | virgo mode |
| Generate | generate comments | false   | generate comments |
| Generate | split generate | false   | split generate sub class |
| Bean | reuse bean | false   | TODO |
| Field | name suffix | true   | class suffix |
| Field | field(private/public) | true   | access level |
| Field | name prefix | true   | field name prefix |
| Field | use serialized name | true  | use serialized name  |
| Field | use wrapper class | true  | use wrapper class，eq: int convert Integer |
| Field | use lombok | true  | use lombok replace Getter/Setter |
| Field | use number key as map | true | use number key as map，TODO |
| Convert library | jackson/fastjson | true | jackson/fastjson convert library |


#### 5. Version Information

**Version 1.6.2 by xweiba**
- Support FastJSON2
- Upgrade IDEA plugin to version 1.5.2 
- Upgrade Gradle plugin to version 7.1
- Update README

**Version 1.6.1 by xweiba**
- Fix comment NPE

**Version 1.6.0 by wangzhejun**
- Support auto format
- Fix comment position
- Fix camel convert

**Version 1.5.8 by wangzhejun**
- Fix JSON camel bug
- Fix boolean property default `is` function
- Fix comment conflict

**Version 1.5.7 by wangzhejun**
- Fix some JSON5 format bugs

**Version 1.5.6 by mars-men**
- Remove JSON dialog `VK_ENTER` listener
- Update README

**Version 1.5.5 by mars-men**
- Upload to JetBrains plugin center

**Version 1.5.2 by wangzejun**
- Support field comments
- Support JSON5 format

**Version 1.5.1 by sun-men**
- Set default to Jackson annotations
- Support using Lombok annotations
- Code refactored in new version of IDEA

**Version 1.5.0 - 3 years ago**
- Fix several bugs
- Fix unlock setting window size

**Version 1.4.0**
- New: Support for Autovalue
- New: Support for Lombok
- New: Support for split generate class

**Version 1.2.2**
- Support field type modification
- Support opening GsonFormat with a shortcut, default is Option+S (Mac), Alt+S (Windows)
- Support field name modification
- Support adding field prefix
- Support multiple conversion libraries (Gson, Jackson, FastJSON, LoganSquare)
- Support private and public modes
- Support filtering out parent class properties
