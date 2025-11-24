# Step Together - 公交站互动地砖游戏

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Framework](https://img.shields.io/badge/Framework-React%20Native%2FExpo-blue.svg)
![Status](https://img.shields.io/badge/Status-Prototype-orange.svg)

**一个旨在革新公共空间等待体验的团队协作式互动地砖游戏。通过光影与游戏化设计，将无聊的公交候车时间转化为一段有趣的社交互动体验。**

---

## 🎯 项目概述

“Step Together”是一个为UQ Lakes公交站设计的交互式地面游戏装置。项目通过 illuminated floor tiles (发光地砖) 吸引候车乘客参与团队游戏，旨在：

- **减轻候车焦虑与无聊感**
- **促进陌生人间的轻度社交互动**
- **通过智能提示有效降低错过公交的几率**
- **探索公共空间中的可持续互动设计**

本项目是 DECO7110 - Design Project 2025 的课程设计作品。

## ✨ 核心功能

- **🏁 团队积分游戏** - 无单人排行榜，所有玩家共同为一个目标分数努力，增强团队感。
- **🎮 直觉式交互** - 通过踩踏不同颜色的地砖进行交互：
  - **绿色 (+1分)**
  - **灰色 (-1分)**
  - **蓝色 (0分)**
  - **红色 (全员淘汰，关卡重置)**
- **🚌 巴士到站智能提示** - 游戏与公交系统联动，巴士进站时，所有地砖变红，游戏暂停，并同步在显示屏上更新巴士信息。
- **🌱 可持续设计** - 系统由太阳能电池板供电，并专门设有 **“安静区域”** ，尊重不愿参与的边缘用户。

## 🖼️ 项目展示
<img src="./media/微信图片_20251124203543.png" />
<img src="./media/微信图片_20251124203543.png" />

## 🛠️ 技术实现与原型

本项目采用快速原型开发策略，以验证核心游戏逻辑与用户体验。

- **开发环境**: [React Native](https://reactnative.dev/) + [Expo](https://expo.io/)
- **编程语言**: JavaScript
- **路由**: 基于 Expo 的 File-based Routing
- **核心实现**:
  - 游戏状态管理（积分、关卡、淘汰机制）
  - 地砖颜色切换与动画模拟
  - 巴士到站触发逻辑


## 📊 设计流程与迭代

我们遵循以用户为中心的设计流程：
1.  **实地调研** -> 发现候车过程中的核心痛点。
2.  **概念生成** -> 通过头脑风暴与“六顶思考帽”法筛选创意。
3.  **原型构建** -> 创建了从纸质原型到数字高保真原型的不同保真度版本。
4.  **用户测试** -> 进行了两轮共14名参与者测试，收集关于吸引力、安全性和规则清晰度的反馈。
5.  **迭代优化** -> 根据反馈调整了游戏难度、提示系统并加强了安全考虑。

---

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
