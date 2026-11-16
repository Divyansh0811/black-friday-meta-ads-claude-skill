# Black Friday Meta Ads Claude Skill: your BFCM ad creative in one prompt

**Free Claude skill that writes your Black Friday & Cyber Monday Meta ads: offers, static concepts, video scripts and copy, built from your competitors' Ad Library. Powered by [Reckon MCP](https://usereckon.ai/?utm_source=x_divyansh).**

Not generic AI copy: every idea is backed by real competitor ads (and your own best ads, if you connect your ad account).

### ⬇️ [Download the skill (reckon-bfcm-kit.zip)](https://github.com/Divyansh0811/black-friday-meta-ads-claude-skill/raw/main/reckon-bfcm-kit.zip)
Upload this ZIP to Claude as-is (Customize → Skills → Upload a skill). Don't use GitHub's green "Code → Download ZIP" button: that downloads the whole repo, not the skill.

One prompt, *"Make my Black Friday ads"*, and you get:

1. **The market right now**: what your competitors are offering, what's crowded, what's barely used, which ads are gaining impressions this week
2. **Your offer**: the exact line, why, and an offer ladder (VIP → Black Friday → Cyber Monday → gifting)
3. **Winners to re-use** with a Black Friday overlay *(if your ad account is connected)*
4. **8–10 static ad concepts**: headline, offer line, visual, copy
5. **3 video scripts** you can shoot in a day
6. **A copy bank**: primary text, headlines, Cyber Monday and gifting sets
7. **Matching email / SMS lines** and landing-page hero copy
8. **A launch calendar** with ad-review deadlines
9. **A compliance check** (reference prices, "up to X%", countdowns, Meta policy)

Every concept ends with **Built on:**, the real competitor ads and data behind it.

## How it works

Every night, Reckon's agent checks your competitors' Meta Ad Library: it watches and transcribes every ad, tags the hook, angle, offer and format, and tracks which ads are gaining impressions. If you connect your ad account, it also knows your own best-performing ads and the offers that worked for you. This skill tells Claude how to read all of that and turn it into a BFCM kit.

## Setup (5 minutes)

1. **Create a free Reckon account:** https://usereckon.ai/?utm_source=x_divyansh
2. **Add Reckon to Claude:** Claude → Settings → Connectors → *Add custom connector* → `https://usereckon.ai/connect/mcp` → sign in
3. **Turn on code execution:** Settings → Capabilities → *Code execution and file creation*
4. **Upload the skill:** download [`reckon-bfcm-kit.zip`](https://github.com/Divyansh0811/black-friday-meta-ads-claude-skill/raw/main/reckon-bfcm-kit.zip) → Customize → Skills → **+** → *Upload a skill*
5. **Ask:** *"Make my Black Friday ads for [your brand]"*

On first run it asks for your competitors' **Meta Ad Library links** (facebook.com/ads/library → search the brand → open its page → copy the link with `view_all_page_id=`). Newly added competitors take a little while to be read.

> Claude Code users: copy the `reckon-bfcm-kit/` folder into `~/.claude/skills/`.

## What's inside

```
reckon-bfcm-kit/
├── SKILL.md                    the workflow: setup → read data → decide → write → check
├── references/
│   ├── offer-playbook.md       % vs $ (rule of 100), discount depth, gift vs bundle, offer ladder
│   ├── formats-and-specs.md    must-have formats, sizes, safe zones, copy lengths, hook formulas
│   ├── compliance.md           reference prices, "up to X%", countdowns, email claims, Meta policy
│   └── launch-plan.md          2026 phases and dates, pre-testing, what to measure
└── templates/kit-template.md   the 10-section kit
```

## FAQ

**How do I write Black Friday ads with Claude?**
Install this skill, connect the Reckon MCP connector, and ask Claude "Make my Black Friday ads for [brand]". It reads your competitors' current Meta ads and your own best ads, then writes the offer, static ad concepts, video scripts, ad copy and a launch calendar.

**How do I see my competitors' Black Friday ads?**
Meta's Ad Library (facebook.com/ads/library) shows every active ad from any page. Reckon's agent checks your competitors' Ad Library pages every night, transcribes their video ads, tags the hook, angle and offer, and tracks which ads are gaining impressions. The skill reads that data.

**Should I use % off or $ off for Black Friday?**
Use the "rule of 100": for products under $100, say the discount as a percentage ("25% off"); over $100, say it in dollars ("$60 off"); for bundles, say the total saved. The skill applies this to your prices automatically.

**When should Black Friday ads launch in 2026?**
Black Friday is Friday 27 November 2026 and Cyber Monday is 30 November. Submit creative several days early (Meta reviews most ads within ~24 hours, but Q4 can be slower), run VIP / early-access ads the week before, and prepare new Cyber Monday and gifting creative in advance. The kit includes a dated launch calendar.

**How do I add a skill to Claude?**
Turn on code execution (Settings → Capabilities), then Customize → Skills → + → Upload a skill, and choose the ZIP. In Claude Code, copy the skill folder into `~/.claude/skills/`.

**Does it work without connecting my ad account?**
Yes. With competitors only, it builds the kit from their ads plus your website. Connecting your Meta ad account adds your own winning ads and the offers that worked for you.

## Notes

- Competitors publish no spend, so anything based on competitor ads is a **test**, not a sure winner. The kit labels every idea with its evidence.
- Not legal advice: check flagged claims (e.g. a "was" price) before running.

Built by [@div908](https://x.com/div908) · I'm building [Reckon](https://usereckon.ai/?utm_source=x_divyansh)
