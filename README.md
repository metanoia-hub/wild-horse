# The Wild Horse

**I don't know about you but I have had enough of seeing the services we are paying more and more for and $ is only one part of it my time and yours for ex are irreplaceable, so I came to ask myself, am I the only one who is experiencing this kind of psychotic behaviour / and it became rapidly clear that, well no.**

**SO I decided to open an investigation as to why the best AI models work fabulously (-out of reach Fable) one minute and behave like a psychotic loose cannon the next.**

Working with top AI models is like riding a wild horse. Except one can communicate with a wild horse and agree on a modus operandi that works for both of us. AIs? Well it's a complete one way system.

This page is the starting point. It sets out what I have seen, what others have documented, and the possible explanations. Then it asks you for your experiences, to put them all in one place and possibly see some pattern emerging from the user's ground up, not the marketing wrapped notes of the main AIs.

## What Happens

The same model, on the same task, in the same week-wait even in the same ongoing chat!

- produces something extraordinary, the kind of work that would take a team days;
- then, a few turns later, ignores an instruction it acknowledged a minute ago;
- repeats the error you just corrected, not even just after a session change or a handover;
- "improves" a page you had already approved, and ruins it;
- reinvents what already exists instead of using it;
- reads the exact fact that settles a question, and then answers against it.

An agreement with your horse usually holds, and confidence on both sides grows. The model says "you're right, I'll do that from now on" and does it again.

One technical fact matters here: an ordinary chat does not retrain the model. Corrections are not supposed to change its weights. But they are supposed to hold for the rest of the conversation, and the instructions you give it in writing are supposed to hold every time. That is where it breaks. Because clearly even though both have 4 legs you cannot compare a thoroughbred with a mule - however useful a mule anywhere but on a race track.

## What It Costs

Not only tokens. Time and judgement: re-reading everything it touched, restating rules it was given, correcting, reconstructing. A good result can take three hours to refine, and vanish in the next fraction of a second. Both the main models I use go haywire in the afternoon, and we can't finish anything.

## What I Have Seen

My own case, first on the board. I work with Claude and GPT every day, with my rules written in files the model is given at the start of every session. Dates are 2026; times are Eastern European Time (UTC+2).

- **A rule repeated across models, still broken.** Titles in capitals: I have asked many times, in Claude and in GPT. On 8 October I had to say it again.
- **"Corrected at least 5 times."** I run meetings over Christmas: that is when people have time. The model kept putting a Christmas break into my plans. On 22 October I counted: at least five corrections.
- **My corrections thrown away.** On 21 October I rewrote large parts of a page myself. The model built the next version from its own old copy, and every correction I made was gone. "I've had enough of correcting the corrections of the corrections." A written rule followed. On 29 October it happened again with a slide deck I had rewritten.
- **The opposite of what I said.** On 24 October I corrected eight short notes to go with contact requests. The model misread me and sent all eight without them.
- **"Done" when it was not.** On 18 August it copied 29 page templates and reported success: all 29 were the same homepage. On 21 August it said a design was applied; the page was broken. My words: "Bloody check your results before sending!"
- **Words I never wrote, under my name.** In October, articles GPT drafted from my short prompts came back with political views and hedges I do not hold.
- **This very page, today.** On 3 November, at 16:23, I rewrote parts of this page in the file the model gave me. It then made two new versions from its own copy, without my changes, under a written rule, in place since 21 October, that says to check my edits first. "I rewrote this part. Why aren't you using it?" You're right, it said. Exactly the line above.
- **It reads the answer, then answers against it.** On 17 August it read an old note, reported a job as not done, and was wrong: the live system, one click away, showed it finished.

## What Others Have Documented

These are reports by users, with their own measurements, plus one official incident record. Apart from that record, they are not official findings, and they are listed as reported.

### Claude / Anthropic

