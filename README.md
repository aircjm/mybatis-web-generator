# Mybatis图形化界面生成工具

通过图形化界面生成Mybatis所需要的entity、mapper、dao文件,提供文件压缩包的下载.




适合团队使用,避免每个人使用不同的Mybatis工具.
该工程完全基于开源项目,项目自带Mybatis-generator-core 1.3.3正式版本源码 支持各种diy.例如生成自定义注释等等.


代码注释,无论是.java文件还是.xml文件的注释都是在DefaultCommentGenerator该类中的方法生成的.



代办事项:

- [ ] 各种异常处理,返回给前端正确的错误信息
- [ ] 代码注释的使用
- [ ] 前端密码输入框样式修改,不直接展示明文密码
- [ ] 考虑去除模块名输入,默认按照表名的大驼峰命名作为模块名


参考资料:

[https://github.com/zhongxintech/generator-web](https://github.com/zhongxintech/generator-web)

[MyBatis-Generator最佳实践](http://arccode.net/2015/02/07/MyBatis-Generator%E6%9C%80%E4%BD%B3%E5%AE%9E%E8%B7%B5/)

[mybatisn_generator_cn](https://github.com/arccode/mybatisn_generator_cn)