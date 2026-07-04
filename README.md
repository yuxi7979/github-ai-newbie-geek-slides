# GitHub AI 新手课件

这是一份面向纯文科新手的 GitHub 入门 HTML 课件，适合用来练习：

- fork 一个公开 repo
- clone 到本地
- 修改 HTML 内容
- commit 并 push 回自己的 GitHub 仓库
- 把项目 pin 到个人主页

## 在线查看

打开 `index.html` 即可查看课件。这个文件是单文件 HTML，CSS 和 JavaScript 已经内嵌，不需要安装框架或构建工具。

如果仓库开启了 GitHub Pages，也可以通过 Pages 链接在线访问。

## 学生练习流程

1. 点击右上角 **Fork**，复制一份到自己的 GitHub 账号。
2. 在自己的电脑上 clone：

   ```bash
   git clone https://github.com/<your-username>/github-ai-newbie-geek-slides.git
   cd github-ai-newbie-geek-slides
   ```

3. 用浏览器直接打开 `index.html`，确认可以看到课件。
4. 用 VS Code 打开项目：

   ```bash
   code .
   ```

5. 修改 `index.html` 里的文字，例如改成自己的课程主题、姓名或项目说明。
6. 保存并提交：

   ```bash
   git status
   git add index.html
   git commit -m "Customize slides"
   git push origin main
   ```

7. 回到 GitHub，确认自己的仓库已经更新。
8. 进入个人主页，点击 **Customize your pins**，把这个 repo pin 到主页。

## 用 Copilot 辅助修改

可以在 VS Code 里安装 GitHub Copilot / Copilot Chat，然后尝试这些 prompt：

```text
请用新手能理解的方式解释这个 index.html 的结构。
```

```text
帮我把这份课件改成适合我的专业方向，但不要改变页面样式。
```

```text
我修改后页面显示异常，请帮我检查 HTML 标签是否闭合。
```

## 注意事项

- 不要把密码、API key、token 等敏感信息写进 HTML 或提交到 GitHub。
- 每次修改前先运行 `git status`，确认自己改了哪些文件。
- commit message 尽量写清楚，例如 `Update course title`、`Add student action checklist`。

