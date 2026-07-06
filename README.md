# Ankey Story Prompts

> **Ankey** = AI-powered family education story generator × ages 3-6 × SEL

[中文版 →](README.zh-CN.md)

---

## What This Is

These prompts power [Ankey](https://www.miuflow.com/ankey/) — a production WeChat Mini Program that turns real-life parenting moments into personalized SEL bedtime stories for children aged 3-6.

## Educational Foundation

Ankey's methodology is grounded in established educational and cognitive science theories.

### Why Ages 3-6?

**Piaget's Cognitive Development Theory**: Ages 3-6 fall in the Preoperational Stage. Children cannot process abstract logic — education must be delivered through concrete, narrative experiences. Abstract instruction ("sharing is important") is ineffective.

**Vygotsky's ZPD**: Children accomplish far more with adult guidance. Bedtime storytelling is a natural Zone of Proximal Development context — the parent's presence enables understanding beyond independent capacity.

**Neuroscience** (Harvard Center on the Developing Child): 90% of brain development occurs before age 5. The neural pathways for emotional regulation enter a critical sensitive period at ages 3-5.

### Why Stories?

**Bruner's Narrative Thinking**: Children develop narrative thinking before paradigmatic thinking. They understand causality, intention, and morality through stories — not through abstract rules.

**Narrative Transport** (Green & Brock, 2000): Story immersion produces a "narrative transport" effect that changes behavior 22x more effectively than direct instruction.

**Memory Encoding Mechanisms**: Emotionally charged stories activate the amygdala, enhancing hippocampal encoding. Bedtime listening leverages sleep-dependent memory consolidation during slow-wave sleep. Personalization engages the default mode network for autobiographical memory integration.

### Why Real-Life Events?

**Dewey's Experiential Learning**: Authentic education builds on direct lived experience. A generic story about "sharing" and a story about "what happened to you at the playground today" are fundamentally different cognitive events for a preschooler.

**Schema Theory**: New knowledge is assimilated by anchoring to existing mental schemas. Real-event stories reduce cognitive load, lower comprehension barriers, and improve long-term retention.

**Self-Reference Effect**: Self-related information is remembered significantly better than generic information. When a story references the child's actual experience, the reticular activating system triggers attention — this is not "a story," this is "my story."

### Why the 6-Hour Golden Window?

**Emotional Memory Consolidation**: The brain enters a plasticity window after emotionally arousing events. Educational intervention within this window produces exponentially stronger results than delayed intervention.

**Sleep-Dependent Consolidation**: The hippocampus transfers short-term to long-term memory during slow-wave sleep. "Today's event → tonight's story" is not coincidental timing — it leverages the brain's natural learning enhancement cycle.

**Immediate Feedback**: Shorter feedback loops produce better behavioral outcomes. The 6-hour window covers the natural period from school pickup to bedtime preparation.

### Why Parents Lead?

**Attachment Theory** (Bowlby, Ainsworth): Secure parent-child attachment provides a "safe base" for learning. Parent-led storytelling reinforces this bond — the child's sense of safety from the parent's voice and presence increases receptivity to educational content.

**Self-Determination Theory** (Deci & Ryan): Three core needs — autonomy, competence, relatedness. Ankey positions parents as active educational designers (autonomy), children feel supported in interaction (relatedness), and gradually build emotional competence.

**Authoritative Parenting** (Baumrind): High-demand + high-response parenting is empirically optimal. Ankey enables parents to set clear educational goals (high demand) while providing emotional engagement through bedtime stories (high response).

> **AI augments the technical workflow; the educational relationship remains between parent and child.**

## The Ankey Implementation

These prompts deliver the story-generation component of a complete educational system. The full workflow — event logging, SEL goal mapping, outline selection, one-click TTS synthesis, and story box delivery — is implemented as a production-grade WeChat Mini Program.

The Ankey Mini Program (available via WeChat search **"小锚助手"**) automates the entire lifecycle from event input to bedtime listening, consistent with the neuroscience recommendation for timely intervention. Parents complete the process in under one minute, with no prompt engineering or technical setup required.

<img src="qr-code.png" alt="Ankey WeChat Mini Program QR Code" width="128">

> These prompts can be used standalone with any LLM. However, the Mini Program provides the integrated implementation — including automated SEL mapping, outline preview, one-click TTS, and story box push — that makes the methodology accessible for daily use.

## Prompt Usage

Two-stage generation pipeline:

| Stage | Input | Output |
|-------|-------|--------|
| **Outlines** | Event description + child's worldview/interests | 3 SEL-tagged story outlines |
| **Story** | Selected outline | Full narrative with fourth-wall narration |

### Example Scenarios

| Scenario | Input | Output |
|----------|-------|--------|
| Sharing | "Wouldn't share toys, loves excavators" | "Excavator Dave's Sharing Day" + SEL tag |
| Bedtime | "Learned to tie shoes today, loves Peppa" | "Peppa's Shoelace Contest" + SEL tag |
| Emotional regulation | "Threw a tantrum, loves Bluey" | "Bluey's Calm Corner" + SEL tag |

## Prompt Files

| File | Purpose |
|------|---------|
| `prompts/outline.md` | Generate 3 story outlines from event + worldview |
| `prompts/story.md` | Generate full story from selected outline |
| `prompts/examples/` | Few-shot examples across SEL topics |

## Key Design Principles

- **Fourth-Wall Narration**: The child's name is used only by the narrator addressing the listener, never as a story character. This creates safe reflective distance.
- **SEL Mapping**: Every story targets specific social-emotional learning competencies (self-awareness, self-management, social awareness, relationship skills, responsible decision-making).
- **Worldview Consistency**: Stories remain within the child's favorite fictional universe (Peppa's world, Bluey's world, etc.), maintaining immersion.
- **6-Hour Golden Window**: Generation within the optimal learning window after the triggering event.

## License

MIT
