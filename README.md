[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18372561&assignment_repo_type=AssignmentRepo)
# SE_Day1
Software Engineering Day1 Assignment

#Part 1: Introduction to Software Engineering

Explain what software engineering is and discuss its importance in the technology industry.

This is a computer science discipline that focuses on the design, development, testing and maintenance of software problems to ensure that the software is relaible, efficient, maintainable and scalable.

Importance of software engineering in technology industry include:
It helps scale and handle large amounts of data and complex data with increasing loads; ensuring that systems are robust and less prone to failures minimizing risks related to system downtime; helping avoid redundant work and improve productivity organizing development stages; facilitating teamwork and continuous delivery of valueto end users through enhancing collaborations; and enhancing communication and improving access to resources that would inaccessible.

Identify and describe at least three key milestones in the evolution of software engineering.

Evolution of software engineering can be categorised into:
Early computing and machine coding when assembly language which used symbolic instructions to make coding easier was introduced in ENIAC and UNIVAC digital computers.
This was followed by development of high-level programming languages such as FORTRAN, COBOL and ALGOL, enabling programmers to write human-readable format codes by using compilers.
It was then followed by the birth of structured programming concepts such as loops, funtions and modular designs which improved code organisations after which software enginnering was first introduced at the NATO Conference of 1968.
This was followed by the rise of object oriented programming which promoted code reuse in languages such as Smalltalk, C++ and Java inputing concepts such as classes, objects and inheritance.
This stage was followed by agile development i.e. Scrum, Kanban and XP, and iterative models that enabled continuous feedback and flexibility in software projects. This enabled continuous integration and deployemnt and DevOps that automated and streamlined software deployment by use of Docker, Kubernetes, Jenkins and Github.
Most recent is the adoption AI-driven software developments tools that assist in coding and debugging hence enhancing automation of the whole process.

List and briefly explain the phases of the Software Development Life Cycle.

Software Development Life Cycle includes the following phases:

Planning phase that involves defining the project scope, objectives, feasibility analysis, and resource allocation. It ensures that the project is viable and aligns with business goals.
Requirement Analysis phase where developers and stakeholders gather, document, and analyze software requirements to understand user needs and system functionalities. This phase often results in a Software Requirement Specification (SRS) document.
Design phase in which the system architecture, user interface, database design, and technology stack are planned. It includes high-level design (HLD) for system structure and low-level design (LLD) for detailed component design.
Implementation (Coding) phase where developers write the actual program based on the design specifications using programming languages. This is the most active phase, where the software takes shape.
Testing phase that involves the software being rigorously tested for bugs, performance, security, and functionality. Testing types include unit testing, integration testing, system testing, and user acceptance testing (UAT) to ensure the software meets the requirements.
Deployment phase is the stage where the software is released for end-users, either as a full launch or in stages. Deployment strategies may include pilot releases, phased rollouts, or continuous deployment based on business needs.
Finally the maintenance phase in which the software requires ongoing support, including bug fixes, updates, performance enhancements, and adapting to new user requirements to ensure long-term usability.

Compare and contrast the Waterfall and Agile methodologies. Provide examples of scenarios where each would be appropriate.

Waterfall is suitable for projects with stable requirements and strict compliance needs since it is adopts a more linear process, changes are difficult once development begins, feedback is usually gathered at the end, and its documentation is extensive and detailed documentation required while Agile works best for projects requiring frequent changes, continuous user feedback, and iterative improvements since it adopts a more flexible process, changes can be made at any stage, there is continuous collaboration with stakeholders, has less documentation and the focus is on working software.

Waterfall is best for predictable and well-defined projects such as Banking software development since Banking systems require strict regulations, detailed documentation, and thorough security testing before deployment, while Agile is best for dynamic, fast-changing projects such as Mobile app development since in them User feedback is critical, and frequent updates and feature enhancements are needed.

Describe the roles and responsibilities of a Software Developer, a Quality Assurance Engineer, and a Project Manager in a software engineering team.

A Software Developer is responsible for designing, coding, debugging and troubleshooting software issues and implementing software applications based on project requirements 

A QA Engineer ensures that the software meets quality standards before deployment by designing and performing different types of testing to identify bugs and ensure software reliability.

A Project Manager oversees the software development process, ensuring timely delivery and alignment with business goals by defining project scope, goals, and deliverables in collaboration with stakeholders and creating project timelines, milestones, and resource allocation plans.

Discuss the importance of Integrated Development Environments (IDEs) and Version Control Systems (VCS) in the software development process. Give examples of each.

Integrated Development Environments (IDEs) helps:
Provide Features like syntax highlighting, code suggestions, and auto-completion, reducing development time; Allow developers to identify and fix errors easily; Navigate through large codebases and refactor code without breaking functionality; and support plugins for databases, testing frameworks, and deployment tools.

Examples of Integrated Development Environments (IDEs) include Visual Studio Code (VS Code), IntelliJ IDEA, and PyCharm

