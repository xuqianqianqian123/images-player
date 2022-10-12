# images-player
## 环境依赖
vue<br>
element ui
## 网页简介
本页展示我喜欢的一些图片，比如平时无聊画的简笔、最近看的觉得不错的电影《星际穿越》、还有一些吃吃喝喝等等。同样本页配有主题颜色切换功能。
## 功能说明
图片会自动轮播，当鼠标移动到某一张图片上会自动展示那张图片，鼠标移走后图片会继续开始轮播
## 代码实现
1、使用vue和element ui完成主题颜色切换功能<br>
2、使用将所有图片放入“box”和“box1”中，“box”中的图片即为现在展示的图片，“box1”中的图片是缩略图的所有图片<br>
3、JS函数：
show函数是核心函数，实现图片的展示和切换<br>
使用onmouseover事件实现当鼠标移动到某一张图片上的时候展示指定图片
autoPlay函数实现图片的自动播放，使用setInterval进行计时，onmouseover时用clearInterval停止计时，鼠标移走触发onmouseout时继续自动播放
## 目录结构描述
├── Readme.md // help<br>
├── index.html<br>
├── vue.js
