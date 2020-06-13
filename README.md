button.css简洁、直观、强悍的前端开发框架，让web开发更迅速、简单。
 --------------------------------------------npm 安装-----------

通过 npm 安装
npm install button.css --save
import 语法
import button from 'button.css';
官网下载
 --------------------------------------------按钮-----------

primary success info warning danger default
primary success info warning danger default
primary success info warning danger default
primary success info warning danger default
primary success info warning danger default
primary success info warning danger default
primary success info warning danger default
primary success info warning danger default
 --------------------------------------------局部大类class-----------

头部：header
主体：center
左侧：sidebar
右侧：right
底部：footer
默认块状图层：layout
底部线条设置(手机上使用)：item-inner
 --------------------------------------------边框设置-----------

默认边框(#ccc)：border-default
无边框：border-0
无上边框：border-top-0
无下边框：border-bottom-0
无左边框：border-left-0
无右边框：border-right-0
 --------------------------------------------overflow-----------

overflow-auto-x{ overflow-x: auto}
overflow-auto-y{ overflow-y: auto}
overflow-scroll-x{ overflow-x: scroll}
overflow-scroll-y{ overflow-y: scroll}
overflow-scroll{ overflow: scroll}
overflow-hidden{ overflow: hidden}
 --------------------------------------------文字对齐-----------

文字向左对齐：align-left
文字居中对齐：align-center
文字向右对齐：align-right
vertical-top{vertical-align: text-top;}
vertical-middle{vertical-align: middle;}
vertical-bottom{vertical-align: text-bottom;}
 --------------------------------------------position定位-----------

绝对定位：position-a
相对定位：position-r
固定定位：position-f
.z-index-10{z-index: 10;}
.z-index-100{z-index: 100;}
.z-index-1000{z-index: 1000;}
.z-index-after{z-index: -1;}
 --------------------------------------------float浮动-----------

左浮动：float-left
又浮动：float-right
取消浮动：clear
取消浮动(父级类)：clearfix
 --------------------------------------------省略号样式-----------

1、单行省略号
class="ellipsis"
overflow: hidden;text-overflow: ellipsis;white-space: nowrap;
2、多行省略号
class="ellipsis2
class="ellipsis3
class="ellipsis4
class="ellipsis5
class="ellipsis6
overflow: hidden;display: -webkit-box;-webkit-line-clamp: 5;-webkit-box-orient: vertical;
 --------------------------------------------div强制换行样式-----------

class="break"
word-break:break-all
 --------------------------------------------图片垂直居中-----------


 --------------------------------------------鼠标状态-----------

pointer{ cursor: pointer;}
move{cursor: move;}
no-drop{cursor: no-drop;}
 --------------------------------------------文字下划线-----------

.none-line{text-decoration: none;}
.underline{text-decoration: underline;}
.hover-underline:hover{text-decoration: underline;}
 --------------------------------------------其他-----------

.bold(文字粗体)
.none{ display:none;}
.block{ display: block;}
.inline-block{ display:inline-block;}
.inline-flex{ display:inline-flex;}
.display-init{ display:initial;}
.italic{font-style:italic;}(文字斜体)
.italic-init{font-style:italic;}(取消文字斜体)
 --------------------------------------------padding 像素(px)-----------

padding-1~padding-100
padding-top-1~padding-top-150
padding-bottom-1~padding-bottom-150
padding-left-1~padding-left-150
padding-right-1~padding-right-150
 --------------------------------------------margin 像素(px)-----------

margin-auto{margin:auto}
margin-1~margin-100
margin-top-1~margin-top-300
margin-bottom-1~margin-bottom-300
margin-left-1~margin-left-300
margin-right-1~margin-right-300
 --------------------------------------------width 像素(px)-----------

width-1180{width: 1180px;}
width-auto{width: auto;}
width-max{width: 100%;}
width-1~width-400
 --------------------------------------------height 像素(px)-----------

height-auto{height: auto;}
height-max{height: 100%;}
height-1~height-400
 --------------------------------------------line-height 像素(px)-----------

line-height-1~line-height-100
 --------------------------------------------radius圆角 像素(px)-----------

.radius-max{border-radius:50%}
radius-1~radius-50
 --------------------------------------------font-size文字大小 像素(px)-----------

font-size-12~font-size-60
 --------------------------------------------top 像素(px)-----------

top-0~top-300
bottom-0~bottom-300
left-0~left-300
right-0~right-300
 --------------------------------------------文字缩进 像素(px)-----------

text-indent-0~text-indent-100
 --------------------------------------------文字颜色-----------

color-primary
color-success
color-info
color-warning
color-danger
color-default
color-red
color-orange
color-yellow
color-green
color-aqua
color-blue
color-purple
color-black
color-333
color-666
color-999
color-ccc
color-ddd
color-eee
color-white(白色)
color-star (表单星号颜色)
 --------------------------------------------链接颜色-----------

a-primary
a-success
a-info
a-warning
a-danger
a-default
a-red
a-orange
a-yellow
a-green
a-aqua
a-blue
a-purple
a-link
a-black
a-red
a-yellow
a-333
a-666
a-999
a-ccc
a-ddd
a-eee
a-white(白色)
 --------------------------------------------标签颜色-----------

tag-primary
tag-success
tag-info
tag-warning
tag-danger
tag-default
tag-red
tag-orange
tag-yellow
tag-green
tag-aqua
tag-blue
tag-purple
 --------------------------------------------背景颜色-----------

background-success
background-info
background-warning
background-danger
background-default
background-red
background-orange
background-yellow
background-green
background-aqua
background-blue
background-purple
background-black
background-333
background-666
background-999
background-ccc
background-ddd
background-eee
background-white
 --------------------------------------------边框颜色-----------

border-primary
border-success
border-info
border-warning
border-danger
border-default
border-red
border-orange
border-yellow
border-green
border-aqua
border-blue
border-purple
border-333
border-666
border-999
border-ccc
border-ddd
border-eee
 --------------------------------------------路径导航-----------

首页 栏目页 详细页
 --------------------------------------------tab选项卡-----------

buttonbuttonbutton
buttonbuttonbutton
buttonbutton
buttonbutton
buttonbutton
 --------------------------------------------复选框颜色-----------

 是  少时诵诗书  否
 是  否  少时诵诗书
 --------------------------------------------单选框颜色-----------

 是  否  少时诵诗书
 是  否  少时诵诗书
 --------------------------------------------文本框样式-----------

请输入...
disabled
readonly
搜索
请输入...
请输入...
搜索
请输入...
 --------------------------------------------星号等级-----------

    
 --------------------------------------------悬浮菜单-----------

重命名
移动到…
下载
分享
重命名
重命名
 --------------------------------------------悬浮信息提示-----------

他们又是跳绳，又是玩接球，等着上课铃声响起 ;他们又是跳绳
他们又是跳绳，又是玩接球，等着上课铃声响起 ;他们又是跳绳
他们又是跳绳，又是玩接球，等着上课铃声响起 ;他们又是跳绳
他们又是跳绳，又是玩接球，等着上课铃声响起 ;他们又是跳绳
他们又是跳绳，又是玩接球，等着上课
他们又是跳绳，又是玩接球，等着上课铃声响起 ;他们又是跳绳
他们又是跳绳，又是玩接球，等着上课
他们又是跳绳，又是玩接球，等着上课铃声响起 ;他们又是跳绳
他们又是跳绳，又是玩接球，等着上课
他们又是跳绳，又是玩接球，等着上课铃声响起 ;他们又是跳绳
他们又是跳绳，又是玩接球，等着上课
他们又是跳绳，又是玩接球，等着上课铃声响起 ;他们又是跳绳
 --------------------------------------------进度条-----------

 --------------------------------------------表格样式-----------

表格一
序号	标题	图片	类型	状态	操作
#	button.css	images.jpg	style样式	正常	编辑 删除
#	button.css	images.jpg	style样式	正常	编辑 删除
#	button.css	images.jpg	style样式	正常	编辑 删除
#	button.css	images.jpg	style样式	正常	编辑 删除
表格二
序号	标题	图片	类型	状态	操作
#	button.css	images.jpg	style样式	正常	编辑 删除
#	button.css	images.jpg	style样式	正常	编辑 删除
#	button.css	images.jpg	style样式	正常	编辑 删除
#	button.css	images.jpg	style样式	正常	编辑 删除
表格三(无边框)
序号	标题	图片	类型	状态	操作
#	button.css	images.jpg	style样式	正常	编辑 删除
#	button.css	images.jpg	style样式	正常	编辑 删除
 --------------------------------------------分类刷选项样式-----------

button.css： 按钮 局部大类class 边框设置 overflow 文字对齐 position定位 float浮动 省略号样式 div强制换行样式 图片垂直居中 鼠标状态 文字下划线 其他
 --------------------------------------------分类刷选项选择状态-----------

button.css： 按钮× button.css： 局部大类class× button.css： 边框设置×
 --------------------------------------------弹窗图层-----------

操作成功
你已成功创建该项目！
关闭
操作失败
您没有权限删除该项目！
关闭
操作成功
您确定要删除该项目吗？
关闭 确定
使用说明
1、引用button.css文件。copy对应的图层!
2、不要随意更改button.css文件!
3、修改图层样式时不要在一用的类目上重新定义。请从新创建新的class类名
关闭 确定
请稍等…
 --------------------------------------------遮罩图层-----------

半透明背景：class="panel-backdrop"
透明背景：class="panel-backdrop2"
 --------------------------------------------js模态框事件-----------

1、js代码弹出加载提示框：model("loading","title") demo
2、js代码弹出中间图层：target_popup(i)(data-popover="modal" data-target="#modal1") demo
3、js代码关闭中间图层：close_popup(i)(data-close="modal")
4、js代码弹出右侧模态框：target_popup_animate(i)(data-popover="modal-animate" data-target="#modal1")demo
5、js代码关闭右侧模态框：close_popup_animate(i)(data-close="modal-animate")
6、js代码弹出信息选择窗体：model("info","title"); demo警告模态框
7、js代码弹出成功窗体：model("success","title"); demo成功模态框
8、js代码弹出失败窗体：model("error","title"); demo失败模态框
