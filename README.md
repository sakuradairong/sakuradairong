<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/profile-hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/profile-hero-light.svg">
  <img src="./assets/profile-hero-light.svg" width="100%" alt="RainySY — Build small. Make it useful. 本地 AI、实用工具与自动化。">
</picture>

<p align="center">
  <br>
  <a href="https://sakuradairong.github.io">博客</a>
  &nbsp; · &nbsp;
  <a href="#selected-projects">精选</a>
  &nbsp; · &nbsp;
  <a href="#project-directory">目录</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/sakuradairong?tab=repositories">仓库</a>
</p>

## 把日常的小麻烦，写成顺手的工具。

我是 **RainySY**，也就是 **@sakuradairong**。

做一些自己会用的小系统：把模型接进本地工作流，让备份和存储少些折腾，也给桌面、聊天机器人和游戏写点实用工具。偏好能落进日常的东西——少一个重复步骤，多一点顺手。

<p>
  <b>本地 AI / Agent 工作流 / 实用自动化</b><br>
  <sub>Python · TypeScript · Go · Kotlin · Rust · C# · Lua · Shell · Cloudflare</sub>
</p>

<br>

<a name="selected-projects"></a>

## 精选项目 <sub>/ Selected work</sub>

从模型、备份到游戏中控，挑了六个不同方向的项目。

<table>
  <tr>
    <td width="50%" valign="top">
      <sub>01 / AGENT WORKFLOW</sub>
      <h3><a href="https://github.com/sakuradairong/omp-config">omp-config ↗</a></h3>
      <p>把 agent 工作流整理成可复用的配置：Oh My Pi 模型覆盖、hooks 与 skills。</p>
      <p><sub>AI AGENTS · CONFIGURATION</sub></p>
    </td>
    <td width="50%" valign="top">
      <sub>02 / LOCAL AI</sub>
      <h3><a href="https://github.com/sakuradairong/local-fusion-gateway">local-fusion-gateway ↗</a></h3>
      <p>本地 OpenAI 兼容多模型融合网关，带受控的 code-research 工具。</p>
      <p><sub>MODEL GATEWAY · LOCAL TOOLS</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <sub>03 / BACKUP &amp; STORAGE</sub>
      <h3><a href="https://github.com/sakuradairong/android-backup-gui">android-backup-gui ↗</a></h3>
      <p>给 Android 做备份与恢复，支持 restic 增量去重、WebDAV / SMB 和断点续传。</p>
      <p><sub>KOTLIN · ANDROID · RESTIC</sub></p>
    </td>
    <td width="50%" valign="top">
      <sub>04 / EVERYDAY TOOLS</sub>
      <h3><a href="https://github.com/sakuradairong/tiez-clipboard">tiez-clipboard ↗</a></h3>
      <p>基于 Tauri 的跨平台剪贴板管理器，把日常复制粘贴整理得更顺手。</p>
      <p><sub>TAURI · DESKTOP</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <sub>05 / SIM &amp; PLAY</sub>
      <h3><a href="https://github.com/sakuradairong/TruckDeck">TruckDeck ↗</a></h3>
      <p>让手机成为 ETS2 / ATS 的横屏中控，在局域网里查看遥测、发送按键操作。</p>
      <p><sub>EXPRESS · WEBSOCKET · ETS2 / ATS</sub></p>
    </td>
    <td width="50%" valign="top">
      <sub>06 / CHATBOT PLUGINS</sub>
      <h3><a href="https://github.com/sakuradairong/astrbot_plugin_fishing">AstrBot Fishing ↗</a></h3>
      <p>给 AstrBot 加一个钓鱼互动插件，在聊天里留一点游戏时间。</p>
      <p><sub>ASTRBOT · CHAT &amp; PLAY</sub></p>
    </td>
  </tr>
</table>

<br>

<a name="project-directory"></a>

## 还有一些小东西 <sub>/ Project directory</sub>

按使用场景整理，展开看看。

<details>
<summary><b>01 · AI Agents 与本地模型</b> — 配置、模型选择与网关</summary>

