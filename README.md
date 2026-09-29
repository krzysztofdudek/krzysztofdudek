<div align="center">

### Hey, I'm Chris.

I build with AI agents and prove their work. So AI-written code can ship to production with confidence.

Yggdrasil came from watching agents say "done" when they're not even close.

<br/>

<a href="https://discord.gg/SZTbgsH8Wm">
  <img src="yggdrasil.svg" alt="Yggdrasil" width="80" />
</a>

<br/><br/>

<a href="https://chrisdudek.com"><img src="https://img.shields.io/badge/Website-chrisdudek.com-0ea5e9" alt="Website" /></a>
<a href="https://www.linkedin.com/in/krzysztofdudek"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://x.com/krzysztofdudekx"><img src="https://img.shields.io/badge/X-Follow-000000?logo=x&logoColor=white" alt="X" /></a>
<a href="https://substack.com/@krzysztofdudek"><img src="https://img.shields.io/badge/Substack-Subscribe-FF6719?logo=substack&logoColor=white" alt="Substack" /></a>
<a href="https://www.reddit.com/user/krzysztofdudek/"><img src="https://img.shields.io/badge/Reddit-Profile-FF4500?logo=reddit&logoColor=white" alt="Reddit" /></a>

</div>

---

Where this is going: from proving AI-written code is right before it ships, to proving it actually worked once it's live. Better prompts don't hold, and agents won't enforce correctness on their own.

Behind it: ten years of production distributed systems (.NET, Kafka, Kubernetes), banking and betting scale. That is where my bar for enterprise quality comes from, and why a green test alone has never convinced me.

Jarl is the loop. Yggdrasil is the law. Grain is the survey. Horde plans a mission onto the law before anyone writes, lands every change through a gate no agent can argue with, and runs on Jarl's loop with Grain in the architect's hands. The four ship under one version number, built and tested against each other, and Yggdrasil, Grain and Jarl each work alone. You are the client: you order a result, get it back in plain words, and only you can lower or veto a rule. An agent raises law inside one component on its own; law that reaches a whole type of code runs as advice until you admit it, in one batch, when the work closes. [The core's shared contracts, on one page.](https://krzysztofdudek.github.io/Yggdrasil/family-contracts)

Start where it hurts. There is no ladder to climb first.

## Jarl

**[The loop.](https://github.com/krzysztofdudek/JarlSkill)** For a branch with more issues than one agent can hold in its head. Every finding becomes an issue, each issue gets one worker in its own worktree, and nothing closes without evidence and a fresh reviewer's word. Where your repository has a check, the check decides what lands. Without one, the loop lands on the reviewers' testimony and tells you so.

## Yggdrasil

**[Say it once.](https://github.com/krzysztofdudek/Yggdrasil)** A rule you write holds in every session after, and the agent has to satisfy it before it moves on. Free local checks, keyless CI. It is the law: the architecture graph, the rules over it, and the log of why each one exists.

## Grain

**[The conventions nobody wrote down.](https://github.com/krzysztofdudek/Grain)** Point it at a repository nobody has annotated and it writes the first architecture graph from the code and the history: the components you actually have, what depends on what, and the rules your own code already keeps, each with the count of places that break it today. Yggdrasil accepts the proposal with one command. Grain measures and never blocks. It earns its keep the moment you are about to write law.

## Horde

**[The mission on the law.](https://github.com/krzysztofdudek/Horde)** For a task too big for one head to plan up front, in a repository that already has law. A one-shot architect plans the whole mission onto Yggdrasil's graph, measuring with Grain. A worker takes each ticket in its own worktree, every change lands through a nine-item gate, and what the mission learned becomes law. Its record is a Jarl loop. You order the mission, and only you can lower or veto a rule it raises. I have not yet measured how much Horde adds over a Jarl loop with a check on the same work, so I quote no number for it.

### Add-ons

Four add-ons attach to the agent, not to the graph. Each works alone and keeps its own version number.

**[Ratatoskr](https://github.com/krzysztofdudek/RatatoskrSkill)**: a translator between you and your codebase, so you follow what it's doing in plain words, not code. Inside Horde's loop it keeps your plain-language registry open at both ends of a mission.

**[Urd](https://github.com/krzysztofdudek/UrdSkill)**: consults the source of truth and asks instead of guessing. Inside Horde's loop it's the stop a worker hits before it guesses.

**[Researcher](https://github.com/krzysztofdudek/ResearcherSkill)**: one file, and your coding agent becomes a scientist. It designs experiments, discards what fails and keeps what works, 30+ overnight. The experiments behind the numbers I publish. Inside Horde's loop it runs the retrospective's measurement.

**[Skald](https://github.com/krzysztofdudek/SkaldSkill)**: films of your real running software, made by your coding agent. It records the live product, never a rebuilt one, and every number and claim on screen traces back to the product's own logs. Horde does not call it.
