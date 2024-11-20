# ØComplexity Principles

This section outlines for every ØComplexity Principle the rationale and outlines
some important implications. 

```{attention} 
A good principle *SHOULD* cause some sort of pain when
applying. Fighting complexity is never simple or easy.
```

## Put People first!


```{admonition} Put people first! Or never ever forget the importance of humans and the human factor.
:class: tip, dropdown

Of course, we know that most systems SHOULD serve humans, and maintenance is also done by humans. 
But looking at digital systems sometimes, we wonder for what kind of humans these systems were created.

```


### Rationale 

Only humans experience the complexity. Humans are in charge
for creating and maintaining your business IT landscape. Most humans
like to be happy. Humans use technology. Explicit or implicit. Humans
know what real value is. Human emotions and fears SHOULD NOT be
neglected.For example, are you willing to put your life in hand of a machine
without any safety guarantee for your health? So whatever you are
designing, never forget it’s all about humans.

To prevent complexity in product development, you MUST prioritize people above all else. When people are happy, healthy, feel safe, and are genuinely motivated to work together, it becomes possible to solve complex problems without creating overly complex products. People are more important than what they produce. Positive, capable individuals will learn and grow. Ensure that learning is encouraged by creating a safe and supportive environment for it.

Creating great software solutions will never make everyone happy. However, if no real harm is done, a little discomfort in the name of changing the world SHOULD be acceptable. You cannot please everyone. Developing simpler and better solutions requires addressing the human factors inherent in any change process—such as friction, discussions, and emotions. So listen, stay open, act with kindness, and be prepared to repeat the process. Iterate. Always remember: all people matter.


### Implications

* Ensure that all environmental factors are conducive to enabling people to work on effective solutions. Organizational culture SHOULD prioritize the people working on solutions over everything else, including short- or long-term profits.
* Ensure that your business or system does not rely on the same small group of people.
* Invest in a process for seamless transfer of activities from one resource to another, if necessary. What may seem simple to you can be challenging and complex for others. How long would it take for a new group to maintain your business and IT systems?
* Humans often have poor intuition when it comes to nonlinear systems. Unfortunately, the entire world and all complex systems are characterized by nonlinear dynamic behavior.
* Most humans are very bad at predicting the future. So focus on a clear time scale that you can oversee. If your time scale is too far in the future, many unforeseen factors will impact the creation of your business or product. Keep complexity low by limiting the time horizon.
* Safety first. Aim to prevent disasters rather than optimize for a single simple solution. Lives matter.


## Only use what you understand


```{admonition} Only use new technologies, methods or concepts when you fully understand the why, what and how of them.
:class: tip, dropdown

Companies and humans will never create new systems with old ancient
technologies. So we tend to have a weak for all kind of new fancy IT
innovations. E.g. not many people have the skills to fully understand
blockchain cryptographic mathematics, but this does not mean people
often pretend to comprise what they are using.
```



### Rationale 
You SHOULD embrace and remain open to new technologies and management methods. However, you MUST understand the short- and long-term risks involved. Be aware that silver-bullet solutions to hard problems never appear overnight. Too often, IT technologies and new management methods overpromise and underdeliver. The result is frequently an even more complex environment without the promised advantages.


So first focus on the problem you want to solve and not on so called
tools that seems to provide a perfect solution. Don't follow the herd
and the hypes. Given a hard, complex problem, keep drilling until the
problem is absolutely clear to you and then start working on the
solution.

### Implications 

-   Experience, test on small scale what the new innovative method or
    technology really is. Do a small production pilot, with real
    customers. See if the new software technology is really x-times
    faster and cheaper for delivering functionality.
-   Develop a structural way for introducing new innovative techniques
    in your organization.
-   You MUST take risks, but you SHOULD have the capacity to handle
    large failures and disasters on this road. Only over several years
    you see effects of your risky decisions. Changes need time to have
    effect. You can not expect to see direct benefits from day zero.
    Often complexity will increase more when starting to resolve it.
    This since you can not stop your current complex business IT
    landscape overnight.

## Create a model of your solution

```{admonition} To solve problems and to prevent complexity you MUST make a model before starting building your solution.
:class: tip, dropdown

A good model always helps to find the real problem cause. If possible create a simple [Causal Loop Diagram](https://nocomplexity.com/causalloopdiagram/)

```


### Rationale 

Models can be created in many ways. However, you SHOULD choose to develop a model that is understandable not only to you but also to your stakeholders. Design a model that simulates all the effects you consider important. For example, you could create an architecture model, a security view, a privacy model, a threat model, a process model, a data model, an interaction model, a governance model, a cost model, or any other type of model that guides development in the desired direction.


### Implications

-   Creating good dynamic models for complex problems is hard. Since
    complexity is never only about software code, you MUST create a
    model that gives insights in the elements that matter for preventing
    complexity.
