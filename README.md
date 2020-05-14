构建Spring Boot Maven项目
1.通过官方的Spring Initializr工具来产生基础项目。
2.访问http://start.spring.io/,该页面提供了以Maven或Gradle构建Spring Boot项目的功能。
3.选择构建工具Maven Project、Spring Boot选择版本，填写Group和Artifact信息，在Search for dependencies中可以搜索需要的其他依赖包，这里我们要实现RESTful API，所以可以添加Web依赖。
4.单机Generate Project按钮下载项目压缩包。
5.解压项目包，并用IDEA以Maven项目导入。
6.从菜单中选择File-->New-->Project from Existing Sources...。
7.选择解压后的项目文件夹，单击OK按钮。
8.单击Import project from external model并选择Maven，一直单击Next按钮。
