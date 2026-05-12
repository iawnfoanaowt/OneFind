<p align="right">
  <a href="./README.md">简体中文</a> | <a href="./README_EN.md">English</a>
</p>

# OneFind

> Read it before, but cannot recall it when you need it?  
> **OneFind makes your local knowledge instantly usable.** It helps users connect papers, notes, attachments, and local files to AI agents for fast retrieval and AI-assisted answers, especially when writing theses, research papers, literature reviews, grant proposals, and project documents.
>
><img width="1536" height="1024" alt="OneFind cover" src="https://github.com/user-attachments/assets/da0d5d0d-4b49-445d-af3e-4274cfdf966b" />

---

## Download

- Download: [OneFind Releases](https://github.com/iawnfoanaowt/OneFind/releases)
- Video introduction: [OneFind: make your knowledge instantly usable](https://www.bilibili.com/video/BV1kSdaBeEBt)
- WeChat official account: **OneFind** — tutorials, community information, and latest contacts

![WeChat official account: OneFind](https://github.com/user-attachments/assets/9488ebce-b03e-4c64-ad3b-a9c542b92601)

---

## 🚀 What is OneFind?

OneFind is a **local knowledge base plugin for AI agents**. It connects your local papers, notes, attachments, and folders to AI, so the AI can retrieve, summarize, and analyze your own materials instead of giving only generic answers.

With OneFind, you can:

- 🔍 Search Zotero / EndNote / Obsidian / Notion / Mendeley / Citavi / local folders from one entry point
- 💬 Ask questions in natural language instead of relying only on keywords
- 📚 Generate answers grounded in your local knowledge base
- ⚡ Build local indexes automatically for faster retrieval
- 🧠 Switch between Balance and Deep modes according to task difficulty
- 🤖 Use Codex or ZCode to connect OneFind with more AI agents and models
- 🧩 Invoke OneFind through Skill or MCP: select the OneFind Skill, or ask the agent to call OneFind directly

In one sentence:

> **OneFind does not replace your reference managers or note apps. It helps AI use the knowledge you already have.**

---

## ✨ Current support

### Supported AI platforms

- **Codex**: suitable for users who already work with ChatGPT / Codex
- **ZCode**: supports AI agent frameworks such as Claude Code, Codex, Gemini, and OpenCode, and can work with third-party model APIs

You can use either Codex or ZCode, or install both. OneFind will adapt to your local environment.

### Invocation methods

Both Codex and ZCode support two ways to call OneFind:

- **Skill invocation**: select or type the `OneFind` Skill in the input box, then ask your retrieval or analysis question.
- **Direct natural-language invocation**: simply ask the agent to “call OneFind” or “search with OneFind”; the agent can call OneFind through the MCP path.

Both methods provide the same OneFind features and improve compatibility when different local environments cannot reliably detect or invoke OneFind through only one path.

### Supported systems

- **Windows**
- **macOS Apple Silicon** devices, such as M-series Macs

### Supported data sources

- Zotero
- Obsidian
- Notion
- Mendeley Reference Manager
- Citavi 7
- EndNote, authorization required
- Local folders, authorization required
- Word / PPT / PDF / Excel / Markdown / CAJ files, partly authorization required

> Advanced parsing features such as EndNote, local folders, Office documents, and CAJ files require authorization. You may send your machine code to `zhtaogis@163.com` to request access. Authorization is available for personal learning and research use.

---

## 📸 Demos

### Search across all knowledge sources

![](https://fastly.jsdelivr.net/gh/bucketio/img1@main/2026/04/16/1776322224610-f069fd40-0e94-4fcf-97a2-6237ddcb06a6.png)

---

### Ask directly and let AI answer from your local knowledge base

![](https://fastly.jsdelivr.net/gh/bucketio/img7@main/2026/04/16/1776322324969-0f13f752-6131-45f2-96e5-7c222afe1ee0.png)

---

### Search across sources or specify one source

![](https://fastly.jsdelivr.net/gh/bucketio/img17@main/2026/04/16/1776322355773-3fec2ef3-b09a-4f11-9eed-17a516251928.png)

---

### Automatic indexing

![](https://fastly.jsdelivr.net/gh/bucketio/img4@main/2026/04/16/1776322397884-f1ce8919-e12e-47ca-8615-e984a5774cab.png)

---

### Local knowledge + web search

![](https://fastly.jsdelivr.net/gh/bucketio/img15@main/2026/04/16/1776322442958-cffc6d9d-ef03-48bf-80a5-41ffd92e7e87.png)

---

## 💡 What problem does it solve?

You may have experienced this:

- You have read many papers, but cannot recall them when writing
- Your Zotero, EndNote, Obsidian, and local folders are scattered across different places
- Finding materials requires switching between apps, folders, and keyword searches
- AI answers look fluent, but you are not sure where the evidence comes from
- It is hard to connect your existing materials when writing reviews, papers, grant proposals, or project reports

OneFind has a simple goal:

> **Make your knowledge available exactly when you need it.**

---

## ⚡ Quick start in 3 steps

### 1️⃣ Download

Download the latest installer for your system from Releases:

```text
https://github.com/iawnfoanaowt/OneFind/releases
```

### 2️⃣ Install

Before installation, prepare:

- Codex or ZCode, at least one of them
- At least one valid knowledge base path, such as Zotero, Obsidian, Notion, or a local folder
- Enough disk space if you plan to use Deep mode

During installation, you can:

- Choose a custom OneFind installation location, not limited to the C drive
- Add knowledge base paths
- Install the Deep module when needed
- Import an authorization file when needed

### 3️⃣ Initialize

In Codex or ZCode, invoke OneFind through the OneFind Skill or ask the agent to call OneFind directly, then enter:

```text
Please call OneFind to initialize the index and check whether Deep mode can be used normally.
```

The first indexing process depends on the size of your materials and your computer performance. After indexing, you can start asking questions directly.

---

## 🧠 How to use

In Codex or ZCode, OneFind can be called in two common ways:

1. **Skill invocation**: select or type the `OneFind` Skill before asking your question.
2. **Direct natural-language invocation**: ask the agent to “call OneFind” or “search with OneFind” in your prompt.

For example:

```text
Please call OneFind and summarize the research progress on water scarcity from my local knowledge base.
```

You can also ask:

- Search only in Zotero for papers on a specific topic
- Compare methods across several papers in EndNote and local PDFs
- Extract monitoring and early-warning related content from my project documents
- Build a literature review outline based on my local papers
- Find which papers discussed the limitations of a specific model

---

## 🔬 Balance vs Deep mode

| Mode | Best for |
| ---- | -------- |
| Balance | Fast retrieval, daily search, simple Q&A |
| Deep | Deeper analysis, full-text evidence retrieval, complex literature questions |

OneFind can automatically choose a suitable mode based on question difficulty. You can also specify the mode manually when needed.

---

## ⚙️ Detailed installation

<details>
<summary>Click to expand</summary>

### Before installation

1. Install Codex or ZCode. Choose at least one of them.  
2. Prepare at least one valid knowledge base path.  
3. If you need EndNote, local folder parsing, Office document parsing, or CAJ parsing, prepare authorization in advance.  
4. If you need Deep mode, reserve enough disk space.  

> ZCode is an AI agent integration platform. It does not directly provide models. To use third-party models, configure your own model API or log in to your existing Claude Code, Codex, Gemini, or other accounts.

---

### Windows installation

1. Download the Windows installer from [OneFind Releases](https://github.com/iawnfoanaowt/OneFind/releases).
2. Run the installer.
3. Choose the OneFind installation location.
4. Add your knowledge base paths.
5. Install the Deep module and import authorization if needed.
6. Open Codex or ZCode, then call OneFind through the OneFind Skill or direct natural-language invocation.

![](https://paperead-zt.oss-cn-beijing.aliyuncs.com/img/20260511100844657.png)

---

### macOS installation

The macOS version currently focuses on **Apple Silicon**, such as M-series Macs.

1. Install Codex or ZCode first.
2. Install the OneFind macOS version.
3. Set knowledge base paths, such as Zotero, Obsidian, Notion, or local folders.
4. Complete authorization if needed.
5. Grant the required local file access permissions.
6. Call OneFind through the OneFind Skill or direct natural-language invocation, then initialize the index.

![](https://paperead-zt.oss-cn-beijing.aliyuncs.com/img/20260511174720228.png)

For first-time use, enter:

```text
Please initialize the index and check whether Deep mode is available.
```

![](https://paperead-zt.oss-cn-beijing.aliyuncs.com/img/20260511182059902.png)

---

### ZCode usage

ZCode can be used to access more AI agents and third-party models.

Common options include:

- Log in to existing Claude Code / Codex / Gemini accounts
- Configure third-party model APIs, such as DeepSeek or Qwen
- Select different models in ZCode and call OneFind to retrieve your local knowledge base

![](https://paperead-zt.oss-cn-beijing.aliyuncs.com/img/20260511110818531.png)

### Skill / MCP invocation

Codex and ZCode both support the Skill + MCP dual-path design for calling OneFind:

- Select or type the `OneFind` Skill before asking a question when you want to explicitly specify the tool.
- Ask the agent directly to “call OneFind” or “search with OneFind” for everyday natural-language use.

Both methods provide the same OneFind features. The dual-path design improves compatibility and reduces cases where OneFind cannot be detected or called because of differences in local environments, platform detection, or Skill recognition.

![image-20260512213124160](https://paperead-zt.oss-cn-beijing.aliyuncs.com/img/20260512213124234.png)

![image-20260512213133250](https://paperead-zt.oss-cn-beijing.aliyuncs.com/img/20260512213133329.png)

For a more detailed guide on choosing and installing AI agents, see:

[AI Agent selection and installation guide](https://mp.weixin.qq.com/s/M_8_JRf6MmcWQwPw4Nj8PQ)

---

### Authorization

By default, OneFind can access common knowledge bases such as Zotero, Obsidian, and Notion.

To enable the following features, send your machine code to `zhtaogis@163.com`:

- EndNote access
- Local folder parsing
- Word / PPT / Excel parsing
- CAJ parsing

---

### Update and uninstall

**Update:**

For v1.5 and later, you can directly install the latest version over the old one. You do not need to re-enter paths or re-authorize.

**Uninstall:**

OneFind will not delete your original knowledge base files. To uninstall, use the uninstaller in the installation directory. On macOS, you can use:

```text
/Users/<username>/Library/Application Support/OneFind/OneFind Uninstaller.app
```

**Modify knowledge base paths:**

You can ask OneFind to modify paths through natural language, for example:

```text
Please change my Obsidian knowledge base path to XXX.
```

---

### FAQ

**Q: What should I do if installation fails?**  
A: It is usually related to network interruption, permissions, or leftovers from an older version. Try switching networks or removing the old installation directory before reinstalling.

**Q: Is ZCode required?**  
A: No. Codex users can continue using Codex. ZCode is useful if you want to connect more models.

**Q: Can Intel-based Macs use OneFind?**  
A: The macOS version currently focuses on Apple Silicon devices. Older Intel Macs may have limited retrieval performance.

**Q: Will OneFind modify my original papers or notes?**  
A: No. OneFind builds indexes from local read-only access and does not replace or damage your original knowledge base.

</details>

---

## 📌 Who is it for?

- Researchers and students
- Users writing papers, reviews, grant proposals, or project documents
- Long-term users of Zotero, Obsidian, EndNote, and similar knowledge tools
- Users with many PDFs, Word documents, PPTs, Excel files, CAJ files, or project materials
- Anyone who wants AI to answer based on their own materials rather than only general knowledge

---

## ⚠️ Notes

- OneFind does not replace your own academic judgment
- OneFind does not automatically download papers
- OneFind is more suitable for long-term knowledge management
- Third-party model APIs, Codex, Claude Code, Gemini, and similar services need to be configured or subscribed to according to their own platform rules

---

## 📄 License

For personal learning and research use only.  
For commercial use or other special authorization, please contact the copyright owner, CrazyGIS.

Email: `zhtaogis@163.com`

WeChat official account: OneFind
