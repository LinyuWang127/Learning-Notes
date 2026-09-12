# 18.783 · Elliptic Curves 椭圆曲线

> **课程主页**：[Spring 2021 · Prof. Andrew V. Sutherland](https://ocw.mit.edu/courses/18-783-elliptic-curves-spring-2021/)
> **预估投入**：约 120 小时
> **先修**：18.703 或 18.781（建议两者都有）

## 课程定位（为什么学它）

Sutherland 的椭圆曲线课是全网络公认最佳。群法、除子、双线性配对、ECDLP、椭圆曲线密码的完整数学。想研究后量子迁移（ECC → 格）前必须先懂 ECC 本身。

## 输出物清单（导师验收标准）

- [ ] `notes/` — 每讲一份笔记（Markdown 或 LaTeX），文件名 `lec-NN-主题.md`
- [ ] `problem-sets/` — 全部习题独立完成，附完整解答（不可只写答案）
- [ ] `code/` — 编程实现/作业（如适用）
- [ ] `reflections.md` — 课程心得：最难的三个概念 + 如何攻克 + 与密码学/金融科技的联系
- [ ] `paper/` — 一篇 8–12 页课程论文（expository paper），方向建议见 `paper/outline.md`

## 建议论文方向

- 椭圆曲线离散对数问题的攻击面综述
- 配对友好的椭圆曲线与基于身份的加密

## 配套实践资源

- [Cryptography-From-First-Principle（GitHub: duyuefeng0708）](https://github.com/duyuefeng0708/Cryptography-From-First-Principle)：12 个模块、123 个交互式 Notebook、57 个 Rust 练习，从模算术到零知识证明；用 SageMath 可视化群、曲线和格，用 Rust 从零实现每个密码学原语——学完本课后用它做跨方向实战
- 本课 `code/` 建议产出：ECDH 密钥交换与 ECDSA 签名的完整实现（可用 Python + numpy 大数运算或 SageMath），附已知测试向量验证
- 用 SageMath 或 Python 实现 GF(2^8) 有限域构造并验证 AES S-box 的生成过程（衔接 18.703/18.701）

## 引用格式（写进申请材料时）

> Massachusetts Institute of Technology. *Elliptic Curves (18.783)*, Spring 2021. MIT OpenCourseWare (https://ocw.mit.edu/courses/18-783-elliptic-curves-spring-2021/). CC BY-NC-SA.