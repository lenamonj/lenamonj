# Jeff Lenamon

I build loops that are hard to fool.

[Jeffy Loop](https://github.com/lenamonj/jeffy-loop) is a verification harness for Claude Code. It audits a repo, fixes one thing, proves the fix with a check that ran and passed, commits locally, and goes again until a fresh audit is clean and a second agent with no part in the run signs off. The model writes the patch. The loop decides whether to believe it. Maintainers at NVIDIA, Arm, Meta, Google, Apple, Microsoft, Netflix, Apache and others have merged its patches, each filed from a local clone. Every run is published, failures included.

What interests me in agentic AI is the exit condition. Anyone can make a model take another step. The work is deciding, with evidence, when it has done enough, and making that a decision the model cannot talk its way past.

Day job: Active total return portfolio manager in New York. The loop was built on nights and weekends and tested on other people's code.
