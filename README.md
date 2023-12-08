# 手动把收藏的文章做成 RSS 源

1. 在网页打开收藏的文章
2. 使用 Quicker 动作 [RSS](https://getquicker.net/Sharedaction?code=6d17cd07-e6fa-4b41-d705-08dbf7217f2d) 获取选中的文字和网页链接，拼成 `<a href="{%}">{%}</a>` 的格式输出到剪贴板
3. [编辑 index.html 文件](https://github.com/TCOTC/MyRSS/edit/main/index.html) ，在前面粘贴
4. [GitHub Action](https://github.com/TCOTC/MyRSS/actions) 自动生成 [静态页面](https://tcotc.github.io/MyRSS/)https://tcotc.github.io/MyRSS/
5. [FeedEverything](https://rsseverything.com/) 根据静态页面生成 [RSS 订阅源](https://rsseverything.com/feed/45acc535-1448-49db-8cb5-d37a76dbfec7.xml)
