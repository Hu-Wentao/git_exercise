# Git协作练习项目

# 0 准备工作
    .md 是MarkDown文件的后缀。
    Markdown是一种可以使用普通文本编辑器编写的标记语言。
    通过简单的标记语法，它可以使普通文本内容具有一定的格式。
## 0.1 Git安装
    进入Git官网 https://git-scm.com 下载对应安装包，一路 next 即可

## 0.2 在IDEA中启用Git
    打开IDEA，Settings -> Version Control -> Git
    在这里配置安装好的Git的路径，一般默认的路径即可，点击右侧的"Test"可以测试路径是否有效

## 0.3 在IDEA中启用Github
    打开IDEA，Settings -> Version Control -> GitHub
    点击左下角 "+" 将自己的Github账号添加到IDEA中

# 1 使用

## 1.1 导入Github上的项目
    复制项目的 Git地址
    打开IDEA，File -> New -> Project from version control -> Git
    将复制的Git地址粘贴到 URL 中，再点击 Clone 
## 1.2 回到过去 —— Revert
    在IDEA中打开项目，随意对 main.md 文件进行编辑，修改。
    然后点击右上角菜单栏中的 "Revert" 按钮（白色撤销状箭头）。
    或者右键编辑窗口 -> 在弹出菜单中选择"Git" -> 在展开菜单中选择 "Revert"
## 1.3 保存更改 —— Commit
Clone项目到本地之后，Git不会自动保存更改，直接点击Revert就会回到最近一次保存的状态

    在IDEA中打开项目，随意对 main.md 文件进行编辑，修改。
    然后点击右上角菜单栏中的 "Commit" 按钮（绿色对号）。
    或者右键编辑窗口 -> 在弹出菜单中选择"Git" -> 在展开菜单中选择 "Commit File..."
    此时会弹出 Commit Changes 窗口，
    窗口中部即为 提交信息，提交信息参照 ../standrad/CommitMessage.md 的要求的书写
## 1.4 拉取Github上的更改 —— Pull
在提交自己的更改之前，应当先从Github上拉取最新版本的代码，在最新版本的基础上进行修改（正常情况下）
    
    在IDEA中打开项目，
    然后点击右上角菜单栏中的 "Update Project" 按钮（蓝色箭头）。
    或者右键编辑窗口 -> 在弹出菜单中选择"Git" -> 在展开菜单中选择 "Repository" -> 选择"Pull..."
    