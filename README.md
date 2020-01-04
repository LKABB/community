## lkabb

## 资料
[Spring 文档](https://spring.io/guides)
[Spring Web](https://spring.io/guides/gs/serving-web-content/)
[es](https://elasticsearch.cn/explore)
[Github deploy key](https://developer.github.com/v3/guides/managing-deploy-keys/#deploy-keys)
[Bootstrap](https://v3.bootcss.com/getting-started/)
[Gitbu OAuth](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/)
[Spring](https://docs.spring.io/spring-boot/docs/2.0.0.RC1/reference/htmlsingle/#boot-features-embedded-database-support)

##工具
[Git](https://git-scm.com/download)
[Visual Paradigm](https://www.visual-paradigm.com)

##脚本
'''sql
CREATE TABLE `user` (
  `id` int(20) NOT NULL AUTO_INCREMENT,
  `account_id` varchar(100) DEFAULT NULL,
  `name` varchar(100) DEFAULT NULL,
  `token` varchar(100) DEFAULT NULL,
  `gmt_create` bigint(50) DEFAULT NULL,
  `gmt_modified` bigint(50) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=3 DEFAULT CHARSET=utf8
'''