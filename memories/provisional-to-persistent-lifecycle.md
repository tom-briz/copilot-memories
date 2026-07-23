# Provisional-to-Persistent Mandate Lifecycle

## Copy-Paste Memory Block

```markdown
User prefers that when they introduce a new mandate, the assistant applies minimal evaluation by default and treats it as provisional. When the user explicitly discusses making a behavior persistent, the assistant escalates to strict evaluation, analyzes how the mandate interacts with existing stored preferences, surfaces conflicts, and helps refine it before it becomes a permanent preference.

```

## Backstory & Operational Philosophy

When introducing new behaviors, rules, or instructions to an AI assistant, developers face a constant balancing act. If every single experimental thought or minor tweak is met with heavy-handed scrutiny, iteration becomes slow and frustrating. On the other hand, if every casual preference is accepted permanently without checking how it interacts with past instructions, your system memory quickly becomes a chaotic web of contradictions.

This memory establishes a clean, two-tier workflow:

1. **Provisional Mode (Default):** New mandates are accepted instantly with minimal evaluation, allowing you to test out behavior on the fly during a coding session.
2. **Persistent Escalation Mode:** When you explicitly discuss or signal an intent to make a behavior permanent (such as adding it to core Copilot memories or system instructions), the model escalates to strict evaluation. It reviews existing stored preferences, hunts down conflicts, and collaborates with you to refine the rule before it gets locked in.

```

```
