# 型推論 \(Type inference\)

TypeScriptには型推論\(type inference\)と呼ばれる機能があります。型推論は、**コンパイラが型を自動で判別する機能**です。プログラマーは型推論を活用すると、型注釈を省略できるので、コードの記述量を減らせる利点があります。

```typescript
let x = 1; // let x: number = 1;と同じ意味になる

x = "hello";
// Error: Type 'string' is not assignable to type 'number'.
```

上の例では変数`x`に`1`の値コードを代入しています。この時点でコンパイラは代入された値から、変数`x`の型を`number`型と自動で判別します。型注釈`x: number`を書くことを省略できます。

型注釈が書かれていないものの`x`は`number`型を推論されているため、`x`に`hello`の文字列型を再代入する記述は、型の不一致によりコンパイルエラーとなります。

