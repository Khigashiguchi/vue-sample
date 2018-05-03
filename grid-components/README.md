# grid-component
https://jp.vuejs.org/v2/examples/grid-component.html

## tips
### テンプレート構文
#### v-on 省略記法
- @click
- https://jp.vuejs.org/v2/guide/syntax.html#v-on-%E7%9C%81%E7%95%A5%E8%A8%98%E6%B3%95

```html
<th v-for="key in columns" @click="sortBy(key)" :class="{ active: sortKey === key }">
```

### Vue Global API
#### props
- https://jp.vuejs.org/v2/api/#props

```
親コンポーネントからデータを受け取るためにエクスポートされた属性のリスト/ハッシュです。
```

- 型チェックとかバリデーションができる

```js
Vue.component('demo-grid', {
    props: {
        data: Array,
        columns: Array,
        filterKey: String
        sample: {
            type: Number,
            default: 0,
            required: true,
            validation: function (value) {
                return value >= 0
            }
        }
    }
})
```

### Javascript
#### Array Object
- https://developer.mozilla.org/ja/docs/Web/JavaScript/Guide/Indexed_collections
- その他、JSの型について
    - https://qiita.com/zawascript/items/a25eaf7a222ac3671275

#### Array.forEach
- https://developer.mozilla.org/ja/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach

```js
array1.forEach(function(element) {
    console.log(elememt);
})
```

#### && || について
- https://qiita.com/Imamotty/items/bc659569239379dded55

#### String.prototype.toLowerCase
- https://developer.mozilla.org/ja/docs/Web/JavaScript/Reference/Global_Objects/String/toLowerCase
- 呼び出す文字列の値を小文字に変換した文字列を返す

#### String.prototype.indexOf
- https://developer.mozilla.org/ja/docs/Web/JavaScript/Reference/Global_Objects/String/indexOf
- 検索する、指定した文字列が出現した場合はそのインデックスを、なければ-1になる
