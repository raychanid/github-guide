# github-guide

关于仓库
本文内容
关于仓库
关于仓库可见性
限制查看仓库中的内容和差异
延伸阅读
仓库包含项目的所有文件，并存储每个文件的修订记录。 您可以在仓库中讨论并管理项目的工作。

关于仓库
您可以个人拥有仓库，也可以与组织中的其他人共享仓库的所有权。

您可以通过选择仓库的可见性来限制谁可以访问仓库。 更多信息请参阅“关于仓库可见性”。

对于用户拥有的仓库，您可以向其他人授予协作者访问权限，以便他们可以协作处理您的项目。 如果仓库归组织所有，您可以向组织成员授予访问权限，以便协作处理您的仓库。 更多信息请参阅“个人帐户仓库的权限级别”和“组织的仓库角色”。

通过个人帐户和组织的 GitHub Free，可与无限的协作者合作处理设置了完全功能的无限公共仓库，或者是设置了有限功能的无限私有仓库， 要获取对私有仓库的高级处理，您可以升级到 GitHub Pro、GitHub Team 或 GitHub Enterprise Cloud。 更多信息请参阅“GitHub 的产品”。

您可以使用仓库管理您的工作并与他人合作。

您可以使用议题来收集用户反馈，报告软件缺陷，并组织您想要完成的任务。 更多信息请参阅“关于议题”。
您可以使用 GitHub Discussions 来提问和回答问题、共享信息、发布公告以及进行或参与有关项目的对话。 更多信息请参阅“关于讨论”。
您可以使用拉取请求来建议对仓库的更改。 更多信息请参阅“关于拉取请求”。
您可以使用项目板来组织议题和拉取请求并排定优先级。 更多信息请参阅“关于项目板”。
仓库和单独文件受大小限制约束。 更多信息请参阅“什么是磁盘配额？”

关于仓库可见性
您可以通过选择仓库的可见性来限制谁有权访问仓库： 公共或私有。

创建存储库时，可以选择将存储库设为公开或私有。还可以通过内部可见性创建使用 GitHub Enterprise Cloud 并由企业帐户拥有的组织中的存储库。 更多信息请参阅 GitHub Enterprise Cloud 文档。

互联网上的所有人都可以访问公共仓库。
私有仓库仅可供您、您明确与其共享访问权限的人访问，而对于组织仓库，只有某些组织成员可以访问。
组织所有者始终有权访问其组织中创建的每个仓库。 更多信息请参阅“组织的仓库角色”。

拥有仓库管理员权限的人可更改现有仓库的可见性。 更多信息请参阅“设置仓库可见性”。

限制查看仓库中的内容和差异
有些类型的资源可能很大，需要在 GitHub 上额外处理。 因此，可设置限制，以确保申请在合理的时间内完成。

以下限制大多会影响 GitHub 和 API。

文本限制
超过 512 KB 的文本文件始终显示为纯文本。 代码不强调语法，散文文件不会转换成 HTML（如 Markdown、AsciiDoc 等）。

超过 5 MB 的文本文件仅通过其源 URL 访问，将通过 raw.githubusercontent.com 提供；例如 https://raw.githubusercontent.com/octocat/Spoon-Knife/master/index.html。 单击 Raw（源）按钮获取文件的源 URL。

差异限制
因为差异可能很大，所以我们会对评论、拉取请求和比较视图的差异施加限制：

在拉取请求中，总差异不得超过您可以加载的 20,000 行 或 1 MB 的原始差异数据。
任何单个文件的差异都不能超过您可以加载的 20,000 行，或 500 KB 的原始差异数据。 四百行和 20 KB 会自动加载为一个文件。
单一差异中的最大文件数限于 300。
单一差异中可呈现的文件（如图像、PDF 和 GeoJSON 文件）最大数量限于 25。
受限差异的某些部分可能会显示，但超过限制的任何部分都不会显示。

提交列表限制
比较视图和拉取请求页面显示 base 与 head 修订之间的提交列表。 这些列表限于 250 次提交。 如果超过该限制，将会出现一条表示附加评论的注释（但不显示）。
