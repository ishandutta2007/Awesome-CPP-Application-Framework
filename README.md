# Awesome-CPP-Application-Framework

# 顶级 C++ 应用框架生态系统



**精选商业产品与开源 GitHub 项目列表**

*聚焦 GUI 工具包、通用库、音频框架与即时模式 UI*

**最后更新：2026 年 10 月**



本仓库追踪 **C++ 应用框架** 领域的知名 **商业产品**与**开源项目**。这些工具帮助 C++ 开发者构建跨平台桌面应用、嵌入式设备 UI、音频处理软件和高性能图形界面。



**示例**包括 Microsoft Foundation Class (MFC)、Qt、wxWidgets、JUCE、Boost、C++Builder VCL、POCO C++ Libraries、FLTK、GTKmm 和 Dear ImGui（该领域的领先者）。



**开源重点**：C++ 应用框架领域拥有 **极为成熟且多样化的开源生态**。**wxWidgets** 和 **FLTK** 允许在专有软件中自由使用，无需开源你的代码 。**GTKmm** 采用 LGPL 许可，可开发闭源商业软件 。**POCO** 和 **Dear ImGui** 则采用宽松的 Boost/MIT 许可，完全免费用于商业项目 。本列表重点收录这些生产级方案。



欢迎贡献！提交 PR 以添加/更新条目。保持描述事实性，并链接到官方网站。



## 目录



