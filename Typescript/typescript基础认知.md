### Typescript 的由来
ts 的代码提示，是由于 d.ts 文件进行了声明

## Typescript 基础类型

- `any`,`boolean`,`number`,`string` 

- `void`：用 void 表示没有任何返回值的函数

```js
  function getName(): void {
    alert("your father's name is DZH!");
  }
```

- `enum`: 枚举
- `never`:
- `tuple`: 
- `Array`: `Array<string>`, `string[]`

## 声明类型

* `:`的在语义中解释为：对冒号之前的变量进行解释和声明
```js
let 变量名称: 变量类型 = 变量的值;
let jay: string = "jay chou";
```

## 类型转换
* 为此变量打上标签
```js
<string>jay.album
```
* 变量作为该类型处理
```js
jay.album as string
```

## 变量结构

```js
function saySomeThing1({ x , y } = {x : 0, y: 0}) {
    console.log(x, y)
}
```



