# staticPage

## AXIT
网站.png图片显示：https://i.loli.net/2018/07/14/5b493d8e9d8ce.png<br>
网站预览:https://jackwong992.github.io/staticPage/AXIT/index.html<br>
小总结：
1. 尽量采用语义化命名类名<br>
2. 第一版是采用 `float`和相对定位实现大致布局，这么做的目的是为了实现在大多数浏览器可以同样展示（第二次会使用`flex`进行页面重构）<br>
3. 布局主要采用了 `从内到外 从上到下`的思路，会刻意的避开使用 `height，width`这样的容易出现bug的属性，先把单元内的文字或者边框固定住，采用`padding , margin`来代替`height,width`，如果万不得已使用`max-width , min-width, max-height, min-height`代替`width,height`<br>
4. 经常采用`marigin`会导致父子间外边距合并，可以采用`overflow`,或者之间加入`0.1px`的`padding`<br>

> *网站psd文件来源于Google搜索，如有侵权请告知，我将于第一时间删除*
