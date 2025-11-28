# K2ge3Airインストール方法
[[English]](README.md)

> [!CAUTION]
> 万一のため、事前に引き継ぎモードの有効化やトーク履歴のバックアップを行なっておくことをお勧めします。iPhoneでiPad版としてサブ端末ログインも可能なため、使用用途に合わせてご検討ください。製作者は署名切れによるデータの損失等に関して責任を負いかねます。あらかじめご了承ください。

## 脱獄環境 (Bootstrapを含む)
製作者の[リポジトリ](https://m4fn3.github.io/repo/index.html)をリンク先から追加したのち、K2ge3Airをインストールしてください。

## TrollStore環境
> [!WARNING]
> [TrollStore](https://ios.cfw.guide/installing-trollstore/)向けのipaを使用する場合はアプリのidを`jp.naver.line`から変更しないでください。LINEアプリを複製しての利用などアプリのidを変更して使用したい場合は、Sideloading向けのipaを使用してアプリのidを変えた上で、TrollStore経由でダウンロードしてください。

TrollStore向けのipaを[こちら](https://github.com/m4fn3/K2ge3Air_docs/releases/tag/TrollStore)からダウンロードして、TrollStore経由でインストールしてください。
> [!TIP]
> 既にAppStoreからインストールしている場合は、そのままTrollStoreでインストールして"Force Installation"を選択することでデータを保持しながらK2ge3Airに切り替えられます。
> 問題が発生した場合や公式のLINEアプリに戻したい場合は、AppStoreからLINEアプリを再インストールすれば安全に元に戻ります。

## Sideloading環境
> [!WARNING]
> Sideloading使用時は署名切れに十分ご注意ください。

Sideloading向けのipaを[こちら](https://github.com/m4fn3/K2ge3Air_docs/releases/tag/Sideloading)からダウンロードして、AltStoreやSideloadlyなどでインストールしてください。

## その他の環境
### LiveContainer
Sideloading向けのipaを[こちら](https://github.com/m4fn3/K2ge3Air_docs/releases/tag/Sideloading)からダウンロードして、LiveContainer内からインストールしてください。

### TrollFools
> [!WARNING]
> debの注入をサポートしているバージョンを使用してください。debの注入時に警告が表示される場合がありますが、問題なく動作します。
> 公式のLINEアプリ(`jp.naver.line`)以外に注入する場合は、Sideloading向けのdebをご利用ください。

TrollStore向けのdebを[こちら](https://github.com/m4fn3/K2ge3Air_docs/releases/tag/TrollStore)からダウンロードして、TrollFools経由でLINEに注入してください。

## よくある質問
### 複数のアカウントを使用したい / アプリを複製したい
Sideloading向けのipaを用いて、アプリのidを別の好きなものに変更してからTrollStoreやSideloadingなどでインストールしてください。通知を受け取ることはできません。
脱獄環境の場合は、Craneを利用することをお勧めします。この場合は適切な設定により通知を受け取ることができます。
なお、K2ge3Airのライセンスはアカウントごとに別途ご用意ください。

### 通知が来ない
Sideloading環境で通知を受け取るには、適切な権限を持つ証明書で署名を行う必要があります。また。アプリのidを`jp.naver.line`のままに保つ必要があります。ただし、無料のAppleIDでは通知を受け取ることはできません。TrollStore環境及び脱獄環境では、アプリのidが`jp.naver.line`である限り通知は機能します。




