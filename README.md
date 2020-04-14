# agile-robots
A summery of mindsets, processes and methods in knowledge intense development processes like robotics. 

> No process, mindset and method will fit to your unique working enviroment and team without a common adaption.

## Mindsets and Experiences 
### Conway's law
`Any organization that designs a system (defined broadly) will produce a design whose structure is a copy of the organization's communication structure.` (1967) [1](https://en.wikipedia.org/wiki/Conway%27s_law)


### The Mythical Man-Month or Brooks's law

`Adding manpower to a late software project makes it later.` (1975)

![the mythical man-month](img/mythical_man_month.png)

* The modern practices of continuous integration, test-driven development, and iterative development significantly reduce the inter-developer communication overhead, and thus allow for better scalability.

* The design pattern defines the rules that the programmers follow, simplifies communication through the use of a standard language, and provides consistency and scalability. Finally, good segmentation helps by minimizing the communication overhead between team members

[2](https://en.wikipedia.org/wiki/The_Mythical_Man-Month)

### Unix Philosophy

Concepts of modularity and reusability into software engineering practice, spawning a "software tools" movement. (1978)

The Unix philosophy favors composability as opposed to monolithic design:
* Make each program do one thing well. To do a new job, build afresh rather than complicate old programs by adding new "features".
* Expect the output of every program to become the input to another, as yet unknown, program. Don't clutter output with extraneous information. Avoid stringently columnar or binary input formats. Don't insist on interactive input.
* Design and build software, even operating systems, to be tried early, ideally within weeks. Don't hesitate to throw away the clumsy parts and rebuild them.
* Use tools in preference to unskilled help to lighten a programming task, even if you have to detour to build the tools and expect to throw some of them out after you've finished using them.

[3](https://en.wikipedia.org/wiki/Unix_philosophy)

### Agile Manifesto  

Representatives from Extreme Programming, SCRUM, DSDM, Adaptive Software Development, Crystal, Feature-Driven Development, Pragmatic Programming, and others sympathetic to the need for an alternative to documentation driven, heavyweight software development processes convened. (2001)
                                    
> Individuals and interactions over processes and tools                          
> Working software over comprehensive documentation                              
> Customer collaboration over contract negotiation                            
> Responding to change over following a plan.                                      

**My personal favourites of the 12 principles:**

* Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done.
* Working software is the primary measure of progress.
* Simplicity, the art of maximizing the amount of work not done, is essential.
* The best architectures, requirements, and designs emerge from self-organizing teams.
* At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly.

[4](https://agilemanifesto.org/principles.html)

### About reinventing the wheel

ROS allows you to stop reinventing the wheel. Reinventing the wheel is one of the main killers for new innovative applications. The ROS goal is to provide a standard for robotics software development, that you can use on any robot. (2007)

<img src="img/reinvent_the_wheel.jpg" height="50%" width="50%" >


## Methods
### Waterfall
The waterfall model is a breakdown of project activities into linear sequential phases, where each phase depends on the deliverables of the previous one and corresponds to a specialisation of tasks

<img src="img/Waterfall_model_.svg" height="50%" width="50%" >

* Scales great if customer, management and developers have a lot experinces with the product.
* Useful for projects where changes cost a lot of resources and time 


### System Engineering and the V-Model

The V-model summarizes the main steps to be taken in conjunction with the corresponding deliverables within computerized system validation framework, or project life cycle development. It describes the activities to be performed and the results that have to be produced during product development.

The V models ensures two major aspacts of your development with traceability:
* Are you building it right? **Validation:** The assurance that a product, service, or system meets the needs of the customer and other identified stakeholders. It often involves acceptance and suitability with external customers. Contrast with verification.

* Are you building the right thing? **Verification:**  The evaluation of whether or not a product, service, or system complies with a regulation, requirement, specification, or imposed condition. It is often an internal process. Contrast with validation.

<img src="img/Systems_Engineering_V_diagram.jpg" height="50%" width="50%">

### Extreme Programming

* Lean Software Development
* SCRUM
* DevOP

## Release and Version Control Processes 
* Continuous Integration 
* Triage
* Gitflow / Github Flow

## Common Missunderstandins about `Agile`
* Agile means less planning.
* Agile allows rapid changes without any costs.
* Agile means no requirements
* Agile means less structure
* Agile is always better than classical project management. 
