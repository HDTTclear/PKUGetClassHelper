# PKU选课助手 无限制版 by thrfirs

对原版PKU选课助手做了如下修改：

* 解除了原版选课助手的频率及次数限制（最低刷新时间间隔从10秒调整为0.1秒，并取消了原本的6000次最大日刷新次数），**请酌情谨慎使用**！
* 添加了随机化刷新时间间隔的功能，现在可以指定参数 A 和 B ，使每次刷新间隔为 [A + rand(0, B)] * 100ms。~~虽然这个功能实际上并没有什么卵用~~
* **2020年2月17日更新**：选课网全面升级到https协议，故调整了程序的API调用以适配该变化。

以下是原作者的README.md内容。

---

# *pku选课助手*

* *本助手是由P大选课网的前端chrome插件，在浏览器模拟访问链接，解放众多P大学子的双手。*
* *本助手不存在任何后门，也不利用任何后门，请投机取巧者绕行。*
* *为了保障学校教务系统的正常运行，本助手有频率限制。使用本助手以及衍生代码造成的后果由使用者自行承担。*

## *使用方法*

* *请参见：[下载and使用方法](http://www.zakelly.com/2016/02/20/get-class-helper-new-version/)*

## *贡献代码*

* *本代码是主要作者大二时期所著，代码结构有些混乱，工程化不足，请见谅。具体调试方法请参见Chrome的插件开发教程。*
* *由于主要作者即将毕业，希望有人能参与到维护当中，共同为同学们的选课提供帮助。请提交Pull request。*
* *Chrome商店的版本发行请联系Zakelly，欢迎邮件交流。*

## *声明*
* *本项目作者(排名不分先后)：cbwang2016, Zakelly, zhouhy*
* *本项目遵循GPL协议*