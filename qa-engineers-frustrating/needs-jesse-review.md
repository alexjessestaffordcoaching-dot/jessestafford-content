# Jesse Review Report

**Draft:** drafts/2026-06-19-qa-engineers-frustrating/medium-article.md
**Date:** 2026-06-19
**Word count:** ~1,090 (~5 min read)
**Title used:** "Your QA Engineers Aren't Slowing You Down. Here's What Is."
**Scheduled publish:** 2026-06-24 (Tuesday)

---

## Story Used

**Primary anchor:** Story 70 — The QA Team That Grieved the Goal Change (supporting context, not anchor)

Riley confirmed: no direct anchor story exists in the story bank for a specific QA frustration moment. The opening sprint review scene was built as a composite.

**Composite construction:**
- Opening sprint review scene (counts, silence, nobody answers the risk question): drawn from the patterns Jesse has described across Stories 57, 38, 64, and the World Quality Report data. The specific moment has not been confirmed by Jesse.
- "I managed a QA team directly for several years in game development": grounded in Story 70 (Jesse incorporated a QA team and changed their goals).
- Goal change (individual defect counts → team-level outcomes: defects reaching customers + whether game team delivered on time): taken verbatim from Story 70's exact description of what Jesse changed.
- "The team resisted the change": also from Story 70 ("They are going to grieve this change. All 7 stages.").
- "I was doing the same thing. I was frustrated with QA and telling everyone about it except QA.": composite inference from Story 38 pattern (the manager who was furious but never said it to the server lead) applied to Jesse's own behavior. Not confirmed by Jesse directly.

**This composite should not be approved until Jesse confirms the sprint review scene resembles what he actually experienced.**

## Sources Referenced (Riley's source log)

- `memory/stories/story-70-qa-team-grieved-goal-change.md`
- `memory/stories/story-57-what-he-hates-about-managing-engineers.md`
- `memory/stories/story-38-manager-furious-never-said-it.md`
- `memory/stories/story-43-return-to-office-product-quality.md`
- `memory/stories/story-64-engineer-told-pm-to-move-the-date.md`
- `memory/voice-reddit.md`
- `memory/guiding-principles.md`
- `drafts/2026-06-19-qa-engineers-frustrating/01-topic-research.md` (Morgan's internet research)

---

## Karen Flagged for Jesse
Nothing flagged for judgment. All violations were auto-fixable (em dashes, paragraph lengths). Two passes ran clean.

## Jordan Flagged for Jesse
Nothing unresolved. All priority flags were addressed by Sam:
- "I once coached a manager" anecdote: removed entirely, replaced with Jesse's direct confession ("I was doing the same thing...")
- Section renamed from "What I Got Wrong" to "What Changed"
- Third "QA..." paragraph opener varied
- Quick Bridge rewritten as declarative (removed conditional "If")

---

## Judgment Calls Made

1. **Composite opening scene.** The sprint review scene (247 test cases, 31 bugs, room goes quiet) is a composite. The specific meeting moment is invented but grounded in Jesse's documented QA experience. See composite note at top of medium-article.md.

2. **"I was doing the same thing" confession.** Jordan flagged the "I once coached a manager" anecdote as undercutting Jesse's direct experience. Sam replaced it with a first-person confession. The confession implies Jesse also failed to bring his frustration directly to QA before changing his approach. If that is not accurate to Jesse's experience, this should be revised.

3. **Title chosen.** "Your QA Engineers Aren't Slowing You Down. Here's What Is." was the strongest candidate for cold traffic (inverts the assumption, promises a reveal). Two alternates are in metadata.json if Jesse wants to choose differently.

4. **Story 70 used as supporting context, not anchor.** Per Riley's guidance, Story 70 is reserved as the primary anchor for Queue #27. The QA team management experience (game dev, goal change) appears in the "What Changed" section but is not the opening story.

5. **Platform cross-link uses placeholder.** The internal link to "Context Beats Process Every Time" points to `https://medium.com/@stafford.jesse` — not the specific article URL. Update with the actual Medium URL before publishing.

---

## Before Approving — Review These Specifically

1. **The opening sprint review scene (medium-article.md, paragraphs 1-4).** The scene: 247 test cases, 31 bugs, room goes quiet when someone asks about customer risk. Does this match how you have experienced sprint reviews with QA? The specific numbers are fabricated — but does the dynamic feel accurate? If this is too generic or too far from how you have described this situation, Sam needs to revise before this publishes.

2. **"I was doing the same thing. I was frustrated with QA and telling everyone about it except QA." (medium-article.md, "What Changed" section).** This is the self-implication moment. It implies Jesse was doing exactly what the manager in Story 38 did — venting sideways instead of going directly to QA. Is that accurate to your experience? If not, this line should be adjusted or removed.

3. **"In every QA team I have worked with, the measurement was defect counts." (medium-article.md, "Why QA Communicates This Way" section).** Confirm this is accurate. This is a strong claim — if there were QA teams where the measurement was different, soften this to "In most of the QA teams I have worked with" or specify the context (game development specifically).

4. **The goal change details (medium-article.md, "What Changed" section).** The post describes the goals changing to: defects reaching customers + whether the entire game team delivered on time. Does that match what you actually changed? These details come directly from Story 70 — but confirm they are accurate to your memory of that situation.

5. **Blogger post: "What Happens When You Change the Goals" section.** The Blogger has an additional section with a concrete before/after example: before, QA gave sprint counts (143 test cases, 22 bugs). After, QA came into planning asking about the authentication flow and payment processing team. These specific examples were invented to illustrate the pattern. Confirm the general dynamic is accurate — or provide a real detail from your memory to replace the invented ones.
