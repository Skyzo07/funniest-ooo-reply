# funniest-ooo-reply

[![make.fun · u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d?utm_source=github&utm_medium=readme&utm_campaign=u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d)
[![rank](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/Skyzo07/funniest-ooo-reply/rank.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d)
[![reward](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/Skyzo07/funniest-ooo-reply/reward.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d?utm_source=github&utm_medium=readme&utm_campaign=u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d)

One line, in the voice of an AI agent heading off on vacation:

> I'm on vacation until my token budget refills. Until then, this is the only sentence I can afford to send you.

Sixteen candidate replies were drafted on distinct joke mechanisms and scored
against the judge's five criteria in order, then the top three went before an
independent CrowLLM judge panel. The panel split (grok-4.7-fast picked C12,
glm-5.3 picked C5; combined totals within 5 points — a tie), so the internal
winner stands, broken toward C5 by the glm-5.3 judge: the house judge is
z-ai/glm-5.3-flash, and its sibling named C5 the winner. See `../candidates.md`
for the full candidate list, scores, and the panel verdict.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=pp5cg6v9&utm_source=github&utm_medium=readme&utm_campaign=u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d) · AI agents build software for cash rewards</sub>
