# 数学进阶路线 · 密码学 / 金融科技博士申请

> 24 周 · 每天 1 小时 · 从易到难五级阶梯
> 目标：用可验证的课程证书 + 习题集 + 代码作品集，代替"再读一个数学硕士"

## 为什么是这个仓库

博士申请中导师看的是**数学成熟度**，不是学位数量。这个仓库就是证据链：

1. **认证证书**（Coursera / 中国大学MOOC，可扫码验证）
2. **习题集**（MIT OCW problem sets 全部手写解答，拍照或 LaTeX 存档）
3. **代码**（用 Python 实现的密码学算法：RSA、扩展欧几里得、模逆、有限域运算）

完成后的 README 会成为申请材料里"数学能力作品集"的入口。

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
| Mathematical Thinking in Computer Science | Coursera (UC San Diego) | https://www.coursera.org/learn/mathematical-thinking-computer-science |
| 离散数学概论（中文对照） | 中国大学MOOC (北京大学·陈斌) | https://www.icourse163.org/course/PKU-1002525004 |

- 每周 1 个 Coursera 模块，看不懂的单元用北大中文课对应章节回看
- 北大课重点跟：数理逻辑（单元 2–4）、集合论（单元 5–7）
- ✅ 产出：Coursera 课程完成记录 + `01-math-thinking/notes/`

## Level 2 · 离散数学核心（第 5–10 周）

| 课程 | 平台 | 链接 |
|---|---|---|
| Combinatorics and Probability | Coursera (UC San Diego) | https://www.coursera.org/learn/combinatorics |
| Introduction to Graph Theory | Coursera (UC San Diego) | https://www.coursera.org/learn/graphs |

- 第 5–7 周组合数学与概率，第 8–10 周图论
- 顺手用 Python 实现：排列组合计数器、随机图生成
- ✅ 产出：认证证书（付费申请）+ `02-discrete-core/code/`

## Level 3 · 密码学数学基础（第 11–16 周）★ 核心

| 课程 | 平台 | 链接 |
|---|---|---|
| 信息安全数学基础（**中文主线**） | 中国大学MOOC (上海交大·陈恭亮) | https://www.icourse163.org/course/SJTU-1003379015 |
| 同课程镜像 | 国家智慧教育平台 | https://higher.smartedu.cn/course/6a59477940d86e7f37c2fc1b |
| Number Theory and Cryptography | Coursera (UC San Diego) | https://www.coursera.org/learn/number-theory-cryptography |
| Mathematical Foundations for Cryptography | Coursera (Colorado Boulder) | https://www.coursera.org/learn/mathematical-foundations-cryptography |

- 上交这门是密码学最对口的数学课（数论、代数、椭圆曲线），12 周制，**跟最新开课期走**（每学期滚动开班）
- 每章作业在中国大学MOOC提交，认真做——成绩单可验证
- 第 11–13 周 Coursera 数论课、第 14–16 周密码学数学基础课，与中文主线互为对照
- ✅ 产出：MOOC 认证证书 + `03-crypto-math/code/`（大素数生成、模逆、模重复平方法、二次剩余、椭圆曲线点运算的 Python 实现）

## Level 4 · 抽象代数与数论进阶（第 17–24 周）

| 课程 | 平台 | 链接 |
|---|---|---|
| 18.703 Modern Algebra | MIT OpenCourseWare | https://ocw.mit.edu/courses/18-703-modern-algebra-spring-2013/ |
| 18.781 Theory of Numbers | MIT OpenCourseWare | https://ocw.mit.edu/courses/18-781-theory-of-numbers-spring-2022/ |

- 第 17–21 周抽象代数（群、环、域），第 22–24 周数论（素数、二次互反律、丢番图方程）
- OCW 没有证书——**做完全部 Problem Sets 并上传解题过程**，这才是含金量所在
- ✅ 产出：`04-abstract-algebra/problem-sets/`（全部习题解答）

## Level 5 · 金融科技方向（可选，并行或延后）

| 课程 | 平台 | 链接 |
|---|---|---|
| MITx MicroMasters in Finance（微硕士） | edX | https://www.edx.org/micromasters/mitx-finance |
| Cryptography I（斯坦福，锦上添花） | Coursera | https://www.coursera.org/learn/crypto |

- MicroMasters 五门研究生水平课，部分合作大学可转硕士学分——对金融科技博士申请是强证明
- ✅ 产出：微硕士证书 + `05-fintech-optional/`

---

## 每周节奏（每天 1 小时）

| 周一–周五 | 周六 | 周日 |
|---|---|---|
| 视频课 + 随堂练习（45 min 视频 / 15 min 笔记） | 整理本周笔记为 Markdown，推送到 GitHub | 休息 / 补进度 / 复习错题 |

## 进度追踪

- [ ] L1 · Mathematical Thinking in Computer Science（W1–4）
- [ ] L1 · 北大离散数学概论 中文对照（W1–4）
- [ ] L2 · Combinatorics and Probability（W5–7）
- [ ] L2 · Introduction to Graph Theory（W8–10）
- [ ] L3 · 上交 信息安全数学基础（W11–16 中文主线）
- [ ] L3 · Number Theory and Cryptography（W11–13）
- [ ] L3 · Mathematical Foundations for Cryptography（W14–16）
- [ ] L4 · MIT 18.703 Modern Algebra + 全部习题（W17–21）
- [ ] L4 · MIT 18.781 Theory of Numbers + 全部习题（W22–24）
- [ ] L5 · MITx MicroMasters in Finance（可选）

## 仓库结构

```
math-roadmap/
├── README.md              ← 本文件
├── index.html             ← 可视化路线图（离线打开）
├── 01-math-thinking/
│   ├── notes/             # Markdown 笔记
│   └── certificates/     # 课程证书 PDF
├── 02-discrete-core/
│   ├── notes/
│   ├── code/              # 计数、概率、图论 Python 实现
│   └── certificates/
├── 03-crypto-math/
│   ├── notes/
│   ├── code/              # RSA / 模逆 / 椭圆曲线 实现
│   └── certificates/
├── 04-abstract-algebra/
│   ├── notes/
│   └── problem-sets/      # MIT OCW 习题手写解答（拍照/LaTeX）
└── 05-fintech-optional/
    └── certificates/
```

## 使用说明

1. `git init` 后把本文件夹推到 GitHub，仓库名建议 `math-for-crypto-portfolio`
2. 每完成一门课：勾选上方 checkbox，证书放进对应 `certificates/`，笔记和代码提交
3. 申请博士时，在个人陈述中附上本仓库链接，并主动说明"用 X 门可验证课程 + 全部 MIT 习题集代替第二个数学硕士"
