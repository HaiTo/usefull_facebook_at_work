# UsefullFacebookAtWork

## Files
    - style.css: mainのスタイルシート
    - style_group.css: Group表示時のスタイルシート、rightColから必要な物を抜き出す
    - style_feed.css: メインフィード用のスタイルシート、rightColを消す

## usage
Stylishでそれぞれセクションを作って導入する、設定URLは以下の通り。
    - style.css: `facebook.com` (ドメイン上のURL)
    - style_group.css: `.*facebook.com/groups/.*` (正規表現)
    - style_feed.css: `.*facebook.com/$` (正規表現)

## LICENSE
MIT
