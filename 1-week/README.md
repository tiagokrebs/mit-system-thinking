# Foundation of systems thinking

- Structure: what we observe about a system, what is
- Function: based on the structure we can see what it does
- Emergence function: what is does give us the value of the system

## System Thinking
Come examples of systems:
- Natural environment
- Education
- Health care
- National Security

Systems thinking is simple thinking of things as systems.
Systems are things that have entities and relationships, elements and connections.

Our limited cognitive ability make systems look too complex. How systems thinking make it simple?

A system is a set of `interrelated entities` that `perform a function` whose functionality is `greater that the sum of its parts`.  
- Entities: modules, elements or chunks that are distinct an otherwise independent.  
- Relationship: to be a system these parts have to be interrelated.  
- Function: the interrelated parts perform a function.
- Emergence: this behavior is grater that can be delivered by the sum of the parts.

Systems thinking helps make complex things appear simple.

Example: coffee machine
- Composed by the water reservoir, the heat system and the coffee pot.
- The emergence is that we put water and coffee grain on one side and take a well-done coffee on another.

Why become a system thinker?
- We live amongst complex systems
- We need to make complex things feel simple
- We need to be problem solvers
- we need to understand emergence


## Emergence

The function of the systems there is **more powerful than the sum of the parts** is called Emergence.

Example:
An hourglass have funnel and sand as the entities. Put his together and a new function emerges, keeping time. Both entities have nothing to do with time until they are putting together in a system.

`Function` is the most powerful type of emergence.
- Run some machine learning code -> Image recognition
- Get on an elevetor -> Transportation

`Performance` is an emergent property of a system. Is also a powerful form of emergence.
- Transporting people -> The elevator move people under 30s
- Image recognition -> Recognize images of X pixels in 1s

There is also `non-functions attributes` we call emergences. We called `"ilities"`
- Reliability -> The measure of performance consistency
    - Breakdowns are loss of the attribute of reliability.
- Serviceability -> The measure if ease of repair
    - If you have to fix a breakdown serviceability is involved.  

Ilities occur in almost any system.
- Elevator -> Safety
- Image recognition -> Reliability

Another type of emergence is `emergency`. That is emergence that is destructive or undesirable.
- Plagues and droughts
- Explosions and, crashes


All types of systems have emergencies. We can have in:
- Mechanical systems
- Organizational systems
- Informational systems
- Natural systems

Emergence of function - the system does something that was never done before   
Emergence of performance – the system does something better than before  
Emergence is of the ilities or non-functional attributes – the system has more reliability  
Emergence of an emergency that we don’t want to happen  


## Function

`Function` are the activities, operations and transformations that cause or contribute to performance.
- Provides the actions
- What happens when a system operates
- Emergence occurs in the functional domain
    - When interrelated entities perform a `function` whose functionality is greater than the sum of the parts
    - The magic is in the function

Examples
- The function of circulatory system on the human body -> deliver oxygen to cell in the body
- The function of a work of art -> intrigue the viewer
- The function of a debit card -> to post a debt eletronically

A function describes a change created by the system. A function contain two parts:
- The change itself or the Process.
    - A pattern of transformation of the operand. The process creates, changes or destroys the operand.
    - You cannot touch a process, it's fleeting, it takes places along the time.
    - Where the change happens.
- The thing it is being changed or operated, the Operand.
    - A thing that exists, and whose states or attributes can be changed by a process.
    - Can be physical, like the art viewer.
    - Can be informational, a record of debit.
    - What has changed.

In a development team developing a new feature, `Develop` is the function and the `feature` is the operand.

The system function is related to the benefit delivered by the system.

All systems have a primary function, the necessary thing a system does, the primary function is usually clear from the designer's intent of from observation. There is of course the possibility that a system to have secondary functions.

Function describes the change created by the system.  The description of a function contains two parts: the change itself, which is what we call the process; and the thing that is changed or operated on, which we called the operand.

- Function is what a system does
- It is how systems create benefit 
- It consists of an operand that is changed, and a process that brings about the change 
- Emergence occurs in the functional domain


## Form

`Form` is what the system is. It's the physical or informational embodiment of the system,
- Material
- Configuration
- Text
- Instructions

What is implemented?
- Written
- Composed
- Manufactured
- Created

If it is some of the above it is probably Form.

Physical form can be:
- Mechanisms
- Molecules
- Facilities
- Circuits
- Building blocks
- Infrastructure

Informational Form can be:
- Poetry
- Literature
- Code
- Instructions

`Form` is the instrument of `function` and must be present for the function to be delivered.
- The function of a work of art -> intrigue the viewer -> The form is the piece of art
- The function of a debit card -> to post a debt eletronically -> The form is the car

`Form` is what the system is
- Can be captured in an image
- It's the instrument of function

`Function` is what the systems do
- It need to be captured in a movie


