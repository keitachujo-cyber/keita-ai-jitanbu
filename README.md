# けいたのAI時短部 LP

このランディングページ（LP）は、モノトーンを基調とした「引き算のデザイン（fluence版）」を採用しています。

## 1. プレースホルダーの差し替え場所一覧
* `index.html` 内の以下の文字列を実際のリンクや情報に書き換えてください。
  * `__INSTAGRAM_URL__` : Instagramの登録・プロフィールURLに差し替え
  * `__CALENDAR_URL__` : Googleカレンダーの予定作成リンクに差し替え

## 2. Googleカレンダーリンクの作り方
以下のURL形式を使って、参加者用のカレンダー登録リンクを作成できます。
`https://www.google.com/calendar/render?action=TEMPLATE&text=【イベント名】&dates=【開始日時】/【終了日時】&details=【詳細・Zoom URL等】&location=【場所】`
* 日時は `YYYYMMDDTHHMMSSZ`（UTC形式）で指定します。日本時間21:00開始ならUTCは12:00になる点に注意してください。

## 3. 写真の入れ方
* `index.html` に画像を追加する場合は、画像ファイルをフォルダー内に配置し、`<img>` タグを使って読み込ませてください。

## 4. 文言変更のしかた
* `index.html` のテキスト部分（見出しや説明文）を直接書き換えることで、いつでも内容を自由に変更できます。