- [💼 商业产品](#-商业产品)

- [🔓 开源 GitHub 项目](#-开源-github-项目)

- [如何贡献](#如何贡献)

- [免责声明](#免责声明)



## 💼 商业产品



> **📊 市场背景**：C++ GUI 框架市场 **高度集中** —— **Qt** 是唯一真正意义上的商业 C++ 应用框架，采用**双重许可模式**（商业许可 + 开源 GPL/LGPL）。**Microsoft MFC** 和 **Embarcadero VCL** 是 Windows 平台专属的框架，随各自 IDE 授权提供 。Qt 的商业许可按订阅制收费，包含技术支持、维护周期延长和合规认证支持 。评估期为 **10 天**，可联系销售延长 。



| 产品 | 描述 | 定价（起步层级） | 免费层级限制 | 公司规模 |

|------|------|------------------|--------------|----------|

| **[Qt 商业许可](https://www.qt.io/development/qt-framework/commercial-qt)** | **最全面的跨平台 C++ 应用框架。** 提供 Application Development（桌面/移动应用）和 Device Creation（嵌入式设备）两种许可。包含 QML、Qt Widgets、Qt Quick、Multimedia、Networking 等模块 。 | **Application Development Professional**：订阅制，需联系销售获取报价。**Device Creation** 另需**每设备 Distribution License** 。 | **10 天评估期**，可联系销售延长。评估期间**不得用于生产或实际产品开发** 。 | **上市公司（Qt Group）** |

| **[Microsoft Foundation Class (MFC)](https://learn.microsoft.com/en-us/cpp/mfc/mfc-desktop-applications)** | **Windows 平台经典 C++ 框架。** 随 Visual Studio 提供，封装 Win32 API 用于构建原生 Windows 桌面应用 。 | **随 Visual Studio 授权提供**。社区版 Visual Studio 免费，但**不包含 MFC**（需单独获取）。 | **Visual Studio Community 免费**，但 MFC 需额外配置。**MFC 再分发**需有效 Visual Studio 许可证 。 | **~$281B 营收（Microsoft FY2025）** |

| **[C++Builder VCL](https://www.embarcadero.com/products/cbuilder)** | **Windows 平台原生 UI 框架。** 随 C++Builder 提供，用于构建数据密集型桌面应用 。 | **Professional**：**$1,599**（促销 $880+$399）；**Enterprise**：**$3,999**（促销 $2,000+$2,999）；**Architect**：**$5,999**（促销 $2,800+$4,199）。 | **Community Edition**：免费，适用于**年收入低于 $5,000 美元**的自由开发者、初创企业和非营利组织 。 | **私有（Embarcadero）** |



## 🔓 开源 GitHub 项目



按星标数降序排列。星标徽章链接到对应仓库的 stargazers 页面。



| 仓库 | 描述 | 星标 |

|------|------|------|

| **[Boost](https://github.com/boostorg/boost)** — **C++ 标准库的试验场。** 提供智能指针、正则表达式、线程、文件系统、日期时间等高质量库，许多已成为 C++ 标准的一部分。**Boost 软件许可**，商业友好。 | [![Stars](https://img.shields.io/github/stars/boostorg/boost?style=social&color=white)](https://github.com/boostorg/boost/stargazers) | ~7,500 |

| **[Dear ImGui](https://github.com/ocornut/imgui)** — **即时模式 GUI 库，专为游戏引擎和工具打造。** 极简、快速、无外部依赖。MIT 许可，完全免费用于商业项目 。 | [![Stars](https://img.shields.io/github/stars/ocornut/imgui?style=social&color=white)](https://github.com/ocornut/imgui/stargazers) | ~65,000 |

| **[wxWidgets](https://github.com/wxWidgets/wxWidgets)** — **跨平台原生 GUI 框架。** 使用各平台原生控件，应用外观与操作系统一致。**允许在专有软件中自由使用**，无需开源你的代码 。 | [![Stars](https://img.shields.io/github/stars/wxWidgets/wxWidgets?style=social&color=white)](https://github.com/wxWidgets/wxWidgets/stargazers) | ~6,000 |

| **[FLTK](https://github.com/fltk/fltk)** — **轻量级跨平台 GUI 工具包。** 体积小、速度快、依赖少。**GNU LGPL 许可**，可用于商业软件 。 | [![Stars](https://img.shields.io/github/stars/fltk/fltk?style=social&color=white)](https://github.com/fltk/fltk/stargazers) | ~2,000 |

| **[JUCE](https://github.com/juce-framework/JUCE)** — **音频应用开发框架。** 用于构建音频插件、DAW、合成器等。**JUCE Personal 免费**（年收入低于 $50K），Indie $35/月，Pro $65/月 。 | [![Stars](https://img.shields.io/github/stars/juce-framework/JUCE?style=social&color=white)](https://github.com/juce-framework/JUCE/stargazers) | ~7,000 |

| **[POCO C++ Libraries](https://github.com/pocoproject/poco)** — **网络和应用程序框架。** 类似 Java 类库或 .NET 框架的 C++ 集合。**Boost 软件许可**，完全免费用于商业和非商业用途 。 | [![Stars](https://img.shields.io/github/stars/pocoproject/poco?style=social&color=white)](https://github.com/pocoproject/poco/stargazers) | ~8,500 |

| **[GTKmm](https://github.com/GNOME/gtkmm)** — **GTK+ 的官方 C++ 接口。** 采用 **LGPL 许可**，可开发开源、自由或**闭源商业软件**，无需购买许可证 。 | [![Stars](https://img.shields.io/github/stars/GNOME/gtkmm?style=social&color=white)](https://github.com/GNOME/gtkmm/stargazers) | ~3,000 |



**值得探索的其他开源选项：**



| 仓库 | 描述 |

|------|------|

| **[NanoGUI](https://github.com/wjakob/nanogui)** — 基于 OpenGL 的极简跨平台 GUI 库，适合图形应用。 |

| **[ImGui Docking](https://github.com/ocornut/imgui/tree/docking)** — Dear ImGui 的 docking 分支，支持可停靠窗口。 |

| **[Slint](https://github.com/slint-ui/slint)** — 声明式 GUI 工具包，支持 C++、Rust 和 JavaScript。 |

| **[Ultralight](https://github.com/ultralight-ux/Ultralight)** — 轻量级 HTML UI 渲染引擎，适用于 C++ 应用。 |



## 如何贡献



1. Fork 仓库。

2. 在 `README.md` 中添加/编辑条目（遵循现有格式）。

3. 包含：名称、链接、1–2 句描述，以及是商业产品还是开源。

4. 提交 PR 并附简短说明。



如果你觉得这个仓库有用，请点星！



## 免责声明



- 这是一个 **社区精选** 列表——并非详尽无遗，也不构成认可。

- C++ 应用框架处理敏感的应用逻辑和用户数据；确保适当的访问控制和合规性。

- **开源现实**：C++ 应用框架领域拥有 **极为成熟且许可友好的开源生态**。**wxWidgets** 和 **FLTK** 允许在专有软件中自由使用 ，**GTKmm** 的 LGPL 许可允许闭源商业开发 ，**POCO** 和 **Dear ImGui** 采用宽松的 Boost/MIT 许可 。**Qt 的开源版本**（GPL/LGPL）同样可用，但商业项目需仔细评估许可条款 —— **开源的核心是自由，而非免费** 。商业产品（MFC、VCL）主要面向 Windows 平台和企业级 Visual Studio/C++Builder 用户 。



---



**为 C++ 开发者、系统架构师、嵌入式工程师和桌面应用开发团队打造。**

让 C++ 应用开发更开放、透明、可移植。
# Awesome-CPP-Application-Framework

# Awesome-CPP-Application-Framework

**Curated List of Commercial Products & Open-Source GitHub Projects**
*Focused on GUI Toolkits, General-Purpose Libraries, Audio Frameworks & Immediate-Mode UI*
**Last updated: October 2026**

This repository tracks notable **commercial products** and **open-source projects** for **C++ Application Frameworks**. These tools help C++ developers build cross-platform desktop applications, embedded device UIs, audio processing software, and high-performance graphical interfaces.

**Examples** include Microsoft Foundation Class (MFC) Library, Qt, wxWidgets, JUCE, Boost, C++Builder VCL, POCO C++ Libraries, FLTK, GTKmm, and Dear ImGui (the category leaders).

**Open-source emphasis**: The C++ application framework ecosystem is **exceptionally mature and license-friendly**. **wxWidgets** and **FLTK** allow free use in proprietary software without open-sourcing your code . **GTKmm** uses LGPL licensing, enabling closed-source commercial development . **POCO** and **Dear ImGui** use permissive Boost/MIT licenses, completely free for commercial projects . This section documents these production-grade solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📖 Table of Contents

- [💼 Commercial Products](#-commercial-products)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## 💼 Commercial Products

> **📊 Market Context**: The C++ GUI framework market is **highly concentrated** — **Qt** is the only true commercial C++ application framework with a **dual-licensing model** (commercial + open-source GPL/LGPL). **Microsoft MFC** and **Embarcadero VCL** are Windows-only frameworks bundled with their respective IDEs . Qt's commercial licenses are subscription-based, including technical support, extended maintenance cycles, and compliance certification support . Evaluation period is **10 days**, extendable by contacting sales .

| Product | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |
|----------|-------------|------------------------|------------------|--------------|
| **[Qt Commercial](https://www.qt.io/development/qt-framework/commercial-qt)** | **The most comprehensive cross-platform C++ application framework.** Application Development (desktop/mobile) and Device Creation (embedded) licenses. Includes QML, Qt Widgets, Qt Quick, Multimedia, Networking modules . | **Application Development Professional**: Subscription-based; contact sales for quote. **Device Creation**: Additional per-device Distribution License required . | **10-day evaluation period**, extendable by contacting sales. **Cannot be used for production or actual product development** during evaluation . | **Public (Qt Group)** |
| **[Microsoft Foundation Class (MFC)](https://learn.microsoft.com/en-us/cpp/mfc/mfc-desktop-applications)** | **The classic Windows C++ framework.** Ships with Visual Studio, wraps Win32 API for native Windows desktop applications . | **Bundled with Visual Studio licensing**. Visual Studio Community is free but **does not include MFC** (requires separate acquisition). | **Visual Studio Community is free** but MFC requires additional configuration. **MFC redistribution** requires a valid Visual Studio license . | **~$281B revenue (Microsoft FY2025)** |
| **[C++Builder VCL](https://www.embarcadero.com/products/cbuilder)** | **Native Windows UI framework.** Ships with C++Builder, used for building data-intensive desktop applications . | **Professional**: **$1,599** (promo $880+$399); **Enterprise**: **$3,999** (promo $2,000+$2,999); **Architect**: **$5,999** (promo $2,800+$4,199). | **Community Edition**: Free for freelancers, startups, and non-profits with **annual revenue under $5,000** . | **Private (Embarcadero)** |

## 🔓 Open-Source GitHub Projects

Sorted by star count (descending). Star badge links to each repo's stargazers page.

| Repo | Description | Stars |
|---|---|---|
| **[Dear ImGui](https://github.com/ocornut/imgui)** — **Immediate-mode GUI library for game engines and tools.** Minimal, fast, no external dependencies. MIT licensed, completely free for commercial projects . | [![Stars](https://img.shields.io/github/stars/ocornut/imgui?style=social&color=white)](https://github.com/ocornut/imgui/stargazers) | ~65,000 |
| **[Boost](https://github.com/boostorg/boost)** — **The C++ standard library proving ground.** Smart pointers, regex, threading, filesystem, date-time, and more—many now part of C++ standard. **Boost Software License**, commercial-friendly. | [![Stars](https://img.shields.io/github/stars/boostorg/boost?style=social&color=white)](https://github.com/boostorg/boost/stargazers) | ~7,500 |
| **[POCO C++ Libraries](https://github.com/pocoproject/poco)** — **Network-centric and application framework.** A C++ collection similar to Java class libraries or .NET Framework. **Boost Software License**, completely free for commercial and non-commercial use . | [![Stars](https://img.shields.io/github/stars/pocoproject/poco?style=social&color=white)](https://github.com/pocoproject/poco/stargazers) | ~8,500 |
| **[JUCE](https://github.com/juce-framework/JUCE)** — **Audio application development framework.** Used for audio plugins, DAWs, synthesizers. **JUCE Personal free** (annual revenue under $50K), Indie $35/month, Pro $65/month . | [![Stars](https://img.shields.io/github/stars/juce-framework/JUCE?style=social&color=white)](https://github.com/juce-framework/JUCE/stargazers) | ~7,000 |
| **[wxWidgets](https://github.com/wxWidgets/wxWidgets)** — **Cross-platform native GUI framework.** Uses native controls, so app appearance matches the OS. **Allows free use in proprietary software** without open-sourcing your code . | [![Stars](https://img.shields.io/github/stars/wxWidgets/wxWidgets?style=social&color=white)](https://github.com/wxWidgets/wxWidgets/stargazers) | ~6,000 |
| **[GTKmm](https://github.com/GNOME/gtkmm)** — **Official C++ interface for GTK+.** Uses **LGPL license**, enabling development of open-source, free, or **closed-source commercial software** without purchasing a license . | [![Stars](https://img.shields.io/github/stars/GNOME/gtkmm?style=social&color=white)](https://github.com/GNOME/gtkmm/stargazers) | ~3,000 |
| **[FLTK](https://github.com/fltk/fltk)** — **Lightweight cross-platform GUI toolkit.** Small, fast, few dependencies. **GNU LGPL license**, usable in commercial software . | [![Stars](https://img.shields.io/github/stars/fltk/fltk?style=social&color=white)](https://github.com/fltk/fltk/stargazers) | ~2,000 |

**Additional open-source options worth exploring:**

| Repo | Description |
|---|---|
| **[NanoGUI](https://github.com/wjakob/nanogui)** — Minimal cross-platform GUI library based on OpenGL, for graphics applications. |
| **[ImGui Docking](https://github.com/ocornut/imgui/tree/docking)** — Dear ImGui docking branch with dockable window support. |
| **[Slint](https://github.com/slint-ui/slint)** — Declarative GUI toolkit supporting C++, Rust, and JavaScript. |
| **[Ultralight](https://github.com/ultralight-ux/Ultralight)** — Lightweight HTML UI rendering engine for C++ applications. |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's commercial or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- C++ application frameworks handle sensitive application logic and user data; ensure proper access controls and compliance.
- **Open-source reality**: The C++ application framework ecosystem is **exceptionally mature and license-friendly**. **wxWidgets** and **FLTK** allow free use in proprietary software , **GTKmm** uses LGPL permitting closed-source commercial development , and **POCO** and **Dear ImGui** use permissive Boost/MIT licenses . **Qt's open-source edition** (GPL/LGPL) is also available, but commercial projects must carefully evaluate licensing terms — **the essence of open source is freedom, not free of cost** . Commercial products (MFC, VCL) target primarily Windows platforms and enterprise Visual Studio/C++Builder users .

---

**Made for C++ developers, systems architects, embedded engineers, and desktop application teams.**
Let's make C++ application development more open, transparent, and portable.
