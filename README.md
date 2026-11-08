# Listing Fixer (v1.1)

A free AI skill that fixes the selling side of a product listing, on any platform. You already have the product. Listing Fixer helps with the rest.

## What it produces
- A ready-to-paste description, tailored to where you sell
- Launch price, later price, and when to raise it
- Package tiers (optional)
- A "what you need" requirements block
- A one-page licence template
- An optional upsell, downsell or cross-sell block with a link placeholder
- Optional images: 3D box mockup, store cover, promo banner. Each comes with a ready-to-paste prompt so you can recreate it in another tool if you do not like the result. If your AI tool cannot make images, you get the prompts alone.
- Name suggestions, only if you say yes

## What it does not do
It does not research competitors or markets, inspect your files, or ask about brand colours. It uses your colours if you give them, otherwise a neutral palette. It does not publish anything.

## Install
Add the `listing-fixer` folder (or the ZIP) as a skill in any AI tool that supports SKILL.md skills. If your tool does not support skills, paste `SKILL.md` into a chat as instructions and share the `references/` files when asked.

## Use
Say "fix my listing" and answer the intake questions, including where you sell.

## Layout
| Path | Purpose |
|---|---|
| `SKILL.md` | Workflow and rules |
| `references/` | Description structure, pricing and packaging, licence template, add-on blocks, platform notes, image briefs |
| `examples/` | One fictional example, illustrative only |
| `evals/` | Test prompts to run yourself |

## Notes and limits
- Price ranges are example anchors for prompt and template products. No market research was performed.
- Platform notes are not checked against live documentation. Verify limits before publishing.
- Image quality and availability depend on your AI tool.
- The licence is a template, not legal advice.
- Not tested on any specific platform. Run `evals/test-prompts.md` to check behaviour in your tool.

## Licence
MIT. See `LICENSE`.
