## 匹配除了click,show,view之外的其他单词或字符
```
\b(?!\b(click|show|view)\b)\S+
```
结果：
```
click: false
show: false
view: false
click : false
 click: false
 click : false
hello: true
click_how: true
clickCount: true
prefixclick: true
```


