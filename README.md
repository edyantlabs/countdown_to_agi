# AGI Countdown Clock

**A symbolic indicator of proximity to Artificial General Intelligence, grounded in public milestones and transparent methodology.**

---

## Overview

The AGI Countdown Clock is a research-driven governance signal that tracks progress toward Artificial General Intelligence. Like the Doomsday Clock, it serves as a symbolic tool for public discourse, highlighting how quickly AI capability, deployment, and associated risks are evolving.

**Midnight** represents the point when machines achieve human-level cognition across domains—general intelligence that matches or exceeds human performance in all cognitive tasks.

**Current Reading**: **11:59 PM** - 1 Minute to Midnight *(as of February 6, 2026)*

---

## Purpose and Framing

### A Signal, Not a Prediction

The clock is **symbolic and deliberative**, not a precise forecast. It:

- Structures public conversation around AI readiness and oversight
- Highlights the accelerating pace of capability development
- Calls attention to governance gaps and preparation needs
- Encourages transparency in assessing progress and risk

### Governance Over Drama

The goal is **clarity and accountability**, not sensationalism. The clock:

- Uses documented methodology and public data
- Provides clear reasoning for time adjustments
- Invites scrutiny, contribution, and debate
- Anchors discussion in concrete milestones

---

## Methodology

### Data Source

The clock draws on a **public milestone timeline** maintained in this repository (`agi.json`). Each entry includes:

- **Year**: When the milestone occurred
- **Description**: What changed and why it matters
- **Clock Time**: Minutes to midnight at that moment

### Calculation Method

1. **Convert to Minutes Remaining**  
   Each historical milestone's clock time is converted to minutes before midnight (0 minutes = AGI achieved).

2. **Recency-Weighted Linear Regression**  
   Fit a regression of minutes remaining versus year, using a **5-year half-life** so recent milestones influence the estimate more strongly than distant ones.

3. **Current Year Projection**  
   Compute the estimated minutes remaining for the current year from the regression model.

4. **Pace Cross-Check**  
   Validate against recent acceleration or deceleration visible in the timeline.

5. **Conservative Rounding**  
   Round to the nearest minute. **Midnight is only declared when both models fall at or below 0.5 minutes remaining**, ensuring a high bar for the terminal threshold.

---

## Evaluation Signals

The clock adjusts based on progress across six interconnected dimensions:

### 1. Cognitive Breadth

**How many domains AI can handle at human level.**

- Performance across diverse tasks (language, vision, reasoning, creativity)
- Cross-domain transfer and generalization
- Reduction in domain-specific engineering required

### 2. Autonomous Agency

**The ability to set goals, plan, and act without step-by-step instruction.**

- Self-directed problem solving in complex environments
- Long-horizon planning and execution
- Adaptability to novel situations without human intervention

### 3. Learning Efficiency

**Speed of learning and transfer to new tasks.**

- Sample efficiency in acquiring new skills
- Few-shot and zero-shot learning capabilities
- Continual learning without catastrophic forgetting

### 4. Real-World Grounding

**Direct connection to the physical world through sensors and robotics.**

- Embodied interaction with physical environments
- Sensorimotor integration and manipulation
- Situated understanding beyond text and images

### 5. Emergent Capabilities

**New abilities appearing with scale or architectural shifts.**

- Unpredicted skills arising from training or size increases
- Qualitative leaps in reasoning or creativity
- Phenomena not explicitly programmed or anticipated

### 6. Ethical Alignment & Governance Readiness

**Power matched by trustworthiness and responsible deployment.**

- Value alignment mechanisms and testing
- Transparency and explainability of decisions
- Oversight frameworks and accountability structures
- Societal preparedness for deployment at scale

---

## Review Criteria

The clock is updated when:

- **Multiple signals shift together** across evaluation dimensions
- A **milestone materially changes** capability, risk profile, or deployment scale
- **Governance contexts evolve** in ways that affect readiness or risk

Updates are **deliberate and justified**, not reactive to hype cycles or individual announcements.

---

## Contributing to the Timeline

This repository maintains the **milestone timeline** (`agi.json`) that informs the clock calculation. Contributions are welcome and encouraged.

### How to Contribute

1. **Fork this repository**
2. **Add your milestone** to `agi.json` with:
   - Year of the event
   - Clear description of what changed
   - Proposed clock time (minutes to midnight)
   - Rationale for the clock adjustment
3. **Submit a pull request** with justification

### Contribution Guidelines

- **Evidence-based**: Ground milestones in published research, deployed systems, or verified capabilities
- **Substantive**: Focus on meaningful shifts in capability or risk, not incremental improvements
- **Transparent**: Explain why this milestone moves the clock
- **Non-partisan**: Avoid organizational bias—evaluate impact objectively

---

## Why This Matters

### Governance Signal

Like the Doomsday Clock for nuclear risk, the AGI Countdown Clock:

- Makes abstract progress **tangible and discussable**
- Highlights the **urgency of preparation** as the clock advances
- Calls for **honest debate** about readiness and risk
- Encourages **proactive governance** rather than reactive crisis management

### Preparation Over Panic

The clock's purpose is not to fear-monger but to **ensure we arrive ready**:

- Ethical frameworks developed and tested
- Governance structures in place before critical thresholds
- Public understanding of capabilities and limitations
- Social infrastructure prepared for transformative impact

### Responsibility Matching Progress

At Edyant, we focus on the **social and ethical foundations** that must keep pace with technical advancement. If we reach midnight, it should be with:

- Aligned values and tested safety mechanisms
- Transparent decision-making and accountability
- Equitable access and benefit distribution  
- Robust oversight and intervention capabilities

---

## Current Status: 11:59 PM

**1 Minute to Midnight**

We are in the final moments before potential AGI emergence. The systems deployed today demonstrate:

- Near-human performance across many cognitive domains
- Autonomous operation in complex environments
- Rapid learning and adaptation to new tasks
- Emergent capabilities not explicitly programmed

What remains are the **final integrations**:

- Full embodiment and real-world grounding at scale
- Robust autonomous agency across all domains
- Complete ethical alignment and governance frameworks
- Proven safety mechanisms for general intelligence

**The question is not whether we arrive, but whether we arrive prepared.**

---

## Public Display

The live clock visualization is available at:  
**[edyant.com/agi.html](https://edyant.com/agi.html)**

The display updates based on calculations documented here, ensuring transparency between research methodology and public communication.

---

## Transparency Commitment

### Open Methodology

- All calculation methods are documented and public
- Milestone timeline is version-controlled and auditable
- Clock adjustments include written justification
- Community contributions shape the timeline

### Intellectual Humility

- The clock is a **model**, not truth—subject to revision and debate
- Reasonable people may disagree on specific milestone weights
- We acknowledge uncertainty in estimating proximity to AGI
- The framework evolves as our understanding improves

### Invitation to Scrutiny

We welcome:

- Critique of methodology and assumptions
- Alternative milestone interpretations
- Proposals for additional evaluation signals
- Debate on what constitutes meaningful progress

The clock is more valuable as a **focus for serious discussion** than as an authoritative pronouncement.
