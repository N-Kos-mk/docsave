# docsave
ページの中身をまるっと持ってきてダウンロードするjs

## 使い方

次のコードをブックマークレットとしてブラウザに登録してください。

```js
javascript:(function(url){s=document.createElement('script');s.src=url;document.body.appendChild(s);})('https://N-kos-mk.github.io/docsave/script.js');
```

実行するとページが端末にダウンロードされます。

## どんなの
documentのouterHTMLをもってきて保存するだけ

## 注意
ブックマークレット自体でよく起きること

![image](https://github.com/N-Kos-mk/screen_capture/assets/82209854/9db28f85-420b-419b-bfbc-b96b9dcdb513)

（写真は別スクリプトから転用）
特定のサイトでは使えません！githubも。

## LICENSE
MIT
