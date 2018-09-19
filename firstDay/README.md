# [LearnJS](../README.md)

Learning about JavaScript

## 第一天

    1. JavaScript的组成
        - 完整的JavaScript是由ECMAScript（语法）、Browser Objects（DOM、BOM）（特性）组成。

    2. 在html中使用的JavaScript
        - 可以在head或body中使用<script>嵌入JavaScript脚本

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <title>Hello world!</title>
        <!-- head引用 -->
        <script>
        // 内部javascript代码
        </script>
        <!-- 引用外部js代码 -->
        <script src="xxxx.js"></script>
    </head>

    <body>
        <!-- body引用 -->
        <script>
            // 内部javascript代码
        </script>
    </body>
</html>
```