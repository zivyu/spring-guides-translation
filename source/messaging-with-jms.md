# 中文标题

> 原文：[Messaging with JMS](https://spring.io/guides/gs/messaging-jms/)
>
> 译者：zivyu
>
> 校对：

## Messaging with JMS
本指南将带你体验使用JMS broker发布和订阅消息的过程。

### 你将会得到什么
你会构建一个应用，这个应用使用Spring的`JmsTemplate`来发布一条消息，并使用一个带`@JmsListener`注解的方法来订阅它。

### 你需要什么
* 大约十五分钟
* JDK1.8或更高版本
* Gradle 2.3+或Maven 3.0+
* 你也可以直接导入代码到IDE中：


### 怎么完成本指南
像其他Getting Started guides一样，你可以从零开始，然后完成每一步，也可以跳过一些你熟悉的步骤，不管是哪种方式，

如果是从零开始，请先移步Build with Gradle。

如果准备跳过基本的步骤，按照如下方式：
* 下载并解压本篇指南的源码，或使用Git命令：
* 进入`gs-messaging-jms/initial`目录
* 跳到

如果你完成了上述步骤，可以使用`gs-messaging-jms/complete`中的代码来检查你的结果。

## 使用Gradle来构建



在此处编写正文，基本翻译规范：

* 正文标题按层次结构 从 \#\# 开始
* 代码片段\`\`\`之后需要写明语言类型
* 如有图片更静态资源保存在static目录下，每篇文章建立自己的目录存储
* 尊重原作、不修改、不删减内容
* 每篇文章翻译完成之后提交PR，并在翻译交流群中找校对人员完成review，最后由管理员完成Merge
* 若译者与校对有不同建议，可以将争议部分发到交流群中一起讨论确定结果

> 本文由spring4all.com翻译小分队创作，采用[知识共享-署名-非商业性使用-相同方式共享 4.0 国际 许可](http://creativecommons.org/licenses/by-nc-sa/4.0/) 协议进行许可。



