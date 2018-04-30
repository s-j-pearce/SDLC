## SDLC-Methodologies

### What does 'SDLC' stand for?
SDLC stands for Software Development Life Cycle. 
### What is SDLC?
SDLC is a term that is used in systems engineering, information systems and software engineering. It simply describes the planning, creating, testing and deploying of an 'information system'. SDLC can apply to a range of hardware and software configurations, this is because a system can be made up of only hardware, only software or mainly a combination of both.
## Sequential methods:
### Waterfall Method:(Sequential)
The waterfall model is a popular version of the systems development life cycle model that is used for software engineering. It is often considered the classic approach to the systems development life cycle, the waterfall model describes a development method that is linear and sequential. Waterfall development has specific goals for each different phase of development. Once a phase of development is completed, the development proceeds to the next phase and there is no turning back, just like a real like waterfall.
#### Advantages:
The advantage of waterfall development is that it allows for departmentalization and managerial control. A schedule can be set with deadlines for each stage of development and a product can proceed through the development process like a car in a carwash, and theoretically, be delivered on time. Development moves from concept, through design, implementation, testing, installation, troubleshooting, and ends up at operation and maintenance. Each phase of development proceeds in strict order, without any overlapping or iterative steps.
#### Disadvantages:
The disadvantage of waterfall development is that it does not allow for much reflection or revision. Once an application is in the testing stage, it is very difficult to go back and change something that was not well-thought out in the concept stage. Alternatives to the waterfall model include joint application development (JAD), rapid application development (RAD), synch and stabilize, build and fix, and the spiral model.
#### Using the Waterfall method:
Firstly, the Development team analyzes the requirements set by the client. They must fully understand the problems as well as the positives. This is the research phase that includes no building or development. The team attempts to ask questions and secure all the answers they need to build the product. The Software team design solutions to the problems set out by the product requirements which includes scenarios, layouts and data models. This phase is usually accompanied by documentation for each requirement, this enables other members of the team to review it for validation.
Once the design is approved the technical implementation will start. This is usually the shortest phase because research and design would have been done in advance. Upon completion of full implementation, testing needs to take place before the product can be released to customers. The software testing team will use the design documents, personas and user case scenarios delivered by the product manager in order to create their test cases.
### V model:(Sequential)
The V model is a methodology used during a software development life cycle. The cycle itself is a linear development methodology. The model itself focuses on a similar method to the waterfall method - a strict, step-by-step method. The V model is a model where the execution of processes happen in a sequential manner in the form of a v shape. It is also known as a verification and validation model. The model itself is based on the associatation of a testing phase for each corresponding development stage. This basically means that for each stage in the development cycle, there is a testing stage which is also associated with it. This model means that the next stage will only happen after the successful completion of the previous stage. 

The V model follows the same flow as waterfall, you would organise it; requirements, design, implementation, verification and maintenance. The main differences are the way the model is presented and how much emphasis is put on testing. With the model there are Verification phases on one side of the ‘V’ and Validation phases on the other side. The Coding Phase joins the two sides of the V-Model. 
#### Advantages:
* Highly disiplined model where each phase is completed one at a time.
* Works best for smaller projects where the requirements are well understood.
* The model is east and simple to understand and use.
* The model is easy to manage due to the review process after each phase.
#### Disadvantages:
* Not very good for complex and object-oriented projects.
* Not good for long or ongoing projects.
* If the requirements are likely to change then this would not be an ideal model.
* Once an application is in the testing phase it is difficult to go back and change the functionality.
* Only near the end of the life cycle is a working software produced.

---

## Iterative models:
### Spiral Model:(Iterative)
The Spiral Model is a combination of the waterfall model and iterative model. Each phase in the spiral model begins with a design goal and ends with the client reviewing the progress. The spiral model was first mentioned by Barry Boehm in his 1986 paper. The development team in Spiral-SDLC model starts with a small set of requirement and goes through each development phase for those set of requirements. The development team adds functionality for the additional requirement in every-increasing spirals until the application is ready for the production phase.
#### Advantages:
Additional functionality or changes can be done at a later stage. Cost estimation becomes easy as the prototype building is done in small fragments. Continuous or repeated development helps in risk management. Continuous or repeated development helps in risk management. There is always a space for customer feedback.
#### Disadvantages:
Risk of not meeting the schedule or budget. It works best for large projects only also demands risk assessment expertise. For its smooth operation spiral model protocol needs to be followed strictly. Documentation is more as it has intermediate phases. It is not advisable for smaller project, it might cost them a lot.
#### How Risk Is Managed
The spiral model is a risk driven model which means that the overall success of a project highly depends on the risks analysis phase. Risk analysis requires specific expertise on every iteration. Firstly, it seems this model is complicated and hard to run but this model has its strong sides. For example, there’s a possibility to add some additional functionality at the last stages of product development. Since risk monitoring and regular expertise are core characteristics of this approach, the overall project becomes more transparent
### Evolutionary Model:(Iterative)
This model is the idea of developing an initial software idea from very broad specifications. Each version of you make will inherit the best features from earlier versions. Each version is changed based upon feedback from yourself or your team members to produce a system which meets the clients needs. At this point the system may be delivered. development and validation are done at the same time with feedback between each.
#### Advantages: 
This is the only method appropriate for situations where a detailed system specification is unavailable. Effective in rapidly producing small systems, software with short life spans, and developing sub-components of larger systems.
#### Disadvantages: 
It is difficult to measure progress and produce documentation reflecting every version of the system as it evolves. This paradigm usually results in badly structured programs due to continual code modification. Production of good quality software using this method requires highly skilled and motivated programmers.
### Prototype Model:(Iterative)
The idea of the Prototype model is that instead of defining the requirements before a design or coding can proceed, a disposable prototype is built to understand the requirements. This idea in this prototype are then developed further as requirements are understood and mapped out.
#### Advantages:
Provides a working model to the user early in the process, enabling early assessment and increasing user's confidence. The developer gains experience and insight by developing a prototype there by resulting in better implementation of requirements. The prototyping model serves to clarify requirements, which are not clear, hence reducing ambiguity and improving communication between the developers and users. There is a great involvement of users in software development. Hence, the requirements of the users are met to the greatest extent. Helps in reducing risks associated with the software.
#### Disadvantages:
If the user is not satisfied by the developed prototype, then a new prototype is developed. This process goes on until a perfect prototype is developed. Thus, this model is time consuming and expensive. The developer loses focus of the real purpose of prototype and hence, may compromise with the quality of the software. For example, developers may use some inefficient algorithms or inappropriate programming languages while developing the prototype. Prototyping can lead to false expectations. For example, a situation may be created where the user believes that the development of the system is finished when it is not. The primary goal of prototyping is speedy development, thus, the system design can suffer as it is developed in series without considering integration of all other components.

