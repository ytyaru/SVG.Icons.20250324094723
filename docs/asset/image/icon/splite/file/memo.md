# SVG外部参照

　SVGスプライトの外部参照をするとき、以下のようにパスやIDを指定する。

```html
<svg class="icon"><use href="./sprite.svg#clipboard"></use></svg>
```

　このとき、`file`プロトコル上だと参照できない。

　HTTPSプロトコル上で参照する必要がある。

　よってローカル上でHTTPSサーバを起動して動作確認した。

