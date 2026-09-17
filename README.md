# 王翊杰 · 机器人结构设计作品集

该仓库包含机器人结构设计求职作品集网站，展示企业项目、个人机构设计与仿真实践。网站采用纯静态 HTML、CSS 和 JavaScript，可由 GitHub Pages 直接托管，无需构建或后端服务。

## 页面

- `index.html`：灵巧手视频首页、精选项目和补充设计案例。
- `about.html`：个人介绍、教育与实习经历、能力及证书照片。
- `project.html?id=...`：六个重点项目的说明、设计图片和运动演示。
- `project.html?extra=...`：控制器外壳、四轴机械臂及其他设计图片。

旧版项目页面地址保留跳转，便于继续使用已有链接。

## 素材与维护

- `data.js` 管理项目介绍、职责、时间与图片关联。
- `media.js` 管理图片和视频路径。
- `assets/` 保存网页使用的压缩图片、无音轨视频、封面、简历和微信二维码。
- 网页使用 `assets/` 中的发布资源；原始项目素材在仓库外的工作目录中维护，不在仓库内重复存放。

所有网站视频均不含音轨，进入可见区域时自动播放、离开时暂停，提供手动播放／暂停按钮。浏览器阻止自动播放时，可点击播放按钮。图片支持放大查看，布局适配电脑和手机。

SO-ARM101 案例是开源项目复现，原始方案见 [TheRobotStudio/SO-ARM100](https://github.com/TheRobotStudio/SO-ARM100)。五指灵巧手模型与代码见 [Easyhand](https://github.com/wangyijie2/Easyhand)。

## 本地预览

在仓库根目录启动任意静态文件服务器，例如：

```sh
python -m http.server 4173
```

然后访问 `http://localhost:4173`。

## GitHub Pages

在仓库的 Settings → Pages 中，选择从默认分支的根目录发布。所有站内资源使用相对路径，兼容项目站点子路径。

