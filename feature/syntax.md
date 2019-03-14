# twista 独自構文

twistaは本家Misskeyにはない独自構文もサポートしています。

独自機能をお探しですか？ → [twista 独自機能](original.md)

MisskeyがサポートするMFM(Misskey Flavored Markdown)はこちら → [文字装飾](https://joinmisskey.github.io/ja/wiki/usage/mfm/)

***

## `<nya>` - nyaize構文
catでないプロデューサーでもcatな文書にできます。例えば以下のように使います。
```
<nya>ねこになってみた</nya>
```
これを投稿すると以下のように見えます
> ねこににゃってみた

もし常にcatになりたいなら、設定からcatになることができます。

## `<!nya>` - denyaize構文
catなプロデューサーでも部分的に投稿のnyaizeをキャンセルすることができます。例えば以下のように使います。
```
<!nya>これならねこにならない</!nya>
```
これをcatなプロデューサーが投稿すると以下のように見えます
> これならねこにならない

使い時の例として、catなプロデューサーがSSを投稿する際などに使えます。アイドルが勝手にcatにならなくなります。