```
┌──────────────────┐
│  Form            │
│ ┌──────────────┐ │
│ │  Process     │ │
│ │  Operand     │ │
│ └──────────────┘ │
│                  │
└──────────────────┘
```

Form and Function are separate and complementary aspects of a system. But why Form is important if Emergence occur in the Function domain? The Form needs to be there in order to enable the function.

A robot that moves a payload has a function "to move" and an operand "payload" but the cost of this operation related to the robot, which is associated with the parts and the manufacture of it.

The benefit of a system is associated with the function, while the cost is largely identified with the form.

Value is benefit at cost.
```
      Value        -> Benefit  <-> Function
(Benefit at cost)  -> Cost     <-> Form
```

The benefit provided by team X
```
Quality product     -> Successful product  <-> Develop product
under budget        -> Salaries            <-> Team of people
```

- Form is the physical or informational embodiment of the system – what it IS
- Form is the instrument of function – what the system does
- Value is benefit at cost, benefit derives from function, cost is dependent on form
- Abstractions help make systems appear simple by hiding un-needed details


### Identifying Entities

After identify the system, its function, and form we can identify the entities, their function, and form too.

The relationship between the whole, the system, and the parts, the entities, is one of the most important aspects of system thinking. The system can be decomposed into the entities. And the entities can be composed into the whole system.

Decomposition. Breaking the problem up into smaller problems.
- Start by identifying the system of interest
- Then the important entities that compose the systems
- The entities are subdivision of the system. They are also known as subsystems, parts, modules, elements, etc.
- Both the systems and its entities have form and function

```
                                    System of Interest
                                   ┌──────────────────┐
                                   │  Form            │
                                   │ ┌──────────────┐ │
                      ┌────────────┤ │  Process     │ ├─────────────┐
                      │            │ │  Operand     │ │             │
                      │            │ └──────────────┘ │             │
                      │            │                  │             │
                      │            └─────────┬────────┘             │
                      │                      │                      │
                      │                      │                      │
            ┌─────────▼────────┐   ┌─────────▼────────┐   ┌─────────▼────────┐
            │  Form            │   │  Form            │   │  Form            │
            │ ┌──────────────┐ │   │ ┌──────────────┐ │   │ ┌──────────────┐ │
Subdivision │ │  Process     │ │   │ │  Process     │ │   │ │  Process     │ │
            │ │  Operand     │ │   │ │  Operand     │ │   │ │  Operand     │ │
            │ └──────────────┘ │   │ └──────────────┘ │   │ └──────────────┘ │
            │                  │   │                  │   │                  │
            └──────────────────┘   └──────────────────┘   └──────────────────┘
                                      Subsystem
                                      Part
                                      Module
                                      Element
```

The relationships between the parts flows two ways. These flows can be applied to organizational, physical and informational systems.
Decomposition:
- Top down
- Divide the system into smaller entities  
Composition
- Bottom up
- The system is defined composing the entities or modules

The entities of a system are often represented in the hierarchy. The system has function and form. Each of the entities of the system will also be a system and have function and form. Sometimes, the hierarchy reflects on form. Some entities just have a higher rank or position.

One of the things that we work on with people is how do you build an understanding of what are the modules, or subsystems, or components, whatever you want to call them. How do you limit the size of those components, so that they're within the bounds of human understanding? They have to be small enough so a human or a team of humans can understand the functioning of that component, individually.

Example
```
                 Graphical Interface
                        ┌─────┐
        ┌───────────────┤     ├───────────────┐
        │               └──┬──┘               │
        │    Business      │                  │
     ┌──▼──┐   Logic    ┌──▼──┐            ┌──▼──┐
   ┌─┤     ├─┐        ┌─┤     ├─┐        ┌─┤     ├─┐
   │ └─────┘ │        │ └─────┘ │        │ └─────┘ │
   │         │        │         │ Utilities        │
┌──▼──┐   ┌──▼──┐  ┌──▼──┐   ┌──▼──┐  ┌──◄──┐   ┌──▼──┐
│     │   │     │  │     │   │     │  │     │   │     │
└─────┘   └─────┘  └─────┘   └─────┘  └─────┘   └─────┘
```

Structuring a system that way we limit the extent to which bad emergence happens in a system.

- A system can be decomposed into entities, and entities can be composed into a system. 
- This decomposition and composition is one of our most powerful tools in managing complex systems. 
- Every system is part of a larger system and can be decomposed into smaller systems. 
- Every system and entity can be thought of as an abstraction with form and function. 
- Systems and entities can be placed in a hierarchy based on issues of form or function. 


## Systems Boundaries

Boundary establishes the entities inside the system (inside the boundary) and the ones outside the system (context). Inside the boundaries the entities could include entities that are highly interwoven into the system, entities essential to the function of the system, or entities supplied or controlled by you. 
- Highly interwoven
- Essential to the function
- Controlled by us

The complexity of a system scale with number.
- Find the minimum number of essential entities
- From 5 to 9 (7+-2)
- 7+-2: acknowledged cognitive limit

