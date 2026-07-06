# Methodology: Life Anchor & SEL Story Generation

> **Ankey** = AI-powered family education story generator × ages 3-6 × SEL

---

## Product Philosophy

"Turn what happened today into tonight's story, accompanying every step of growth."

The most effective educational moment is right after a child's real-life experience. Wrapped in familiar characters and worlds, every life moment becomes the power of growth.

### One-Minute Four-Step Flow

<img src="conception.png" alt="Ankey product philosophy" width="500">

## Life Anchor Theory

The **Life Anchor** approach is based on the insight that the most effective educational moments for young children (ages 3-6) occur within a **6-hour golden window** after a real-life event. When a child experiences something emotionally significant — a conflict, a triumph, a frustration — their brain is primed to absorb related lessons.

**Core thesis**: Replace generic bedtime stories with personalized narratives that mirror the child's real experiences, mapped to proven educational goals.

### The Cycle

```
Real-life event → Parent logs → AI maps to SEL goal
    → Personalized story generated → Child listens
    → Lesson anchored to lived experience → Growth
```

## SEL Framework

Social-Emotional Learning (SEL) provides the educational backbone. Each story targets one or more competencies:

| Category | Tags |
|----------|------|
| Self-Awareness | emotional recognition, self-confidence, identity |
| Self-Management | emotional regulation, perseverance, impulse control |
| Social Awareness | empathy, perspective-taking, respect |
| Relationship Skills | sharing, cooperation, conflict resolution |
| Responsible Decision-Making | problem-solving, ethical judgment, safety |

## Fourth-Wall Narration

A key innovation: the child is never the story protagonist. Instead, the narrator (storyteller) occasionally breaks the fourth wall to address the child directly:

> "Mia, today we're going to tell a story about Peppa at the playground..."

This creates:
- **Immersion without ego**: The child identifies with the lesson without being the "problem character"
- **Safe distance**: The child can reflect on the character's choices without feeling judged
- **Engagement**: Direct address captures attention

## Prompt Engineering

The prompts use a structured two-stage pipeline:

1. **Outline stage**: Divergent thinking — 3 options from different angles
2. **Story stage**: Convergent execution — full narrative from selected option

Both stages enforce:
- JSON output for reliable parsing
- Worldview-consistent storytelling (no IP characters in the real world)
- Content safety gates (parent review step in product)

---

## ———— 中文版 ————

# 方法论：Life Anchor & SEL 故事生成

## 产品哲学

把今天发生的事，变成今晚的睡前故事。教育最有效的时机就在孩子真实经历之后。用孩子熟悉的角色和世界包装教训，让每一次生活瞬间都变成成长的力量。

### 一分钟四步法

<img src="conception.png" alt="小锚产品哲学" width="500">

## Life Anchor 理论

**生活锚定（Life Anchor）** 的核心洞察：3-6 岁儿童最有效的教育时机发生在真实事件后的 6 小时黄金窗口内。当孩子经历情感上重要的事件——冲突、成功、挫折——他们的大脑对相关课程处于最佳接收状态。

**核心论点**：用反映孩子真实经历的个性化故事替代通用睡前故事，映射到经过验证的教育目标。

### 教育循环

```
真实事件 → 家长记录 → AI 映射 SEL 目标
    → 生成个性化故事 → 孩子收听
    → 教训锚定在真实经历上 → 成长
```

## SEL 框架

社会情感学习（SEL）提供教育支撑。每个故事针对一个或多个能力维度。

## 第四面墙叙事

孩子不是故事主角。讲述者偶尔打破第四面墙直接称呼孩子，创造安全的反思距离。

## 提示词工程

两阶段流水线：
1. **梗概阶段**：发散思维，从不同角度生成 3 个方案
2. **故事阶段**：收敛执行，从选定方案生成完整叙述
