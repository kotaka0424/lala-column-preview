# lala-column-preview

LaLa Beauty Clinic「コラム」機能（WordPress実装前）の開発用プレビュー（社内確認用・noindex）。

- 想定URL: https://lalabeautyclinic.jp/column/ 配下（一覧 / category/<slug>/ / <記事slug>/）
- テーマCSSは本番サイトから読み込み、追加分は column.css（テーマの css/pages/column.css 想定）
- top/ artmake/ price/ などは本番ページの複製にコラム導線（COLUMNセクション・メニュー・フッター）を追加したもの
- 記事・サムネイルはダミー。生成元: build_column.py + コラム/articles/*.md
- 検索エンジンには登録されません（noindex / robots.txt）