The boundary is very important because what's inside and what I care about is the scope of the work. What's outside are the things that are going to impact my work.
```
                    Boundary
              ┌───────────────────────────┐
              │                           │
              │ ┌────────┐                │
              │ │        │                │
Context       │ │        │                │
  ┌────────┐  │ └────────┘    ┌────────┐  │
  │        │  │               │        │  │
  │        │  │               │        │  │
  └────────┘  │ ┌────────┐    └────────┘  │
              │ │        │                │
              │ │        │                │
              │ └────────┘                │
              │                           │
              └───────────────────────────┘
```
- Boundary can change and should be checked from time to time

To better understand how to refine the entities and boundaries we can separate them in two categories, Holism and Focus.
- Holism
    - Thinking as widely as is reasonable to consider what should be in the system
    - Give us confidence that we're not missing the unknown
    - How each of these components contributes on the large system (eg: performance)
- Focus 
    - Focus in what is truly important
    - It may change from day to day depending on the issues we're considering
    - Try to have a number from 5 to 7 entities
    - Just focus on what the contribution of the individual components are

Systems have tree main entities categories
- Entities in the system
- Entities there are not in the system but are in the context
    - Emerge function and performance
- Entities temporariliy supress
  

Finaly
- Identify the entities by decomposition or composition 
- Try to limit the number of entities to 7 +/- 2 
- Use holistic thinking to identify all reasonable entities of a system 
- Focus on the minimum set of essential entities 
- Draw a boundary that divides the system from its context 

Remember that system thinking distinguishes three categories of entities: the entities `in the system`, the ones not in the system but are `in the context`, and those that are temporarily `suppressed`.

Example:  
The perspective of the rider who wants to safely and reliably ride to work in 15 minutes.
Entities: bike wells, bike seat, bike frame, ground, rider (you), helmet, traffic signals, weather, companion rider, GPS, water bottle, cars

- The entities that span all three criteria (essential to function delivery, integral and highly interwoven into the system, and developed/supplied by you or a supplier) are all part of the system.  
- The entities that are essential to function delivery but are not part of the bicycle (e.g., rider, ground, helmet, and traffic signals) provide context to the system.  
- The remaining are temporarily suppressed.

These criteria should be taken as guidelines for deciding where to place entities, and not as absolute truths. For example, you could argue that the cars on the road are as important to safety as the traffic signals. We made this placement because the traffic signals are part of nominal operations, while the cars only pose a hazard when their driver makes an error. But it is a close call and relies on your judgement. You should also keep in mind the 7 +/-2 guidance.

With all of this we completed two of the four tasks of the systems thinking.
1. Identify the system, its function, and form
2. Identify the entities, their function, and form  
    2.1 Focus on the minimum number of essential entities  
    2.2 Draw a boundary to divide the system from its context


## Function Relationships

The third step is to identify the relationships amongst the entities, their form and function. A system becomes a system because the relationships otherwise, it's just a collection of independent entities.

- Relationship Form
    - How things are connected
    - Structure
        - Exists
        - Is implemented
        - It is stable
        - Can be photographed
    - What the relationships are
    - Enables interaction, is the instrument of interaction
    - Types of structures
        - Connections
        - Electrical wire
        - Fluidic pipes
        - Data buses
        - Mechanical connectors
        - Location. Eg: people can talk when they are in the same room
        - Sequence. Eg: In software or in a book
    - Where is a interaction there is an element of structure
    - When a relationship of the system cross the system boundary, these interface have both form and function.
    - 
- Relationship Function
    - How things interact
        - What the relationships do
    - Remember emergence occurs in the functional domain
    - The interaction happen, it takes place along a timeline
    - Types of interactions
        - One entity affects another. Eg: a wheel moves the bike 
        - An operand is passed from one entity for another. Eg: a package from a manufacturer for a costumer trough a distributor
        - An operand is share amongst entities. Eg: a design document between two teams working in the same project
        - Are represented by unidirectional or bidirectional arrows
        - Relationships can occur within the context or between entities that are in the system boundary and outside
        - All these functional relationships are interactions that allow the overall system function to emerge.



Function Relationships
- A group of entities become a system when there are relationships 
- Relationships have form and function – emergence happens as a direct result of functional relationships 
- Functional relationships are inter-actions – one entity affects another, an operand is passed or an operand is shared 
- Functional relationships can be among the entities within the system, or with entities outside the system in the context 

Formal Relationships
- Where there is a functional relationships (an interaction) there is usually a formal relationship (the structure) 
- The functional interaction is usually enabled by a formal relationships 
- Structure can include all kinds of connections, as well as location and sequence. 
- When structure and interaction cross a system boundary, careful system thinking is required 

With this we conclude tree of the four tasks in system thinking.
1. Identify the system, its function, and form
2. Identify the entities, their function and form
3. Identify the relationships, their relation, and form