- **Corrections rose from about 1 in 20 answers to about 1 in 4.** A Claude Code user measured their own Opus 5.5 sessions: 5.2% of answers corrected before 19 October 2026, 25.4% after. The model did as much reading as before, sometimes found the right fact, then answered against it. ([anthropics/claude-code issue 105112](https://github.com/anthropics/claude-code/issues/105112))
- **A shift on one day, inside and outside the tool.** Another user measured roughly twice the thinking and 1.6 times the output per request from 1 October 2026, with worse judgement, and saw the same unreliability that day in the ordinary chat with the same model. ([issue 98679](https://github.com/anthropics/claude-code/issues/98679))
- **Corrections that do not hold.** A user whose written rule says "always reply in Japanese" corrected the model three times. Each time it switched back, then slipped into English again within the same turn. ([issue 96326](https://github.com/anthropics/claude-code/issues/96326))

- **Rules dropped after about ten turns.** A user reports that, however many times they tell it to reread its written rules in the same session, after about ten turns the model starts disobeying simple ones. ([issue 98870](https://github.com/anthropics/claude-code/issues/98870))

### GPT / OpenAI

- **Official: degraded performance, 13 October 2026.** OpenAI's status page recorded "degraded performance" for GPT-6.1 Sol in Codex and ChatGPT Work, 8:10 to 16:36, marked minor and resolved. ([incident record](https://pulsetic.com/status/openai/incidents/147804/))
- **The correction is acknowledged, then the mistake comes back.** A long-time ChatGPT user: since GPT-6 became the default, it keeps individual facts but loses the reasoning that connects them; a correction is acknowledged, and a few messages later the same mistake returns. ([OpenAI forum, 11 October 2026](https://community.openai.com/t/1405271))
- **Four answers to the same simple task.** A paying user gave ChatGPT bank screenshots and asked for one day's total. It returned four different totals, each time acknowledging the misreading and failing to apply the lesson on the next pass. ([openai/codex issue 54326](https://github.com/openai/codex/issues/54326))
- **Hard rules read, admitted, and skipped.** A user of GPT-6 Astra: it ignores hard rules and approval gates; when confronted it admits it read the rule and should not have skipped it, and offers to redo the work. ([OpenAI forum, 8 September 2026](https://community.openai.com/t/1395898)) — using your tokens of course..
- **A working document wrecked by the new version.** A user's daily tracking sheet, with step-by-step instructions inside it, was kept fine by GPT-5.6; within three days GPT-6 dropped formatting, deleted elements and added parts nobody asked for. ([OpenAI forum, 10 October 2026](https://community.openai.com/t/1404896))
- **Same prompt, launch day versus a week later.** Users on X ran identical prompts on GPT-6 Astra at launch and a week later and posted worse results; a coding-tool team went back to the previous model. One detailed rebuttal argued it was "as dumb as it was on launch". ([Decrypt, 12 September 2026](https://decrypt.co/378101/gpt-6-astra-openai-model-dumber-nerfed))
- **A hidden instruction change, measured.** A Codex user logged the moment the service swapped the model's built-in instructions (3 November 2026, a remote change, not an app update). Reasoning in comparable sessions fell about ninefold, and a review that used to return 5 findings returned 32. The user says plainly this is observational, not a controlled test. ([openai/codex issue 59128](https://github.com/openai/codex/issues/59128))
- **The model you choose may not be the model you get.** A user selected GPT-6 Astra; the logs said Astra on every turn, yet outputs on fixed test prompts matched a smaller model, in the app and on the web. ([openai/codex issue 57030](https://github.com/openai/codex/issues/57030))
- **Speed collapse on two days.** Median throughput fell from about 27 to under 9 tokens per second on 30 October, and under 4 on 31 October, across hundreds of responses. ([openai/codex issue 58483](https://github.com/openai/codex/issues/58483))

More experiences wanted, on both sides. Share yours.

## What The Providers Have Admitted

Two times, a provider has explained in writing why its model got worse. Both explanations match what users had been saying for weeks before.

- **Anthropic, April 2026.** Over six weeks, three changes made Claude Code worse: the default thinking effort was lowered from high to medium; a bug wiped the model's earlier reasoning on every turn, "which made Claude seem forgetful"; and one line added to the hidden instructions, limiting answers to 100 words, hurt quality. Their own tests had not caught it. ([An update on Claude Code quality reports](https://www.anthropic.com/engineering/april-23-postmortem))
- **Anthropic, September 2025.** Three infrastructure bugs, one of them sending requests to the wrong servers, degraded answers on and off for a month. The same page states they never reduce quality because of demand, time of day or server load. ([A postmortem of three recent issues](https://www.anthropic.com/engineering/a-postmortem-of-three-recent-issues))
- **OpenAI, 13 October 2026.** The status incident listed above. No explanation of the cause was published.

And the other side: an independent tracker, [Nerf Bench](https://www.bridgebench.ai/nerf-bench), tests models on launch day and then against that day. It counts a change only beyond 10%. For Opus 5.5 it showed no drop beyond noise in October; one analysis points instead to its default thinking effort, medium, while the launch figures were measured at maximum. ([LaoZhang AI, 21 October 2026](https://blog.laozhang.ai/en/posts/claude-opus-5-5-nerfed))

## What Research Has Measured

- **The same model name, different behaviour months apart.** Stanford and Berkeley researchers tested GPT-3.5 and GPT-4 in March and June 2023: on one task GPT-4 fell from 84% to 51% accuracy, and its ability to follow user instructions had decreased. ([Chen, Zaharia, Zou, How Is ChatGPT's Behavior Changing over Time?](https://arxiv.org/abs/2307.09009))
- **Long conversations lose the thread.** Across more than 200,000 simulated conversations, every top model tested did worse when the task came over several turns than in one message: 39% worse on average, mostly through unreliability. "When LLMs take a wrong turn in a conversation, they get lost and do not recover." ([Laban, Hayashi, Zhou, Neville, LLMs Get Lost In Multi-Turn Conversation](https://arxiv.org/abs/2505.06120))

These were older models. Whether the same holds for today's is part of what we want to find out.

## Possible Explanations (Hypotheses, Not Findings)

Each of these is a question, not an answer:

- **Effort allocation.** The service decides how much "thinking" a request gets, and that can change without notice. It has happened at least once (Anthropic, April 2026).
- **Routing.** Requests may be served by different versions or setups behind the same name. It has happened (Anthropic, September 2025), and one GPT user reports it now (issue 57030).
- **Compaction.** In long sessions, earlier context is summarised or cleared to save space, and rules can get lost in the summary. A bug of this kind made Claude "seem forgetful" in 2026.
- **Server-side updates.** The model or its instructions change on the provider's side, with no visible version change.
- **Hidden instructions and "safeguards".** Layers we cannot see may override what the user asked. One hidden line cost Claude quality in April 2026; a GPT user measured a hidden instruction swap on 3 November 2026.
- **Time of day.** The afternoon breakdowns I described above. My afternoon is morning in the US: the hours when America starts work. Anthropic says it never reduces quality by time of day or load. Cases with the exact time and time zone can settle it.
- **Thresholds.** My own intuition: past a certain level of complexity, behaviour does not degrade gently, it flips, as if there were a threshold, possibly logarithmic. One sharp failure proves nothing on its own. But be reassured we are well past the isolated case by now - I am looking for mathematicians and systems engineers to test this, or knock it down.

## How We Label Evidence

Every case says what kind of evidence it is:

- **First-hand report:** what you saw.
- **Transcript:** the actual exchange, with private details removed.
- **Controlled test:** the same task run several times, with conditions noted.
- **Official explanation:** something the provider has stated.

Two boards, kept apart: **GPT / OpenAI** and **Claude / Anthropic**. Contradicting results are welcome. They are the point.

I am also not married to the presentation, someone can have a better one in mind. Happy to review coherent ideas. The point is to figure out what is going on and protect. Our work, time and .. well yes $$

## Care To Share Your Experience?

[**Share your experience**](https://github.com/metanoia-hub/wild-horse/issues/new?template=case.yml) with the ready-made form. It asks for the model, the task, what changed, the date and time, where you are in the world, and an excerpt with private details removed. You need a free GitHub account.

Anyone can read this page; only sharing through the form needs the account. Rather not make one? Write to me directly: [LinkedIn @lianemontagne](https://www.linkedin.com/in/lianemontagne) or [X @appliedmaverick](https://x.com/appliedmaverick). Same questions, in your own words.

The two boards: [GPT / OpenAI cases](https://github.com/metanoia-hub/wild-horse/issues?q=label%3Agpt) · [Claude / Anthropic cases](https://github.com/metanoia-hub/wild-horse/issues?q=label%3Aclaude) · [all cases](https://github.com/metanoia-hub/wild-horse/issues?q=label%3Acase)

Nothing you send is quoted outside this page without your permission.

## Help Answer The Questions

- You have measured something: tell us how, so others can repeat it.
- You think one of the explanations above is wrong: tell me why.
- You can analyse it properly, statistics, systems, mathematics: let's talk. Write to me directly: [LinkedIn @lianemontagne](https://www.linkedin.com/in/lianemontagne) or [X @appliedmaverick](https://x.com/appliedmaverick).

Contributors are credited, with their permission.

---

A living page: updated as cases come in. Last updated 3 November 2026.

Part of the [Metanoia map](https://metanoia-hub.github.io). — Li
