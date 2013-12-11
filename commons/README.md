# Commons / 共通要素

各トピックレポジトリにサブモジュールとして配置。  
Jadeの`include`を使って各トピックサイトから呼び出し。

## List of Commons

- `system/head.jade`: `<head>`内に記述する要素群
- `system/foot.jade`: `</body>`前に記述する要素群
- `contents/head.jade: コンテンツヘッダー要素群。e.g. ナビゲーション
- `contents/foot.jade`: コンテンツフッタ要素群。e.g. フッターリンク
- `modules/`: 共通モジュール群。