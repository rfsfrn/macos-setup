Dock
====

サイズ：
-------

拡大：
-----

拡大「する」

```sh
defaults write com.apple.dock 'magnification' -bool true
```

拡大するときのアイコンサイズを「72」にする

```sh
defaults write com.apple.dock 'largesize' -int 72
```

画面上の位置：
-------------

画面上の位置を「下」にする

```sh
defaults write com.apple.dock 'orientation' -string 'bottom'
```

ウインドウをしまうときのエフェクト：
-----------------------------------

ウインドウをしまうときのエフェクトを「スケールエフェクト」にする

```sh
defaults write com.apple.dock 'mineffect' -string 'scale'
```

ウインドウタイトルバーのダブルクリックで
----------------------------------------

ウインドウタイトルバーのダブルクリックで「しまう」

```sh
defaults write NSGlobalDomain 'AppleMiniaturizeOnDoubleClick' -bool true
```

ウインドウをアプリケーションアイコンにしまう
--------------------------------------------

ウインドウを「アプリケーションアイコンにしまう」

```sh
defaults write com.apple.dock 'minimize-to-application' -bool true
```

起動中のアプリケーションをアニメーションで表示
----------------------------------------------

起動中のアプリケーションをアニメーションで「表示しない」

```sh
defaults write com.apple.dock 'launchanim' -bool false
```

Dock を自動的に隠す／表示
-------------------------

Dock を自動的に「隠す」

```sh
defaults write com.apple.dock 'autohide' -bool true
```

起動済みのアプリケーションにインジケータを表示
----------------------------------------------

起動済みのアプリケーションにインジケータを「表示する」

```sh
defaults write com.apple.dock 'show-process-indicators' -bool true
```
