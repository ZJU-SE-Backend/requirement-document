# 说明

本仓库用于存放各个小组的需求。当各个小组需要服务端支持时，应按照以下流程编写文档提出申请：

1. 首先明确自己所需接口数量，接口类型，数据表定义，并按照Require.md中样例编写需求文档，每个需求单独一个文档。
2. 需求文档命名必须是全英文大驼峰命名，尽量遵循PSM规范
3. 目录结构示例如下：C1（大组）/im（个人负责的模块名）/若干文档
4. 文档写好后，直接push就行，然后**必须联系C3组，将修改内容告知后端开发人员**
5. **在本仓库中提交issue**，标题形如"C3:狄志鹏 获取商家信息"，内容简单介绍一下需求，并附上需求文档的连接，并在issue的左侧关联**后端研发看板**
6. 后端开发人员审核文档，确认无误后进入开发排期
7. 可以在本团队的Project选项卡中后端研发看板上看到目前的排期以及开发进度。

![image-20210413205818648](https://tva1.sinaimg.cn/large/008eGmZEly1gpiey540gaj320m0u0gse.jpg)

---

注意：请不要把图片上传到github仓库中，如果必须在需求文档中使用图片，请使用图床（自行百度"什么是图床" "typora 图床"），推荐使用typora作为markdown编辑器。



# 说明2（中期展示后）

### 前期反馈

已结束的需求文档：不再更新测试样例与API列表等，以swagger为准，后端若有跟前端相关的更新（如API改名）会写到更新日志中。

各子系统模块设计命名还是按照原先的规范，模块**逻辑完备**，提交新的需求文档时请放在对应模块的文件夹下。

数据库建议要求：请检查**数据类型无误**（能在自己的mysql上跑通），数据表设计满足API需要提取的内容，**最好有测试数据**。API文档**【无需】**建议数据库操作的sql语句（其实用不到hhh）。



### 后期API的提出和修改规范

- 新模块的需求：按照之前的操作，提交需求文档并提交issue和绑定开发面板，如“C3-胡丽雅：新模块-测试模块-这个模块用于测试“。

- 已有模块下的新API：仅在已有需求文档添加，并提交issue和绑定开发面板，如”C3-胡丽雅：增加API-测试模块-这个API用于测试“。

- 修改已有的API：仅在已有需求文档中修改，并提交issue和绑定开发面板，如“C3-胡丽雅：修改API-测试模块-这个API用于测试”。

issue命名规范：【小组号-提交人：类型-所属模块-描述】

后续确认需求文档中的问题会直接找提交人（不一定找组长），组长们也可以拉成员到需求侧。