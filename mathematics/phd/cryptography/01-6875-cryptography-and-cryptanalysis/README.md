# 6.875 · Cryptography and Cryptanalysis (Silvio Micali)

> **课程主页**：[Spring 2005 · Graduate](https://ocw.mit.edu/courses/6-875-cryptography-and-cryptanalysis-spring-2005/)
> **预估投入**：约 120 小时
> **先修**：6.1200J / 18.781（数论与离散概率）

## 课程定位（为什么学它）

MIT 研究生级密码学导论（图灵奖得主 Micali 主讲）：公钥加密、数字签名、伪随机数生成、
双方协议与零知识证明，**重点在证明技术**——这正是密码学博士资格考的核心。
配套免费教材：Boneh & Shoup《A Graduate Course in Applied Cryptography》
（[在线版](https://toc.cryptobook.us/) · [PDF v0.6](https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup_0_6.pdf)）。

## 输出物清单（导师验收标准）

- [ ] `notes/` — 每讲一份笔记（Markdown 或 LaTeX），文件名 `lec-NN-主题.md`
- [ ] `problem-sets/` — 全部习题独立完成，附完整解答（不可只写答案）
- [ ] `code/` — 编程实现（如用 Python 实现 OAEP / 零知识协议演示）
- [ ] `reflections.md` — 课程心得：最难的三个概念 + 如何攻克 + 与研究方向的联系
- [ ] `paper/` — 一篇 8–12 页课程论文（expository paper），方向建议见 `paper/outline.md`

## 建议论文方向

- 可证明安全框架：IND-CPA / IND-CCA 归约链条梳理
- 零知识证明：从 Sigma 协议到 zk-SNARK 的技术演化
- 伪随机生成器与单向函数的等价性链条

## 前沿研究级资源（博士方向）

- [IACR ePrint Archive](https://eprint.iacr.org/)：密码学预印本档案库，追踪最新研究；建议每周固定浏览一次新论文清单
- [Cryptopals Challenges](https://cryptopals.com/)：48 个密码学实战挑战，从经典密码到现代攻击（分组密码、RSA、DSA nonce 泄露、CBC padding oracle、格归约），做完即具备真实攻击者的工程直觉
- [CryptoHack](https://cryptohack.org/)：100+ 互动挑战，覆盖对称密码、数论、椭圆曲线到后量子密码，适合穿插在 L3–L4 课程中随时练手
- zk-SNARK 实践：用 [Circom](https://docs.circom.io/) 或 [Arkworks](https://github.com/arkworks-rs) 完成一个简化 zk-SNARK 电路（如范围证明或成员证明），放入本课 `code/`——这是零知识证明方向的敲门砖产出

## 引用格式（写进申请材料时）

> Massachusetts Institute of Technology. *Cryptography and Cryptanalysis (6.875)*, Spring 2005. MIT OpenCourseWare (https://ocw.mit.edu/courses/6-875-cryptography-and-cryptanalysis-spring-2005/). CC BY-NC-SA.