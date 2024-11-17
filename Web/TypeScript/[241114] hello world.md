# js→ts 新概念

## 类型推断

- 随意书写一个变量，后期可以赋值为任意类型
- ts会根据给变量存放的初始值，进行**变量类型限定**

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411140112260.png"/>

↑ str这个变量刚开始给的值是string，后期就只能存放string type的值

> 这样的写法不直观，不推荐书写

## 类型注解

- 书写变量的时候给变量的类型做限定

语法：

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411140117535.png"/>

也可以直接预声明：

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411140117706.png"/>

那么之后赋值的时候，如果类型不符就会报错

## 类型断言

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411140123330.png"/>

对数组进行内容查找，条件是>2；原始情况下，程序认为存在undefined的可能性（NaN）。

此时可以断言“这是一个number类型”

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411140125828.png"/>

# 基础类型和联合类型

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411140130827.png"/>