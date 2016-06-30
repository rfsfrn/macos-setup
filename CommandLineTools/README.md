Command Line Tools のインストール
---------------------------------

**Command Line Tools** をインストールすると、 **Homebrew** でも利用されている **Git** など、基本的な開発ツールが利用できるようになります。

ターミナルを起動して、インストールコマンドを実行します。
まずは、「command (⌘) + Space」キーを押して、 **Spotlight** を起動してください。
検索ウインドウが表示されたら、 「 **terminal** 」 と入力し、「 **ターミナル** 」を起動しましょう。

以下のコマンドをターミナルから実行し、 **Command Line Tools** がすでにインストール済みかどうか確認します。

```sh
xcode-select --print-path
```

インストール済みであれば次のように出力されます。

```sh
/Library/Developer/CommandLineTools
```

> **NOTE**: オペレーティングシステムのインストール後には **Command Line Tools** はインストールされていません。

ターミナルから以下を実行して、 **Command Line Tools** をインストールしましょう。

```sh
xcode-select --install
```

**Command Line Tools** のインストールが完了後、 **Homebrew** をインストールする準備が整います。
