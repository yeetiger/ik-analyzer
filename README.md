# ik-analyzer
﻿IKAnalyzer maven化，并且支持lucene5.0。

IKAnalyzer是一个开源的，基于java语言开发的轻量级的中文分词工具包。

1.IKAnalyzer的作者为林良益（linliangyi2007@gmail.com），项目网站为http://code.google.com/p/ik-analyzer/。

-----------------------------------------------------------------

2. Maven第一版本工程由王坤山创建（wks1986@gmail.com）。创建的目的是为了方便用于其他Maven工程。你可以在 https://github.com/wks/ik-analyzer 网站找到本工程。

Maven用法：

将以下依赖加入工程的pom.xml中的<dependencies>...</dependencies>部分。
    <dependency>
        <groupId>org.wltea.ik-analyzer</groupId>
        <artifactId>ik-analyzer</artifactId>
        <version>3.2.8</version>
	</dependency>

在IK Analyzer加入Maven Central Repository之前，你需要手动安装，安装到本地的repository，或者上传到自己的Maven repository服务器上。

要安装到本地Maven repository，使用如下命令，将自动编译，打包并安装：
mvn install -Dmaven.test.skip=true

------------------------------------------------------------------

3. Maven第二版本由bidtime创建，以支持lucene5.x以上，https://github.com/bidtime/ik-analyzer

4. 配套使用的 IKAnalyzer - 4Pinyin 也在本站中，https://github.com/bidtime/ik-analyzer-4Pinyin
