+++
title = "帮助VSCode识别「Ctrl+`」"
date = 2023-06-25
taxonomies.tags = ["Rust", "VSCode"]
+++

昨天我遇到了[这个issue][issu]描述的问题，在VSCode里按下`` Ctrl+` ``完全没有反应，也无法录入这个组合键。根据评论区的提示，我尝试写一个[小工具][proj]注册这个热键并转发到活动窗口，竟然就生效了欸。问题解决了~

[issu]: https://github.com/Microsoft/vscode/issues/63659
[proj]: https://github.com/catsalwaysmeow/vscode-cjk-toggle-terminal-fixer