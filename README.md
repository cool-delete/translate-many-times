# translate-many-times
用谷歌翻译API翻译文本内容很多次

## 使用方式

```
node index.js [options]

Options:
  -t, --time      翻译次数，默认为5000次

```

也可以用简略形式调用：

```
node index.js <文本内容|(-c|--content) 文本文件路径> [次数]
```

```
node index.js [次数] <文本内容|(-c|--content) 文本文件路径>
```

## 演示截图

![简略形式调用](https://github.com/frederick-wang/translate-many-times/blob/master/screenshot/1.gif?raw=true)

![参数调用（次数在后）](https://github.com/frederick-wang/translate-many-times/blob/master/screenshot/2.gif?raw=true)

![参数调用（次数在前）](https://github.com/frederick-wang/translate-many-times/blob/master/screenshot/3.gif?raw=true)

![读取本地文件](https://github.com/frederick-wang/translate-many-times/blob/master/screenshot/4.gif?raw=true)

