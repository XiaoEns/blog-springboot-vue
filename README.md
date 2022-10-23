# 需求分析



## 游客/普通用户

+ 首页
  + 文章列表
  + 个人信息
  + .....
+ 归档
  + 时间轴
+ 友情链接
  + 其他人的blog地址

+ 标签
+ 分类

+ 评论功能
  + 文章浏览数
  + 评论
  + 回复
  + 点赞数

+ **登录/注册/登出**



## 管理员

+ 首页
  + 网站浏览量
  + 文章数量
  + .....
+ 文章管理
  + 增，删，改，查
+ 评论管理
  + 增，删，改，查
+ 个人信息管理
  + 增，删，改，查
+ 友情链接管理
  + 增，
  + 删，
  + 改，
  + 查
+ 标签和分类管理
  + 增，
  + 删，
  + 改，
  + 查





# E-R模型

文章：标题，分类，标签.....

用户：账号，密码，昵称，个性签名，头像

标签：标签名

分类：分类名

归档对象：文章数

友情链接：头像，名称，博客地址

评论相关：评论，回复

![image-20221023201819463](D:\MyCode\GitCode\blog\B4\blog-springboot-vue\image-20221023201819463.png)





# 数据库设计









# 项目搭建

技术选型

+ 前端：vue2，axios，element-ui，vuex，router
+ 后端：springboot，mybatis-plus，SSM
+ 数据库：mysql
+ 其他：maven，git



## 参考结构

![image-20221023204601473](D:\MyCode\GitCode\blog\B4\blog-springboot-vue\image-20221023204601473.png)





![image-20221023205604202](D:\MyCode\GitCode\blog\B4\blog-springboot-vue\image-20221023205604202.png)