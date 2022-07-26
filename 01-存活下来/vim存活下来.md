## vim - 存活下来

### practice

- [x] 存过下来.

```ts
const a: number = 1
const b: string = '2'
const c: number[] = [1, 2, 3, 4, 5]
const d: (params: any) => void = params => {
  console.log('anx')
}

let aa: number = 11
let bb: string = '22'
let cc: symbol = Symbol('cc')

const add: (a: number, b: number) => number = (a, b) => {
  return a + b
}
```

## 在 vs code 中安装插件

1. [vim 插件](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
2. 在扩展应用商店搜索 vim

## 概念

> ### 模式
>
> - normal 模式 和 insert 模式
> - 切换为 insert 模式 -> i / a (append)
> - 退出 insert 模式 -> esc / ctrl + [

> ### 移动
>
> - 上 -> K
> - 下 -> J
> - 左 -> H
> - 右 -> L
