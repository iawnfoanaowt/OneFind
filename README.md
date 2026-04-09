# Knowledge Base Gateway

`Knowledge Base Gateway` 是面向 Codex 的本地科研知识检索网关，用于把 `Obsidian` 与 `Zotero` 中已经积累的资料统一纳入只读检索与问答流程。

它的目标不是替代你的知识库管理习惯，而是让 Codex 先从本地证据中检索，再基于命中的资料回答问题、做主题梳理、论文比较和方法分析。

## 当前版本

- 版本号：`1.0.2026.40922`
- 发布日期：`2026-04-09`
- 发布说明：[docs/releases/v1.0.2026.40922.md](docs/releases/v1.0.2026.40922.md)

## 当前版本已实现功能

- 支持同时接入 `Obsidian` 与 `Zotero`，也支持任一单独使用。
- 只读读取本地知识库，不写入或修改 Obsidian 源资料、Zotero 数据库或 storage。
- 建立本地索引，覆盖：
  - Obsidian Markdown 笔记
  - Zotero 文献元数据
  - Zotero 笔记与批注
  - Zotero 全文缓存文本
- 提供 `fast`、`balanced`、`deep` 三种检索/分析模式。
- `deep` 模式支持更重的全文证据分析，并在存在 NVIDIA GPU 时优先利用 GPU。
- 提供图形化安装器、图形化卸载器和便携包三种交付形式。
- 安装器支持安装前路径校验、旧版本卸载、首次环境准备和基础自检。
- 安装结果固定落到当前用户 `.codex` 目录，不写注册表、不改 PATH、不建快捷方式。
- 提供自然语言友好的首用流程，可让 Codex 直接执行索引初始化与 `deep` 模式检测。

## 发布文件

当前版本对应 3 个分发文件：

- `KnowledgeBaseGatewayInstaller.exe`
- `KnowledgeBaseGatewayUninstall.exe`
- `KnowledgeBaseGateway_Portable.zip`

由于 GitHub 仓库单文件限制为 `100 MB`，这 3 个打包产物不适合直接提交进仓库历史。
仓库中保留的是说明文档、截图、版本清单和校验信息；二进制安装包建议放到 GitHub Releases 作为版本资产发布。

## 安装与使用

- 安装说明：[安装说明.md](安装说明.md)
- 版权说明：[版权声明.txt](版权声明.txt)

首次安装完成后，建议在 Codex 中执行：

```text
请检测 deep 模式能否正常调用，并初始化建立索引
```

## 截图预览

### 安装器界面

![安装器界面](docs/screenshots/installer-ui.png)

### 在 Codex 中启用技能

![Codex 技能入口](docs/screenshots/codex-skill-entry.png)

### 普通模式检索示例

![普通模式回答示例](docs/screenshots/answer-example.png)

### deep 模式分析示例

![deep 模式分析示例](docs/screenshots/deep-analysis-example.png)

### deep 检测与索引初始化示例

![deep 检测与索引初始化示例](docs/screenshots/deep-check-and-index-init.png)

## 适用场景

- 文献和笔记长期积累较多，需要围绕具体问题快速回溯证据。
- 同时使用 `Zotero` 和 `Obsidian` 管理科研资料。
- 需要让 Codex 在本地知识库中做统一检索，而不是手工翻找或重新上传资料。

## 维护建议

- 每次重新打包后，先更新版本号与发布说明，再上传对应 release 资产。
- 若 Obsidian 或 Zotero 内容变化较大，建议重新构建索引。
- 若 Windows 阻止未签名 EXE，可优先使用便携包中的安装脚本。

## 版权

版权所有：`CrazyGIS`

仅限个人学习与科研使用，禁止商用、二次售卖和未授权再分发。详细条款见 [版权声明.txt](版权声明.txt)。