| 项目 | 用来做什么 |
| --- | --- |
| [omp-config](https://github.com/sakuradairong/omp-config) | Oh My Pi agent 配置、模型覆盖、hooks、skills |
| [local-fusion-gateway](https://github.com/sakuradairong/local-fusion-gateway) | 本地多模型融合网关 |
| [pi-model-selector](https://github.com/sakuradairong/pi-model-selector) | pi 的交互式模型选择扩展 |
| [pi-moa](https://github.com/sakuradairong/pi-moa) | pi / agent 相关工具 |

</details>

<details>
<summary><b>02 · 输入法与效率</b> — 输入、剪贴板与键盘</summary>

| 项目 | 用来做什么 |
| --- | --- |
| [rime-config](https://github.com/sakuradairong/rime-config) | 基于雾凇拼音的个人 Rime 配置 |
| [rime-lua-scripts](https://github.com/sakuradairong/rime-lua-scripts) | 个人 Rime Lua 脚本 |
| [tiez-clipboard](https://github.com/sakuradairong/tiez-clipboard) | Tauri 跨平台剪贴板管理器 |
| [keystats-heatmap](https://github.com/sakuradairong/keystats-heatmap) | 3D 键盘使用热力图 |

</details>

<details>
<summary><b>03 · Android、备份与存储</b> — 数据的整理与安放</summary>

| 项目 | 用来做什么 |
| --- | --- |
| [android-backup-gui](https://github.com/sakuradairong/android-backup-gui) | Kotlin Android 备份恢复 GUI |
| [backup_script](https://github.com/sakuradairong/backup_script) | 支持远程存储的备份脚本 |
| [samba](https://github.com/sakuradairong/samba) | Samba Android arm64 静态构建产物 |
| [normalize-filenames](https://github.com/sakuradairong/normalize-filenames) | 清理 NFD / NFC 文件名重复 |

</details>

<details>
<summary><b>04 · 聊天机器人</b> — 互动、查询与链接预览</summary>

| 项目 | 用来做什么 |
| --- | --- |
| [astrbot_plugin_fishing](https://github.com/sakuradairong/astrbot_plugin_fishing) | AstrBot 钓鱼互动插件 |
| [astrbot_plugin_pubg](https://github.com/sakuradairong/astrbot_plugin_pubg) | AstrBot PUBG 战绩查询 |
| [astrbot_plugin_Gitparser](https://github.com/sakuradairong/astrbot_plugin_Gitparser) | GitHub 仓库解析与事件通知 |
| [astrbot_plugin_linuxdo](https://github.com/sakuradairong/astrbot_plugin_linuxdo) | linux.do 链接预览与截图 |
| [astrbot-plugin-linuxsb](https://github.com/sakuradairong/astrbot-plugin-linuxsb) | linux.sb 论坛帖子预览 |
| [astrbot-plugin-dev](https://github.com/sakuradairong/astrbot-plugin-dev) | AstrBot 插件开发工作区 |

</details>

<details>
<summary><b>05 · 桌面与游戏</b> — 日常小工具，也有兴趣使然</summary>

| 项目 | 用来做什么 |
| --- | --- |
| [TruckDeck](https://github.com/sakuradairong/TruckDeck) | ETS2 / ATS 遥测与按键注入手机中控 |
| [7dtd-server-manager](https://github.com/sakuradairong/7dtd-server-manager) | 七日杀专用服管理（Telnet / RCON） |
| [XUnity.AutoTranslator.AIUniversal](https://github.com/sakuradairong/XUnity.AutoTranslator.AIUniversal) | 游戏 AI 翻译插件（OpenAI 兼容 API） |
| [bilidesk](https://github.com/sakuradairong/bilidesk) | B 站 Windows 桌面客户端（自用） |
| [minimaximage](https://github.com/sakuradairong/minimaximage) | Minimax 图像生成 CLI / GUI |
| [OfficeTap](https://github.com/sakuradairong/OfficeTap) | Excel VSTO 工作簿标签任务窗格 |
| [office-data-matcher](https://github.com/sakuradairong/office-data-matcher) | Office 数据匹配工具 |
| [go-123pan-pic](https://github.com/sakuradairong/go-123pan-pic) | 123 盘图片上传 CLI |

</details>

<details>
<summary><b>06 · Web、Cloud 与个人基础设施</b> — 服务、脚本与自己的角落</summary>

| 项目 | 用来做什么 |
| --- | --- |
| [smartstrm-cleanroom](https://github.com/sakuradairong/smartstrm-cleanroom) | Go 实现的 STRM 自动化服务 |
| [r2-explorer-template](https://github.com/sakuradairong/r2-explorer-template) | Cloudflare R2 文件浏览器模板 |
| [SubConverter-Extended](https://github.com/sakuradairong/SubConverter-Extended) | 基于 Aethersailor/SubConverter-Extended 的扩展构建 |
| [typix](https://github.com/sakuradairong/typix) | TypeScript 工具集 |
| [deepseek-monitor](https://github.com/sakuradairong/deepseek-monitor) | DeepSeek API 状态监控 |
| [sakuradairong.github.io](https://github.com/sakuradairong/sakuradairong.github.io) | GitHub Pages 博客 |
| [picture](https://github.com/sakuradairong/picture) | 个人图床仓库 |

</details>

<br>

---

<p align="center">
  <b>小而有用，慢慢打磨。</b><br>
  <sub>RainySY · <a href="https://sakuradairong.github.io">写点东西</a> · <a href="https://github.com/RainySY">旧账号 @RainySY</a></sub>
</p>
