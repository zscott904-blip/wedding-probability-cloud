# Wedding Probability Cloud PRD

## Objective

Create a mobile-first wedding interaction page that lets guests feel the statistical significance of the couple's meeting. The visual metaphor is a probability cloud: countless possible life paths narrow through conditions until two gold sample points meet, then enter a new shared sample space.

## Core Theme

The page should communicate:

> In a vast sample space of possible lives, a small-probability event occurred. It was significant enough to change the distribution of everything that came after.

## Experience Structure

The current proposed experience uses five steps.

### Step 1: Sample Space

Narrative:

> 相遇之前，我们都只是无数可能中的一个样本点。

Purpose:

- Establish infinite life possibilities.
- Show a large drifting probability cloud.
- Keep the two gold points hidden but present.

Visual behavior:

- Many moonlight-blue and lavender particles drift softly.
- The cloud is broad and unresolved.
- Gold particles are faint, not yet emphasized.

### Step 2: Conditions Appear

Narrative:

> 学科、时间和地点，开始给随机的人生加入条件。

Purpose:

- Introduce conditional probability.
- Show that life choices begin shrinking the sample space.

Visual behavior:

- Some particles fall away.
- Remaining particles zoom in and pull slightly toward center.
- The visual field becomes more focused.

### Step 3: Paths Converge

Narrative:

> 条件一层一层叠加，两条原本独立的轨迹开始靠近。

Purpose:

- Show repeated conditions accumulating.
- Shift from randomness toward convergence.

Visual behavior:

- More particles fall away.
- Remaining particles continue zooming inward.
- The gold points become more readable.

### Step 4: Significant Meeting

Narrative:

> 直到一个小概率事件发生，并且显著到无法忽略。

Purpose:

- Make the meeting feel statistically significant.
- Let the two gold points become the unmistakable signal.

Visual behavior:

- Ordinary particles mostly fall away.
- Two gold particles move toward each other.
- A gold connection appears between them.
- After the meeting, a faint echo of the original probability cloud reappears behind them, like a brief zoom-out.

Product decision:

- The "zoom out to the original cloud" should be an automatic transition inside Step 4, not a separate step.
- Reason: it functions as a reflective moment, showing that the meeting is the brightest outcome inside the old infinite sample space. Making it a separate click would slow the ceremony and visually repeat the future cloud too much.

### Step 5: Shared Future

Narrative:

> 从此，未来不再是两条独立路径，而是我们一起探索的概率云。

Purpose:

- Reframe the meeting as the beginning of a new joint sample space.
- Move from proof of meeting to shared future.

Visual behavior:

- The two gold particles fly into a new probability cloud.
- Future particles move from far to near and toward screen edges.
- This creates a tunnel/cloud traversal effect.
- Gold particles drift and pulse in size to suggest floating together through the future.

## Visual Direction

Primary palette:

- Moonlight blue
- Pale lavender
- Silver white
- Soft champagne gold

Tone:

- Dreamlike
- Elegant
- Statistical without looking like a dashboard
- Immersive rather than modular

UI principle:

- The page should open directly into a full-screen visual.
- Text and controls should feel like subtle subtitles blended into the scene.
- Avoid visible cards, heavy borders, or explanatory UI modules.

## Interaction Model

The guest taps one button to advance.

Recommended button sequence:

- Step 1 to 2: 继续缩小样本空间
- Step 2 to 3: 继续缩小样本空间
- Step 3 to 4: 继续缩小样本空间
- Step 4 to 5: 进入共同的未来
- Step 5: 重新看一次

## Current Implementation Files

- `index.html`: Current main deployed version.
- `index-five-step.html`: Five-step experimental narrative version.
- `index-warm-dream.html`: Warm dream color backup version.

## Next Decisions

- Decide whether the five-step version should replace `index.html` for Netlify deployment.
- Tune Step 4 echo-cloud timing after testing on a phone.
- Tune Step 5 future-cloud traversal speed after testing on a phone.
- Replace generic narrative with the couple's real story details if desired.