-   You SHOULD use good (FOSS) software to model your solution and run
    some typical use cases. Software simulation is easy, predictable and
    good models can be created very fast. Check [the list](https://nocomplexity.com/documents/reports/SimplifyIT.pdf) of good
    FOSS simulation tools. Or use mature open architecture tools, [check our list](https://nocomplexity.com/documents/arplaybook/introduction.html)!

* Never fall in love with your model. No model is perfect. There is only one way to determine if your model works: try it out in real-world scenarios! With software development, this is straightforward—there are no expensive material costs involved in creating software products. Simply discard the software if it doesn’t work as expected. Take full advantage of this unique property of software products. This is also why many complex electronic products are first created in software: it’s far faster and cheaper to test if they work!   


## Define specific criteria that are tangible to measure complexity

```{admonition} Define specific criteria that are tangible, realistic and measurable to check if your system is not getting too complex.
:class: tip, dropdown

Feedback based on facts is valuable. This also applies to managing complexity within your systems. Make the complexity data concrete. How many components are involved? How many interfaces are required? How many concurrent user requests will be served? Too often, tangible criteria for evaluating the complexity of a system are missing. Instead, conflicting opinions and perceptions dominate the discussion.

```



### Rationale 
Since complexity SHOULD be defined differently depending on
the specific context, you MUST define context specific rules to steer
your design process in order to avoid complexity for your situation.

### Implications

-   Define criteria like change cost, change time, repair time (MTTR),
    disaster recovery time needed, or number and competencies of
    resources required.
-   Create a process to prevent complexity growth due to adding new user
    requests.
-   A checklist for controlling complexity SHOULD be constructed using
    clear and simple explicit rules. Avoid opinion based and implicit
    arguments on your checklist whenever possible.

## Separation of concerns

```{admonition} Separation of concerns (SoC)
:class: tip, dropdown

Separation of concerns results in more degrees of freedom. Separation of concerns is crucial to the design of very complex systems, e.g.Internet. It is also practised within Systems Engineering, the art to make aircraft's, space stations and cars.

```


### Rationale 

Problem-solving is challenging. Making complex problems simple is even harder. Too often, we end up with overly complex solutions and IT systems to simple problems. 

By using the principle of separation of concerns, it is easier to understand how a system works and where improvements can be made. Separation of concerns means that, at times, you SHOULD strive to create autonomous Solution Building Blocks (SBBs). You can think of it as working toward a microservices architecture for your software building blocks. However, separation of concerns also applies to business domains. For example, do not mix external regulatory processes with internal customer value processes. When applying SoC, the separation of work across all agile methodologies becomes possible.



### Implications

-   Keep clear boundaries. Be very strict on the logical layers involved
    when solving a problem. Respect domains. This accounts for business
    domains and IT domains. Especially for software: you SHOULD NOT mix
    business logic with infrastructure logic. You SHOULD NOT expose
    business process logic in your IT components. Else easy reuse or
    creating changes becomes hard.
-   Use loosely coupled APIs. Validate why the principles of the
    [Twelve-Factor-App](https://12factor.net/) SHOULD NOT be applicable
    for you.
-   Solve problems on the level where there problem is caused. So if
    your business process sucks, you can never add enough components and
    nice looking user interfaces to make users happy.
-   Components can be replaced if better components are developed. So
    make sure that over time system building blocks will be replaced in
    your system.

Using this principle MUST BE done with care: From system science we know
that we SHOULD NOT neglect the crucial system thinking principles for a
system. So separating a system in subsystems (decomposition) can have
drawbacks. This since systems are formed from their emergent properties,
what means that the properties of the complete system is more than the
properties of the separate parts.

## Reduce all waste

```{admonition} Reduce all waste upfront in your design.
:class: tip, dropdown
The art of simple is to start simple and keep it simple!
```


### Rationale 
Remove all activities, documents, software code and even
people that do not deliver value. Call it zero waste. Spending too much
time, money or resources on hypothetic discussions will not give you a
working product faster. Start building. Go for execution. Start a real
life-pilot as fast as possible. Do not design everything in front. But
pay attention to on what functionality is minimally needed and define
what is maximally needed for maintenance and changes. Kill the rest to
prevent getting dead weight in your product and organization. To use a
buzz term, call it a minimal viable product (MVP).

Overhead in organizations lead to [Conway's
law](https://en.wikipedia.org/wiki/Conway%27s_law). The more people
involved directly in a design phase, the harder it gets to deliver a
simple system without all kind of strange concessions.

Especially for software design you SHOULD strive for KISS (Keep It
Simple, Stupid). Simple is hard enough already. Another trap with too
much stakeholders involved is the YAGNI trap. YAGNI means You aren't
going to Need it. Implement only functionality that have a direct
obvious purpose. Do not create functionality or integration logic for
later. Later will not come. Requirements for later will almost never fit
in your architecture without adjusting anyway. Creating functionality
for later use will often lead to unneeded features and over engineered
systems.

Of course you MUST make your architecture and design adaptive for
change. But this SHOULD NOT mean to create functionality or abstractions
that are not used directly.

### Implications 

-   Keep your organization and processes simple to avoid the risks of
    implementing needless complexity in software.
-   Only spend time on creating functionality when it is clear who will
    use it.

## Problems should be fixed through simple solutions

```{admonition} Problems SHOULD be fixed through simple solutions.
:class: tip, dropdown
Finding a simple fix for a problem too often results in over complicated solutions.
You SHOULD use system thinking to find the most simple and most effective fix. A simple solution is often very effective.
Use a proven method based from our [PSM collection](https://www.bm-support.org/problem-solving-methods/)
```


### Rationale 
Use simple solutions over complex ones. Unfortunately, designing a simple solution is much harder than creating a complex one. Senior engineers and domain experts with years of experience often develop a skewed perspective on what is simple and what is complex. To be clear: A simple solution is one where no configuration, maintenance, or control is required.

Elegantly simple designs don’t happen by chance. They’re the result of difficult decisions and discussions. Whether in the ideation, design, or testing phases of projects, all participants play a critical role in restraining the feature set to reduce the complexity of the resulting product.


Simple solutions don’t focus on features only, they focus also on
clarity.

Be aware that all problems can be solved in multiple ways. There is
never one a best solution. But there are bad solutions. So strive to
find multiple simple solutions and choose the one that fits you. Good
solutions needs to be so simple and transparent you forget how hard it
was to get it simple.

For serious [problem solving](https://nocomplexity.com/documents/reports/SimplifyIT.pdf) it is common to separate the problem in
various domains. Things go wrong when you are creating a solution that
you think is best for all domains involved.

Over engineering often occurs when for every sub process or sub function
the perfect solutions is implemented. Perfect solutions however do not
exist. Every solution fits on a typical use case and every solution has
negative side effects.

### Implications

-   Never stop directly when a solutions seems appropriate. Creating a
    simple solution takes far more time than a complex solution.
-   Be open for other solutions that also match, but have other strings
    attached.
-   Always evaluate if an available FOSS (Free and open-source software)
    solutions fits on your use case and within your context.

## Design for change

```{hint} Design for change.
```


### Rationale 
The only constant for every business is change. Dealing with
change SHOULD not be delayed by IT. So whatever the business process is
your IT systems must support: Make sure you can implement changes with
minimal effort and minimal cost.

### Implications 

-   Keep your business process simple, so changes can be easily
    incorporated.
-   Minimize the number of dependencies. This to minimize testing
    efforts and to minimize business risks when introducing new
    functionality.
-   Make use of open standards supported by FOSS software
    implementations. This so you do not have an vendor lock in when you
    do want it.
-   All basic tests SHOULD be automated when possible. Nowadays every
    serious business IT system must meet an enormous amount of explicit
    and implicit standards and requirements. E.g. for safety, security,
    privacy and of course error free is always nice to have.
    Implementing changes is not always hard. But validating that changes
    have no negative impact on other system part is. So to minimize
    business and human risks you SHOULD make a difference by automating
    testing whenever possible.

## Make sure you can manage IT!


```{hint} Make sure you can manage IT!
The management capacity MUST be able to manage the systems
that MUST be controlled.
```


### Rationale
Somewhere, there seems to be a magical number of people, systems, applications, or software (micro)services that can be managed. Management involves the control, change, and maintenance of systems, software, people, or even customers. Management can be done automatically or through human activities. However, it is obvious that when the number of objects that must be managed by one person increases, automation becomes the only solution.


### Implications

-   If management software, e.g. automatic CI/CD (Continuous Integration
    / Continuous Deployment) software is used, this software MUST be:
    Scalable, error-free and SHOULD be able to work on task in parallel.
-   Enough resources MUST be available to prevent chaos.

## Privacy by design


```{tip} 
**Privacy by design. Needs [Security-By-Design](https://nocomplexity.com/documents/securitybydesign/intro.html). Without security, no privacy!**
```
 

### Rationale 
Do not store private data if it is not needed and remove
private data when as soon as possible.

When using this principle you have less challenges to comply with legal
regulations (local, global). E.g. to comply with the EU General Data
Protection Regulation (GDPR). Limiting data collection prevents risks on
data leakage.

### Implications 

-   Visibility and transparency and traceability of data in your
    systems.
-   Respect for User Privacy.
-   Data Minimization.Collection of personally identifiable information
    SHOULD be kept to a strict minimum.

## Never over engineer

 
```{hint} **Never over engineer.**
```


### Rationale
We all like simple and easy solutions. However, when decomposing a problem, we often fall into the trap of trying to solve all the subproblems and then stop once we have a working system. However, real simplicity is hard to achieve. It takes time, iterations, and crucial feedback. The risk is that we over-engineer. The balance between working on a simple solution and over-engineering is hard to find. In general, when your system cannot be made any simpler, stop engineering. Maybe later you will see a way or opportunity for simplifying.

Over-engineering often occurs during optimization. Optimization SHOULD always be considered harmful. In particular, optimization often introduces complexity, as well as tighter coupling between components, layers, and a close coupling between business processes and IT systems. So stop engineering when it works, but never stop making it simpler—just be mindful of the trap of over-optimization.



### Implications

-   Prototype before polishing. First get it working, then simply,
    simplify and simplify.
