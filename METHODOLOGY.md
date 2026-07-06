# Methodology: Life Anchor & SEL Story Generation

## Life Anchor Theory

The **Life Anchor** approach is based on the insight that the most effective educational moments for young children (ages 3-6) occur within a **6-hour golden window** after a real-life event. When a child experiences something emotionally significant — a conflict, a triumph, a frustration — their brain is primed to absorb related lessons.

**Core thesis:** Replace generic bedtime stories with personalized narratives that mirror the child's real experiences, mapped to proven educational goals.

### The Cycle

```
Real-life event → Parent logs it → AI maps to SEL goal
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
