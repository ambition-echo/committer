## Commiter
### 任务描述


基于pyside2 和python 开发一款本地提单工具客户端。

此应用涉及内容如下：

- 该应用是禅道提单系统的一个客户端，采用Qt打造的一个PC客户端应用；
- 与禅道系统通过API接口来进行数据交互；--关键接口信息样例，[可点击参考文档](https://github.com/babyfengfjx/coding-quarter/blob/master/2.%E8%BF%9B%E9%98%B6%E9%9A%BE%E5%BA%A6/%E6%8F%90%E5%8D%95%E5%B7%A5%E5%85%B7/%E7%A6%85%E9%81%93API%E6%8E%A5%E5%8F%A3%E4%BF%A1%E6%81%AF.md)，本地可采用搭建mysql数据库方式，来与接口进行数据提交，其他接口可参考上述接口自行定义。
- 客户端应用主要是能提供模板功能，能够让使用者快速复用模板内容进行快速提单；
- 提供草稿功能，能保存多份待提交的bug内容；
- 提供用户提交BUG汇总统计、待处理BUG统计与查看等信息；
- 后期期望能支持提单时根据标题推荐可能存在的问题单信息；
- PyQt来开发客户端前端界面，python编写逻辑功能，后端逻辑功能只需编写基本类和方法体，无需使用真正的后端接口；
- 应用能打包成deb格式，并在deepin上正常安装、卸载；
- 应用界面时尚易用（大致原型可参考下文参考文档部分），界面设计不做要求，以个人审美来决定界面风格。


### 验收标准

   
- [x] 有配套的开发文档，包括但不限于：需求分析文档、方案设计文档；([需求分析文档](docs/%E9%9C%80%E6%B1%82%E5%88%86%E6%9E%90.md),[接口方案设计文档](docs/%E6%8E%A5%E5%8F%A3%E6%96%B9%E6%A1%88%E8%AE%BE%E8%AE%A1.md),[数据库结构文档](docs/%E6%95%B0%E6%8D%AE%E5%BA%93%E8%AE%BE%E8%AE%A1.md))
- [ ] 代码逻辑清晰，注释明了，命名规范，具备分而治之、高内聚、低耦合等特点；
- [x] 应用能按照deepin应用打包规范进行deb格式打包，并能成功安装、卸载；([Release](https://github.com/ambition-echo/committer/releases))
- [x] 应用能正常稳定运行，需求功能完整；(完整的需求分析文档内容均已实现)
- [x] 应用界面时尚美观易用。(有完整的qss样式覆盖)


### 参考文档

- [需求原型可参考](https://app.mockplus.cn/s/jKro-S8ne);
- [禅道提单界面](https://demo16.zentao.net/bug-create-27-0-moduleID=0.html?tid=fpdtppru) --首次进入会先需要登录，登录后再次访问该链接即可看到提单界面大致内容；
- [图标元素参考](https://www.iconfont.cn/)
- [应用打包规范](https://doc.chinauos.com/content/M7kCi3QB_uwzIp6HyF5J)