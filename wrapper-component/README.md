# wrapper-component
- jQuery Plugin の統合
- https://jp.vuejs.org/v2/examples/select2.html

## Library
- https://select2.org/

## Tips
### Vue instance
#### mounted
https://jp.vuejs.org/v2/api/index.html#mounted

```
新たに作成される vm.$el によって置き換えられる el に対して、インスタンスがマウントされたちょうど後に呼ばれます。ルートインスタンスがドキュメントの中の要素にマウントされる場合、vm.$el も mounted が呼び出されるときにドキュメントの中に入ります。
```

#### destroyed
https://jp.vuejs.org/v2/api/index.html#destroyed

```
Vue インスタンスが破棄された後に呼ばれます。このフックが呼ばれるとき、Vue インスタンスの全てのディレクティブはバウンドしておらず、全てのイベントリスナは削除されており、そして全ての子の Vue インスタンスは破棄されています。
```

### ライフサイクルダイアグラム
https://jp.vuejs.org/v2/guide/instance.html#%E3%83%A9%E3%82%A4%E3%83%95%E3%82%B5%E3%82%A4%E3%82%AF%E3%83%AB%E3%83%80%E3%82%A4%E3%82%A2%E3%82%B0%E3%83%A9%E3%83%A0
