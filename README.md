<p align="center">
  <img src="./assets/readme-cover-21x9.png" alt="Sun-Style Writing: cold narrative, wealth manifesto, technical systems" width="100%">
</p>

<h1 align="center">sunology-writing-skill</h1>

<p align="center">
  <strong>一个把动作、数字、物件、系统和沉默写进中文长文的 Codex Skill。</strong><br>
  <strong>A Codex Skill for writing Chinese long-form prose with cold narrative, precise details, systems, and silence.</strong>
</p>

<p align="center">
  <a href="https://github.com/Leon-KTlan/sunology-writing-skill/releases/latest"><img alt="GitHub Release" src="https://img.shields.io/github/v/release/Leon-KTlan/sunology-writing-skill?style=flat-square&color=7A1E1E"></a>
  <img alt="Codex Skill" src="https://img.shields.io/badge/Codex%20Skill-sun--style--writing-111111?style=flat-square">
</p>

<p align="center">
  <a href="#中文">中文</a> · <a href="#english">English</a>
</p>

---

## 中文

**推荐仓库名：`sunology-writing-skill`**

一句话介绍：

> 一个用于生成和改写“孙学体”中文长文的 Codex Skill：冷叙事、数字锚定、物件回环、财富宣言、技术系统感。

`sunology-writing-skill` 不是复刻某一篇文章，也不是简单把句子切短、塞几个金额、最后写一句“什么都没有发生”。

它做的是另一件事：

> 先把情绪拿掉。
>
> 再把动作、数字、物件、账单、系统提示和沉默放上去。
>
> 最后让读者自己把情绪补回来。

### 它适合什么

- 第一人称非虚构
- 人物特写
- 创业故事
- 财富观和技术观点文
- 公众号长文
- 情感回忆、关系叙事、离职叙事
- 已经写得太抒情、太 AI、太空泛，需要降温的稿子

### 它怎么写

这个 skill 会先从素材里找四样东西：

| 元素 | 作用 |
| :--- | :--- |
| 命题 | 文章真正要证明什么 |
| 砝码 | 能压住全文的数字、金额、时间、人数、距离 |
| 物件 | 旧照片、门禁卡、账单、验证码、会议牌 |
| 空处 | 缺席的人、没发出的消息、没有人问为什么的现场 |

然后选择一种模式：

| 模式 | 适用 |
| :--- | :--- |
| 冷叙事 | 情感故事、失败、决裂、遗憾、荒诞经历 |
| 财富宣言 | 财富观、创业复盘、个人成长、技术判断 |
| 人物神话 | 创业者故事、个人 IP、品牌人物稿 |
| 混合模式 | 需要更强后劲的中文长文 |

### 安装

把这句话发给支持 Skills 的 Agent：

```text
帮我安装这个 skill：https://github.com/Leon-KTlan/sunology-writing-skill
```

或者把仓库放到本机 Skills 目录：

```text
~/.codex/skills/sun-style-writing/
```

### 使用

```text
使用 $sun-style-writing，把下面这段材料改成一篇孙学体长文。
```

更完整的提示词：

```text
使用 $sun-style-writing。

目标：写一篇 3000 字左右的第一人称创业复盘。
语气：冷叙事 + 财富宣言，少抒情。
保留事实：融资 200 万美元、办公室 18 个人、第一次失败发生在 2024 年 7 月。
可用物件：旧门禁卡、第一张发票、服务器账单。
不要编造新人物，不要写鸡汤结尾。

素材如下：
...
```

### 文件结构

```text
.
├── SKILL.md
├── README.md
├── assets/
│   └── readme-cover-21x9.png
├── examples/
│   └── my-boyfriend-hu-wenjie.md
└── references/
    ├── style-anatomy.md
    └── source-notes.md
```

### 边界

这个项目是写作技法研究和文本生成辅助，不代表孙宇晨、景甜或任何现实人物的立场。

它不判断任何故事真假，不提供投资建议，不鼓励冒充真实人物，也不应该被用来编造现实人物隐私。

如果写真实人物和真实事件，先核验事实。

如果写虚构故事，先标明是虚构。

---

## English

**Recommended repository name: `sunology-writing-skill`**

Short description:

> A Codex Skill for generating and rewriting Chinese long-form prose in a “Sun-style” mode: cold narrative, numerical anchors, object callbacks, wealth manifesto logic, and technical-system texture.

`sunology-writing-skill` is not a clone of any single viral essay. It is not just short lines, large sums of money, and an empty final sentence.

It works by removing explicit emotion first, then replacing it with observable actions, precise numbers, recurring objects, receipts, system messages, and silence.

### Best For

- First-person nonfiction
- Character profiles
- Startup stories
- Wealth, technology, and personal strategy essays
- Chinese long-form posts
- Relationship, campus, career, and departure narratives
- Drafts that feel too emotional, too generic, or too AI-written

### Writing Model

The skill looks for four anchors before drafting:

| Anchor | Purpose |
| :--- | :--- |
| Thesis | What the piece is really proving |
| Weight | The number, amount, duration, distance, or count that carries pressure |
| Object | A small recurring item such as a badge, invoice, old photo, receipt, or reminder |
| Absence | The empty room, missing reply, blank memo field, or unexplained silence |

Then it chooses one main mode:

| Mode | Best for |
| :--- | :--- |
| Cold narrative | Relationships, failures, breakups, regret, absurd situations |
| Wealth manifesto | Startup retrospectives, wealth views, strategy essays, technology judgments |
| Character myth | Founder profiles, personal brands, public-persona writing |
| Hybrid mode | Stronger long-form essays with narrative and argument |

### Install

Ask a Skills-capable agent:

```text
Install this skill: https://github.com/Leon-KTlan/sunology-writing-skill
```

Or place the repository in your local Skills directory:

```text
~/.codex/skills/sun-style-writing/
```

### Use

```text
Use $sun-style-writing to rewrite the following material into a cold, precise Chinese narrative.
```

Better prompt:

```text
Use $sun-style-writing.

Goal: Write a 3000-character first-person startup retrospective.
Tone: cold narrative + wealth manifesto, minimal explicit emotion.
Facts to preserve: raised USD 2M, 18 people in the office, first failure happened in July 2024.
Objects available: old access card, first invoice, server bill.
Do not invent new people. Do not end with a motivational lesson.

Material:
...
```

### Project Structure

```text
.
├── SKILL.md
├── README.md
├── assets/
│   └── readme-cover-21x9.png
├── examples/
│   └── my-boyfriend-hu-wenjie.md
└── references/
    ├── style-anatomy.md
    └── source-notes.md
```

### Boundaries

This project is a writing-technique study and generation aid. It does not represent Justin Sun, Jing Tian, or any real person.

It does not verify stories, provide investment advice, encourage impersonation, or support fabrication of real-person private facts.

Verify real-world claims before writing about real people or real events.

Label fiction as fiction.
