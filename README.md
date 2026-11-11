# Jeff Lenamon

I build loops that are hard to fool.

**[Jeffy Loop](https://github.com/lenamonj/jeffy-loop)** is a verification harness for Claude Code. It audits a repo, fixes one thing, proves the fix, commits, and goes again until a fresh audit is clean and a second agent signs off. The model writes the patch. The loop decides whether to believe it. Maintainers at NVIDIA, Meta, Google, Apple, Microsoft, Tesla, Uber, Netflix, Apache, Oracle, IBM, Cisco, Tencent, Square and others have merged its patches. Pointed at its own repository, it runs almost the whole [recursive self-improvement (RSI)](https://github.com/lenamonj/jeffy-loop/blob/main/docs/recursive-self-improvement.md) cycle on its own engine, with a human in the loop on every final decision.

**[housebroken](https://github.com/lenamonj/housebroken)** is the manners. Gates an agent must pass before it opens a pull request on someone else's repo: one finding, the smallest diff, a test that fails on their main, a body under 120 words, their AI policy read first, a second model's review. The gate refuses until every rule is met.

The hard problem in agentic AI is the exit condition. Anyone can make a model take another step.  
The work is deciding, with evidence, when it has done enough.
