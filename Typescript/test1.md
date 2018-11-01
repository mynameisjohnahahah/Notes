# TypeScript Study

## 前言

npm用户下载

  - npm install -g typescript  

创建一个.ts文件

  - vscode可以直接运行它 在终端输入tsc xx.ts 它会输出成一个xx.js 
  

## 看看有什么特别的

```js
// 类型注解 
function greeter (person: string) {
    return 'Hello, ' + person
}

let user = 'lxp User'

console.log(greeter(user))

// 运行结果：lxp User

而如果你把user的值赋值数据的话 编译就会报错
error TS2345: Argument of type 'string[]' is not assignable to parameter of type 'string'.

// ts的类型注解能很好为函数或变量添加约束 实际项目就不会乱来了 QWQ
//注意：就算编译出错 xx.js还是会被创建出来 
```

