***
**Weixin Script代码规范**  
  
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

***
**WXSS代码规范**  

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
