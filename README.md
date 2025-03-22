# Solana Web 项目 🌐

## 项目简介  
这是一个基于 **Solana 区块链** 的 Web 项目，旨在帮助开发者快速上手 Solana DApp 开发。  
本项目采用以下技术栈构建，并集成了 Solana 相关 SDK，通过提供一些简单的 Demo，帮助大家学习和实践 Solana 的开发。

---

## 技术栈  
- **Vite 6** - 现代化的前端构建工具，支持快速开发  
- **React 19** - 构建用户界面的主流框架  
- **Tailwind CSS 4** - 实用的 CSS 工具库，用于快速创建美观的 UI  
- **i18next 24** - 国际化解决方案，支持多语言切换  
- **Valtio** - 轻量级状态管理工具，简化全局状态管理  
- **ECharts** - 强大的数据可视化库  

---

## 功能特点  
- **Solana SDK 集成**：项目将逐步集成常用的 Solana SDK，包括但不限于：
  - 账户和钱包连接  
  - Token 转账和余额查询  
  - Solana program 调用等等

- **Demo 示例**：提供简单易懂的 Demo，涵盖 Solana 的常见开发场景，供开发者学习和参考。

---

## 项目结构  
```
solana-web/
├── public/                   # 静态资源文件夹
│   └── locales/              # 国际化json文件  
├── src/                      # 项目源代码目录  
│   ├── assets/               # 静态资源文件夹（如图片、SVG 等）  
│   ├── components/           # 复用型 React 组件目录  
│   ├── demo/                 # 示例和演示代码，用于展示具体功能  
│   ├── hooks/                # 自定义 React Hooks，处理逻辑复用  
│   ├── i18n/                 # 国际化配置（语言文件等）  
│   ├── idl/                  # Solana Program 的 IDL 文件（接口定义）  
│   ├── lib/                  # 公共库或第三方封装库  
│   ├── pages/                # 页面组件，负责页面级视图渲染  
│   ├── routes/               # 路由配置和路由相关逻辑  
│   ├── services/             # API 请求逻辑与业务逻辑的封装  
│   ├── store/                # 状态管理目录（使用 Valtio 等进行全局状态管理）  
│   ├── utils/                # 工具函数（如格式化工具、辅助函数等）  
│   ├── App.css               # 顶层应用样式文件  
│   ├── App.tsx               # 顶层 React 组件，应用入口文件  
│   ├── index.css             # 全局通用样式配置  
│   ├── main.tsx              # 应用主入口，挂载 React 应用  
│   └── vite-env.d.ts         # TypeScript 声明文件，指定 Vite 环境配置  
│  
├── .gitignore                # Git 忽略文件配置  
├── eslint.config.js          # ESLint 配置文件，用于代码风格检查  
├── index.html                # Vite HTML 入口文件  
├── package.json              # 项目配置文件及依赖管理  
├── package-lock.json         # npm 自动生成的锁定文件，确保依赖一致性  
├── README.md                 # 项目自述文件，包含项目介绍、运行指南等  
├── tsconfig.app.json         # TypeScript 编译配置（应用级别）  
├── tsconfig.json             # TypeScript 编译器的主配置文件  
├── tsconfig.node.json        # 针对 Node.js 环境的 TypeScript 配置  
└── vite.config.ts            # Vite 项目配置文件，定义插件、服务器等  
```

---

## 项目运行指南  
### **安装依赖**  
**使用 npm**  
```bash
npm install
```

**使用 yarn**  
```bash
yarn install
```

### **启动开发环境**  
**使用 npm**  
```bash
npm run dev
```

**使用 yarn**  
```bash
yarn dev
```

### **构建项目**  
**使用 npm**  
```bash
npm run build
```

**使用 yarn**  
```bash
yarn build
```

---

## 贡献指南  
欢迎对本项目提出建议或贡献代码！  
如果你想为本项目做出贡献，可以遵循以下步骤：
1. Fork 项目  
2. 创建你的功能分支 (`git checkout -b feature/my-feature`)  
3. 提交更改 (`git commit -m 'Add some feature'`)  
4. 推送到分支 (`git push origin feature/my-feature`)  
5. 提交 Pull Request  

---

## 开源协议  
本项目遵循 [Apache License 2.0](./LICENSE)，欢迎自由使用、修改和分发。

---

## 社交媒体  
关注我们的推特，获取最新项目动态和更新！  
- [Twitter](https://x.com/bigBorderCollie)

---

感谢你对 Solana 开发的关注和支持！🚀
