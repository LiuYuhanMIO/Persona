####Weixin Script代码规范

变量命名
关于变量命名，主流分为驼峰式命名和下划线式命名两大阵营。我们约定，统一使用驼峰式命名。

推荐写法
let userId = 654321; 
function getUserInfo () {
 ....
}
不推荐写法
let user_id = 654321; 
function get_user_info () {
  ....
}

分号
分号紧跟代码的最后一个字符。

推荐写法
let loading = -1;
不推荐写法
let loading = -1 ;

逗号
逗号分割列表时，逗号放置在当前行的末尾。

推荐写法
let bar = 1, 
    foo = 2;
不推荐写法
let bar = 1 
    , foo = 2;

缩进
统一使用2个空格字符进行代码缩进。






####WXML代码规范

代码大小写
所有标签和属性，大部分属性值统一使用小写

推荐写法
<view class="demo">
    ...
</view>
不推荐写法
<view class="DEMO">
    ...
</view>

<VIEW CLASS="DEMO">
    ...
</VIEW>

标签的闭合
在小程序里，有些组件必须写成双标签，如视图容器类组件view；有些组件可以写成单标签，如媒体类组件image；但在小程序运行时，它们都会解析成双标签。

在小程序里，所有的标签一旦使用都必须被闭合，使用标签不闭合会报错，导致程序无法运行。

正确写法
<view>
  <image src="src"></image>
  <image src="src"/>
  <text>我是一段文字，我有始有</text>
</view>
错误写法
<view>
  <image src="src">
  <text>我是一段文字，我有始有
</view>






####WXSS代码规范

展开格式
样式代码书写一般有两种形式，一种是紧缩格式

.home{padding-top:44rpx;border:1rpx solid #fff;}
一种是展开格式

.home {
  padding-top: 44rpx;
  border: 1rpx solid #fff;
}
团队约定
统一使用展开格式，这跟微信开者工具自动格式化也是一致的。

缩进
统一使用2个空格代替Tab进行代码缩进

分号
每个属性声明末尾都要加上分号;

推荐写法
.avatar {
  width: 200rpx;
  height: 200rpx;
}
不推荐写法
.avatar {
  width: 200rpx;
  height: 200rpx
}
