滚动屏的实现思路
1.定义2个div正常填写样式-里面加入文字
2.使用transform-origin 设置折叠点。对2个div分别折叠(rotateY) 一个向左一个向右  形成折角
3.里面的文字使用span 绝对定位
4.创建一个动画的keyframes ,span的位置为从left：100 开始 
5.在执行动画为即可
6.串联起来的话  需要使用animation-delay 进行延迟加载 产生串联的效果
