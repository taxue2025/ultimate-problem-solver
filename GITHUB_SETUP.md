# GitHub 发布指南

## 步骤 1: 在 GitHub 上创建仓库

1. 打开 https://github.com/new
2. 仓库名称: `ai-skills-collection` (或其他你喜欢的名字)
3. 描述: `AI助手技能集合 - 为创作者、写作者和知识工作者设计`
4. 选择 "Public" (公开)
5. 不要勾选 "Initialize this repository with a README"
6. 点击 "Create repository"

## 步骤 2: 推送本地代码到 GitHub

在终端执行以下命令：

```bash
cd /Users/taxuexunxian/Documents/trae_projects/2026/Skill
git remote add origin https://github.com/你的用户名/ai-skills-collection.git
git push -u origin main
```

## 步骤 3: 验证

推送成功后，访问：
https://github.com/你的用户名/ai-skills-collection

你应该能看到所有 Skill 文件和 README。

## 可选: 使用 GitHub CLI (更快)

如果你安装了 GitHub CLI，可以直接执行：

```bash
cd /Users/taxuexunxian/Documents/trae_projects/2026/Skill
gh repo create ai-skills-collection --public --source=. --push
```

## 分享链接

发布后，你可以分享这个链接：
https://github.com/你的用户名/ai-skills-collection

其他人可以直接复制 Skill 文件内容使用。
