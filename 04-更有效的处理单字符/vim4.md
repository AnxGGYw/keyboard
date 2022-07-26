# vim4

更有效的处理单字符 & undo / redo

### practice

```js
function getElementByClassName() {
  const aaa = {
    name: 'name'
  }
  const a = 123
  const b = 456
  const c = 789LLLL
  const d = 'anx'
}
```

> - 删除光标所在字符 -> x
> - 删除光标前的字符 -> X （大写）
> - 删除光标所在字符并进入 insert 模式 -> s
> - 删除光标所在行并进入 insert 模式 -> S （大写）
> - 替换当前字符 -> r
> - 替换多个字符 -> R （大写）

### undo / redo

可撤销块 -> 进入 insert 模式开始，直到返回 normal 模式为止，在此期间输入或删除的任何内容都被当作一次修改。
上下左右键也算作一次修改

> - undo -> u
> - redo -> ctrl + r
