# :musical_keyboard: Karabiner-Elements Configuration
by Dr Liang Jin

## :zap: Quick Start
```bash
git clone https://github.com/drliangjin/.karabiner.d.git && ln -sf ~/.karabiner.d ~/.config/karabiner
```
- - -

<p align="center"><img src="/assets/images/davy_jones.jpg" alt="davy_jones"/></p>
<p align="center">
  <b><a href="#introduction">Introduction</a></b>
  |
  <b><a href="#features">Features</a></b>
  |
  <b><a href="#installation">Installation</a></b>
  |
  <b><a href="#resources">Resources</a></b>  
  |
  <b><a href="#features">FAQ</a></b>  
</p>

- - -

## :scroll: Introduction

This is my configuration for [Karabiner-Elements](https://pqrs.org/osx/karabiner/), a powerful and low-level keyboard manipulation tool. **Karabiner** is one of the main reasons I choose to stay with macOS while there are too many troubles to implement the same/similar layout in GNU/Linux distributions (I really tried...maybe later...).

## :sparkles: Features

### Modifiers

| From                    | To                      | Press Alone                   | Device         |
|-------------------------|-------------------------|-------------------------------|----------------|
| <kbd> Ctrl </kbd>       | <kbd> Hyper </kbd>      | <kbd> F18 </kbd>              | -              |
| <kbd> Command </kbd>    | <kbd> Option/Alt </kbd> | <kbd> F19 </kbd>              | Apple Keyboard |
| <kbd> Option/Alt </kbd> | <kbd> Command </kbd>    | <kbd> F20 </kbd>              | Apple Keyboard |
| <kbd> Caps Lock </kbd>  | <kbd> Ctrl </kbd>       | <kbd> ESC </kbd>              | -              |
| <kbd> Enter </kbd>      | <kbd> Ctrl </kbd>       | <kbd> Enter </kbd>            | -              |
| <kbd> Shift </kbd>      | <kbd> Shift </kbd>      | <kbd> ( </kbd> <kbd> ) </kbd> | -              |

### Switchers (mimic Ubuntu Unity)


### Launchers (mimic Ubuntu Unity)

### Dash (mimic Ubuntu Unity)

### Editing (mimic Emacs)

| Key                              | From | To (key_code)    | Mimic (Emacs Function)  |
|----------------------------------|--------|----------------|-----------------|
| <kbd> Ctrl </kbd> <kbd> g </kbd> | `NA`   | `esc`            | `keyboard-quit` |
| <kbd> Ctrl </kbd> <kbd> d </kbd> | `NA`   | `delete_forward` | `delete-char`   |
| <kbd> Ctrl </kbd> <kbd> h </kbd> | `NA`  | `delete_or_backspace`  |                 |
| <kbd> Ctrl </kbd> <kbd> w </kbd> |      | `cmd + c`               |                 |
| <kbd> Ctrl </kbd> <kbd> y </kbd> |      | `cmd + v`               |                 |
| <kbd> Ctrl </kbd> <kbd> s </kbd> |      | `cmd + f`               |                 |
| <kbd> Ctrl </kbd> <kbd> b </kbd> |      | `left_arrow`               |                 |
| <kbd> Ctrl </kbd> <kbd> f </kbd> |      | `right_arrow`               |                 |
| <kbd> Ctrl </kbd> <kbd> n </kbd> |      | `down_arrow`               |                 |
| <kbd> Ctrl </kbd> <kbd> p </kbd> |      | `up_arrow`               |                 |
| <kbd> Ctrl </kbd> <kbd> a </kbd> |      | `home`         |    `move-begining-of-line`             |
| <kbd> Ctrl </kbd> <kbd> e </kbd> |      | `end`            | `move-end-of-line`                |
| <kbd> Ctrl </kbd> <kbd> v </kbd> |      | `page_down`      | `scroll-up-command`                |
| <kbd> Ctrl </kbd> <kbd> i </kbd> |      | `tab`            | `forward-button`        |

## :hammer_and_wrench: Installation
```bash
brew cask install karabiner-elements
```

## :loudspeaker: Updates

## :construction: Development

## :medal_military: Acknowledgement

## :open_book: Resources

## :raising_hand_woman: FAQ
