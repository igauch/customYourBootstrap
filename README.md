#说明
#####主要目的和作用：翻译variables中的less变量以供快速配置，当然也可以直接前往bsp网站定制
* 此文档是本人在学习和使用过程中总结的，可用于速查，实际使用和遇到问题时推荐大家直接到[bsp官方](http://getbootstrap.com/)或[bsp中文站](http://v3.bootcss.com/)学习使用
* 此文档是针对bsp3.3.7整理的
* 请至custom bootstrap下的custom-variables配置，此文件已经过翻译整理，能力有限，比较粗鄙
* bsp的很多组件和栅格系统等并未整理到下面的常用类中，依旧建议前至[bsp官方](http://getbootstrap.com/)或[bsp中文站](http://v3.bootcss.com/)
### 目录说明
* bootstrap-3.3.7是官方文件，原则上不建议改动
* custom bootstrap是定制bsp的文件目录，css是主要活动目录，毕竟fonts和js我们是不会轻易动的，那也不是我们这里研究的
* custom-bootstrap.less是用来生成定制的bsp的less文件；</br>custom-variables.less是配置变量的文件，通过此可以以最简单和最快捷的方式定制属于你项目的bsp；</br>custom-other.less是用来添加和配置除正常bsp配置以外的
#bsp常用class
* text-center:文本居中对齐，类似的还有text-left | text-right | text-justify
* text-nowrap:文本不换行
* center-block:使内容水平居中
* text-lowercase:转为小写，text-uppercase转为大写，text-capitalize:单词首字母大写
* list-unstyled:去除li等样式
* list-inline:使li成为行内元素，横向水平排列
* table:改变表格默认样式为bsp风格的
* table-striped:使table拥有斑马条纹样式
* table-bordered:使table有边框
* table-hover:使table在hover时作出相应
* table-condensed 可以让表格更加紧凑，单元格中的内补（padding）均会减半
* form-inline:可以让包裹在此类下的表单元素水平横向排列
* form-control:使用此类可以很方便的优化表单元素的默认样式
* input-group-addon:添加此类的元素可以在视觉上成为input的一部分，须在父元素上添加input-group类
* btn:改变按钮默认样式为bsp风格的
* pull-left、pull-right:左右浮动,如果是导航条nav请使用navbar-left或navbar-right
* clearfix:清除浮动
* show、hidden:显示或隐藏内容
* btn-group：可快速去除几个按钮之间因代码格式化导致的间距问题
* btn-group-vertical:使按钮组垂直排列
####一些常用的类集合
- success、warning、error、danger、info等，这些类都是改变颜色、背景色等基本样式的，在很多元素上都有用到
    - 表格：直接在tr、td上使用active、success、warning、danger、info改变基本样式
    - 表单：直接在label、input等父元素上使用has-success、has-warning、has-error改变基本样式
    - 按钮：直接在按钮元素添加btn-success、btn-info、btn-warning、btn-danger等改变基本样式
    - 文本元素：bg-primary、bg-success、bg-info、bg-warning、bg-danger改变基本样式
    - 标签：label-default、label-primary、label-success、label-info、label-warning、label-danger改变基本样式
    - 警告框：alert-success、alert-info、alert-warning、alert-danger改变基本样式
    - 面板：panel-primary、panel-success、panel-info、panel-warning、panel-danger改变基本样式
- lg、sm、xs这些类都是改变大小的类，可用在
    - 表单组：form-group-lg（增大的）
    - 输入框：input-sm（小的）
    - 按钮：btn-xs（超小的）
