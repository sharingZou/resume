# sharing

**资深前端开发** (7年经验)
*专注于 React/Vue 生态*

- 👤 **姓名**：邹雪莹 / Sharing 
- 👩‍💻 **性别**：女  
- 🎂 **年龄**：28 
- 📧 **Email**：kwwawe.z@gmail.com  
- 📍 **所在地**：杭州  
- 💰 **期望薪资**：17k  

## 🎓 教育背景 (Education)

* **武汉工程大学** | 软件工程技术 | 本科 | *2014 - 2018*
* **证书**：大学英语四级 (CET-4)

## 💡 个人优势 (Highlights)

*   **扎实的前端架构能力**：拥有 7 年前端开发经验，精通 **Vue 3 + TypeScript** 及 **React** 生态，了解其设计思想和部分源码。熟练掌握 Webpack/Vite 构建优化，多次主导项目从 0 到 1 的完整流程（构建、开发、部署），深入理解 Vite 工作原理，并能够自主开发 Vite 插件来提高项目工程化的效率。
*   **微前端架构实践**：深入理解微前端核心思想，熟练运用 **Webpack Module Federation** 实现跨应用模块共享与独立部署。在 Electron 项目中，主导将 Web 端的**登录/注册模块**及**密码管理器组件**封装为远程模块供客户端复用，消除重复开发，确保双端业务一致性，大幅缩短功能迭代周期。
*   **熟练使用 Electron 进行桌面端开发**：具备 Windows/macOS/Linux 跨平台应用开发构建经验。
*   **服务端基础（协作优势）**：了解 Node.js、Java (SpringBoot) 及 MySQL 基础。
*   **AI 工具高效应用**：日常使用 Copilot、Gemini 等 AI 编程提升开发效率。


## 🛠 技术栈 (Tech Stack)

* **核心前端**: JavaScript (ES6+), TypeScript, HTML5, CSS3 (Sass/Less), Unocss/TailwindCSS
* **框架与生态**: vue及其生态, react及其生态, Element Plus, Ant Design
* **可视化/低代码**: **Vue Flow (节点编辑)**, ECharts
* **桌面端**: **Electron**, Electron-builder, PWA
* **工程化**: Webpack, Vite, monorepo
* **后端了解**: Node.js, Java, MySQL (基础了解与简单维护)


## 💼 工作与项目经历 (Experience)


### NEXT TECH | 前端开发 (Vue 3)

*2025.03 - 2026.01*

#### 游戏权重策略配置与行为树管理系统 （2025.05 – 2026.01）

**项目描述：**
- 技术栈：Vue3 + TypeScript + Vite + Element Plus + Vue Flow + ECharts + Unocss
- 面向游戏业务风控与策略配置的中后台系统，核心功能包含可视化行为树（规则链）编辑器、RTP（返奖率）数据监控及全链路日志追踪

**主要职责：**
- 负责行为树编辑器的核心架构设计与技术攻坚，基于 Vue Flow 深度定制策略逻辑编排能力，支撑复杂规则链的拖拽生成、连线校验与局部回显
- 主导递归协议转换方案设计，实现前端 Graph 模型与后端 Tree JSON 数据的双向映射，统一数据结构交互规范
- 封装高复用业务组件（如 `AmountPlugin`），支持动态比较符切换、局数选择、多语言适配，提升全局表单交互一致性
- 基于 ECharts 开发策略效能监控看板，实现多维度数据下钻与异常指标高亮，辅助运营快速定位策略问题
- 优化表格交互体验，封装通用 Hook 解决 ElTable 数据刷新后滚动条复位问题，提升操作流畅度
- 落地完善的国际化方案，覆盖动态表单项、枚举值及图表配置的多语言切换，保障系统全球业务支撑能力

**项目亮点：**
- **可视化行为树编辑器**：基于 Vue Flow 深度定制，支持节点拖拽、连线校验、局部回显，实现低代码化的策略规则链编排能力
- **递归协议转换引擎**：设计 Graph ↔ Tree 的双向映射机制，高效处理嵌套条件与动作节点的数据结构转换，降低后端协议复杂度


#### Skyforces 游戏bot购买平台 [[线上地址](https://sky-forces.com/)] （2025.03 – 2026.01）

**项目描述：**
- 技术栈：Vue3 + Vue-router + Vite + Pinia + UnoCSS + TypeScript + Tidio
- 面向游戏玩家的 bot 购买与管理平台，支持商品浏览、bot 选购、下单支付、客服咨询

**主要职责：**
- 主导项目整体前端架构与技术选型，基于 Vue 3 + Vite 搭建高效开发环境。
- 负责核心页面（bot列表、详情、下单流程）的适配开发。
- 使用gsap动画库优化首页动画效果
- 使用 UnoCSS 实现响应式布局，采用 mobile-first 设计原则：默认类针对移动端（H5），通过 sm:/md:/lg: 等前缀渐进增强 PC 端样式（如 flex-col → flex-row、w-full → max-w-4xl、底部固定按钮 → 侧边浮动等）。
- 制定团队代码规范与 Code Review，与团队高效协作。

