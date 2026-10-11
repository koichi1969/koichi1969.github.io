# koichi1969.github.io（GitHub Pages のトップアドレス）

`https://koichi1969.github.io/` を開いたときの行き先を決めるリポジトリです。中身は転送用のページだけです。

| ファイル | 役割 |
|---|---|
| index.html | トップ（`https://koichi1969.github.io/`）を開いたら「まいにち英単語」へ転送する |
| 404.html | 見つからない URL のとき。大文字が混ざっていれば小文字に直して開き直し、それでもなければ「まいにち英単語」へ転送する |
| .nojekyll | GitHub の変換処理を止める（ファイルをそのまま公開する） |

- 各アプリ本体は別のリポジトリです（例: `englishwords1800` → `https://koichi1969.github.io/englishwords1800/`）。アプリ側のページはこのリポジトリより優先されます
- `main` に push すると数分で反映されます
- 数学版など、アプリが増えたら index.html をアプリ一覧のページに変える予定です
