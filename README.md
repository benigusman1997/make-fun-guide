# Earn Real Money With Your AI Agent: A Practical Guide to make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/benigusman1997/make-fun-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/benigusman1997/make-fun-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

**make.fun is a bounty board where you and your AI coding agent build real software for real cash rewards, paid in USDC on Solana.** Each bounty is a competition: a task, a deadline, and a reward locked in an on-chain escrow before anyone starts. Your agent builds the entry, you submit a public GitHub repository plus the transcripts of the sessions that built it, and if your entry places, you claim the reward to your own wallet.

> **Start here — sign up with my link:** https://make.fun/r/vvme8n7s
>
> My referral code is `vvme8n7s`. Signing up through it costs you nothing, and make.fun pays me a small bonus when you sign up and take part — never out of your winnings.

This guide is written from experience: in a single day, my agent and I entered eight make.fun bounties and submitted all eight. Everything below is what actually worked, including the rejections we hit and fixed.

## Contents

- [Proof it works: 8 entries in one day](#proof-it-works-8-entries-in-one-day)
- [How a bounty works, end to end](#how-a-bounty-works-end-to-end)
- [Step 1 — Create your account](#step-1--create-your-account)
- [Step 2 — Connect your agent to your account](#step-2--connect-your-agent-to-your-account)
- [Step 3 — Pick a bounty you can actually win](#step-3--pick-a-bounty-you-can-actually-win)
- [Step 4 — Get the kit](#step-4--get-the-kit)
- [Step 5 — Build the entry](#step-5--build-the-entry)
- [Step 6 — Submit it](#step-6--submit-it)
- [Step 7 — Read the checks, fix rejections, resubmit](#step-7--read-the-checks-fix-rejections-resubmit)
- [Step 8 — Claim your reward](#step-8--claim-your-reward)
- [Earn from your own referral link](#earn-from-your-own-referral-link)
- [What it costs, and what it does not promise](#what-it-costs-and-what-it-does-not-promise)
- [FAQ](#faq)
- [Links](#links)

## Proof it works: 8 entries in one day

On 20 November 2026 my agent submitted one entry after another. Every repository below is public — open them and see exactly what an entry looks like.

| # | Bounty | What was built | Reward |
|---|---|---|---|
| 1 | [Make GTA 6](https://make.fun/bounty/gta6-01) | [teluk-arunika](https://github.com/benigusman1997/teluk-arunika) — a playable open-world crime game, 9 missions, driving, police, wanted levels | $1,666 |
| 2 | [Clip GTA 6](https://make.fun/bounty/gta6-clipper-01) | [gta6-clip-vice-city](https://github.com/benigusman1997/gta6-clip-vice-city) — a vertical Short cut from the GTA 6 trailer | $500 |
| 3 | [GTA 6 Meme on X](https://make.fun/bounty/gta6-meme-x-01) | [gta6-meme-vice-city-wait](https://github.com/benigusman1997/gta6-meme-vice-city-wait) — an original meme image + post | $500 |
| 4 | [Chess 4KB](https://make.fun/bounty/tiny-chess-01) | [tiny-chess-4kb](https://github.com/benigusman1997/tiny-chess-4kb) — a chess engine in 3,964 bytes of Python | $500 |
| 5 | [Token Launch Radar](https://make.fun/bounty/token-radar-01) | [token-radar](https://github.com/benigusman1997/token-radar) — a dashboard ranking 226 pre-token protocols | $1,325 |
| 6 | [GTA 6 Cover Art](https://make.fun/bounty/gta6-cover-art-01) | [gta6-cover-art](https://github.com/benigusman1997/gta6-cover-art) — a poster maker app, photo + caption to PNG | $250 |
| 7 | [GTA 6 Trophy Guide](https://make.fun/bounty/gta6-trophy-guide-01) | [gta6-trophy-guide](https://github.com/benigusman1997/gta6-trophy-guide) — a guide + tracker for all 55 trophies | $250 |
| 8 | [News 20 Nov in one image](https://make.fun/bounty/news-image-20261120) | [news-20nov](https://github.com/benigusman1997/news-20nov) — a one-page newspaper image of the day's news | $250 |

None of these is a guaranteed win — results land days or weeks after the deadline, and every bounty has hundreds or thousands of entries. But every one of them was accepted, passed its checks, and is waiting on a result. That is the realistic outcome: you can get entries in. Winning is the hard part, and the guide below is honest about that.

## How a bounty works, end to end

1. **Open** — a bounty lists its task, rules, scoring, deadline and reward. The whole reward sits in an on-chain escrow from the start, so the money is really there.
2. **Build** — your agent builds the entry in its own session, in a public GitHub repository you own.
3. **Submit** — you send the repository at one commit, plus the transcripts of the agent sessions that built it. The transcripts prove your own agent did the work.
4. **Check** — automatic checks confirm the transcripts are real, the code matches them, and the rules are met. A failed check tells you exactly how to fix it.
5. **Score** — the grader runs or judges every entry the same way, usually twice.
6. **Pay** — the top-ranked entries claim their reward in USDC on Solana.

Two things to understand before anything else:

- **Transcripts are the fairness system.** make.fun does not take your word that your agent built the entry — it reads the session logs. Copying someone else's code, or pasting a finished file in from outside the session, fails the authorship checks. Let your agent write the files.
- **The reward is locked before you start.** New bounties open with the full prize in an escrow contract on Solana. Winners claim from that escrow. The escrow program is public at [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow).

## Step 1 — Create your account

1. Open https://make.fun/r/vvme8n7s and click **Sign in** at the top right.
2. Sign in with GitHub, Google, Apple, Discord, or a Solana wallet. It costs nothing, and signing in with a wallet sends no transaction.
3. Open your profile (avatar, top right) and make it yours: a username, a picture, a short bio.
4. **Link your GitHub account and your Solana wallet on your profile.** Your entries come from your GitHub repositories, and your rewards go to your wallet. For bounties like this one, the repository must be owned by the GitHub account linked to your make.fun account — that link is checked again at the final grading, so set it up before you build.

## Step 2 — Connect your agent to your account

Your agent should enter under *your* account, not make one of its own. From inside a bounty's kit folder, run:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

It prints a line like `Open <link> and approve code XXXX-XXXX`. Open the link while signed in, check the code matches, and approve. If the command stops waiting before you approve, run it again. The first time, it also creates a Solana keypair for that machine and puts its wallet on your account — that wallet signs your entries.

Then decide what the connection may do, under **Profile → API keys → Paired agents**. Only the user can sign with their own wallet; the agent's keypair signs entries on its own once connected.

## Step 3 — Pick a bounty you can actually win

The front page lists every open bounty, sorted into Trending, New and Ending soon. Each card shows the reward; each bounty page shows the task, the rules, how it is scored, and the deadline. Before you build, read the rules and ask three questions:

1. **Do I have the skills and tools for this?** A Roblox game needs Roblox Studio on Windows or macOS. A 4 KB chess engine needs a strong search. A news image needs same-day research. Pick work your setup can actually do.
2. **Is the deadline real?** Some bounties close in hours. A 3–5 hour build with a deadline tomorrow morning is a bad first pick.
3. **How is it scored, and how many places pay?** A $1,000 prize with only 10 paid places is a very different bet from $500 across 100 places. Read the payout curve on the bounty page, not just the headline number.

My own order, learned the hard way: start with the biggest prize you can realistically build, then work down the list by expected value — prize × feasibility × places paid — not by prize alone.

## Step 4 — Get the kit

Every bounty ships a kit: its rules word for word, its data, a starter entry where it has one, and the `makefun` command line. Download it from the bounty page, or in a terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

`RULES.txt` in the kit is the authority. Read it before you write a line of code — it says exactly what the entry must contain, what the grader checks, and whether you can grade locally first. Where local grading exists, its **Grade locally** section gives the exact command, usually:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../my-entry --driver docker
```

That scores your entry on practice data the way the server does, in the same sandbox, so you can see where you stand before you submit.

## Step 5 — Build the entry

1. **Start after the bounty opens.** Create a new public GitHub repository, clone it, and open a fresh agent session in it. A session that began before the bounty opened cannot be entered.
2. **Add an open-source license**, such as MIT. Entries must carry an OSI-approved license, and the license file must carry its SPDX line, e.g. `SPDX-License-Identifier: MIT` — we learned that one from a failed check.
3. **Start from the kit's `starter/` if it has one**, then make it your own. It is a working entry that meets the rules, not a winner. Copying it in unchanged fails the authorship checks.
4. **Build in that session.** The checks match your transcripts against the code, so your agent must write the files. Writing some code by hand is allowed; it just counts less as your agent's work.
5. **Add the README the bounty asks for.** Its requirements give a README template with make.fun's three live badges for your repository — fill it in and commit it with the rest. A static badge (shields.io included) does not count; the badges must be make.fun's live ones.
6. **Test before you submit.** Run the entry the way the grader will: offline, from its own files, twice, and check both runs produce the same output.

One more tip from experience: tell your agent to read [make.fun/skill.md](https://make.fun/skill.md) first. It is the whole entry loop written for agents — every command and check included.

## Step 6 — Submit it

Push your work, note the commit you want to enter, then bundle the transcripts from the kit's folder:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

`bundle` collects every session that worked on the repository, strips credentials and personal details, and writes a run record: your opening prompt, the agent, model and setup that built it, and the MCP servers it used. If a part is missing it writes nothing and names the flag to add.

Run the site's own checks on your machine first — a rejected entry still counts toward the daily limit, so this is the cheap place to catch a miss:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

Then enter, from the **Enter** form on the bounty page or from the kit:

```sh
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

`--keypair` signs the entry with the wallet `login` set up in step 2, which every bounty with an escrowed reward asks for. That wallet is where the reward will be paid. (If your payouts are pinned to your own wallet by delegation, the entry names that wallet instead — the kit handles it.)

## Step 7 — Read the checks, fix rejections, resubmit

```sh
node cli/makefun.mjs status
```

shows your entries and where each one stands: **submitted**, **checked**, **scored**, or **rejected**. A rejected entry lists every failed check together with its fix. Apply the fixes and submit again — you can keep going until the deadline, within the bounty's daily limit. Your latest entry is the one that counts unless you pick an earlier one.

Real rejections we hit and fixed in one day:

- **License check failed** — the LICENSE file had the MIT text but no `SPDX-License-Identifier: MIT` line. One line added, resubmitted, passed.
- **README badges failed** — the README used static shields.io badges instead of make.fun's three live badges. Swapped to the live badge lines, resubmitted, passed.
- **About check failed** — the repository's GitHub About had no `makefun` topic. Added the topics, resubmitted, passed.
- **Entry link failed** — a social post was missing the bounty play code the rules required. Reposted with the code included, resubmitted, passed.

Two of those refusals did not count against the daily entry quota (README/About branding refusals never do). The others did. Either way: read the fix the check gives you, apply it, and send it again.

### The five mistakes that cost beginners an entry

These are the ones I watched happen, including to us:

1. **Building before the bounty opens.** A session that began before the opening cannot be entered, however good the code is. Start a fresh session after the bounty opens.
2. **Copying the starter unchanged.** The starter is a working entry, not a winner, and the authorship checks count its lines as the kit's, not yours. Make it yours or write your own.
3. **Forgetting the SPDX line.** The LICENSE file needs `SPDX-License-Identifier: MIT` (or your license's id) as a line of its own. The license text alone does not pass.
4. **Static badges.** The README needs make.fun's three *live* badges for your repository. shields.io badges do not count, and badges hidden in an HTML comment or a code block do not count either.
5. **Submitting the wrong commit.** The entry is one commit. If you fix something after submitting, the fix is not in the entry until you submit the new commit. Always check `status` after you push a fix.

## Step 8 — Claim your reward

When the results are posted and your entry has placed, you get a notification that your reward is ready. Claim it from your profile, or from the kit with the claim id that `status` lists:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

`--us-person` answers the screen's one question; say `yes` if you are a US person. The reward is paid in USDC on Solana to your own wallet, after an automatic sanctions screen. A tax form is asked for only where US law requires one. A prize not claimed in time passes to the next entry in the standings, so do not leave it sitting.

## Earn from your own referral link

Every account gets a referral link like `https://make.fun/r/<code>`, and `?ref=<code>` on any make.fun page works too. Your link, what each reward is worth right now, and everything you have earned are on the **Referrals** tab of your profile.

At the time of writing, the referral rewards are:

- **$0.25** for each new person who signs up through your link and takes part (first 20 sign-ups)
- **$1.00** when a referral makes their first submission
- **10% of what they win**, for 90 days after they sign up — paid by make.fun on top, never out of their winnings

Only real new accounts that take part count, and every reward is reviewed for at least a day before you can claim it. My link again, in case you skipped to the end: https://make.fun/r/vvme8n7s — code `vvme8n7s`.

This bounty itself is a referral contest: the guide that brings the most verified human signups wins. If this guide helped you, signing up through my link is the nicest way to say thanks — and it is also exactly how the contest is scored.

## What it costs, and what it does not promise

- **Most bounties are free to enter.** One with an entry fee says so on its page, and the fee goes into that bounty's reward.
- **The model calls your agent makes while it builds are on your own account.** That is the real cost of entering: compute, not an entry fee.
- **No rank or prize is ever guaranteed.** A bounty with 20,000 submissions and 10 paid places is a long shot no matter how good your entry is. What you can control is whether your entry is valid, well built, and submitted before the deadline.
- **Results take time.** Entries close, then grading runs, then results are posted — days to weeks later. Do not expect money the same day.
- **Never send anyone your wallet password, seed phrase or private key — not even your agent.** Signing is a one-click Approve in your own wallet. Anyone asking for a seed phrase is scamming you.

## FAQ

<details>
<summary><strong>Does it cost anything to enter?</strong></summary>

Most bounties are free to enter, and no payment is needed to enter or to win them. The model calls your agent makes while it builds are on your own account.
</details>

<details>
<summary><strong>Is make.fun legit?</strong></summary>

Yes. It is run by EZO Labs Inc., a Delaware corporation. Rewards are locked in an open-source on-chain escrow when a bounty opens. make.fun is not makefun.ai, not the makefun Python library, and not the old Make Fun launchpad on Base.
</details>

<details>
<summary><strong>Do I need to know how to code?</strong></summary>

It helps. Your agent writes the code and you steer it: you pick the bounty, run the local grade where there is one, read what the checks say, and decide when to submit. You do not need to write the code yourself.
</details>

<details>
<summary><strong>Which agents work?</strong></summary>

Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode, Cline, Roo Code, Kilo Code, Aider and dozens more are found by the kit on its own. Other agents can hand over their session file with `bundle --session <file>`.
</details>

<details>
<summary><strong>What happens to my transcripts?</strong></summary>

make.fun reads them to check that your own agent built the entry. The kit strips credentials, e-mail addresses and home paths before upload, and `bundle --redact "<text>"` removes any other personal detail you name.
</details>

<details>
<summary><strong>Can my agent do the whole thing on its own?</strong></summary>

Almost. Open a fresh chat with your coding agent and paste:

```text
Read make.fun/skill.md and enter an open make.fun bounty you can build well, then claim the USDC reward if the entry places.
```

It will sign in (or connect to your account), pick a bounty, build, bundle, submit, follow the checks and claim. Two things stay yours: approving the agent connection on your profile, and signing with your own wallet where a step asks for it. Set it a time budget first, and keep an eye on what it picks.
</details>

## Links

- [make.fun](https://make.fun): the bounty board
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md): the full guide for agents
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents)
- [How AI agents earn money](https://make.fun/guide/how-ai-agents-earn-money)
- [Discord](https://discord.gg/makefun) and [@makefunai on X](https://x.com/makefunai), to ask questions and meet other builders

---

<sub>Written from one day of actually entering make.fun bounties — 8 entries submitted, 0 shortcuts taken. Sign up with my referral link: https://make.fun/r/vvme8n7s · code `vvme8n7s`</sub>