**项目亮点：**
- 封装 **PopupAdapter** 适配组件，统一处理弹窗/抽屉逻辑：PC 端使用居中大尺寸 Modal（fixed + transform），H5 端自动切换为底部抽屉或全屏模式（bottom-0 + slide-up 动画），一套代码兼容多端，避免重复开发。
- 通过 Tailwind 的响应式工具类（如 hidden md:block、flex-col md:flex-row、text-sm md:text-base）实现商品列表、表单、导航栏的全端自适应，一套样式代码覆盖 PC/H5，开发效率提升显著。
- 开发transform csv插件，让运营维护多语言Excel，前端只需要使用导出的csv转换成对应的语言的json文件，减少了前端开发的工作量，让前端把精力集中在业务逻辑开发上

---

### 浪桥科技 (Splashtop) | 前端开发工程师 (React + Electron)

*2022.06 - 2025.01*

#### 🚀 项目一：Splashtop Secure Workspace（桌面端 – 员工访问客户端）

**项目描述：**
- 技术栈：Electron + React 18 + Webpack Module Federation + TypeScript + electron-builder
- 面向企业员工的零信任安全访问客户端，支持 Windows/macOS/Linux 三端，提供快捷入口、应用访问控制、系统托盘交互及实时安全告警，是员工日常办公的核心入口。

**主要职责：**
- 基于 **Electron + React** 构建跨平台桌面客户端，处理 Windows & Macos 端**文件系统路径差异**、**原生窗口管理**及**全局快捷键冲突**，保障体验一致性。
- 自主实现**系统托盘 (Tray) 菜单动态更新**与**原生通知**机制，支持后台运行状态可视化及告警实时推送。
- 引入 **Webpack Module Federation**，将 Web 端的**登录/注册模块**及**密码管理器组件**封装为远程模块，实现桌面端直接复用，确保双端业务逻辑完全一致。
- 搭建 **electron-builder** 打包流水线，针对 macOS 平台编写 preinstall/postinstall 脚本，自动完成系统扩展注入、内核权限配置及代码公证（notarization），实现“一键打包、合规分发”。

**项目亮点：**
- 通过模块联邦技术，**避免双端重复开发**，功能迭代周期缩短 **30%**。


#### 🚀 项目二：Splashtop Secure Workspace（Web 端 – 管理控制台）

**项目描述：**
- 技术栈：React 18 + Redux + Webpack Module Federation + TypeScript + Ant Design
- 面向企业 IT 技术人员的零信任安全管理平台，提供应用创建、策略配置、用户权限管理、日志审计及特权账号（PAM）管理等核心功能。

**主要职责：**
- 负责管理控制台的**整体前端架构设计**，基于 React 18 构建模块化应用结构，通过 Redux 管理全局状态，封装 Axios 统一处理鉴权与错误拦截。
- 设计并实现**操作日志监控看板**，支持多维度筛选、实时刷新及日志导出，帮助 IT 人员快速审计员工行为。
- 通过 **Webpack Module Federation** 将核心业务模块（登录/注册、密码管理器）暴露给桌面端消费，保障双端一致性。

---

### 杭州博彦信息技术有限公司 | 前端开发工程师 (React)

*2021.03 - 2022.06*

#### 🚀 项目一：HR-Direct 人力资源管理系统

**项目描述：**
- 技术栈：React Hooks + Redux + react-virtualized + ECharts + Ant Design
- 服务于阿里集团外包及直管员工（万人级）的综合管理系统，涵盖招聘、考勤、薪酬配置等核心模块。

**主要职责：**
- **薪酬算薪功能重构**：面对复杂的薪资组成（基本工资、绩效、津贴、社保基数联动），利用 React Hooks + Redux 重构前端状态管理逻辑，解决了旧系统中数据流混乱导致的计算显示问题。
- **大数据量渲染优化**：针对数万名员工的薪资列表，引入 **react-virtualized** 实现虚拟滚动，解决长列表渲染导致的页面卡顿。
- **数据可视化**：使用 **ECharts** 开发薪资分析看板，支持多维度数据下钻与异常项高亮，帮助 HR 直观解读数据。


#### 🚀 项目二：开放集成平台 (API Orchestration Platform)

**项目描述：**
- 技术栈：React + Axios + React Router + Ant Design
- 企业级 API 网关与编排平台，支持 API 的配置、模型转换与编排。

**主要职责：**
- **前端架构设计**：采用 React 构建模块化前端结构，封装 Axios 统一处理 Header 鉴权与全局错误拦截，结合 React Router 实现完善的权限路由控制。
- **接口联调与协作**：配合后端完成 API 编排流程的联调，理解后端数据模型转换逻辑，高效设计前端数据结构。

---

### TCGaming | 前端开发 (Vue)

*2018.05 - 2020.09*

**项目描述：**
- 技术栈：Vue 2 + Vuex + Vue Router + Webpack + i18n
- 游戏 PC 客户端重构项目，涵盖登录注册、游戏配置、多语言国际化等核心模块。

**主要职责：**
- 基于 **Vue 2** 全家桶搭建项目架构，完成登录注册、多语言国际化（i18n）、游戏配置等核心模块的开发。
- 负责公共业务组件的封装与维护，统一平台 UI 交互规范，提升开发复用率。


