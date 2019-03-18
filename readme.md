- css命名词汇
    feeds *-item列表命名
- html结构及布局
从上到下，从左到右，语义化和功能性
 1. 套路
 content>h3+p
 2. 盒子
 3. a 作为盒子在移动端是很正常的
 display:block /* 行内转块级 */
 4. 盒子模型
 文字line-height padding margin
 5. 文字截断
    tmall 商铺信息是由商家填的，它的高度。不被限制，
    display:-webkit-box：新的盒子模型，像flex来划分父元素的空间 （弹性布局也不好完成）
    overflow: hidden;/*多出的将隐藏起来*/
    -webkit-line-clamp:3;/*只显示三行*/
    -webkit-box-orient: vertical; 在垂直方向上划分

 6. 浮动 float: left | right
 离开文档流
 在一个盒子里，将要浮动的元素写在最前面，
 左右布局，
 在弹性布局之前，我们一般借助于float来布局
 图片的宽高？宽度用百分比，自适应的需求。
 高度怎么做？ div padding-top:自身的高度来做比例100% 正方形
 自适应设备里盒子的等比例设置 width 百分比，
 高度用padding-top


 -webkit-内核，移动端都是这个内核