[LearnJS](../README.md)
===

Learning about JavaScript

第六天
---

<!-- TOC -->

- [JavaScript-输出内容 document.write](#javascript-输出内容-documentwrite)
    - [第一种:输出内容用""括起，直接输出""号内的内容。](#第一种输出内容用括起直接输出号内的内容)
    - [第二种:通过变量，输出内容](#第二种通过变量输出内容)
    - [第三种:输出多项内容，内容之间用+号连接。](#第三种输出多项内容内容之间用号连接)
    - [第四种:输出HTML标签，并起作用，标签使用""括起来。](#第四种输出html标签并起作用标签使用括起来)

<!-- /TOC -->

# JavaScript-输出内容 document.write

*document.write()* 可用于直接向 HTML 输出流写内容。简单的说就是直接在网页中输出内容。

## 第一种:输出内容用""括起，直接输出""号内的内容。

```html
<script type="text/javascript">
  document.write("I love JavaScript！"); //内容用""括起来，""里的内容直接输出。
</script>
```

## 第二种:通过变量，输出内容

```html
<script type="text/javascript">
  var mystr="hello world!";
  document.write(mystr);  //直接写变量名，输出变量存储的内容。
</script>
```

## 第三种:输出多项内容，内容之间用+号连接。

```html
<script type="text/javascript">
  var mystr="hello";
  document.write(mystr+"I love JavaScript"); //多项内容之间用+号连接
</script>
```

## 第四种:输出HTML标签，并起作用，标签使用""括起来。

```html
<script type="text/javascript">
  var mystr="hello";
document.write(mystr+"<br>");//输出hello后，输出一个换行符
  document.write("JavaScript");
</script>
```

