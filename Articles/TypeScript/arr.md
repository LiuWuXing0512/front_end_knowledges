### 数组类型

```ts
// 普通类型数组
let arr: number[] = [1, 2, 3]
let arr4: number[] = []
// 泛型数组
let arr2: Array<number> = [1, 2, 3]
let arr3: Array<any> = [1, 2, '3']

// 元祖数组
let arr5: [string, number] = ['1', 1]

function arrFn() {
    // 内置对象 arguments
    const arg: IArguments = arguments
}

```