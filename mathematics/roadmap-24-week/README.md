# 数学进阶路线 · 密码学 / 金融科技博士申请

> 24 周 · 每天 1 小时 · 从易到难五级阶梯 · **全部课程来自 MIT OpenCourseWare（免费）**
> 目标：用习题集 + 代码作品集 + 每课笔记，代替"再读一个数学硕士"
> 本路线是 [`../`](..) 完整课程体系（31 门 / 4,010h）的**快速启动通道**：先用 24 周建立习惯与直觉，再无缝切入主线。

## 为什么是这个仓库

博士申请中导师看的是**数学成熟度**，不是学位数量。这个仓库就是证据链：

1. **完整课程记录**（MIT OCW 课程页 + 自己的笔记与习题解答，全程免费、无证书依赖）
2. **习题集**（MIT OCW problem sets 全部手写解答，拍照或 LaTeX 存档）
3. **代码**（用 Python 实现的密码学算法：RSA、扩展欧几里得、模逆、有限域运算）

MIT OCW 不发证书——**做完全部 Problem Sets 并上传解题过程**，这才是导师认的含金量。

---

## 阶梯总览

```
L1 ──► L2 ──► L3 ──► L4 ──► L5(可选)
数学    离散     密码学    抽象     金融科技
思维    数学     数学基础  代数进阶  数学
W1-4   W5-10   W11-16   W17-24   并行/延后
```

可视化路线图见 [`index.html`](./index.html)（本地双击打开即可，无需联网）。

---

## Level 1 · 数学思维入门（第 1–4 周）

| 课程 | 平台 | 链接 |
|---|---|---|
| 6.1200J Mathematics for Computer Science（前段：逻辑、证明、归纳、不变量、状态机） | MIT OpenCourseWare | https://ocw.mit.edu/courses/6-1200j-mathematics-for-computer-science-spring-2024/ |

- 免费教材《Mathematics for Computer Science》（Lehman / Leighton / Meyer）在课程页可直接下载 PDF
- 每周跟 2–3 讲 lecture + 对应 problem set 精选习题（不用全做，24 周版是第一遍快速过）
- ✅ 产出：`01-math-thinking/notes/`（4 篇）+ 勾选记录

## Level 2 · 离散数学核心（第 5–10 周）

| 课程 | 平台 | 链接 |
|---|---|---|
| 6.1200J Mathematics for Computer Science（后段：数论入门、图论、计数、离散概率） | MIT OpenCourseWare | https://ocw.mit.edu/courses/6-1200j-mathematics-for-computer-science-spring-2024/ |

- 与 L1 同一门课，W5–10 推进后半部分——MIT 这门课正好覆盖"组合 + 图 + 概率"三块
- 顺手用 Python 实现：排列组合计数器、随机图生成
- ✅ 产出：`02-discrete-core/code/` + 6 篇笔记

## Level 3 · 密码学数学基础（第 11–16 周）★ 核心

| 课程 | 平台 | 链接 |
|---|---|---|
| 18.781 Theory of Numbers | MIT OpenCourseWare | https://ocw.mit.edu/courses/18-781-theory-of-numbers-spring-2012/ |

- 数论是密码学的地基：素数、模算术、二次互反律、丢番图方程
- 每周做 course page 上的 problem set 并上传解答过程
- 卡壳时可回看 6.1200J 数论单元（L2 已覆盖基础）
- ✅ 产出：`03-crypto-math/code/`（大素数生成、模逆、模重复平方法、二次剩余、椭圆曲线点运算的 Python 实现）+ 习题解答

## Level 4 · 抽象代数与数论进阶（第 17–24 周）

| 课程 | 平台 | 链接 |
|---|---|---|
| 18.703 Modern Algebra | MIT OpenCourseWare | https://ocw.mit.edu/courses/18-703-modern-algebra-spring-2013/ |
| 18.701 Algebra I (Artin) | MIT OpenCourseWare | https://ocw.mit.edu/courses/18-701-algebra-i-fall-2010/ |

- 第 17–21 周抽象代数（群、环、域，18.703 为入门），第 22–24 周切入 18.701（Artin 亲授，难度陡增，24 周内只求起步，完整推进交给主线 S3 阶段）
- OCW 没有证书——**做完全部 Problem Sets 并上传解题过程**，这才是含金量所在
- ✅ 产出：`04-abstract-algebra/problem-sets/`（习题解答）

## Level 5 · 金融科技方向（可选，并行或延后）

| 课程 | 平台 | 链接 |
|---|---|---|
| 15.401 Finance Theory I (Andrew Lo) | MIT OpenCourseWare | https://ocw.mit.edu/courses/15-401-finance-theory-i-fall-2008/ |
| 18.642 Topics in Mathematics with Applications in Finance | MIT OpenCourseWare | https://ocw.mit.edu/courses/18-642-topics-in-mathematics-with-applications-in-finance-fall-2024/ |

- 15.401 建立金融理论直觉（估值、组合、衍生品），18.642 是量化数学工具箱（线性代数/概率/统计在金融中的直接应用）
- ✅ 产出：`05-fintech-optional/notes/` + 每课复现一个模型

---

## 每周节奏（每天 1 小时）

| 周一–周五 | 周六 | 周日 |
|---|---|---|
| 视频课 + 随堂练习（45 min 视频 / 15 min 笔记） | 整理本周笔记为 Markdown，推送到 GitHub | 休息 / 补进度 / 复习错题 |

## 进度追踪

- [ ] L1 · MIT 6.1200J 前段：逻辑与证明（W1–4）
- [ ] L2 · MIT 6.1200J 后段：图论 + 计数 + 离散概率（W5–10）
- [ ] L3 · MIT 18.781 Theory of Numbers + 习题（W11–16）
- [ ] L4 · MIT 18.703 Modern Algebra + 习题（W17–21）
- [ ] L4 · MIT 18.701 Algebra I 起步（W22–24，衔接主线 S3）
- [ ] L5 · MIT 15.401 + 18.642（可选）

## 仓库结构

```
mathematics/roadmap-24-week/
├── README.md              ← 本文件
├── index.html             ← 可视化路线图（离线打开）
├── 01-math-thinking/
│   ├── notes/             # Markdown 笔记
│   └── problem-sets/      # 习题解答（拍照/LaTeX）
├── 02-discrete-core/
│   ├── notes/
│   └── code/              # 计数、概率、图论 Python 实现
├── 03-crypto-math/
│   ├── notes/
│   ├── code/              # RSA / 模逆 / 椭圆曲线 实现
│   └── problem-sets/
├── 04-abstract-algebra/
│   ├── notes/
│   └── problem-sets/      # MIT OCW 习题手写解答（拍照/LaTeX）
└── 05-fintech-optional/
    └── notes/
```

## 使用说明

1. 本文件夹属于 `Learning-Notes` 仓库的 `mathematics/` 目录，直接随仓库推送
2. 每完成一门课：勾选上方 checkbox，笔记、习题解答和代码提交进对应文件夹
3. 24 周结束后，直接切入 [完整课程主线](../README.md)（31 门 / 4,010h，S0 入门层起步）
4. 申请博士时，在个人陈述中附上仓库链接，并主动说明"用 31 门 MIT OCW 完整课程 + 全部习题集代替第二个数学硕士"
