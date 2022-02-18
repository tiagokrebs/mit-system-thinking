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

## Project management simulator

How to register as an instructor for the MIT simulator?

Tree scenarios:
- Construction
- Hardware <--
- Software

How the project works.

- We're going to choose to staff
    - The simulated HR is going to create the vacancies, interview candidates and, onboard new hires
    - This process take time
    - New hires can be inexperienced
        - Not productive
        - Deliver less quality
        - Commit more errors
        - Take time from experience people of the team
    - People gain experience over time
    - People quit, retire, leave the team
    - Attrition increases when the staff is burned out
        - Fatigued
        - Over stressed 
        - Under too much pressure

Error Generation and Error Discovery
- No one is perfect. Even experienced people make mistakes
- Will be affected primarily by
    - Schedule pressure
    - Fatigue
    - More inexperienced workers
- Can be discovered within one phase of the project
- Can be discovered by the next phase (downstream))
    - Return to the last phase (upstream)
- Is possible to not be discovered in any phase and go for release

Learning strategies for simulators
- Play many games quickly
- Try many strategies
    - Deliberately fail (stress tests)
- Be a good scientist
    - Design, execute & evaluate experiments
- Reflect on your strategy and results

The objective here is to learn, not to win.

## Play the hardware project management simulation
### Experimenting
Strategy 2: Not meet expectations
- Overlap phase A and B 4 weeks
- Work force A: 70
- Work force B: 40
- Progress pressure: -3
- Quality pressure: +3
- 20% add proposed new features
- 10% reduce project scope
- 10% accelerate work

Strategy 1: Excellent
- Overlap phase A and B 4 weeks
- Work force A: 70
- Work force B: 40
- Progress pressure: -3
- Quality pressure: +3
- 0% add proposed new features
- 0% reduce project scope
- 0% accelerate work

### playing
Strategy 1
- What strategy you intend to try (i.e., settings on the control panel)
    - Maintain pressure and quality. Every time a new set of features appear attend to 25% of them and reduce the scope removing the other 10% of the features. Increase the acceleration up to 10% when the task output is below expected. Start with a workforce of 75 and 40 for phases A and B since the beginning.
- What you expect to happen (i.e., the expected behavior of output measures)
    - The project should run normally until the first set of new features is requested and 25% is accepted. Reducing the previous scope and accelerating a bit in both occasion this situation happen should be enough to deliver the project as expected. 
- What happened (i.e., behavior over time)
    - In phase A the required work as increasing a little by each week but seems to be controlled. When phase B the deadline immediately grows about 3 weeks but after some weeks starts to reduce again, as the required output. All seems to be good but the project doesn't meet the expectations, it seems good enough for me though.
- Why you think it happened (i.e., causes and effects)
    - There was a fair amount of defects discovered and rework on phase B. As a result, a peak in the material cost and work hours happen.


Strategy 2
- What strategy you intend to try (i.e., settings on the control panel)
    - To believe that the both A and B phases were well planned and have a little more attention on quality at the same time there is less pressure on the progress. That is to say, none proposed new features will be accepted, there will not be scope reduction not accelerated work. On top of that an overlap of 4 weeks will be used between phases. Phase A will have 70 people and B 40 people available.

- What you expect to happen (i.e., the expected behavior of output measures)
    - With more quality and less pressure since the beginning features will have more time to be more researched and refined, this should make the adding of new features smaller or even not needed. At the same time, less pressure on the progress could result in some delay in the estimated completion but through this, maybe we will have less rework and less stress on the team.

- What happened (i.e., behavior over time)
    - As in the first strategy the required work keep increasing a little each week on phase A. In the overlap between phases the estimated completion once again jump to 58 weeks, but during the rest of phase B stared to reduce again. Close to the end phase B need to be increased until the week 52 to finish the project.

- Why you think it happened (i.e., causes and effects)
    - Rework was lower on phase B this time. And even without any project acceleration were bigger peaks of working hours on both phases, but this time with less quits. Looking for the results the lifetime cost of defects was way bigger than the goal (298%) but market share and lifetime profit were approximately 30% bigger. 

The goal is to learn how each strategy influences the performance of the project so that you deliver the new hardware product on time and within your budget while delivering a high-quality project that will delight the customer.

