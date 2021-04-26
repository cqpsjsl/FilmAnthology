# FilmAnthology
依赖ThinkPHP框架的获取主流影视平台剧集链接，俗称选集文件，常见使用系统：千月影视、完美网服、七彩视界等。

# 版本

​	测试环境：PHP 5.6、7.0、7.2

# 使用方法

将PHP文件上传到application/app/controller/目录下

前端请求：域名+/app/tencent?url=https://m.youku.com/video/id_XNDk2MzA5Nzc2MA==

url为手机端链接。

# 支持平台

腾讯、爱奇艺、优酷、芒果、搜狐、韩剧tv、哔哩哔哩部分番剧



# 验证是否成功

搭建好之后使用域名+/app/tencent?url=https://m.youku.com/video/id_XNDk2MzA5Nzc2MA==

提示`Use of undefined constant ...(this will throw an Error in a future version of PHP)`则是不兼容PHP版本



若有正常信息返回则有效。若无任何信息则可能是环境问题。
