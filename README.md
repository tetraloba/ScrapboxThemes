# ScrapboxThemes
Scrapbox用のテーマ(CSS)です。  
- ページ一覧を1行1ページのコンパクトに表示する(compact.css)
- 背景を`#000000`の真っ黒にする(trueDark.css)

## 使用方法
Scrapboxの[UserCSS](https://scrapbox.io/help-jp/UserCSS)機能を用いて反映します。  

例えば、
compact.cssを反映させたい場合は、タイトルが`settings`または`ユーザ名`であるページに、以下のように記載してください。
```
code:style.css
    ここにcompact.cssの中身をコピー・アンド・ペーストする
```
`settings`に記載した場合は、プロジェクト内で、全てのユーザに反映されます。  
`ユーザ名`に記載した場合は、プロジェクト内で、そのユーザのみに反映されます。

同ソースを[Scrapboxのページ](https://scrapbox.io/tetraloba/themes)でも公開しておりますので、以下をそのままコピペしても反映されると思います。  
こちらの方がソースはスッキリしますが、やや読み込みが遅いかもしれません。
```
code:style.css
    @import "/api/code/tetraloba/themes/compact.css";
```
