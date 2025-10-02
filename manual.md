# Howdy, I’m Basil Crow 👋

Perhaps you know me from my work on [Jenkins](https://www.jenkins.io/).
More likely, you’re here as a colleague seeking guidance on how we can best work together.

This site, inspired by [Manual of Me](https://my.manualof.me/), serves as a guide for colleagues on how to collaborate with me most effectively.

## My name is pronounced …

- Basil Crow = BAZ-uhl KROH
- Basil: /ˈbæzəl/ rhymes with “dazzle” (not “BAY-zil”)
- Crow: /kroʊ/ like the bird

## If I came with a warning label, it would say …

> The more you explain your reasoning to me, the better we’ll get along.

The quickest way to win me over is to explain the reasoning behind your request.
Once I grasp a cogent argument, I’ll be fully on board and will make every effort to bring it to fruition.

On the other hand, the fastest way to create friction between us is to issue a request without reasoning, with reasoning that’s merely implied rather than explicitly stated, or with flawed reasoning.
Without any rationale, I may grow skeptical of the request itself (even if I still trust you overall), prompting me to probe for more details.
If your reasoning is implied, my interpretation of it might not align with your intent, inviting miscommunication.
If I perceive your reasoning as flawed, we may have a misunderstanding about the nature of the problem, or I may not be able to accommodate your request efficiently.

When I ask you to clarify your reasoning, it’s not a lack of trust; rather, it’s a desire to work as efficiently as possible and sidestep misunderstandings.
Articulating an implicit argument (or discussing it with someone else) often reveals subtle improvements to the thought process.
Establishing mutual understanding upfront is far more efficient than discovering gaps later, which could require rework.

Complex tasks involve countless smaller decisions.
When I fully understand the reasoning behind your original request, I can make those decisions confidently.
Without that clarity, or with only partial insight, they become far more challenging.

If you’re my manager, know that while you’re not obligated to justify your requests, providing explicit and cogent reasoning will make it dramatically easier for me to align quickly and execute them efficiently.

## My working hours are …

I’m a morning person.
I typically start work as soon as I’m fully awake and wrap up about eight hours later.
Because I often collaborate with Europe, my schedule skews toward early‑morning Pacific Time rather than late nights.

I aim to respond to pings within one business day.
If you haven’t heard back, I most likely missed the notification, so please feel free to follow up.

In return, I appreciate replies to my pings within one business day; otherwise the silence can be confusing and leaves me unsure whether to ping again.

## My preferred channels of communication are …

In general, I prefer:

- Written communication to verbal communication
- Public communication to private communication
- Group communication to one-on-one communication

This reflects my commitment to transparency and to writing as the primary medium for clear thinking.

I’ve long believed that sunlight is the best disinfectant, and my experience is that full transparency accelerates the discovery of facts that move the process forward.
When communication happens privately, it often leaves no durable record, making it harder to revisit or reverse decisions as circumstances change.

The reasoning behind my preference for written communication is captured well in:

- Amazon’s [six-page narrative memo](https://www.sixpagermemo.com/)
- Oxide’s [Request for Discussion (RFD) 1](https://rfd.shared.oxide.computer/rfd/0001)

In short, both pieces argue that narrative, written communication outperforms slides and unstructured conversation.
Well-crafted documents force clear thinking: laying out context, data, assumptions, and tradeoffs.
At Amazon, they’re read carefully (often silently at the start of a meeting) so everyone shares the same baseline.
The artifacts are durable and searchable, enabling accountability, asynchronous review, and broad participation beyond the room.
The result is fewer, better meetings and more transparent, higher-quality decisions.

There are important exceptions to this preference where privacy is the responsible default and public forums can feel unsafe.
These include conflict resolution, HR and people matters (performance reviews, health and safety, etc.), legal or compliance topics, customer or partner–confidential information, security incidents and investigations, and early drafts of incident postmortems or other sensitive retrospectives.
In these cases, I invert the order: start privately with the smallest necessary group to create psychological safety, surface facts, and protect dignity, all the while keeping a durable record.
As the situation stabilizes, and where confidentiality allows, I broaden visibility and publish a privacy-aware summary that emphasizes learning and decisions, not blame.
The aim is stewardship first, followed by as much transparency as circumstances responsibly permit.

## When you ask me for help …

Please start by explaining the high-level problem you’re trying to solve.
Frame the problem statement in terms of a specific symptom that affects users or the business, and avoid describing it in terms of your proposed solution.
If possible, include a minimal reproducible example (MRE) with steps to reproduce, expected results, and actual results.
If possible, also explain what you’ve tried so far to solve the problem.

Why ask for this? It helps avoid the [XY problem](https://xyproblem.info/).
In short, you might be asking about your attempted solution (Y) instead of the actual root issue (X).
If I can reproduce your problem, I’m far more likely to help you find a solution.
And if I can see that you’re actively taking steps to diagnose it, I know a fix is likely close at hand and that my time guiding you toward it will be well spent.

## When you open a pull request …

Please structure your PR description using my [pull request template](./pull_request_template.md) whenever possible.
It mirrors how I think and review: start with background and a crisp, user-facing problem (ideally with a minimal reproducible example), include any evaluation or root-cause analysis, describe the chosen solution and alternatives considered, note how you tested it, call out implementation nuances and anything reviewers should look at first, outline the deployment plan, and list future work.
If a section doesn’t apply, simply skip it, but note that the **Testing Done** section is mandatory rather than optional.
Using the template speeds reviews, reduces back-and-forth, and leaves a durable record for future readers.

## I prefer to receive feedback …

- In writing, so I can refer back to it, share it with my manager, and use it for performance reviews.
- For nuanced or sensitive topics (e.g., interpersonal conflicts), let’s discuss privately in person first, then follow up in writing so I have a record.
- Be candid and specific.
I know I have areas to improve, and I want to be aware of them so I can act on them.
- In small, regular doses: ideally microfeedback every few weeks.
Even brief check-ins help me track trends, confirm progress, and highlight good work.

## I work best when …

- My team’s culture has a high degree of transparency, accountability, and integrity.
- I have large blocks of uninterrupted time to focus, following the [maker’s schedule](https://www.paulgraham.com/makersschedule.html).
- The reasoning behind corporate strategies, organizational initiatives, team priorities, high-level deliverables, and low-level requests is cogent and clearly articulated.
- I am empowered to make decisions that are in the long-term interest of the business or project (or the justification for a short-term approach is clearly articulated).
- I am empowered to build or improve internal tools, debugging support, build systems, or documentation as part of my overall work on a subsystem.
- I am able to stand on the shoulders of giants in the open source movement and regularly contribute back upstream during working hours.
- I have access to a quiet space of my own with four walls, such as my home studio, a private office with a closing door, or (less ideally) a cubicle, rather than an open floor plan that requires headphones to concentrate or sharing a desk with another person.

## I add value to a team by …

- Holding myself and my colleagues to a high standard of intellectual integrity
- Unblocking teammates when they get stuck by debugging issues, reviewing unfamiliar code, or mentoring junior engineers
- Stepping back to consider the ideal solution (even when changing the status quo isn’t immediately practical)
- Equitably distributing both desirable and undesirable work across the team, including myself
- Having the courage to tackle old tickets, messy migrations, long-standing technical debt, and legacy code cleanup
- Building and improving internal tools, build systems, debugging tools, and documentation as part of my day-to-day work
- Optimizing globally by balancing the organization’s macro-level needs with the micro-level needs of specific teams and individuals
- Giving credit for everyone’s contributions: ideas, issue reports, code, documentation, and more
- Completing tasks end-to-end (not just throwing code over the wall) by ensuring end users and customers are up and running and satisfied with the outcome

## My philosophy regarding short-term workarounds is …

While I prefer long-term solutions, I can accept a short- to medium-term workaround if you first consider and articulate what the long-term solution would look like and justify why it’s prohibitively impractical at present.

Why require you to at least consider and articulate the long-term solution? Because my experience shows that this exercise often yields a key insight about the problem.
That insight can point to a more sustainable medium-term solution or suggest improvements to the short-term one.
Problems often have a range of possible solutions, each with increasing levels of effort, complexity, or pain.
There’s frequently a sweet spot that balances effort and reward, but finding it can be tricky.
Considering and articulating the long-term solution is one effective way to get the process started.

Why require a justification for why the long-term solution is prohibitively impractical? So the cost/benefit calculus can be reevaluated over time.
Long-term solutions can’t always be implemented immediately: economic or business constraints, scheduling issues, staffing limitations, and personal factors must all be balanced.
At the same time, short-term decisions often compound into long-term technical debt, and it’s not uncommon for that debt to eventually dwarf the original benefit of the short-term solution.
By documenting this calculus clearly, we enable future reevaluations grounded in transparent reasoning.
Circumstances can shift, potentially invalidating the original rationale and necessitating a pivot, such as prioritizing the long-term solution.

Why have a philosophy about this at all? Without a clear, shared strategy, miscommunications arise and decisions become inconsistent.
Worse, outcomes can be inequitable: new contributors may be asked to justify short-term workarounds while established ones may not be.
Articulating the philosophy up front sets consistent expectations, promotes fairness, and speeds up decision-making.

## What motivates me to come into work each day is …

- Collaborating with talented colleagues (both new hires and long-tenured teammates) and learning from people at all levels
- Solving interesting, meaningful problems
- Delivering value to both internal and external customers
- Growing and helping others grow

## Some other things you should know about me are …

- I prefer to keep third-party dependencies up to date and will proactively upgrade outdated tools and automate updates going forward.
- I use Linux as my primary operating system and prefer to develop locally rather than on a remote machine.
- I often use “we” when discussing work to refer to the team rather than centering myself.
- Please tag me on GitHub or Slack whenever you want me to read something. I’d rather receive a notification than have to search for references.

## My personal interests are …

I love typography and can happily nerd out over a well-designed typeface.
If you really want to get me excited, ask me about the [Knuth-Plass line-breaking algorithm](https://en.wikipedia.org/wiki/Knuth%E2%80%93Plass_line-breaking_algorithm) in TeX.
