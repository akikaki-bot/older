# What is this?
インターネットエクスプローラーを使っている人をGoogleChrome教に入信させるための物です。

# 仕組み

[こちらのサイトの物を参考...丸パク....リスペクトしました。](https://wemo.tech/1611)

```js
function isIE() {
    var userAgent = window.navigator.userAgent.toLowerCase();
    if ( userAgent.indexOf( 'msie' ) !== -1 || userAgent.indexOf( 'trident' ) !== -1 ) {
        return true;
    }
    return false;
  }
```
で判別できるんですって奥さん！

すごいですね！

# 実際に使ってみよう！

(~~https~~ってかんじのやつ出るけどただ判別するだけだし何も抜き取らないから安心してね)

[こっち](https://old.f5.si)
