# 头部制作

- 1号是版心盒子header1200*42的盒子水平居中对齐，上下给一个margin值就可以
- 版心盒子里面包含2号盒子logo
- 版心盒子里面包含3号盒子nav导航栏
  - 导航栏注意点：
  - 实际开发中，我们不会直接用链接a而是用li包含链接（li+a)的做法。
    1. **li+a**语义更清晰，一看这就是有条理的列表型内容。
    2. 如果直接用a,搜索引擎(SEO)容易辨别为有**堆砌关键字**嫌疑（故意堆砌关键字容易被搜索引擎有**降权的风险**）,从而影响网站排名
- 版心盒子里面包含4号盒子search搜索框
  - 一个search大盒子里面包含2个表单
    1. input文本框
    2. button按钮
- 版心盒子里面包含5号盒子user个人信息
- 注意：要求里面的4个盒子必须都是浮动

# 课程模块

# 精品推荐小模块

- 大盒子水平居中goods精品，注意此处有个盒子阴影
- 1号盒子是标题H3左侧浮动
- 2号盒子里面放链接左侧浮动，goods-item距离可以控制链接的左右外边距（注意行内元素只给左右内外边距）
- 3号盒子右浮动mod修改

# 精品推荐大模块

- 1号盒子为最大的盒子，box版心水平居中对齐
- 2号盒子为上面部分，box-hd--里面左侧标题H3左浮动，右侧链接a右浮动
- 3号盒子为底下部分，box-bd--里面是无序列表，有10个小li组成
- 小li外边距的问题，这里有个小技巧：给box-hd宽度为1215就可以一行装开5个li


