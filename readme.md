# Github 模版文档

This repo is a template for projects on github. Specifically, it is an example of the documentation and project management tools that should be included in any project.

## 安装

If you are starting a project completely from scratch, clone this repo right into that folder. Otherwise, copy files into your project as needed.

## 使用

These files only change how your project behaves on github, and most of them will only take effect once merged into your default branch (usually `master` or `dev`).

Keep them up-to-date as your project evolves.

## 内容

Here's a rundown of the files included, as well as why they're important:

### 说明

Every project should have a Readme (usually a Markdown file). It should describe your specific project and have at least three sections:

1. **Project Name** and description.
1. **Installation** List any major dependencies, system requirements, and gotchas.
1. **Usage** How to run the project.

### PR模版

This Markdown file prepopulates new Pull Requests. Using it as a prompt helps team members write infomative pull requests, makes code easier to test, and leaves a paper trail of code and decisions.

It can live in the `/.github` folder, the `/docs` folder, or the project root.

### 问题模版

Issue templates benefit developers and any other team members who may be performing QA or developing project requirements.

These markdown files prepopulate new Issues filed on github. When a team member files an issue, they are given different prompts based on what type of issue they are creating. For example, a Bug issue template may include steps to reproduce, and a CMS template may include optional vs. required fields.

You can create as many issue templates as you want. They live in the `/.github/ISSUE_TEMPLATE` directory.

Each issue template needs to start with this markup:

```
---
name: Issue Type
about: Further description of this category.

---
```

This frontmatter will be used to populate the Issue Picker UI in Github.

## Other things to explore

- Steve Mao has a huge repository of issue templates [here](https://github.com/stevemao/github-issue-templates)
- This repo contains the essentials for running any project, but if your project is community-based, you should leverage additional documentation such as a [code of conduct](https://help.github.com/articles/adding-a-code-of-conduct-to-your-project/), [changelong](https://github.com/olivierlacan/keep-a-changelog), and [contribution guidelines](https://help.github.com/articles/setting-guidelines-for-repository-contributors/).
