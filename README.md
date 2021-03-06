# youtube-ads-auto-skipper
This Chrome extension can skip Ads on YouTube automatically.

## 説明

YouTubeで動画を再生した際に表示される広告を自動で閉じてくれるChrome用拡張機能です。
PCにてChromeにインストールすると利用できます。
インストール手順は次です。

1. このリポジトリをクローンあるいは[`src`](https://github.com/oioigohan/youtube-ads-auto-skipper/tree/main/src)フォルダをダウンロード
2. [拡張機能を管理](chrome://extensions/)へ移動
3. ツールバー右の「デベロッパーモード」を有効にする
4. 「パッケージ化されていない拡張機能を読み込む」をクリック
5. ポップアップしたエクスプローラーにて[`src`](https://github.com/oioigohan/youtube-ads-auto-skipper/tree/main/src)フォルダを選択

## スキップできる広告

動画プレイヤー上に表示される広告全般

- 5秒待つとスキップができるようになるメインの広告
  - 通常は最低5秒待たなければいけないところも、今のところほぼ待ち時間なくスキップ可能
- xボタンで閉じるタイプのプレイヤー下部に表示される小さい広告
- 回答せずにスキップできるアンケート
- アプリのインストール用サイトなどにリンクされたボタンが一定時間表示される広告

広告のスキップに成功した場合はデベロッパーツールの`Console`にメッセージが出力されます。

## スキップできない広告

もともと人の操作でもスキップできない広告

- 5秒あるいは15秒前後のスキップができないタイプの広告

その他考えられるスキップできないケース

- 公式によって広告表示の仕様が変更された場合
- 今後新しく実装される広告

