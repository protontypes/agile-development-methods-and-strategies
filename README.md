# agile-robots
A summery of mindsets, processes and methods in knowledge intense development processes like robotics. The document intention is to give a entry point to the ROS community for professional robotic development processes, mindsets and methods. 

> No process, mindset and method will fit exactly to your unique working enviroment and team without a common adaption. The following content shall be used as experiences to learn from and not as scrict guidelines.

* [Mindsets and Experiences](#mindsets-and-experiences)
   * [Conways law](#conways-law)
   * [The Mythical Man-Month or Brooks law](#the-mythical-man-Month-or-brooks-law)
   * [Unix Philosophy](#unix-philosophy)
   * [Reinventing the wheel](#reinventing-the-wheel)
   * [Key Aspacts In a Nutshell](#key-aspacts-in-a-nutshell)
 * [Methods](#methods)
   * [Waterfall Model](#waterfall-model)
   * [System Engineering and the V-Model](#system-engineering-and-the-v-model)
   * [SCRUM and Agile Development](#SCRUM-and-Agile-Development)
   * [Release, Deploy and Version Control Processes](#Release-Deploy-and-Version-Control-Processes) 

## Mindsets and Experiences 

### Conways law
`Any organization that designs a system (defined broadly) will produce a design whose structure is a copy of the organization's communication structure.` (1967) [[1](https://en.wikipedia.org/wiki/Conway%27s_law)]

### The Mythical Man-Month or Brooks law

`Adding manpower to a late software project makes it later.` (1975)  [[2](https://en.wikipedia.org/wiki/The_Mythical_Man-Month)]

![the mythical man-month](img/mythical_man_month.png)

* The modern practices of continuous integration, test-driven development, and iterative development significantly reduce the inter-developer communication overhead, and thus allow for better scalability.

* The design pattern defines the rules that the programmers follow, simplifies communication through the use of a standard language, and provides consistency and scalability. Finally, good segmentation helps by minimizing the communication overhead between team members. 

### Unix Philosophy 

Concepts of modularity and reusability into software engineering practice, spawning a "software tools" movement. (1978) [[3](https://en.wikipedia.org/wiki/Unix_philosophy)] 


The Unix philosophy favors composability as opposed to monolithic design:
* Make each program do one thing well. To do a new job, build afresh rather than complicate old programs by adding new "features".
* Expect the output of every program to become the input to another, as yet unknown, program. Don't clutter output with extraneous information. Avoid stringently columnar or binary input formats. Don't insist on interactive input.
* Design and build software, even operating systems, to be tried early, ideally within weeks. Don't hesitate to throw away the clumsy parts and rebuild them.
* Use tools in preference to unskilled help to lighten a programming task, even if you have to detour to build the tools and expect to throw some of them out after you've finished using them.                         

### Reinventing the wheel 

ROS allows you to stop reinventing the wheel. Reinventing the wheel is one of the main preventer for new innovative applications. The ROS goal is to provide a standard for robotics software development, that you can use on any robot. (2007) [[4](https://www.theconstructsim.com/history-ros/)]

<img src="img/reinvent_the_wheel.jpg" height="50%" width="50%" >

### Key Aspacts In a Nutshell
<img src="img/key_aspacts.svg" height="50%" width="50%">

## Methods
### Waterfall Model 
The waterfall model is a breakdown of project activities into linear sequential phases, where each phase depends on the deliverables of the previous one and corresponds to a specialisation of tasks. [[5](https://en.wikipedia.org/wiki/Waterfall_model)]

<img src="img/Waterfall_model_.svg" height="50%" width="50%" >

* Scales great if customer, management and developers have a lot experinces with the product.
* Useful for projects where changes cost a lot of resources and time 


### System Engineering and the V-Model 

The V-model summarizes the main steps to be taken in conjunction with the corresponding deliverables within computerized system validation framework, or project life cycle development. It describes the activities to be performed and the results that have to be produced during product development. [[6](https://en.wikipedia.org/wiki/V-Model)]

The V models ensures two major aspacts of your development with traceability:
* Are you building it right? **Validation:** The assurance that a product, service, or system meets the needs of the customer and other identified stakeholders. It often involves acceptance and suitability with external customers. Contrast with verification.

* Are you building the right thing? **Verification:**  The evaluation of whether or not a product, service, or system complies with a regulation, requirement, specification, or imposed condition. It is often an internal process. Contrast with validation.

<img src="img/Systems_Engineering_V_diagram.jpg" height="50%" width="50%">

### SCRUM and Agile Development 

SCRUM is a agile method for project management. It consists out of a process and and a mindset based on the Agile Manifesto [[7](https://agilemanifesto.org/principles.html)]:

> Individuals and interactions over processes and tools                          
> Working software over comprehensive documentation                              
> Customer collaboration over contract negotiation                            
> Responding to change over following a plan.                                      

**My personal favourites of the 12 agile principles:**

* Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done.
* Working software is the primary measure of progress.
* Simplicity, the art of maximizing the amount of work not done, is essential.
* The best architectures, requirements, and designs emerge from self-organizing teams.
* At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly.

<img src="img/File_ScrumSchwaberBeedle.svg" height="50%" width="50%">   
 
Further agile methods:   
* [Extreme Programming](http://www.extremeprogramming.org/)                 
* [Lean Software Development](https://en.wikipedia.org/wiki/Lean_software_development)                  

### Common Missunderstandins about Agile Development Methods

* Agile means less planning.
* Agile allows rapid changes without any costs.
* Agile means no requirements.
* Agile means no process.
* Agile is always better than classical project management.
* Agile development can not be used within the V-Model.  

## Release, Deploy and Version Control Processes 
### DevOP and Continuous Integration 
<img src="img/Devops-toolchain.svg" height="50%" width="50%">       

### Defect Triage    

### Gitflow    


