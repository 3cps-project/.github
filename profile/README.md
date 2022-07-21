# 3-CPS: An Environment-Centric IR for Compiling Strict Higher-Order Languages

3-CPS is an NSF supported project on intermediate representations, analyses,
and compiler optimizations for strict higher-order programming languages.
At the center of our project lies an annotated CPS-based IR called 3-CPS.
The general annotation mechanism allows "facts" determined by program analysis
and "decisions" determined by optimization policies to be associated with the
program's representation. One of the most important classes of fact annotations
is explicit information about the environment structure required to manage bindings
of variables; this is designed to be closely connected to the run-time machine resources
needed for these bindings (heap records, stack frames and registers). This information is
key to mapping the source language efficiently onto these resources.
