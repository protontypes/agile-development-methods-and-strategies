# Agile Concept of Robots
A summery of development concept in knowledge intense domains like robotics. The document intention is to give a entry point for professional robotic development processes, mindsets and methods. 

No process, mindset and method will fit exactly to your unique working enviroment and team without a common adaption. The following content shall be used as experiences to learn from and not as strict rulesets.

* [Mindsets and Experiences](#mindsets-and-experiences)
   * [Conway's law - About the importance of Communication](#Conways-law-About-the-importance-of-Communication)
   * [Brook's law - About the Overhead of Communication](#Brooks-law-About-the-Overhead-of-Communication)
   * [Unix Philosophy - About Slicing Complexity](#Unix-Philosophy-About-Slicing-Complexity)
   * [Reinventing the wheel](#reinventing-the-wheel)
   * [Software is knowledge](#software-is-knowledge)
   * [Safety and Security Culture](#safety-and-security-culture)
 * [Methods and Processes](#methods-and-processes)
   * [System Engineering and the V-Model](#system-engineering-and-the-v-model)
   * [SCRUM and Agile Development](#SCRUM-and-Agile-Development)
   * [Extreme Programming](#Extreme-Programming)
   * [Test-driven development](#Test-driven-development)
   * [DevOPs and Continuous Integration](#DevOPs-and-Continuous-Integration)   
   * [The W-Model and Lean Scaled Agility for Engineering](#The-W-Model-and-Lean-Scaled-Agility-for-Engineering)  
 * [Development Workflow](#development-workflow)
   * [Release and Branching Process](#release-and-branching-process)
   * [Issue Triage](#issue-triage) 

## Mindsets and Experiences

### Conway's law - About the Importance of Communication

> `Any organization that designs a system (defined broadly) will produce a design whose structure is a copy of the organization's communication structure.` (1967) [[1](https://en.wikipedia.org/wiki/Conway%27s_law)] 

### The Golden Circle - Intrinsic Motivation by Communication

>  `Simon Sinek says people are inspired by a sense of purpose (or "Why"), and that this should come first when communicating, before "How" and "What". Sinek calls this triad the golden circle, a diagram of a bullseye with "Why" in the innermost circle (representing people's motives or purposes), surrounded by a ring labeled "How" (representing people's processes or methods), enclosed in a ring labeled "What" (representing results or outcomes).` [[12](https://en.wikipedia.org/wiki/Start_With_Why)]


### Brook's law - About the Overhead of Communication

> `Adding manpower to a late software project makes it later.` (1975)  [[2](https://en.wikipedia.org/wiki/The_Mythical_Man-Month)]

![the mythical man-month](img/mythical_man_month.png)

* The modern practices of continuous integration, test-driven development, and iterative development significantly reduce the inter-developer communication overhead, and thus allow for better scalability.

* The design pattern defines the rules that the programmers follow, simplifies communication through the use of a standard language, and provides consistency and scalability. Finally, good segmentation helps by minimizing the communication overhead between team members. [[2](https://en.wikipedia.org/wiki/The_Mythical_Man-Month)]

Autoware.Auto gives you an example on how to create [guidlines for contributing](https://autowarefoundation.gitlab.io/autoware.auto/AutowareAuto/cpp-development-process.html).

### Unix Philosophy - About Slicing Complexity

Concepts of modularity and reusability into software engineering practice, spawning a "software tools" movement. (1978) [[3](https://en.wikipedia.org/wiki/Unix_philosophy)] 


The Unix philosophy favors composability as opposed to monolithic design:
* Make each program do one thing well. To do a new job, build afresh rather than complicate old programs by adding new "features".
* Expect the output of every program to become the input to another, as yet unknown, program. Don't clutter output with extraneous information. Avoid stringently columnar or binary input formats. Don't insist on interactive input.
* Design and build software, even operating systems, to be tried early, ideally within weeks. Don't hesitate to throw away the clumsy parts and rebuild them.
* Use tools in preference to unskilled help to lighten a programming task, even if you have to detour to build the tools and expect to throw some of them out after you've finished using them.                         

### Reinventing the wheel 

ROS allows you to stop reinventing the wheel. Reinventing the wheel is one of the main preventer for new innovative applications. The ROS goal is to provide a standard for robotics software development, that you can use on any robot. (2007) [[4](https://www.theconstructsim.com/history-ros/)]

<img src="img/reinvent_the_wheel.jpg" height="50%" width="50%" >

### Software is knowledge

To not reinvent the wheel you need to know about the wheel. Knowledge management is one of the most underestimated steps in software development and engineering in general. It is important to always keep in mind that most problems you get involved with have already occurred somewhere else on this planet. The ROS community delivers a treasure of solved robotic problems. A major part of robotic development is gathering the right information and knowledge.

### Safety and Security Culture

> `Safety culture is a culture where employees can tell the boss bad news.` - Sidney Dekker

The term ‘safety culture’ was first used in the Report on the chernobyl disaster and was described as:
> `That assembly of characteristics and attitudes in organizations and individuals which establishes that, as an overriding priority, nuclear plant safety issues receive the attention warranted by their significance.`  [[5](https://en.wikipedia.org/wiki/Safety_culture)]
## Methods and Processes 

### System Engineering and the V-Model 

Systems engineering utilizes systems thinking principles to organize this body of knowledge. The individual outcome of such efforts, an engineered system, can be defined as a combination of components that work in synergy to collectively perform a useful function.[[6](https://en.wikipedia.org/wiki/Systems_engineering)]

The V-model summarizes the main steps to be taken in conjunction with the corresponding deliverables within computerized system validation framework, or project life cycle development. It describes the activities to be performed and the results that have to be produced during product development. [[7](https://en.wikipedia.org/wiki/V-Model)]

The V models ensures two major aspacts of your development with traceability:
* Are you building it right? **Validation:** The assurance that a product, service, or system meets the needs of the customer and other identified stakeholders. It often involves acceptance and suitability with external customers. Contrast with verification.

* Are you building the right thing? **Verification:**  The evaluation of whether or not a product, service, or system complies with a regulation, requirement, specification, or imposed condition. It is often an internal process. Contrast with validation.

<img src="img/Systems_Engineering_V_diagram.jpg" height="50%" width="50%">  [[7a](https://upload.wikimedia.org/wikipedia/commons/9/9b/Systems_Engineering_V_diagram.jpg)]   


### Model Based Design or Model-based Systems Engineering

Model-based design provides an efficient approach for establishing a common framework for communication throughout the design process while supporting the development cycle (V-model).

The model-based design is significantly different from traditional design methodology. Rather than using complex structures and extensive software code, designers can use Model-based design to define plant models with advanced functional characteristics using continuous-time and discrete-time building blocks. These built models used with simulation tools can lead to rapid prototyping, software testing, and verification.[[8](https://en.wikipedia.org/wiki/Model-based_design)]

Even if model-based systems engineering it is used for state-of-the-art engineering for multiple safety related product today it is uncommen to use in complex robotic development. Some reasons for that can be found here: [[9](https://en.wikipedia.org/wiki/Model-based_design#Disadvantages_of_MBD)]

### SCRUM

SCRUM is a agile method for project management. It consists out of a process and and a mindset based on the Agile Manifesto [[10](https://agilemanifesto.org/principles.html)]:

> Individuals and interactions over processes and tools                          
> Working software over comprehensive documentation                              
> Customer collaboration over contract negotiation                            
> Responding to change over following a plan.                                      

**Some agile principles:**

* Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done.
* Working software is the primary measure of progress.
* Simplicity, the art of maximizing the amount of work not done, is essential.
* The best architectures, requirements, and designs emerge from self-organizing teams.
* At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly.

<img src="img/File_ScrumSchwaberBeedle.svg" height="50%" width="50%"> 


### Extreme Programming 

Extreme Programming (XP) describes four basic activities that are performed within the software development process: coding, testing, listening, and designing.

XP takes this concept to the extreme level, writing automated tests (sometimes inside software modules) which validate the operation of even small sections of software coding, rather than only testing the larger features.

XP knows two forms of user stories aligning with the V-Model validation and verification.
  * Validation: Unit tests determine whether a given feature works as intended. Programmers write as many automated tests as they can think of that might "break" the code; if all tests run successfully, then the coding is complete. Every piece of code that is written is tested before moving on to the next feature.
  * Verification: Acceptance tests verify that the requirements as understood by the programmers satisfy the customer's actual requirements.

<img src="img/Extreme_Programming.svg.png" height="50%" width="50%"> 

[[10](https://en.wikipedia.org/wiki/Extreme_programming)]

### Test-driven development
In Test-Driven Development (TDD), each new feature begins with writing a test. When developing a product ready function with high quality, availability and reliability creating the tests can even be more complex than the actual function.
The tests are created out of the requirements and user stories. This aligns with V-Model first steps. [[11](https://en.wikipedia.org/wiki/Test-driven_development)]

<img src="img/tdd_circle_of_life.svg" height="50%" width="50%">   

### DevOPs and Continuous Integration 
DevOps is a set of methods, practices and mindsets which aims to shorten the systems development life cycle and provide continuous delivery with high software quality. This is done by the automation of software development phases of the V-Model.

<img src="img/Devops-toolchain.svg" height="50%" width="50%">       

The [AutowareAuto Continuous Integration](https://gitlab.com/autowarefoundation/autoware.auto/AutowareAuto/-/blob/master/.gitlab-ci.yml) templates shows how use automated integrating and testing processes on a complete software stack.

### The W-Model and Lean Scaled Agility for Engineering
https://www.researchgate.net/publication/316945758_Automotive_Software
https://gitlab.com/autowarefoundation/autoware.auto/AutowareAuto/-/issues/206
https://gitlab.com/autowarefoundation/autoware.auto/AutowareAuto/-/boards/1517206?milestone_title=AVP%20MS2%3A%20Follow%20waypoints%20with%20the%20ndt_localizer
https://assets.vector.com/cms/content/consulting/publications/Agile_Requirements_Engineering.pdf
https://assets.vector.com/cms/content/consulting/publications/AgileSystemsEngineering_Vector_Ford.pdf

## Development Workflow
### Issue Triage    
https://about.gitlab.com/handbook/engineering/quality/issue-triage/

### Release and Branching Process   
One of the first processes showing how to work together with mutliple people on one project was [Gitflow](https://nvie.com/posts/a-successful-git-branching-model/). 

This process has been adapted and modified in many ways over the last years. The [AutowareAuto Branching Model](https://autowarefoundation.gitlab.io/autoware.auto/AutowareAuto/develop-in-a-fork.html) shows you how integrate your development with the work of multiple other developers.

