# web-font-host
ただこのように，webフォント化したフォントをGithubにアップロードすることによって，ブログやwebページにおいてwebフォントとして使用することができます。  
However, by uploading webfont-ized fonts to Github, you can use them as web fonts on your blog or web page.  

# attention⚠️
ここにアップロードされているフォントは著作権が切れたフォントですが，ほとんどのフォントは利用規約を確認した上で試してください。  
(再配布に当たってしまうかもなので，ほとんど無理・・・？)  
The fonts uploaded here are out-of-copyright fonts, but you should check the terms of use for most fonts before trying them.  
(This would mean redistribution, which may not be possible in most cases.)  

# example
headerに以下を追記することでこのフォントを使用することができます。  
You can use this font by adding the following to the header.  
```html
<style>
@font-face {
  font-family: "JF-Dot-Ayu18";
  src: url("https://raw.githubusercontent.com/yamato3010/web-font-host/master/test.woff2") format('woff2'),
       url("https://raw.githubusercontent.com/yamato3010/web-font-host/master/test.woff")  format('woff');
}
</style>
```


```html
<span style="font-family: JF-Dot-Ayu18">こんな感じで，フォントを変えられます！</span>
```
