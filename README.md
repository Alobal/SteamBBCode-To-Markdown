# SteamBBCode to Markdown

将Steam BBcode格式转换为Markdown格式。Convert SteamBBCode To Markdown

``-i``: 输入文件路径, 格式仅支持utf-8
``-o``: 输出文件路径, 默认为输入文件同名的.md文件

由于Markdown语法不能涵盖所有BBCode语法, 因此**以下标签不支持转换, 会自动忽略**:  ``u,spoiler,code``。

另外, **不支持标签的交叉使用, 会自动视为同等级标签**如: ``[b][i]test[/b][/i]`` ==> ``[b][i]test[/i][/b]``
