# web-font-host
ただこのように，webフォント化したフォントをGithubにアップロードすることによって，ブログやwebページにおいてwebフォントとして使用することができます。  

# attention⚠️
ここにアップロードされているフォントは著作権が切れたフォントですが，ほとんどのフォントは利用規約を確認した上で試してください。  
(再配布に当たってしまうかもなので，ほとんど無理・・・？)

# example
headerに以下を追記することでこのフォントを使用することができます。
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
