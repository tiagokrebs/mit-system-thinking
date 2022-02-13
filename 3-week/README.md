# Tools for learning in a complex world

Here we discuss the dynamic behavior of a system, what happens along a timeline.

- System Dynamics Method for System Thinking
- Modeling complex dynamical systems
- Project management
    - Pathologies
        - Being late
        - Over budget
        - Fail to meet customer requirement
        - Low quality

## System Dynamics

One of the reasons for Systems Thinking and System Dynamics to exist is a phenomenon called `policy resistance`. The idea is when some policies are implemented something happens. Even when the policies are well-intentioned and put together to address the problems in hand they tend to not work very well. A common behavior is they work but only locally at one point, but later the problem come back in another place.

One example are the policies implemented to prevent forest fires on the United States. They were created long time ago and in fact reduce the occurrence of events since today. But there is an unintended consequence of the initial success of the policy. And that's fairly typical. Fires now are much bigger than before and last huge amount of times, making more dangerous for the firefighters and more difficult to deal with. This happens mainly for some reasons:
- Wildfire is a natural ecosystem of many forests
- Without fire the number of threes is largely bigger than before
- Climate change increases the temperature each year

So the increasing severity of fire is `a direct, but unintended consequence of the initial success of the policy`.

Off-topic: Projects are often LEW (Late Expensive Wrong).

How policy resistance arise?  
Fundamentally, it's due to the mismatch between the simplicity, the bias, the errors in our mental models, the complexity of the systems in which we're embedded.

Decision Making.  
```
                 ┌────────────┐
   ┌─────────────►            │
   │             │ Decisions  ├──────┐
   │             │            │      │
   │             └──▲─────────┘      │
┌──┴─────────┐      │                │
│            │      │                │
│  Goals     │  Feedback             │
│            │      │                │
└────────────┘      │     ┌──────────▼─┐
                    │     │ State of   │
                    └─────┤            │
                          │ the System │
                          └────────────┘
```

The mental model above is often incomplete because `we are embedded in a larger system`. This king pf thinking is one of the reasons for future problems arise. One can call the side effects but in reality there is no such thing as a side effect. There is no such thing. There are just effects. You make decisions. Your decisions have multiple effects.

```
                 ┌────────────┐
   ┌─────────────►            ├──────┬───────────────┐
   │             │ Decisions  ├──────┤               │
   │             │            │      │               │
   │             └──▲─────────┘      │       ┌───────▼────┐
┌──┴─────────┐      │                │       │ "Side      │
│            │      │                │       │    Effects"│
│  Goals     │ Feedback              │       │            │
│            │      │                │       └───────┬────┘
└────────────┘      │     ┌──────────▼─┐             │
                    │     │ State of   │             │
                    └─────┤            │             │
                          │ the System │◄────────────┘
                          └────────────┘
```

The thing is that there's all these other actors out there. In a corporate setting, those other actors include your colleagues, your subordinates, your bosses, your customers, your suppliers, the community in which you operate, the financial markets, plus the natural world from which you draw your raw materials and into which you spew your wastes.

All those other actors, all those other agents they have their own goals. And those goals are typically different from your goals. But we all share the same world.

```
CAUSAL LOOP DIAGRAM
                 ┌────────────┐
   ┌─────────────►            ├──────┬───────────────┐
   │             │ Decisions  ├──────┤               │
   │             │            │      │               │
   │             └──▲─────────┘      │       ┌───────▼────┐
┌──┴─────────┐      │                │       │ "Side      │
│            │      │                │       │    Effects"│
│  Goals     │ Feedback              │       │            │
│            │      │                │       └───────┬────┘
└────────────┘      │     ┌──────────▼─┐             │
                    │     │ State of   │             │
                    └─────┤            │             │
                          │ the System │◄────────────┘
                          └──┬──────▲──┘
                             │      │
                             │      │
                             │      │
       ┌────────────┐     ┌──▼──────┴──┐
       │Other agents│     │ Action of  │
       │   Goals    ├─────►   Others   │
       │            │     │            │
       └────────────┘     └────────────┘
```

What we can do is you can look at a picture like this and ask, are there any concepts, variables, actions that affect the system, but are not, in turn, affected by the system, that aren't part of the feedback structure?

The goals are not exogenous. They're part of the system structure.

Apps for creating causal loop diagrams: https://ncase.me/loopy/v1.1/

## System Dynamics on Project Management

Common projects problems:
- Late, over budget, fail to meet requirements
    - LEW - Late, Expensive and Wrong
- 90% syndrome
- Corner cutting and quality erosion
    - Accepting defects as normal
- The liar's club
- Firefighting
- Blaming people for process problems
    - Self-confirming attribution error

What do people say they do when their project gets off the rails?
- Use of overtime
    - Stay late, work on the weekends
- Hire more people
- Outsource
- Poach talent
    - From another projects
- Cutting corners/Speed up
- Cut testing, documentation, training, coaching
- Increase concurrency
- Slip deadline
- Cut scope
- Add scope to justify more time
- "Soft Launch"
- Re-sequence to release pieces
- ~~Kill the project~~
- ~~Kill the project manager~~
- ~~Find a scapegoat~~
- ~~Polish your resume~~
- **What we really need to do is we need to stop. We need to identify the root cause of the problems we're having and then improve our process.**

## Acceleration and Project Performance
- Newton, P. (2019) ‘Fighting the Physics of Human Nature: Acceleration Mental Model Effects on Project Schedule and Cost Performance’, 37th International Conference of the System Dynamics Society, pp. 1–16. Available at: https://proceedings.systemdynamics.org/2019/proceed/papers/P2017.pdf.
- Repenning, N. P. and Sterman, J. D. (2002) ‘Nobody ever gets credit for fixing problems that never happened: Creating and sustaining process improvement’, IEEE Engineering Management Review, 30(4), pp. 64–78. doi: 10.1109/EMR.2002.1167285. Available at https://web.mit.edu/nelsonr/www/Repenning=Sterman_CMR_su01_.pdf.

