---
title: Writing Good Git Commit Messages
localeTitle: 编写好的Git提交消息
---
1.  用空白线将身体与身体分开
2.  将主题行限制为50个字符
3.  资本化主题
4.  不要以句点结束主题行
5.  使用主题行中的命令式情绪
6.  包裹身体72个字符
7.  用身体来解释什么以及为什么与如何对比

**正确形成的git commit主题行应始终能够完成以下句子：**

> 如果应用，此提交将_`<<your subject line here>>`_

**例如：**

*   如果应用，此提交将**_重构子系统X以提高可读性_**
*   如果应用，此提交将**_更新入门文档_**
*   如果应用，此提交将**_删除不推荐使用的方法_**
*   如果应用，此提交将**_发布1.0.0版_**
*   如果应用，此提交**_将从用户/分支合并拉取请求＃123_**

**请注意这不适用于其他非命令性形式：**

*   如果应用，此提交将_修复Y的错误_
*   如果应用，此提交将_改变X的行为_
*   如果应用，此提交将_更多修复损坏的东西_
*   如果应用，此提交将是_甜蜜的新API方法_

**请记住：** _使用命令仅在主题行中很重要。你在写身体时可以放松这个限制。_

**参考：** [http](http://chris.beams.io/posts/git-commit) **：** [//chris.beams.io/posts/git-commit](http://chris.beams.io/posts/git-commit)