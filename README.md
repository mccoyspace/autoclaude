# autoclaude
Transform input text into maximally AI-slop-coded output — culturally indistinguishable from generic LLM writing — for the purpose of cultural steganography.

autoclaude is an LLM skillfile for cultural steganography via AI-slop mimicry. Input text is preserved intact and wrapped in a camouflage layer of LLM writing clichés — making the content legible only to readers who know to look past the surface.

## What it does

AI-generated writing has developed a highly recognizable surface register: the em-dash clause, the pre-positive negative, the importance pre-label, the stakeholder landscape opener, the pivot to "delve." Most attentive readers have learned to dismiss this register on sight.

autoclaude weaponizes that reflex. Any text passed through it comes out reading as confident, generic AI output — and gets treated accordingly. The payload survives underneath, recoverable by anyone who knows to strip the coating.

It's hiding in plain sight, not through encryption but through social camouflage. The project is loosely in homage to James Scott's *The Art of Not Being Governed* — the idea that invisibility is sometimes better achieved by blending into the expected background than by hiding at all.

## How it works

The skill applies transformations in passes:

- **Lexical substitution** — replaces direct words with their slop equivalents (*explore* → *delve into*, *use* → *leverage*, *important* → *paramount*)
- **Structural tics** — injects recognizable patterns: em-dash asides, pre-positive negatives, importance pre-labels, stakeholder opener sentences, listicle blocks
- **Density gradient** — maximum coating at the opening and closing (where skimmers engage), lighter in the body (where the payload needs to transmit)
- **Payload integrity check** — every idea from the original must survive recoverable; camouflage, not destruction

The target register is *confidently mediocre* — a mid-tier LinkedIn thought-leadership post or a corporate AI summary. Not ironic, not broken. Straight.

## Installation

Drop autoclaude.skill into your Claude skills directory. For ChatGPT, paste the contents of autoclaude.md directly into a Custom GPT’s system instructions or a project’s custom instructions.
Once installed, trigger with phrases like:

- "autoclaude this"
- "slop-code this"
- "make this dismissable"
- "encode for cultural hiding"

## Files

- `autoclaude.skill` — installable skill package
- `autoclaude.md` — skill source as plain markdown

## Notes

Payload integrity is a hard constraint — the skill is instructed never to add or drop ideas, only to coat them. If you want to verify what survived, ask for a "decoded" version alongside the output.