Version Control Systems (VCS) helps:
Multiple colaborators work on the same project without overwriting each other's changes; Track modifications, revert to previous versions, and identify who made specific changes; Create separate branches for new features and merge them into the main project when ready and restore previous versions if a code is accidentally deleted or corrupted

Examples of Version Control Systems (VCS) include Git, Apache Subversion (SVN) and Mercurial

What are some common challenges faced by software engineers? Provide strategies to overcome these challenges.

Common challenges and stratergies to overcome include:

As projects grow, the complexity of code increases, making it harder to maintain, refactor, and scale; but the software engineer can break down the system into small, manageable components or modules, following principles like Separation of Concerns, adopt well-established design patterns (e.g., MVC, Singleton) to ensure code scalability and maintainability and regularly refactor the code to improve its structure, readability, and performance.

Software development often involves tight deadlines and limited resources, making it difficult to deliver quality software on time; but the software engineer can adopt agile practices like Scrum or Kanban to break projects into manageable sprints, use task management tools (e.g., Jira, Trello) to prioritize high-impact tasks and focus on delivering MVP (Minimum Viable Product) first, and regularly communicate with stakeholders to manage expectations and adjust timelines or resources as needed.

The tech industry evolves rapidly, and software engineers need to constantly learn new tools, frameworks, and programming languages to stay relevant but the software engineer can dedicate time to learning new technologies through online courses, books, and tutorials (e.g., Udemy, Coursera, Pluralsight), participate in developer communities, attend conferences, and follow industry leaders to stay updated on trends and build side projects to experiment with new tools and technologies in real-world scenarios.

Software engineers often work in teams and with diffrent clients with different skills and communication styles, leading to misunderstandings and coordination problems but the software engineer can maintain comprehensive, up-to-date documentation for code, processes, and decisions to ensure smooth collaboration, hold daily standups or weekly syncs to discuss progress, roadblocks, and next steps and use tools like Slack, Microsoft Teams, or GitHub for real-time communication and version control, ensuring everyone stays aligned.

Explain the different types of testing (unit, integration, system, and acceptance) and their importance in software quality assurance.

Unit testing involves testing individual components or units of a software application in isolation to ensure that each part functions correctly. Typically, unit tests focus on a single function or method within a class or module. It helps catch bugs early in the development process, making it easier to debug and fix issues. When refactoring code, unit tests ensure that the changes do not break existing functionality. It also encourages developers to write modular, testable code, improving long-term maintainability.

Integration testing checks how different modules or components of an application interact with each other. After unit testing ensures individual components work, integration testing ensures that they work together seamlessly. It helps detect issues in the interaction between modules, such as incorrect data exchange or mismatched expectations between different parts of the system and ensures that integrating new code or features does not break existing functionality.

System testing evaluates the complete system as a whole. This phase tests the entire application to ensure it meets the specified requirements and works under different conditions and configurations. IT ensures the whole system operates as intended, covering all functional and non-functional requirements, including security, performance, and usability and helps identify problems related to the system's interaction with hardware, operating systems, or network configurations.

Acceptance testing is the final phase of testing, where the software is evaluated from the perspective of the end-user or client. This test confirms whether the software meets business requirements and is ready for release. It ensures that the software meets all the requirements outlined by stakeholders, ensuring the system does what it is supposed to do and reduces the risk of launching a product that doesn’t meet the business or user needs by identifying major issues just before release.

#Part 2: Introduction to AI and Prompt Engineering

Define prompt engineering and discuss its importance in interacting with AI models.

Prompt engineering is the process of providing the right instructions to guide artificial intelligence (AI) models i.e. large language models (LLMs) toward generating the most relevant, accurate, or useful output.

Its importance in interacting with AI models include: Improving accuracy and relevance of responses since the interpretation of the prompt is highly dependent on the clarity and context provided, and by crafting the right prompt, users can reduce the chances of receiving irrelevant or confusing answers; Enhancing task-specific performance since the users can tailor their interactions to align with the model’s strengths and guide it to perform specific tasks more effectively; Maximizing Efficiency since properly engineered prompts help users get the information they need more quickly and efficiently. 

Provide an example of a vague prompt and then improve it by making it clear, specific, and concise. Explain why the improved prompt is more effective.

Vague Prompt: "Tell me about climate change."

Improved Prompt: "Provide a 300-word summary of the causes, effects, and potential solutions to climate change, focusing on its impact on coastal cities."

The improved prompt is more effective because it guides the AI toward producing a well-defined, targeted answer in terms of: 

Clarity: The vague prompt, "Tell me about climate change," is open to broad interpretation, and the AI could generate a response covering any aspect of the topic. The improved prompt specifies what exactly is being asked: causes, effects, and solutions of climate change, making it easier for the AI to understand the context.

Specificity: The improved prompt adds more detail, such as focusing on the impact on coastal cities, which narrows the scope of the information provided. This helps the AI target its response more effectively and prevents it from discussing unrelated aspects of climate change, like its effects on agriculture or forests.

Conciseness: The improved prompt is still concise, providing just enough context and detail without becoming overly complex. It gives clear direction on length (300 words) and the topic focus, ensuring that the response is not too lengthy or too shallow.
