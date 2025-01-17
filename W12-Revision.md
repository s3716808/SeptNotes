# Week 12 Revision

## Why Process and Tools

- What are some of the characteristics of modern software construction.

  - 

- How does Process help:

  - Manage the complexity, reduces risk and improves quality

- How do Tools help:

  - Automation, reduce human error

- What else do we need:

  - Culture, commitment

  

## Topic 1: SE Processes, Agile

- Why is good SE Process so critical? What does good process manage, reduce, maximise? Explain the Quality Triangle. 
- What are the main parts of the SE life cycle? What are the main activities in SE? 

- What are the main SE Processes? Their advantages and disadvantages? 

- What are the characteristics of Incremental and Agile methods? How does Agile address the problems of the traditional Waterfall approach? What are its strengths? 

- How does Scrum work? What are its benefits? How do the task-tracking tools like Trello and JIRA support it? How would you organise a Trello/JIRA board to manage Scrum? 
- How are the Scrum team roles and what do they do? Who fills them? 
- What are the different Scrum meetings and their purpose? 



## Topic2: User stories and backlogs

- User Stories: how are they different to Use Cases? How do they fit with agile development? How do they reduce risk associated with requirements change? 
- What are the main parts of a User Story? What does a User Story look like? How are User Stories used? What are characteristics of a good User Story? 
- How are task times/sizes estimated? What is the relationship between User Stories and Backlogs? 
- What is a Definition of Done? What are different possible definitions? 



## Topic 3: Version control, Git, Gitflow 

- Why is version control critical (multiple reasons!)? What is version control’s role in modern SE process? 

- What is the difference between centralized and distributed Version Systems? What are some advantages of the Distributed model? 

- What are the main operations in Git and how do they work, esp. clone, commit, merge, push/pull, tag, but also rebase. roll-back? 

  – You should understand how to perform these and some basic “good practice” 

  – You should understand some issues that might arise and how to resolve them (e.g., conflicts) 

- When/how often should you commit/merge/push etc? 

- What are good practice workflows, e.g., branch-per-feature, Gitflow? 

  What are their benefits? How do they support CI/CD 



## Topic 4: Unit Testing, Logging

- What is Test Driven Development? What are its benefits? 
- What are Mock Objects and what are they used for (multiple reasons)? 
- What are Java Assertions and what are they used for? 
- Be prepared to design and write JUnit tests for a simple short program, using @BeforeClass, @Before, etc, testing for Exceptions, etc 
- What is Logging useful for? What sort of information should be logged? What are the basics for using the Java Loggger? In particular, how are Levels used? 



## Topic 5: Testing and Test/Issue Management 

- What is testing for? How is early testing important? 

- What are the different stages of testing and what are the inputs to them? 

  – What is Regression testing and why is it important? 

- What goes into a Test Case description? How/when are users engaged in testing? What are good features of a test case? You should be prepared to design some small number of test cases for a simple application. 

- Why is issue tracking important? What are the different uses for a good bug report? What are the characteristics of a good bug report? You may be required to critique a bug report. 

- What are the different states/stages a bug goes through? How are bugs ranked? How are Severity and Priority measured? 

## Topic 6: Builds

- Why is semi/automating the build process important? Where are the complexities in build processes? What risks are involved with manual builds? 

- What are the steps in a standard build process? How do build files help us manage dependencies? 

- What is Maven – not details? What are the extra features of Maven over, say, Ant (in general terms)? In particular, how does Maven manage library dependencies and using up-to-date versions? How are lists of dependencies encoded 

  – You do not need to write Maven code but you should know “how it works” at an appropriate (abstract) level 

## Topic 7: Continuous Integration and Delivery 

- What is Continuous Integration (CI)? How does it tie in with Agile process? What problems does it solve / what risks does it reduce? 
- Does CI require an automation framework like Travis or Jenkins? How are Git, Maven, and other tools involved? 
- How does a CI process integrate with the code repository? What role does the branch-per-feature/Gitflow model play in Continuous Delivery? 
- What are some of the essentials rules for practicing CI / CD? – e.g., why can you never go home on a broken build? 
- You will not need to know how to write detailed Travis scripts, but you should know generally what it does and how it works, and generally how it encodes workflow (i.e,. via yaml file) 

## Topic 8: Deployment via containers / Docker 

- Docker and containerization: what is it for, how is it used? 

- Comparison between Docker containers and standard virtualisation: 

  containerisation is more “lightweight” ... why? 

- What is the process for creating a Docker container, in the abstract? (You do not have to remember all Docker commands, although you should remember the main operations; knowing the main commands may help to be precise in describing operations.) 

## Topic 9: Design characteristics, patterns, refactoring 

- What are some of the important design characteristics and what do they mean, esp coherence and coupling? What are the implications? You should be able to recognise these properties in specific designs and be able to suggest how to achieve them in designs (to a simple degree). 
- What are some of the “design smells”, the blocks to reusability, extensibility, modifiability --- don’t memorise them all but know how to describe them and why they are a problem. 
- What are the SOLID principles for? Be prepared to identify why some code violates a SOLID principle and describe a fix. 
- What is Refactoring, why is it important/critical in Agile. You do not have to memorise the catalog of Refactoring operations, but you should be able to recognise an opportunity for application of a simple Refactoring operation. 
- What are Design Patterns and what is their benefit? What are the motivations for some of them --- i.e., what problems do they solve? You should be able to provide some design, even some **simple** code to demonstrate understanding (Observer, Factory Method, Facade, Visitor) 

## Topic 10: NFRs Performance Testing 

- What are Non-Functional Requirements? How do they relate to System Quality? What are the important System Qualities to design for? 
- What do we write NFRs? Why is it critical to be specific and precise?? Be prepared to critique and potentially write NFRs for some of the System Qualities (e.g., Performance/Speed, Reliability, Usability) 
- What is Performance Testing? Why is it critical to success of products? What are the risks of not doing it? What aspects of requirements cover it? 
- What are the aims of performance testing? What are the different sorts of performance testing? What does each one hope to discover/explore? 
- What are some of the steps of doing performance testing? Why does the data used need to be carefully designed? What do we risk if we do not vary the data? 
- Why do we use automated tools to do performance testing? Why is it important to test different Loads? How do we do this? 

## Topic 11: Not examinable

Not examinable

