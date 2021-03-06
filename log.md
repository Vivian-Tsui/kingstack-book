# 11. 日志 {#11}

金山私有云平台上的“日志”服务模块管理员和普通用户分别拥有不同的权限。

## 11.1 管理员“日志” {#11-1}

管理员Admin登录控制台后，点击左侧导航栏“日志”，可查看某段时间云平台上所有用户对所有项目的操作信息，包括：操作时间、操作内容、操作人、操作结果等。
借助日志列表上方的筛选选项，管理员可按照时间段、操作对象、项目、操作人和受理结果对日志条目进行筛选。此外，通过点击右侧的“导出当前结果”按钮，还可将当前的日志信息导出到excel表格。

1. 时间选择：用户可快捷选择“今天”、最近一周“7天”、最近一个月“30天”，也可定义具体的时间段。
2. 操作对象、项目、操作人及操作结果快捷选择：点击“项目”按钮可从下拉框中选择云平台上某个特定项目对其日志进行搜索；点击“操作对象”可以从下拉框中选择某一特定资源对其日志进行快捷搜索，也可在下拉框的中输入操作对象名称进行精确搜索；点击“操作人”可以从下拉框中选择某一特定操作人对其日志进行快捷搜索，也可在下拉框的中输入操作人名称进行精确搜索；点击“结果”可从下拉框中选择某个特定结果进行快捷搜索。
3. 导出当前结果：点击“导出当前结果”按钮，日志信息会以Excel表格的形式导出，方便管理员用户进行统计分析。

![](/assets/日志列表.png)

## 11.2 普通用户“日志” {#11-2}

* Owner用户登录控制台后，选择左侧“日志”，可查看所有人在当前项目中的操作历史，并可导出日志信息到Excel表格。
* 普通member用户登录控制台后，选择左侧“日志”，仅可查看自己在当前项目中的操作历史，并可导出日志信息到Excel表格。