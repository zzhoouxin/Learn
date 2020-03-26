
#悬浮button交换思路
- 定义好各个span 作为基础颜色
- 定义伪元素::before 和之前span重叠
- 之前span 通过:nth-child 进行奇偶性的translateY
- 然后对伪元素 进行相反的操作 就展示为最基本的样式了
- 添加hover 将span 位置初始化到最初
- end

