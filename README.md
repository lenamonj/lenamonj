# Jeff Lenamon

I build loops that are hard to fool.

[Jeffy Loop](https://github.com/lenamonj/jeffy-loop) is a verification harness for Claude Code. It audits a repo, fixes one thing, proves the fix with a check that ran and passed, commits locally, and goes again until a fresh audit is clean and a second agent with no part in the run signs off. The model writes the patch. The loop decides whether to believe it. Maintainers at NVIDIA, Arm, Meta, Tesla, Google, Apple, Microsoft, Netflix, Apache, Palo Alto Networks, Oracle, IBM, HashiCorp, Cisco, Uber, Square, Cloudflare, Dropbox, Tencent and others have merged its patches, each filed from a local clone. Every run is published, failures included.

[housebroken](https://github.com/lenamonj/housebroken) is the other half: manners for an agent calling at someone else's repository. It is a set of scripts that stand between the agent and the pull request it wants to open. One finding per pull request. The smallest diff, in the project's own style, with no comment added to their code. A test that fails on their main and passes with the patch, proven on a fresh clone. A body under 120 words, no tool footer. Their AI policy read before anything is filed, and an adversarial review by a different model before it leaves. The gate refuses until every rule is met, because a rule that only suggests is followed when remembered.

What interests me in agentic AI is the exit condition. Anyone can make a model take another step. The work is deciding, with evidence, when it has done enough, and making that a decision the model cannot talk its way past.

The two project paragraphs mirror each other on purpose: Jeffy decides whether to believe the patch, housebroken decides whether to let it out the door. The closing line now says "Both" since there are two tools.
