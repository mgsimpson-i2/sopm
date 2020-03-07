---
description: "Oh heavens, it's COBIT 5."
---

# Levels of process management.

When talking about process management, I draw on a combination of
[Deming](https://en.wikipedia.org/wiki/W._Edwards_Deming) and \(with
apologies in advance\) the [COBIT v5
framework](https://en.wikipedia.org/wiki/COBIT). You can probably tell
that I find COBIT a little cumbersome and frustrating, but credit
where it's due, that's where a non-trivial part of my inspiration
originated.

In general, processes begin as very informal, and increase in
formality through the following stages:

*   **Level 0 - Incomplete \("We do it, and it doesn't work."\)**: An
    incomplete process is where you always have to begin, with
    piloting and prototyping. Experimentation is ongoing, and so the
    process is unstable, rapidly changing, and generally not ready for
    prime-time. This is also the least expensive time to quit if
    things don't seem to be working out -- before you spend a large
    amount of time and energy, if it's clear that there's a
    better/different way to do it.
	
*   **Level 1 - Performed \("We do it, and it seems to work."\)**:
    This stage is just a level zero process plus lots of
    **experience** -- we've done it enough times that we've smoothed
    most of the rough edges off, and it seems to be working okay. We
    haven't documented things, so we're probably doing it a little
    differently each time, and we're not really tracking success or
    failure at any level of detail. Lots of processes wind up living
    here by default.
	
*   **Level 2 - Managed \("We do it, and we make sure it works."\)**:
    Starting from level 1, we add **verification** and **tracking** --
    now we have some success/failure criteria we can use for outcome
    testing, and we're keeping a record of what went well and what
    went badly. If a particular iteration doesn't work, we at least
    know we need to keep trying until we get it right. We also will
    start to build a track record of which processes seem to be more
    stable, versus those that are still acting squirrelly, which are
    good indicators for whether or not we want to continue
    formalizing, or else wait until the process settles down some
    more.
	
*   **Level 3 - Established \("We do it the same way every time."\)**:
    Building on level 2, we add a formal **definition** for the
    process, including a checklist of all of the steps required to
    execute it. This opens up the possibility of **delegation** as
    well: can this process be assigned to operational staff, or
    possibly automated, and treated as a \(self-\)service request? For
    many processes, this is a reasonable level of maturity, and where
    we start to pay back the overhead we've incurred with increased
    efficiency and reliability.
	
*   **Level 4 - Predictable \("We're controlling the process."\)**:
    Beyond level 3 we enter the realm of lean process management,
    where we add **measurement** \(usually in the form of artifacts
    like [control charts](https://en.wikipedia.org/wiki/Control_chart)
    and [fishbone
    diagrams](https://en.wikipedia.org/wiki/Ishikawa_diagram)\). At
    this point, we are subjecting the process to analysis in an
    attempt to promote **understanding** of its performance
    parameters, with a focus on [isolating common vs specific
    causes](https://en.wikipedia.org/wiki/Common_cause_and_special_cause_%28statistics%29)
    of variation, and eliminating specific causes wherever
    possible. The ultimate goal is to bring the process under
    statistical control, so that we can have high predictability
    around its outcomes. This level incurs a significant amount of
    overhead to achieve, so it should be used only where there is the
    potential for a high return on that investment.
	
*   **Level 5 - Optimizing \("We're steadily making the process
    better."\)**: Once we have established statistical control of a
    process and eliminated specific-cause variation, we can begin the
    process of optimization: making incremental **improvement** to the
    process to decrease variation and increase desired output
    \(i.e. managing and minimizing common-cause variation, and
    increasing/decreasing target metrics as appropriate\). There is
    also the possibility of introducing true **innovation** --
    experimentation with large process changes to see if we can find
    an even better way to do things. This level of maturity is very
    expensive to maintain.

Note that it is incredibly common \(and usually very dangerous\) to
jump straight to trying to optimize a process \(Level 5\) before it
has been brought under statistical control \(while it's still at
Levels 1/2/3\). This can be highly problematic, because you're trying
to perform process improvement before you understand the common vs
specific causes of variation for the process in question: if you have
a little spare time, there's an [interesting online
simulator](http://www.symphonytech.com/funnelexp.htm) based on an old
Deming game called The Funnel Experiment, that demonstrates the
dangers of over-controlling a process that you don't yet understand.
