构建spring源码到eclipse
1、环境要求：jdk8+，安装有 gradle，eclipse安装有gradle插件，eclipse安装有groovy插件。
2、安装JDK8，略。。。
3、安装 gradle，在https://gradle.org/  下载最新版，然后解压到某文件夹（路径须纯英文），将该路径加入 环境变量（跟安装maven差不多的套路）。
4、eclipse安装gradle插件，点击“help”==》“eclipse marketplace”==》搜索“gradle”==》选择“buildeship for eclipse gradle”安装。
5、eclipse安装groovy插件，到https://github.com/groovy/groovy-eclipse/wiki根据eclipse版本找到对应的“Release Update Site”，如：http://dist.springsource.org/snapshot/GRECLIPSE/e4.5/
	然后，点击“help”==》“install new software”==》“add”刚刚的URL地址，安装即可。
6、从GitHub上下载spring源码（可以从spring.io官网找到对应的GitHub地址链接进入。）
7、在下载好的spring源码根文件夹中先后执行：gradlew.bat==》import-into-eclipse.bat
8、在eclipse中点击鼠标右键==》选择“import”==》“gradle”==》找到指定的项目导入

20171207
	1、以“Aspect.class”为关键字搜索，重点分析：“org.springframework.aop.aspectj.annotation.AbstractAspectJAdvisorFactory”类。




