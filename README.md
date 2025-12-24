# 欢迎使用你的秒哒应用代码包
秒哒应用链接
    URL:https://www.miaoda.cn/projects/app-8bfaqnpyt79d

## 介绍

网文写作助手是一款专为网络小说创作设计的智能写作工具。集成 AI 实时补全、章节管理、自动保存等功能，帮助作者提升创作效率，激发写作灵感。

### 核心功能

- **章节管理**：创建、编辑、删除章节，轻松组织小说结构
- **实时 AI 补全**：停顿 1 秒自动触发，智能续写建议
- **幽灵文本显示**：补全建议以半透明文本显示在光标位置
- **快捷键操作**：Tab 键接受建议，Esc 键拒绝建议
- **自动保存**：章节内容实时保存到云端，永不丢失
- **补全历史**：记录每次 AI 建议，可随时查看和应用
- **字数统计**：实时显示章节字数

### 设计特色

- 米白色背景（#F8F6F0）营造温暖舒适的写作氛围
- 深蓝色文字（#2C3E50）确保长时间阅读不疲劳
- 橙色强调（#F39C12）突出关键操作和 AI 建议
- 三栏布局：章节列表 + 编辑器 + 信息面板
- 8px 圆角和柔和阴影，打造现代简洁的视觉效果

### 使用方法

**章节管理**：
1. 点击"新建"按钮创建章节
2. 输入章节标题（如：第一章 穿越异界）
3. 在章节列表中点击切换章节
4. 点击章节旁的删除按钮可删除章节
5. 点击章节标题旁的编辑按钮可修改标题

**AI 补全写作**：
1. 在编辑器中开始输入小说内容
2. 停止输入 1 秒后，AI 自动分析上下文
3. 补全建议以灰色半透明文本显示在光标位置
4. 按 **Tab 键**接受建议，内容自动插入
5. 按 **Esc 键**拒绝建议，继续手动输入
6. 继续输入会自动取消当前建议

**补全历史**：
1. 切换到"补全历史"标签页
2. 查看当前章节的所有补全记录
3. 点击"应用"按钮将历史补全添加到文档
4. 点击删除按钮清除不需要的记录

### 最佳实践

- 输入至少 10 个字符后才会触发补全
- 保持情节连贯，人物性格一致
- 适当使用对话推动剧情发展
- 注重场景描写和细节刻画
- 合理运用 AI 建议激发创作灵感
- 内容自动保存，但建议定期手动保存

## 目录结构

```
├── README.md # 说明文档
├── components.json # 组件库配置
├── index.html # 入口文件
├── package.json # 包管理
├── postcss.config.js # postcss 配置
├── public # 静态资源目录
│   ├── favicon.png # 图标
│   └── images # 图片资源
├── src # 源码目录
│   ├── App.tsx # 入口文件
│   ├── components # 组件目录
│   ├── contexts # 上下文目录
│   ├── db # 数据库配置目录
│   ├── hooks # 通用钩子函数目录
│   ├── index.css # 全局样式
│   ├── layout # 布局目录
│   ├── lib # 工具库目录
│   ├── main.tsx # 入口文件
│   ├── routes.tsx # 路由配置
│   ├── pages # 页面目录
│   ├── services  # 数据库交互目录
│   ├── types   # 类型定义目录
├── tsconfig.app.json  # ts 前端配置文件
├── tsconfig.json # ts 配置文件
├── tsconfig.node.json # ts node端配置文件
└── vite.config.ts # vite 配置文件
```

## 技术栈

Vite、TypeScript、React、Supabase

## 本地开发

### 如何在本地编辑代码？

您可以选择 [VSCode](https://code.visualstudio.com/Download) 或者您常用的任何 IDE 编辑器，唯一的要求是安装 Node.js 和 npm.

### 环境要求

```
# Node.js ≥ 20
# npm ≥ 10
例如：
# node -v   # v20.18.3
# npm -v    # 10.8.2
```

具体安装步骤如下：

### 在 Windows 上安装 Node.js

```
# Step 1: 访问Node.js官网：https://nodejs.org/，点击下载后，会根据你的系统自动选择合适的版本（32位或64位）。
# Step 2: 运行安装程序：下载完成后，双击运行安装程序。
# Step 3: 完成安装：按照安装向导完成安装过程。
# Step 4: 验证安装：在命令提示符（cmd）或IDE终端（terminal）中输入 node -v 和 npm -v 来检查 Node.js 和 npm 是否正确安装。
```

### 在 macOS 上安装 Node.js

```
# Step 1: 使用Homebrew安装（推荐方法）：打开终端。输入命令brew install node并回车。如果尚未安装Homebrew，需要先安装Homebrew，
可以通过在终端中运行如下命令来安装：
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
或者使用官网安装程序：访问Node.js官网。下载macOS的.pkg安装包。打开下载的.pkg文件，按照提示完成安装。
# Step 2: 验证安装：在命令提示符（cmd）或IDE终端（terminal）中输入 node -v 和 npm -v 来检查 Node.js 和 npm 是否正确安装。
```

### 安装完后按照如下步骤操作：

```
# Step 1: 下载代码包
# Step 2: 解压代码包
# Step 3: 用IDE打开代码包，进入代码目录
# Step 4: IDE终端输入命令行，安装依赖：npm i
# Step 5: IDE终端输入命令行，启动开发服务器：npm run dev -- --host 127.0.0.1
```

### 如何开发后端服务？

配置环境变量，安装相关依赖
如需使用数据库，请使用 supabase 官方版本或自行部署开源版本的 Supabase

### 如何配置应用中的三方 API？

具体三方 API 调用方法，请参考帮助文档：[源码导出](https://cloud.baidu.com/doc/MIAODA/s/Xmewgmsq7)，了解更多详细内容。

## 了解更多

您也可以查看帮助文档：[源码导出](https://cloud.baidu.com/doc/MIAODA/s/Xmewgmsq7)，了解更多详细内容。
