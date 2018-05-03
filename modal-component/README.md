# modal-component
https://jp.vuejs.org/v2/examples/modal.html

## Tips
- $emitメソッド
    - https://jp.vuejs.org/v2/guide/components.html<Paste>
```
ボタンをクリックすると、すべての投稿のテキストを拡大する必要があることを親コンポーネントに伝える必要があります。幸いにも、Vue インスタンスはこの問題を解決するカスタムイベントシステムを提供しています。親コンポーネントにイベントを送出するには、ビルトインの$emit メソッドを呼び出して、イベントの名前を渡します:
```
