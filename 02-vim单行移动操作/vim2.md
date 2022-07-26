# vim2

在单行中更有效率的移动和插入

### practice

这是大写的 O  
 这是大写的 I, 这是大写的 I this is test 这是大写的 A, 这是大小的 A
这是小写的 o

这是大写的 O
这是小写的 o
这是小写的 o 这是 yy 复制的

这是大写的 I, 这是大写的 I this is test 这是大写的 A, 这是大小的 A

这是小写的 o 这是 yy 复制的

```ts
function assert(condition: boolean, msg?: string) {
  if (!condition) {
    throw new Error(msg || `unexpected compiler condition`)
  }
}

const condition: boolean = false
```

> ### 移动
>
> - 移动到行首 -> 0 / ^
> - 移动到行尾 -> g\_ / $

## 映射 vs code 按键

```js
"vim.operatorPendingModeKeyBindings": [
  {
    "before": ["H"],
    "after": ["^"]
  },
  {
    "before": ["L"],
    "after": ["g", "_"]
  }
]
```

> ### 插入
>
> - 行首插入 -> I
> - 行尾插入 -> A
> - 上一行插入 -> O （大写）
> - 下一行插入 -> o （小写）

> ### 复制 / 粘贴 / 删除
>
> - 复制当前行 -> yy
> - 粘贴 -> p
> - 删除 -> dd
