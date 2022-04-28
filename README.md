# demo-dom
增
```
dom.create(`<div>hi</div>`) 用于创建节点
dom.after(node, node2) 用于新增弟弟
dom.before(node, node2) 用于新增哥哥
dom.append(parent, child) 用于新增儿子
dom.wrap(`<div></div>`) 用于新增爸爸
````
删
···
dom.remove(node) 用于删除节点
dom.empty(parent) 用于删除后代
···
改
···
dom.attr(node, 'title', ?) 用于读写属性
dom.text(node, ?) 用于读写文本内容
dom.html(node, ?) 用于读写 HTML 内容
dom.style(node, {color: 'red'}) 用于修改 style
dom.class.add(node, 'blue') 用于添加 class
dom.class.remove(node, 'blue') 用于删除 class
dom.on(node, 'click', fn) 用于添加事件监听
dom.off(node, 'click', fn) 用于删除事件监听
···
查
···
dom.find('选择器') 用于获取标签或标签们
dom.parent(node) 用于获取父元素
dom.children(node) 用于获取子元素
dom.siblings(node) 用于获取兄弟姐妹元素
dom.next(node) 用于获取弟弟
dom.previous(node) 用于获取哥哥
dom.each(nodes, fn) 用于遍历所有节点
dom.index(node) 用于获取排行老几
···


