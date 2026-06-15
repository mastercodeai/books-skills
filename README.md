# 66-Book Knowledge Library for AI Agents

> 66 本书蒸馏的 AI Skill 知识库，覆盖创业、产品、营销、增长、财务、股权、团队、经济学 8 大领域

基于 **波兰尼悖论**（我们所知多于我们所能言说）和 **第一性原理** 构建的知识库调度系统。

## 核心架构

```
books/
├── SKILL.md                          ← 总调度（波兰尼悖论 + 第一性原理）
├── economics-and-trends/             ← 经济学和大势 (8本)
├── entrepreneurial-thinking/         ← 创业思维 (15本)
├── product-design/                   ← 如何做产品 (10本)
├── marketing-and-positioning/        ← 营销和定位 (7本)
├── growth-and-traffic/               ← 增长和流量 (10本)
├── finance-and-law/                  ← 财务金融 (3本)
├── equity-and-funding/               ← 股权融资 (5本)
└── team-building/                    ← 团队建设 (8本)
```

## 66 本书清单

### 创业思维 (15本)
从0到1、精益创业、大败局I+II、小米创业思考、段永平投资问答录、创业维艰、创新者的解答、富甲美国、格鲁夫给经理人的第一课、重新定义公司、十亿美金的教训、一胜九败、经营者养成笔记

### 增长和流量 (10本)
流量池、增长黑客、硅谷增长黑客实战笔记、关系飞轮、小群效应、拉新、精益数据分析、流媒体时代、直播电商的逻辑、回头客战略

### 如何做产品 (10本)
俞军产品方法论、微信背后的产品观、上瘾、启示录、简约至上、任天堂体验设计、李想产品实战16讲、用户体验要素、用户体验度量、鞋狗

### 营销和定位 (7本)
定位、升级定位、影响力、超级符号就是超级创意、品牌12心理原型、21世纪的定位、如何让他买

### 团队建设 (8本)
网飞文化手册、OKR、穷查理宝典、金字塔原理、七个习惯、学会提问、不拘一格、创造时间

### 经济学和大势 (8本)
激荡三十年(上+中+下)、黄奇帆分析与思考、黄奇帆战略与路径、亚洲大趋势、21世纪货币政策、当音乐停止之后

### 股权融资 (5本)
股权架构、穿越寒冬、融资知识、给你一个亿(1+2)

### 财务金融 (3本)
财务报表分析、从报表看企业、什么是金融

## 每本书的 Skill 结构

每本书蒸馏为一个可调用的 AI Skill，包含：
- **场景路由表**：用户说什么 → 进入哪个模块
- **核心方法论**：从书中提取的可操作框架
- **失败模式**：if X then Y 的明确分支
- **反例禁区**：不要做什么
- **检查点**：关键决策前的自检清单

## 总调度器

`SKILL.md` 是总调度器，基于两个核心原理：

1. **波兰尼悖论**：挖掘单一书籍无法揭示的隐性认知——书与书之间的隐藏连接
2. **第一性原理**：先拆解问题本质，再从书中找证据，避免被书的框架限制思维

5 种隐性认知挖掘模式：
- 镜像互补（相反角度描述同一现象）
- 层次嵌套（宏观框架 × 微观执行）
- 矛盾揭示（矛盾本身揭示更深真相）
- 盲区暴露（都没提到的领域是重要信号）
- 涌现效应（多规则组合产生复杂行为）

## 安装

```bash
# Hermes Agent
hermes skills install mastercodeai/books-skills

# Claude Code
git clone https://github.com/mastercodeai/books-skills.git
cp -r books-skills/* ~/.claude/skills/books/

# 或手动
git clone https://github.com/mastercodeai/books-skills.git
```

## 使用

```
# 总调度（自动路由到相关书籍）
帮我分析这个问题：该不该接这个项目

# 指定书籍
用《定位》帮我分析这个品牌策略

# 跨书分析
跨书分析：产品留存率低怎么办
```

## 制作流程

每本书经过三步流程：
1. **agent-skill-creator**：读取原文 → 生成精华版 + 初始 Skill
2. **book-to-skill**：添加场景路由、逻辑流程、触发词
3. **darwin-skill**：添加失败模式、反例禁区、检查点，9维度评估优化

## License

MIT

---

## 更多AI实战工具

这个项目是 **零一AI编程出海** 开源工具链的一部分。

### 4个开源Skill，覆盖学习、决策、商业分析、知识管理

| 项目 | 功能 | 安装 |
|------|------|------|
| [ai-learn-any-skill](https://github.com/mastercodeai/ai-learn-any-skill) | 5步AI学习闭环，SMART+SQ3R+费曼+KISS | `npx skills add mastercodeai/ai-learn-any-skill` |
| [thinking-7-frameworks](https://github.com/mastercodeai/thinking-7-frameworks) | 7个顶级思维框架，马斯克/芒格/贝索斯同款 | `npx skills add mastercodeai/thinking-7-frameworks` |
| [mckinsey-12-prompts](https://github.com/mastercodeai/mckinsey-12-prompts) | 12个商业咨询提示词，价值$115,500 | `npx skills add mastercodeai/mckinsey-12-prompts` |
| [books-skills](https://github.com/mastercodeai/books-skills) | 66本书蒸馏的AI知识库，8大领域 | `hermes skills install mastercodeai/books-skills` |

### 关注公众号「零一AI编程出海」

回复「**工具包**」免费获取《AI Agent Skill 实战手册》PDF，包含4个项目的完整使用指南和实战案例。

### License

MIT
