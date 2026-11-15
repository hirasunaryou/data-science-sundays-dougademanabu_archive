# 日曜の朝、300回。

「動画で学ぶデータサイエンス」の学びと思い出を振り返る公開アーカイブです。

**サイトURL（GitHub Pagesを有効にすると閲覧できます）**  
https://hirasunaryou.github.io/data-science-sundays-dougademanabu_archive/

## はじめての公開設定

[Settings → Pages](https://github.com/hirasunaryou/data-science-sundays-dougademanabu_archive/settings/pages) を開き、次を設定します。

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/(root)**
- **Save** を押す

初回公開には数分かかる場合があります。以後は main の更新で自動的に再公開されます。

## できること

- 2020〜2026年の296日付を、年・テーマ・活動・用語で絞り込み
- 84日付の要約、節目、テーマをまたぐ復習ルート
- 当日視聴を照合できた19日付・21件の動画リンク
- 関心テーマ、情報共有テーマ、動画視聴／情報共有の記載の構成比
- 議事メモに残る時間の手がかりとconnpass登録人数の断片的な記録
- 8枚の投影モードと、みんなで振り返る25分の進め方

グラフは記録から読み取れた範囲の集計です。全Slack投稿の集計でも、全開催回の正確な時間測定でもありません。欠測をゼロとせず、各図の説明を合わせて読んでください。

## ファイルと更新

- `index.html`: サイト本体。データ・CSS・JavaScriptを内包した静的HTML
- `archive.csv`: 掲載日付・回番号・テーマの一覧
- `.nojekyll`: GitHub Pagesで静的ファイルをそのまま配信する指定

サイトの表示データは `index.html` 内の `archive-data` というJSONにまとまっています。記録を変更した際は、関連する集計とCSVも更新してください。

特定の日付へのリンクは `#entry-YYYY-MM-DD` です。例: `#entry-2020-11-29`。
ローカルでは `index.html` を開くだけで検索・グラフ・投影モードを使えます。外部教材の閲覧には通信が必要です。

## 公開範囲と資料

公開用の要約と、一般に見られる教材・イベントへのリンクを掲載しています。原本議事録、会議録画、会議パスワード、Slack招待URLは含めていません。

サイトは軽量なためGitHub内で配信できます。今後の動画や大きな資料は別の保存先に置き、一般公開が確認できたファイルだけをここからリンクする構成を想定しています。

[勉強会のconnpass](https://learning-data-science-from-youtube.connpass.com/)
