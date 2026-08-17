# 常皓林 (Haolin Chang) 个人学术主页

参考 [Haojie Zhang 的主页](https://zhj12399.github.io/project) 样式构建的个人学术主页,纯静态 HTML,无需任何构建工具,可直接部署到 GitHub Pages。

## 文件结构

```
homepage/
├── index.html          # Home:简介、单位、教育经历、联系方式
├── journal.html        # Journal Paper:期刊论文
├── conference.html     # Conference Paper:会议论文
├── patent.html         # Patent:专利
├── project.html        # Project:科研项目
├── award.html          # Awards:获奖
├── activity.html       # Activity:学术活动
└── assets/
    ├── css/style.css   # 样式(改编自 minimal 主题)
    └── js/scale.fix.js # 移动端视口修复脚本
```

## 部署到 GitHub Pages

1. 在 GitHub 新建一个仓库,命名为 `你的用户名.github.io`(例如 `changhaolin.github.io`)。
2. 把本目录中的所有文件上传(或 `git push`)到该仓库的默认分支。
3. 进入仓库 **Settings → Pages**,确认 Source 已选为默认分支的根目录(新建的 `用户名.github.io` 仓库默认自动开启)。
4. 等待 1~2 分钟,访问 `https://你的用户名.github.io` 即可看到主页。

> 也可以部署到任意仓库:Settings → Pages → Source 选择分支和 `/ (root)` 目录,然后访问 `https://你的用户名.github.io/仓库名`。本站所有链接均使用相对路径,两种部署方式都能正常工作。

## 上线前需要补充的内容

所有待填位置都用 `【待补充】` 或 `<!-- TODO: ... -->` 注释标记,直接搜索这两个关键词即可找到:

- **侧边栏外链**:Google Scholar、ResearchGate、GitHub、ORCID 四个链接目前指向 `#`,替换为你的真实主页地址(7 个页面都要改)。
- **index.html**:个人简介、所属单位、本/硕/博教育经历、邮箱与地址;不需要的学段整段删除即可。
- **journal / conference / patent / project / award / activity**:每个页面都有一条【待补充】占位项,并附有格式示例(在 HTML 注释里)。
- **导师/单位侧边栏信息**(可选):`index.html` 中有一段被注释掉的 `author-info`,需要时取消注释并填入内容。
