# 一括登録のユースケースのサンプル

## 要件
- Product(id, code, name, price)を一括で登録できるようにする
  - code: null禁止, ユニーク
  - name: null禁止
  - price: null禁止, 数値, 1以上
- 5件分の入力フォームを用意する

# 新規作成画面
[![Image from Gyazo](https://i.gyazo.com/17b421d653534a9f87d5282f4c9034ba.png)](https://gyazo.com/17b421d653534a9f87d5282f4c9034ba)

バリデーションエラー時の表示
[![Image from Gyazo](https://i.gyazo.com/9ba20aebe09213a07b51d0be29cad9c4.png)](https://gyazo.com/9ba20aebe09213a07b51d0be29cad9c4)

# 一覧画面
[![Image from Gyazo](https://i.gyazo.com/f6f6f668748bdbec3cb3632bbff64ada.png)](https://gyazo.com/f6f6f668748bdbec3cb3632bbff64ada)
