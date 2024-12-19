#贴吧签到 Github Action

## 今日签到状态

![百度贴吧自动标牌](https://github.com/gwtak/TieBaSign/workflows/Baidu%20Tieba%20Auto%20Sign/badge.svg)

## 使用说明

1. Fork 本仓库，然后点击你的仓库右上角的 Settings，找到 Secrets 这一项，添加一个库秘密变量。其中 `BDUSS` 存放你的 BDUSS。支持同时添加多个帐户，BDUSS 之间用 `#` 隔开即可。

2. 设置好环境变量后点击你的仓库上方的 `行动` 选项，第一次打开需要点击 `我明白。`按钮，我喜欢你的行动

3. 任意发起一次commit，可以参考下图流程修改readme文件。

- 打开`README.md`，点击修改按钮
- 修改任意内容，这里在末尾插入了空格。移动到最下面，点击提交。

4. 至此自动签到就搭建完毕了，可以再次点击`行动`查看工作记录，如果有`百度贴吧自动标牌`则说明workflow创建成功了。点击右侧记录可以查看详细签到情况。

1

2
