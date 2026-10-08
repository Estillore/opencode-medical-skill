# Medical skill for OpenCode (v1.2)

Free, local skill. Decision support only. The clinician stays accountable.

The folder and skill name are `medical` so OpenCode can load it for medical safety questions. It does not answer every medical question. It structures emergencies, reports, assessments, and assumption checks, and it refuses diagnosis, dosing, and invented facts.

## Install

1. Install OpenCode: https://opencode.ai/docs/
2. Copy the `skills/medical` folder into one of these locations:
   - Global: `~/.config/opencode/skills/medical/`
   - Project: `.opencode/skills/medical/`
3. Start OpenCode and ask for the workflow.

## Example prompts

- "SBAR for a new fever and low blood pressure. I will fill the facts."
- "I-PASS for end of shift. Leave blanks."
- "ABCDE prompt list for a sudden drop in oxygen. Do not invent values."
- "Focused assessment outline for chest pain. Data only."
- "List the assumptions in this draft note, with risk rank and what I must verify."

## Safety stance

Aligned with ANA guidance that AI supports clinical judgment and does not replace it, Joint Commission handoff expectations, and ABCDE rapid assessment. Facility policy, current orders, and the clinician's own assessment override anything this skill drafts.

Not a medical device. Not legal advice. Not a substitute for training, protocols, or the licensed clinician.
