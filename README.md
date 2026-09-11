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

Three jobs, one core, in layers — the client (that's you) orders a result, gets it back in plain words, and only you can lower or veto a rule; every rule an agent raises comes from work it actually did in the codebase. From 6.0.0 the core ships as one version. Adoption runs Grain first, day zero, soft law that never blocks; Yggdrasil next, as the core you keep long term; Horde last, through its one door, once a mission needs more hands than one agent. [Shared contracts between the three, one page.](https://krzysztofdudek.github.io/Yggdrasil/family-contracts)

## Yggdrasil

**[Say it once.](https://github.com/krzysztofdudek/Yggdrasil)** A rule you write holds in every session after, and the agent has to satisfy it before it moves on. Free local checks, keyless CI. It is the law: three jobs, one core, in layers, and this is the layer the other two stand on.

## Grain

**[From clone to graph.](https://github.com/krzysztofdudek/Grain)** Point it at a repository nobody has annotated and it writes the first architecture graph from the code and the history: the components you actually have, what depends on what, and the rules your own code already proves, each one carrying its evidence and the count of places that break it today. Yggdrasil accepts the proposal with one command. It's the survey of the terrain — install it day zero, before Yggdrasil's hard law is worth writing by hand.

## Horde

**[Hand it any mission, one door in.](https://github.com/krzysztofdudek/Horde)** Turns your coding agent into a director running a software house on Yggdrasil's law: zero standing roles, a worker per ticket refined onto the graph and given a tick, a one-shot architect who rules the whole plan once, and you as the client who orders the mission and can veto any rule it raises. It works the graph Yggdrasil holds, so the same standards ride a whole mission instead of one agent's context.

### Add-ons

**[Ratatoskr](https://github.com/krzysztofdudek/RatatoskrSkill)** — a translator between you and your codebase, so you follow what it's doing in plain words, not code. Inside Horde's loop it keeps your plain-language registry open at both ends of a mission.

**[Urd](https://github.com/krzysztofdudek/UrdSkill)** — consults the source of truth and asks instead of guessing. Inside Horde's loop it's the stop a worker hits before it guesses.

**[Researcher](https://github.com/krzysztofdudek/ResearcherSkill)** — one file, and your coding agent becomes a scientist: it designs experiments, discards what fails and keeps what works, 30+ overnight. The experiments behind the numbers I publish. Inside Horde's loop it runs the retrospective's measurement.
