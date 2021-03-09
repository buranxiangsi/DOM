运行

parcel src/index.html



```js
window.dom //全局对象

//增
dom.create('<div>hi</div') //创建节点
dom.after(node, node2) //新增弟弟
dom.before(node, node2) //新增哥哥
dom.append(parent, child)//新增儿子
dom.wrap('<div></div>')//新增爸爸

//删
dom.remove(node) //删除节点
dom.empty(parent) //删除爸爸

//改
dom.attr(node, 'title', ?) //读写属性
dom.text(node,?) //读写文本内容
dom.html(node, ?) //读写html内容
dom.style(node, {color:'red'}) //修改style
dom.class.add(node,'blue') //添加class
dom.class.remove(node,'blue') //删除class
dom.on(node, 'click', fn) //添加事件监听
dom.off(node, 'click'. fn) //删除事件监听

//查
dom.find('选择器')//获取标签/标签们
dom.parent(node)//获取父元素
dom.children(node)//获取子元素
dom.siblings(node)//获取兄弟姐妹元素
dom.next(node)//获取弟弟
dom.previous(node)//获取哥哥
dom.each(nodes, fn)//遍历所有节点
dom.index(ndoe)//排行第几

```

