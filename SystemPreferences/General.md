一般
====

アピアランス：
-------------

外観を「グラファイト」にする

```sh
defaults write NSGlobalDomain 'AppleAquaColorVariant' -int 6
```

メニューバーと Dock を暗くする
------------------------------

メニューバーと Dock を「暗くする」

```sh
defaults write NSGlobalDomain 'AppleInterfaceStyle' -string 'Dark'
```

メニューバーを自動的に隠す／表示
--------------------------------

メニューバーを自動的に「隠す」

```sh
defaults write NSGlobalDomain '_HIHideMenuBar' -bool true
```

強調表示色：
-----------

強調表示色を「グリーン」にする

```sh
defaults write NSGlobalDomain 'AppleHighlightColor' -string '0.752941 0.964706 0.678431'
```

サイドバーのアイコンサイズ：
---------------------------

サイドバーのアイコンサイズを「小」にする

```sh
defaults write NSGlobalDomain 'NSTableViewDefaultSizeMode' -int 1
```

スクロールバーの表示：
---------------------

スクロールバーの表示を「常に表示」にする

```sh
defaults write NSGlobalDomain 'AppleShowScrollBars' -string 'Always'
```

スクロールバーのクリック時：
---------------------------

スクロールバーのクリック時は「クリックされた場所にジャンプ」にする

```sh
defaults write NSGlobalDomain 'AppleScrollerPagingBehavior' -bool true
```

デフォルト Web ブラウザ：
------------------------

書類を閉じるときに変更内容を保持するかどうかを確認
--------------------------------------------------

書類を閉じるときに変更内容を保持するかどうかを「確認する」

```sh
defaults write NSGlobalDomain 'NSCloseAlwaysConfirmsChanges' -bool true
```

アプリケーションを終了するときにウインドウを閉じる
--------------------------------------------------

アプリケーションを終了するときにウィンドウを「閉じる」

```sh
defaults write NSGlobalDomain 'NSQuitAlwaysKeepsWindows' -bool false
```

最近使った項目：
---------------

この Mac と iCloud デバイス間での Handoff を許可
------------------------------------------------

使用可能な場合は LCD で滑らかな文字を使用
-----------------------------------------

