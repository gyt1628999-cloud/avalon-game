<div align="center">

![Avalon Banner](readme-assets/banner.png)

# 🏰 阿瓦隆 · Avalon

### 🤖 一个人的桌游 · 你 vs 大模型 AI 玩家

**这不是联机游戏，也不是双人对战——你是桌上唯一的人类，其他几位"骑士"都是接入 AI 的真演员。**
他们会装好人、装糊涂、互相 cue、合伙演戏。

[![React](https://img.shields.io/badge/React-18-61dafb?logo=react)](https://react.dev) [![Solo](https://img.shields.io/badge/玩法-单人_vs_AI-7c3aed)]() [![Free](https://img.shields.io/badge/智谱GLM--4--Flash-永久免费-88b070)](https://bigmodel.cn) [![Providers](https://img.shields.io/badge/AI厂商-7家-d8843c)]() [![Desktop](https://img.shields.io/badge/桌面版-Windows%20%2B%20Mac-blue?logo=electron)]() [![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

[🇨🇳 中文](#-中文文档) · [🇬🇧 English](#-english)

</div>

---

## 📜 来自亚瑟王传说的故事

> *剑栏血战之夜——长矛与利刃在血色月光下相会。*
>
> *亚瑟王的长矛刺穿了**莫德雷德**的盾牌，而那叛子卯足全力，双手握剑削去了王者半个头盔。世界本应于此沉寂。*
>
> *可**梅林**与**派西维尔**不愿放弃。他们扶起奄奄一息的王者，登上一叶小舟，驶向迷雾深处的圣岛——**阿瓦隆**。*
>
> *岛上由精灵守护，没有时间，没有岁月。只要圣杯之水能送到王者唇边，亚瑟便能起死回生。*
>
> ***但这艘船上，并非所有人都希望王者复活。***
>
> *莫甘娜——王者同母异父的姐姐，眉宇间藏着千年的恨。*
> *莫德雷德——王者的私生子，剑栏之上几乎砍下王者头颅的复仇者。*
> *奥伯伦——精灵王，受湖中女仙之命混入凡人血肉。*
>
> *他们与暗影骑士团混入了护卫队。要在小舟靠岸之前——**刺死那位知晓圣杯秘密的人——梅林**。*
>
> *—— 故事在这里展开。但这一次，桌上只有你一个真人。*

---

## 🇨🇳 中文文档

### 💡 这个游戏到底是什么

> **阿瓦隆**是一款 5-10 人的经典身份推理桌游。但凑齐这么多人不容易——所以这个项目让你**一个人也能玩**：
> 桌上 4-9 个 AI 玩家，每人有独立人格、独立策略、独立"心声"，会推理、会演戏、会互相质疑。
> 接入大模型 API 后，AI 的发言和真人几乎没区别。

### 🤖 桌上只有你一个人是真的

打开游戏后，你会**坐进一个 7 人或 5/6/8/9/10 人的桌子**——但其他人**全部是 AI**。

**这不是普通的"AI 当陪练"** ——这里的 AI 玩家**会真演戏**：

<table>
<tr>
<td width="50%">

#### 🎭 AI 角色扮演

- **AI 梅林会装糊涂**——绝不精准指认（怕被 AI 刺客盯上），用"我感觉""说不清"模糊词
- **AI 莫甘娜装梅林**——故意指好人陷害，让 AI 派西维尔分不清真假
- **AI 莫德雷德主动出击**——梅林看不见他，他大胆装好人推理
- **AI 奥伯伦发暗号**——孤独红方靠"勉强反对干净人"试探搭子
- **AI 刺客整局观察**——每轮记录谁像梅林（包括你），最后给你致命一刀

</td>
<td width="50%">

#### 🧠 AI 真在思考

- **AI 会算双队对比**——"3 号在第 1 轮 + B 失败，第 2 轮 + C 成功 → B 红 C 蓝"
- **AI 会记投票模式**——某号反对率高 = 梅林嫌疑大
- **AI 改主意会解释**——"我上轮反对，听了 5 号的觉得有道理才改"
- **AI 会避嫌**——红方 bom 完下一轮发言会克制
- **AI 会反思**——"全场都支持的车居然失败了……我们被骗了"
- **AI 有沉浸感**——偶尔会说"我以骑士之名担保""王者在上""火光摇曳间有些不对劲"

</td>
</tr>
</table>

### 🎲 新特性 · 一桌 6 个 AI 用 6 家不同模型同台辩论

> **每个 AI 玩家都可以单独选不同品牌+模型**——主打自由搭配。

<table>
<tr>
<td width="60%">

```
🤖 玩家 2  →  智谱 GLM-4-Flash  🆓
🤖 玩家 3  →  阿里 Qwen-Plus    🟢
🤖 玩家 4  →  DeepSeek V4-Pro   💸
🤖 玩家 5  →  Kimi K2.5         💸
🤖 玩家 6  →  豆包 Doubao Mini  🟢
🤖 玩家 7  →  📜 本地预设台词   🆓
```

听**风格各异的 AI** 跨家辩论——智谱直接简洁、Kimi 长篇推理、豆包接地气、阿里严谨、百川偏文学。

</td>
<td width="40%">

#### 三个一键模式
- 🔄 **全部用当前模型**——6 个 AI 都用同一家
- 🎲 **随机搭配**——从已开通厂商里随机分配
- ✗ **清空**——回到全局默认

#### 智能特性
- 复盘和建议**自动挑最快模型**
- 模式切换时智能提醒重新配置
- 续盘时还原本局的模型快照

</td>
</tr>
</table>

### 🎮 你和 AI 怎么互动

```
🧑 自己玩       → 你亲自发言、投票、做任务，AI 是你的对手
                  ← 推荐！最有沉浸感

💡 建议模式     → 轮到你时，AI 给你"思路+话术"建议，你自己决定
                  ← 适合新手 / 不想敲字

🤖 AI 代理      → AI 完全替你玩，你纯观战 7 个 AI 互相博弈
                  ← 看 AI 之间的对决，能看到所有 AI 的"心声"
```

### 🎯 AI 玩家发言长这样

> 这是一段**真实游戏录像**（节选 · 你是 1 号，其他全是 AI）：

```
1号(队长开场) [你]：信息少，先随便带几个看看。3、5、7号上车。
                   我自己也在车上担保。

3号 [AI]：嗯…我跟一把，但 7号上轮没动静我有点犹豫。

5号 [AI]：我先反对。不是不信 1号你，是 7号那波太安静了，
        不能就这么放过去。

7号 [AI]：哎，5号别盯我，我就是没想好。让我想想啊…
        1号你这队里其实 3号最稳，但 5号你反对的逻辑我没看懂。

(投票后任务失败——你和其他 AI 都看到这一轮失败)

3号 [AI]：卧槽这都失败了？我跟错车了！

5号 [AI]：我说什么来着，7号果然有问题。

(其实 5 号是莫德雷德 + 7 号是刺客 —— 但你还不知道)
```

### 🚀 一分钟开始

#### 🌐 方法 1：浏览器版（最简单）
```
下载 avalon.html → 双击在浏览器打开 → 立刻能玩
```

#### 🖥 方法 2：桌面版（Windows / Mac）
```
下载 release 里的 .exe / .dmg → 双击安装 → 双击图标玩
```
> 桌面版好处：不用浏览器、跨域稳、有自己的 Dock/任务栏图标。
> 编译说明见仓库里的 `electron-app/README.md`。

#### 🤖 方法 3：接入大模型 AI（强烈推荐）
```
1. 打开网页或桌面版
2. 点 ⚙ AI 设置
3. 选择 1-7 家大模型（推荐先填免费的智谱 GLM）
4. 复制 API Key 填入 → 点"测试 Key" → 绿色 ✓
5. （可选）展开「🎲 高级 · 每个 AI 玩家单独选模型」自由搭配
6. 开始游戏
```

### 💰 接入大模型多少钱

接入 AI 后游戏体验完全不同——AI 会真实推理、装好人、用情绪词。**强烈推荐至少试一次**。

| AI 服务商 | 价格档位 | 特点 | 推荐场景 |
|----|----|----|----|
| 🆓 **智谱 GLM** | **GLM-4-Flash 永久免费** + 实名送 500 万 Token | 清华团队·中文最强 | **首推！0 成本玩** |
| 🟠 **阿里通义** | 新用户每模型送千万级免费 token，90 天 | 国产顶级旗舰 Qwen3-Max | **个人开发者最友好** |
| 🆓 **百度千帆** | X1-Turbo 免费 + 实名送额度 | 国内访问最稳 | 备选免费 |
| 🐳 **DeepSeek** | ¥10 起，按量付费 | 推理质量国产顶尖 | 想要顶级体验 |
| 🌙 **Kimi** | ¥1 起，按量付费 | K2.5/K2.6 推理强 | 想要长篇文学发言 |
| 🔴 **字节豆包** | 价格便宜 10 倍 | Doubao Lite/Mini 极便宜 | 想要海量便宜对局 |
| 🟣 **百川** | 实名送 80 元代金券 | Baichuan4 中文写作好 | 想要文学性发言 |

**🎯 价格档位标识**（每个模型名后会标）：
- 🆓 永久免费 / 有免费额度
- 🟢 便宜（每局几分钱）
- 💸 稍贵（每局几毛钱）
- 💎 贵（每局 ¥1+）

> 💡 **0 成本玩法**：智谱 GLM-4-Flash 永久免费 + 阿里 Qwen-Turbo/Flash 免费额度 + 百度 X1-Turbo 免费——三家全填，**完全不用充值**就能体验跨家 AI 辩论。

### 🃏 你和 AI 玩家会扮演哪些角色

![Roles](readme-assets/roles.png)

每局游戏里，你和 AI 会**随机分到角色**——你可能是梅林、刺客、奥伯伦……AI 们会拿到剩下的角色。

#### 🔵 蓝方 · 亚瑟王的忠臣

<table>
<tr>
<td width="33%" valign="top">

**🪄 梅林**

*传说中的伟大魔法师，亚瑟王的挚友与导师。*

知晓所有红方（除莫德雷德）。但若被 AI 刺客认出，王者将永远沉睡。

</td>
<td width="33%" valign="top">

**🛡 派西维尔**

*亚瑟王最信任的圆桌骑士。*

视野中有 2 个候选梅林（一真一假），需用观察辨认。

</td>
<td width="33%" valign="top">

**⚔️ 忠臣**

*亚瑟王的圆桌骑士。*

无视野，靠观察任务结果、AI 投票、AI 发言找出叛徒。

</td>
</tr>
</table>

#### 🔴 红方 · 暗影中的背叛者

<table>
<tr>
<td width="33%" valign="top">

**🗡 刺客**

*莫德雷德派系最锋利的剑。*

蓝方完成 3 次任务时拔剑指认梅林——刺中则红方反败为胜。

</td>
<td width="33%" valign="top">

**🌒 莫甘娜**

*亚瑟王同母异父的姐姐。*

伪装成梅林，让派西维尔陷入混乱。

</td>
<td width="33%" valign="top">

**👑 莫德雷德**

*亚瑟王与莫甘娜之子。*

最大优势：梅林看不见他。可以堂堂正正坐在桌前装最忠诚的骑士。

</td>
</tr>
<tr>
<td width="33%" valign="top">

**🌫 奥伯伦**

*精灵王。*

不认识任何同伴，同伴也认不出他。一场孤独的破坏。

</td>
<td width="33%" valign="top">

**🐍 莫德雷德的爪牙**

*暗影骑士团成员。*

认识所有红方同伴（除奥伯伦），装作忠诚搞破坏。

</td>
<td width="33%" valign="top">

</td>
</tr>
</table>

### 🎲 一轮怎么玩

![Flow](readme-assets/flow.png)

```
1. 队长选 N 人组队（队长可能是你、也可能是 AI）
   ↓
2. 队长选发言方向（左手起 / 右手起）
   ↓
3. 队长开场——解释为什么这么组队
   ↓
4. 玩家依序发言（你和 AI 轮流说）
   ↓
5. 队长总结——决定维持原队 or 重新组队
   ↓
6. 全员投票（你和 AI 同时投）
   ↓
7. 任务执行——队员暗投成功/失败
   ↓
↻ 循环 5 轮
   蓝方 3 胜 → 进入刺杀环节
   红方 3 胜 / 5 次连续流局 → 红方直接胜利
```

#### 🗡 刺杀环节（蓝方达成 3 胜时触发）

```
1. 揭晓所有红方身份（你和 AI 都看到）
2. AI 红方公开讨论梅林是谁（你也参与，如果你是红方）
3. AI 刺客（或者你，如果你是刺客）做最终决定
   ↓
   ✓ 刺中梅林 → 红方反败为胜
   ✗ 刺错 → 蓝方真正胜利
```

### 💡 新手避坑指南

<table>
<tr><th>角色</th><th>常见死法</th><th>怎么避免</th></tr>
<tr>
<td>🔵 梅林</td>
<td>第 1 轮就精准指认红方 → AI 刺客锁定你</td>
<td>第 1 轮装得和普通好人一样模糊</td>
</tr>
<tr>
<td>🔵 派西</td>
<td>公开说"X 号是真梅林" → AI 刺客谢谢你</td>
<td>永远保持"两个我都不太确定"</td>
</tr>
<tr>
<td>🔴 莫甘娜</td>
<td>第 1 轮就装梅林 → 直接暴露</td>
<td>第 1 轮也老实当好人，第 2 轮以后才发力</td>
</tr>
<tr>
<td>🔴 红方搭子</td>
<td>每次都互相支持 → 全场识破</td>
<td>偶尔反对自己搭子（用好人逻辑）</td>
</tr>
<tr>
<td>🔴 奥伯伦</td>
<td>2 人车 1 失败时不知道指认谁</td>
<td>和好人一样硬指对方（"我投的成功"）</td>
</tr>
</table>

### 🛠 技术栈

- **前端**：单文件 React 18 + Tailwind CSS（无构建步骤！）
- **AI 接入**：7 家 OpenAI 兼容 API（智谱 / 阿里通义 / DeepSeek / Kimi / 千帆 / 豆包 / 百川）
- **存储**：浏览器 localStorage（API Key 不上传服务器）
- **部署**：纯静态 HTML，可部署到任何静态服务器
- **桌面打包**：Electron 32 + electron-builder（Windows + Mac）

### 📂 项目结构

```
avalon/
├── avalon.html                 ← 整个游戏（一个文件，约 8500 行 React）
├── index.html                  ← 同上的副本（GitHub Pages 入口）
├── README.md                   ← 项目介绍
├── readme-assets/
│   ├── banner.png              ← 顶部横幅
│   ├── roles.png               ← 角色介绍图
│   └── flow.png                ← 流程图
├── 阿瓦隆-1分钟入门.pdf          ← 速查手册（A4 单页）
└── electron-app/               ← 桌面 app 项目（可选）
    ├── package.json
    ├── main.js                 ← Electron 主进程
    ├── preload.js
    ├── avalon.html             ← 编译后的 standalone 单文件
    ├── README.md               ← 桌面版打包说明
    └── build/
        ├── icon.svg            ← 矢量原图
        ├── icon.ico/.icns/.png ← 各平台图标
        └── regenerate_icons.py ← 一键重生成所有分辨率
```

### 🚀 部署到 GitHub Pages（浏览器版）

```bash
# 1. fork / 创建一个新 repo
# 2. 把 avalon.html、index.html、README.md、readme-assets/ 都丢进去
# 3. Settings → Pages → Source 选 main 分支 / root → Save
# 4. 等 1-2 分钟，访问 https://你的用户名.github.io/repo名/
```

### 🖥 自己打包桌面版（Windows / Mac）

详细教程见 [`electron-app/README.md`](electron-app/README.md)。简版：

```bash
cd electron-app
npm install                # 第一次会下 Electron ~250 MB
npm start                  # 先跑一下试试
npm run dist:win           # 打 Windows .exe（要在 Windows 上跑）
npm run dist:mac           # 打 Mac .dmg（要在 Mac 上跑）
```

打包产物在 `electron-app/dist/`：
- `AI阿瓦隆-Windows-1.0.0-x64.exe`（NSIS 安装版）
- `AI阿瓦隆-便携版-1.0.0.exe`（绿色版，单文件）
- `AI阿瓦隆-Mac-1.0.0-x64.dmg` / `arm64.dmg`

**⚠️ 国内打包注意**：
- 第 1 步先设镜像：`npm config set registry https://registry.npmmirror.com`
- 设环境变量：`$env:ELECTRON_MIRROR="https://npmmirror.com/mirrors/electron/"`（PowerShell）
- Windows 打 exe 报符号链接错？**开 Windows 开发者模式**（设置→开发人员设置→打开开关），一次性永久解决

### 🤔 常见问题

<details>
<summary><b>这是网络对战游戏吗？能跟朋友联机吗？</b></summary>

**不是网络对战**——这是**纯单人**游戏。桌上其他玩家全部是 AI（接入大模型驱动）。
你不需要找队友，不需要等人，打开就能玩。AI 玩家有独立人格、独立策略，发言推理像真人。

</details>

<details>
<summary><b>API Key 测试失败显示 "Failed to fetch" 怎么办？</b></summary>

通常是网络问题：
- 切换到**智谱 GLM** 或**百度千帆**（国内最稳）
- 关闭浏览器扩展（广告拦截器、隐私插件可能拦截请求）
- 切换网络（手机热点 / 不同网络）

</details>

<details>
<summary><b>不接入 AI 也能玩吗？</b></summary>

可以！游戏内置本地预设台词，不接入 AI 也能跑完整流程。但 AI 玩家的发言会**比较模板化**，没有真实推理。
**强烈推荐至少试一次接入 AI 的体验，差别巨大**。智谱 GLM-4-Flash **永久免费**，0 成本就能体验。

</details>

<details>
<summary><b>API Key 安全吗？</b></summary>

完全安全：
- Key 只保存在**你自己浏览器**的 localStorage 里
- 没有任何后端服务器收集
- 没有埋点、没有 analytics

</details>

<details>
<summary><b>能跨设备玩吗？比如手机和电脑同步？</b></summary>

不能。游戏存档存在浏览器 localStorage 里，换设备就要重开。如果想保留某局战绩，可以截图保存。

</details>

<details>
<summary><b>为什么发了句脏话游戏就直接结束了？</b></summary>

游戏里设置了**文明发言机制**——检测到攻击性词汇会立刻终止本局并删除战绩。
这个游戏想营造的是**圆桌骑士的氛围**——彼此可以质疑、可以背叛、可以互相试探，但不应有侮辱和攻击。
请保持骑士般的风度。

</details>

<details>
<summary><b>怎么修改游戏规则 / AI 策略？</b></summary>

整个游戏在 `avalon.html` 一个文件里（约 8500 行）。所有 AI prompt 都在文件里搜：
- `qianfan` / `kimi` / `zhipu` / `qwen` / `doubao` / `baichuan` —— 各家专属 prompt 强化
- `aiSpeakViaAPI` —— AI 玩家发言主流程
- `aiAssassinate` —— 刺客刺梅林
- `aiRecapViaAPI` —— 复盘生成

直接改保存即可，不用编译。

</details>

<details>
<summary><b>桌面版和浏览器版有什么区别？</b></summary>

**功能完全一样**——同一份 `avalon.html`。区别在：

- 🌐 **浏览器版**：双击 .html 文件即开。Key 和存档存在浏览器 localStorage。
- 🖥 **桌面版**：独立 .exe / .app，有自己的 Dock/任务栏图标。Key 和存档存在系统目录（Win: `%APPDATA%\AI 阿瓦隆\`；Mac: `~/Library/Application Support/AI 阿瓦隆/`）。**清浏览器缓存不会丢数据**。
- ⚡ **跨域**：桌面版禁用了 webSecurity，**跨域请求更稳**。

强烈推荐桌面版作为长期使用，浏览器版作为快速试玩。

</details>

<details>
<summary><b>"一桌 6 个 AI 用 6 家不同模型" 怎么开？</b></summary>

1. 进 ⚙ AI 设置
2. 至少填 2 家以上的 API Key（比如智谱 + 阿里 + 豆包）
3. 在「🎲 高级 · 每个 AI 玩家单独选模型」按钮（位置在 AI 学习进度和提供商之间）点开弹窗
4. 给每个 AI 玩家选不同的厂商+模型——也可以选「📜 本地预设台词」让某个 AI 不接大模型
5. 点完成 → 开始游戏

游戏中顶栏会显示「多家 AI 协同（N 家）」，AI 失败时会精确显示哪个座位、哪个厂商、哪个模型挂了。

</details>

<details>
<summary><b>哪几家是免费的？怎么 0 成本玩？</b></summary>

**永久免费**：智谱 GLM-4-Flash

**有大量免费额度**（实名认证后送）：
- 阿里通义：每个模型送千万级 token，90 天
- 百度千帆：X1-Turbo-32K 等

**完全 0 成本玩法**：把上面三家 Key 都填了，进「🎲 高级 · 每个 AI 玩家单独选模型」，给 6 个 AI 配上面三家的免费模型——一桌 AI 跨家辩论，**钱包毫发无伤**。

</details>

### 📝 反馈 / 贡献

发现 bug 或想加功能？欢迎：
- 提 [Issue](../../issues) 报 bug 或建议
- 提 [Pull Request](../../pulls) 直接贡献代码

### 📜 License

MIT — 自由使用、修改、分发

### ❤️ 致谢

灵感来自 Don Eskridge 的经典桌游 [The Resistance: Avalon](https://en.wikipedia.org/wiki/The_Resistance_(game))。

故事内容引自亚瑟王传说与凯尔特神话。

---

## 🇬🇧 English

### 📜 The Tale

> *On the night of the Battle of Camlann—Arthur's spear pierced Mordred's shield. The traitor, with his last strength, raised his sword and cleaved off half the King's helmet. The world should have ended there.*
>
> *But **Merlin** and **Percival** would not let it. They lifted the dying King onto a small boat and rowed into the mist toward the holy isle—**Avalon**.*
>
> *On this island guarded by faeries, time does not pass. The Holy Grail's water can revive the King.*
>
> ***But not everyone on this boat wishes the King to live.***
>
> *Morgana—the King's half-sister, harboring centuries of hatred.*
> *Mordred—the King's bastard son, who once nearly took his head at Camlann.*
> *Oberon—the Faerie King, sent by the Lady of the Lake.*
>
> *They mingle among the loyal knights. Their goal: kill the only one who knows the Grail's secret—**Merlin**—before the boat reaches shore.*
>
> *—— Here the story begins. But this time, you are the only human at the table.*

### 🤖 You vs AI Players — Solo Avalon

> **Avalon** is a classic 5-10 player social deduction board game. But getting that many people together is hard.
> This project lets you **play alone**: 4-9 AI players at the table, each with unique personality, strategy, and "inner voice".
> They reason, they bluff, they accuse each other. With LLM API connected, AI speech is nearly indistinguishable from real humans.

### 🎬 What's special

Not your usual "AI chatbot" — these AI players **actually act**:

#### 🎭 Role-playing on point
- **AI Merlin plays dumb** — never points fingers precisely (assassin AI is watching), uses vague words
- **AI Morgana fakes Merlin** — deliberately accuses good guys to confuse Percival
- **AI Mordred goes offensive** — Merlin can't see him, so he boldly "deduces" as a good knight
- **AI Oberon sends signals** — lone evil player tries to find partners via subtle speech
- **AI Assassin keeps notebook** — quietly tracks who looks like Merlin every round (including you)

#### 🧠 AI actually thinks
- **Cross-team comparison** — "Player 3 was in failed Round 1 with B, success Round 2 with C → B is evil, C is good"
- **Vote pattern tracking** — high opposition rate = Merlin suspect
- **Mind-change explanations** — "I opposed last round, but #5's argument convinced me"
- **Post-failure reactions** — "Wow that failed", "Knew it was suspicious"
- **Immersion lines** — "I swear on my honor as a knight", "Something feels off in the firelight"

### 🎮 Three play modes

```
🧑 Self play     → You speak, vote, mission personally; AI players are opponents
                   ← Recommended! Most immersive

💡 Advice mode   → AI gives you "thinking + speech" suggestions when it's your turn
                   ← Beginner-friendly

🤖 AI agent      → AI plays for you; you watch 7 AIs battle each other
                   ← See AI vs AI, all "inner voices" visible
```

### 🚀 Quick start

```bash
# Method 1: Browser version (simplest)
Download avalon.html → Double-click → Play

# Method 2: Desktop version (Windows / Mac)
Download .exe / .dmg from Releases → Install → Launch

# Method 3: With AI (recommended, much better experience)
Open page → ⚙ AI Settings → Pick provider → Enter API Key → Test
```

**7 AI providers** (mix and match per-seat):

| Provider | Pricing | Notes |
|----|----|----|
| 🆓 **Zhipu GLM** | **GLM-4-Flash forever free** + 5M tokens after ID verification | Tsinghua team, best Chinese; **TOP PICK** |
| 🟠 **Aliyun Qwen** | Generous free tokens per model (90 days) | Most developer-friendly |
| 🆓 **Baidu Qianfan** | X1-Turbo free + bonus quota | Most stable in China |
| 🐳 **DeepSeek** | Pay-as-you-go, ¥10 minimum | Strongest reasoning |
| 🌙 **Kimi** | Pay-as-you-go, ¥1 minimum | Best literary expression (K2.5/K2.6) |
| 🔴 **Doubao (ByteDance)** | 10× cheaper than competitors | Lite/Mini for cheap mass play |
| 🟣 **Baichuan** | ¥80 voucher for verified users | Strong Chinese writing |

**🎲 New Feature**: Mix providers — assign different model to each AI seat for cross-vendor debates.

### 🖥 Desktop version

We package the game as Electron app for Windows/Mac. See `electron-app/README.md` for detailed build instructions.

```bash
cd electron-app
npm install
npm run dist:win    # or dist:mac
```

### 🃏 Roles

#### Blue (Good) — Win by 3 successful missions
| Role | Vision | Goal | How to play |
|----|----|----|----|
| 🔵 Merlin | All evil (except Mordred) | Help Blue win without being identified | Play dumb! Use vague words |
| 🔵 Percival | 2 Merlin candidates | Protect real Merlin | Watch candidates; can fake Merlin |
| 🔵 Loyal Servant | None | Find evil players | Track mission results |

#### Red (Evil) — Win by 3 failed missions / Stab Merlin
| Role | Vision | Goal | How to play |
|----|----|----|----|
| 🔴 Assassin | All evil + assassinate at Blue's 3rd win | Fail missions / Stab Merlin | Pretend good, watch for Merlin |
| 🔴 Morgana | All evil | Make Percival think you're real Merlin | Fake vision, mis-accuse |
| 🔴 Mordred | All evil (Merlin can't see) | Use invisibility | Boldly "deduce" |
| 🔴 Oberon | None | Pretend good + find partners | Send subtle signals |
| 🔴 Minion | All evil | Coordinate with partners | Use good-guy logic |

### 🎲 One round

```
1. Leader picks N players (could be you or AI)
2. Leader chooses speaking direction
3. Leader's opening speech
4. Players speak in order (you and AIs take turns)
5. Leader's summary (keep team or revise)
6. Vote (you and AIs vote together)
7. Mission (secret success/fail)
```

**Win conditions**:
- 🔵 Blue: 3 successes → BUT Assassin can name Merlin → if hits, Red wins
- 🔴 Red: 3 fails / Hits Merlin / 5 consecutive rejections

### 🛠 Tech stack

- **Frontend**: Single-file React 18 + Tailwind CSS (no build step!)
- **AI**: 7 OpenAI-compatible providers (Zhipu / Qwen / DeepSeek / Kimi / Qianfan / Doubao / Baichuan)
- **Storage**: Browser localStorage (no server upload, all keys local)
- **Web deploy**: Pure static HTML, deploy anywhere
- **Desktop**: Electron 32 + electron-builder, Windows + Mac packaging

### 🚀 Deploy to GitHub Pages

```bash
# 1. Fork / create new repo
# 2. Drop avalon.html, index.html, README.md, readme-assets/ into it
# 3. Settings → Pages → Source: main / root → Save
# 4. Wait 1-2 min, visit https://yourname.github.io/reponame/
```

### 📝 Contributing

PRs welcome! Improve AI strategies, add UI, fix bugs.

The codebase is mostly:
- `avalon.html` — entire game (one file, ~7000 lines, React + inline CSS)

To develop:
```bash
# Just open avalon.html in browser - no build needed!
```

### 📜 License

MIT

### ❤️ Credits

Inspired by Don Eskridge's classic [The Resistance: Avalon](https://en.wikipedia.org/wiki/The_Resistance_(game)) board game.

Story content draws from Arthurian legend and Celtic mythology.

---

<div align="center">

**🏰 May the realm of Logres be yours, brave knight. 🏰**

*愿罗格里斯王国永属于你，勇敢的骑士。*

**🤖 Solo · You vs AI · No Multiplayer**

</div>
