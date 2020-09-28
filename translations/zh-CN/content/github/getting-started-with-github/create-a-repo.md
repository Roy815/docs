---
title: 创建仓库
redirect_from:
  - /create-a-repo/
  - /articles/create-a-repo
intro: '要将项目放在 {{ site.data.variables.product.product_location }} 上，您需要创建一个仓库来存放它。'
versions:
  free-pro-team: '*'
  enterprise-server: '*'
---

您可以在 {{ site.data.variables.product.product_name }} 仓库中存储各种项目，包括开源项目。 通过[开源项目](http://opensource.org/about)，您可以共享代码以开发更好、更可靠的软件。

{% note %}

**注：**您可以为开源项目创建公共仓库。 创建公共仓库时，请确保包含[许可文件](http://choosealicense.com/)以确定您希望与其他人共享项目。 {{ site.data.reusables.open-source.open-source-guide-repositories }} {{ site.data.reusables.open-source.open-source-learning-lab }}

{% endnote %}

{{ site.data.reusables.repositories.create_new }}
2. 为仓库键入简短、令人难忘的名称。 例如 "hello-world"。 ![用于输入仓库名称的字段](/assets/images/help/repository/create-repository-name.png)
3. （可选）添加仓库的说明。 例如，“我在 {{ site.data.variables.product.product_name }} 上的第一个仓库”。 ![用于输入仓库说明的字段](/assets/images/help/repository/create-repository-desc.png)
{{ site.data.reusables.repositories.choose-repo-visibility }}
{{ site.data.reusables.repositories.initialize-with-readme }}
{{ site.data.reusables.repositories.create-repo }}

恭喜！ 您已成功创建第一个仓库，并使用*自述文件*对其进行了初始化。

{% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.19" %}
{% tip %}

**Tip**: You can also create repositories using the {{ site.data.variables.product.prodname_cli }}. For more information, see "[`gh repo create`](https://cli.github.com/manual/gh_repo_create)" in the {{ site.data.variables.product.prodname_cli }} documentation.

{% endtip %}
{% endif %}

### 提交您的第一个更改

A *[提交](/articles/github-glossary#commit)*就像是项目中所有文件在特定时间点的快照。

创建新仓库时，您使用*自述文件*对其进行了初始化。 *自述文件*是详细介绍项目的好工具，您也可以添加一些文档，例如介绍如何安装或使用项目的文档。 *自述文件*的内容自动显示在仓库的首页上。

让我们提交对*自述文件*的更改。

1. 在仓库的文件列表中，单击 ***README.md***。 ![文件列表中的自述文件](/assets/images/help/repository/create-commit-open-readme.png)
2. 在文件内容的上方，单击 {% octicon "pencil" aria-label="The edit icon" %}。
3. 在 **Edit file（编辑文件）**选项卡上，键入一些关于您自己的信息。 ![文件中的新内容](/assets/images/help/repository/edit-readme-light.png)
{{ site.data.reusables.files.preview_change }}
5. 查看您对文件所做的更改。 您会看到新内容以绿色显示。 ![文件预览视图](/assets/images/help/repository/create-commit-review.png)
{{ site.data.reusables.files.write_commit_message }}
{{ site.data.reusables.files.choose_commit_branch }}
{{ site.data.reusables.files.propose_file_change }}

### 祝贺

恭喜！ 您现在已经创建了一个仓库，其中包括*自述文件*，并在 {{ site.data.variables.product.product_location }} 上创建了您的第一个提交。 接下来您要做什么？

- “[设置 Git](/articles/set-up-git)”
- **创建仓库**
- “[复刻仓库](/articles/fork-a-repo)”
- “[社交化](/articles/be-social)”
- {{ site.data.reusables.support.connect-in-the-forum-bootcamp }}