# OS-Install-Guide  
各OSのインストール手順（[ブータブルUSB](https://e-words.jp/w/%E8%B5%B7%E5%8B%95%E3%83%A1%E3%83%87%E3%82%A3%E3%82%A2.html#google_vignette)の作成）  

# [Ubuntu](https://ja.wikipedia.org/wiki/Ubuntu)

1. [ISOイメージファイル](https://ja.wikipedia.org/wiki/ISO%E3%82%A4%E3%83%A1%E3%83%BC%E3%82%B8)の用意
    1. [Ubuntuのダウンロード](https://jp.ubuntu.com/download)にアクセス
    1. [ダウンロード] を選択
    1. "ubuntu-24.04-desktop-amd64.iso" を任意の場所に保存（約5.7GB）

1. [ブータブルUSB](https://e-words.jp/w/%E8%B5%B7%E5%8B%95%E3%83%A1%E3%83%87%E3%82%A3%E3%82%A2.html#google_vignette)の作成  
    1. [Rutus](https://rufus.ie/ja/) (ルーファス) にアクセス
    1. "rufus-4.5.exe"を任意の場所に保存
    1. "rufus-4.5.exe"を起動
    1. USBメモリ (8GB以上) をPCに挿す
    1. [選択] から上記のISOイメージファイルを選択し [スタート] (下図)  
    ![image](https://raw.githubusercontent.com/mubirou/OS-Install-Guide/master/webp/202408101450.webp)  
    1. [ISOイメージモードで書き込む (推奨)] を選択

1. インストール
    1. 上記で作成した[ブータブルUSB](https://e-words.jp/w/%E8%B5%B7%E5%8B%95%E3%83%A1%E3%83%87%E3%82%A3%E3%82%A2.html#google_vignette)をPCに挿入し起動
    1. [BIOS (UEFI)](https://www.pc-master.jp/jisaku/bios-uefi.html)を起動
    1. USBメモリを優先的に起動させる
    1. 指示に従ってUbuntuをインストール

実行環境：Windows 11、[Ubuntu 24.04 LTS](https://wiki.ubuntu.com/NobleNumbat/ReleaseNotes/Ja)、[Rufus 4.5](https://rufus.ie/ja/)  
作成者：夢寐郎  
作成日：2024年08月10日

# [ChromeOS Flex](https://ja.wikipedia.org/wiki/ChromeOS_Flex)

* [ChromeOSとの違い](https://support.google.com/chromeosflex/answer/11542901?hl=ja&ref_topic=11618314&sjid=9172043556111588356-AP)
* [デバイスの最小要件](https://support.google.com/chromeosflex/answer/11552529?hl=ja&sjid=9172043556111588356-AP&visit_id=638588818416467419-2940016808&ref_topic=11551271&rd=1)など

1. [ブータブルUSB](https://e-words.jp/w/%E8%B5%B7%E5%8B%95%E3%83%A1%E3%83%87%E3%82%A3%E3%82%A2.html#google_vignette)の作成
    1. [Google Chrome](https://www.google.com/intl/ja/chrome/)から[Googleアカウント](https://accounts.google.com/)にログイン  
    （シークレットウィンドウでは不可）
    1. [Chrome ウェブストア](https://chromewebstore.google.com/)にアクセス
    1. [**Chromebook リカバリ ユーティリティ**](https://chromewebstore.google.com/detail/chromebook-%E3%83%AA%E3%82%AB%E3%83%90%E3%83%AA-%E3%83%A6%E3%83%BC%E3%83%86%E3%82%A3%E3%83%AA%E3%83%86%E3%82%A3/pocpnlppkickgojjlmhdmidojbmbodfm)を検索し [Chromeに追加]-[拡張機能を追加]
    1. [![image](https://raw.githubusercontent.com/mubirou/OS-Install-Guide/master/webp/202408102043.webp)]-[[**Chromebook リカバリ ユーティリティ**](https://raw.githubusercontent.com/mubirou/OS-Install-Guide/master/webp/202408102043.webp)] を選択し [始める]
    1. [Chromebookの識別] 画面で [リストからモデルを選択] し次の通り設定し [続行]  
        * メーカーを選択：**Google ChromeOS Flex**
        * 製品を選択：ChromeOS Flex
    1. USBメモリをPCに挿す
    1. [使用するメディアを選択してください。] で上記のUSBメモリを選択し [続行]-[今すぐ作成]
    1. "リカバリ メディアの作成が完了しました"と表示されたら [完了]！

1. インストール
    1. 上記で作成した[ブータブルUSB](https://e-words.jp/w/%E8%B5%B7%E5%8B%95%E3%83%A1%E3%83%87%E3%82%A3%E3%82%A2.html#google_vignette)をPCに挿入し起動
    1. [BIOS (UEFI)](https://www.pc-master.jp/jisaku/bios-uefi.html)を起動
    1. USBメモリを優先的に起動させる
    1. 指示に従ってChromeOS Flexをインストール

実行環境：Windows 11、[ChromeOS Flex](https://chromeenterprise.google/os/chromeosflex/)、Google Chrome 127、[Chromebook リカバリ ユーティリティ](https://chromewebstore.google.com/detail/chromebook-%E3%83%AA%E3%82%AB%E3%83%90%E3%83%AA-%E3%83%A6%E3%83%BC%E3%83%86%E3%82%A3%E3%83%AA%E3%83%86%E3%82%A3/pocpnlppkickgojjlmhdmidojbmbodfm)  
作成者：夢寐郎  
作成日：2024年08月10日

© 2024 夢寐郎
