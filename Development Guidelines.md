# Development Guidelines

Status: Template

### Introduction

1. Overview, summary, abstract. Explain what the project is, use a brief amount of words to describe the main objective, what it will do and solve.
2. Purpose of this document. Providing a shared and established sets for guidance and fundamentals at all steps of development.
3. Scope of this document. Serves only as technical documentation and planning resolve, does not include all artifacts or elements.

### General Description

Main purpose, objective, inspiration and problem to solve.

Desired result and outcome, scope of the project and use case.

Resource Planning, indicate what technology and tools will be used for the development stage.

### Requirement Description

1. **Functional Requirements.** The main structure of what features the project will have.
2. **Specification of Functional Requirements.** Specification of each feature, going into full detail about how the entire process around it will work. Define all functions of software, data objects, flow of data, overall behavior of the working system, minimal constraints and special characteristics.
3. **Performance Requirements.** Optimization and best practices for coding and developing.
4. **Interface Requirements.** System limitations and necessities.
5. **Design Constraints.** Limitations of packages and tools depending on the scope and specifications.
6. Review of requirements for improvement and refinement.

### Design and Architecture

Modeling, designing the UI/UX and software architecture is a core part of the development cycle, defining how things should interact, communicate, look and feel.

Only one tool should be used for each purpose. In the case of available diagrams, highlighted ones are prioritized and required, however, it is suggested to make them only if they provide useful insight that couldn’t be acquired with the required ones. All of them can be used freely.

### Development Phase

Establish what tools and technologies will be used for the development of the entire project, excluding IDEs or other development software, explain the main purpose of each tool, it’s integration and goal within the project. References to services, repositories, online project spaces and providers must be included.

Included specifications are coding languages, frameworks, services, key components, plugins, add-ons, and every main piece of software that needs to be tracked, including version, language and/or framework and author or source, otherwise, a repository which clearly establishes the main tools and technology used, that updates automatically, is enough.

Code, APIs and other such documentation must be made with the following guidelines in mind, within the code, in the case of specifying anything additional it must be done independently:

- Intention: Document the intention of the code and why it is the way it is, not how it works.
- Inline: Use inline comments on any complex segments, to distinguish sections and improve readability.
- Consistency: Code documentation is different in each language, so specify a common format and guidelines, usage of certain tools and guarantee coherence.
- Version Control: Keep well documented each commit and keep accessibility to older documentation.
- Clarity: Specify the possible incomes, outcomes, errors, intended usage and anything that might be of use.
- Levels: Design documentation for an external level, user friendly and thought of as a walk-through of the project, for a medium level, API, Classes and Functions that may be used as standalone options or outside the main scope of the project, for an internal level, each main component and sub-component must be documented.

A recommended list of coding documentation checks, they can be adjusted to the projects content:

- [ ]  Normalized naming conventions and structures.
- [ ]  Explanation comments without redundancy.
- [ ]  Detailed docstrings.
- [ ]  Prerequisites and environment setups.
- [ ]  Comprehensible, user friendly README.
- [ ]  Tool configurations.
- [ ]  Changelogs for each main update.
- [ ]  Code reviews with documentation updates.

Unless an interactive implementation or tool needs to be specified, **Obsidian** is the main documentation tool.

Testing data must be included in the development phase for easier testing implementations, as such, data collection and analysis is required if it can be done within the software.

### Testing Phase

Once the first development phase ends, the secondary development phase can start, in which testing is the main focus, however this testing leads to code corrections, regression and more, as such, development must still be done, but with a higher emphasis on testing and reporting results in. Testing data analysis is done at this phase to determine if the performance and interface requirements are met/

Reports of each version must be correctly done and kept logged and tracked. Design a common template for a specific type of test, fill it in, validate the input, results and create a conclusion that will further improve the secondary development phase.

There is a series of steps to follow in order to guarantee a successful testing phase:

1. **Planning:** Effort, scope and resources, types of tests.
2. **Design:** Step by step, input and output specification, expected result, details of each test.
3. **Pre-Test:** Define which tools will be used and set up the testing environment.
4. **Execution:** Evaluate each test carefully, report any and all findings.
5. **Regression:** Fix errors and details for the next version.
6. **Continuous Progress:** Repeat all steps according to the requirements.

### Deployment, Maintenance and Support

Set everything up to work in a real environment, all keys, files, configurations and everything that needs to be changed for a production environment, publish and utilize the software until any new problems or errors occur, keep in check and document each error for a future update, as well as any new implementation or change that may be needed, maintain the service up and available, log and report each finding and suggestion, additions and update support for following versions.

### Parameters

Established coding languages, frameworks, patterns, models, programs and more are offered here:

**Development Cycle Models.**

| **Model** | **Description** | **Pros** | **Cons** | **Best For** |
| --- | --- | --- | --- | --- |
| **Waterfall** | Linear and sequential. | Easy to manage, clear documentation, predictable budget & timeline. | Very rigid, late testing phase, hard to adapt to change. | Projects with well‑defined, stable requirements. |
| **V‑Model** | Dedicated testing phase linked to each development phase. | Early testing, defect detection, high quality. | Still rigid, minimal flexibility. | Safety‑critical systems, regulated industries. |
| **Incremental** | Adds features in successive increments: each increment includes requirements, design, build, test | Early delivery, adaptable, feedback‑driven. | Requires clear modular planning. | Medium-to-large projects with evolving scope. |
| **Iterative** | Repeats development cycles, refining based on feedback. | Flexible, continuous improvement. | Potential complexity, resource demands. | Projects needing gradual evolution. |
| **Spiral** | Risk-driven, cyclic model. | Excellent risk management, stakeholder input, adaptive. | Complex, costly to manage. | Large-scale, high-risk, long-duration projects. |
| **RAD** | Rapid prototyping and development in short cycles. | Fast delivery, frequent feedback. | May sacrifice depth and control. | Small to medium projects with tight deadlines. |
| **Prototype** | Build throwaway or evolutionary prototypes to gather feedback. | Clarifies requirements early, allows testing. | Time-consuming prototype development. | UX heavy or ambiguous requirement projects. |
| **Agile** (Scrum, XP, Kanban) | Iterative sprints: plan, code, test, review. | Highly flexible, frequent delivery, strong stakeholder engagement. | Hard to scale, demands cultural shift. | Most modern software projects. |
| **DevOps** | Integrates development and operations: CI/CD, monitoring, automation. | Faster delivery, stable environments. | Requires tool chain and cultural adoption. | Frequent deployment environments. |
| Component Based | Each piece of software is created independently in small components. | Modularity, Abstraction, Encapsulation, Reusability, Separation of Concerns. | Extensive documentation and rigor for each component. | Large and scalable platforms and frameworks. |
| Test Driven | Unit tests are written first, then enough code to pass and careful refactoring. | Cleaner code, faster debugging, excellent test coverage and easy maintenance. | Initial slowdown, steeper learning curve, bias towards test induced code. | High reliability with clear requirements on defined infrastructure or frameworks. |
| Acceptance Test Driven | Acceptance criteria are defined collaboratively beforehand. | Tangible and quick, non wasteful progress. | Constant communication for all decisions before initializing any new requirement. | Relevant high scale projects with regulatory alignments. |
| Behavior Driven | Top level descriptions of usage and functionalities. | Improved communication, focused on the user experience. | Slow and superficial documentation, development and testing. | Agile environments on customer-first applications. |
| Domain Driven | Long lived large scale sophisticated workflow systems and business. | Methodical, maintainable and scalable code. | Resource intensive, steeper learning curve and high initial investment. | Long lived, enterprise grade suites and systems. |

[UI/UX Tools](Development%20Guidelines/UI%20UX%20Tools%202c0de6de8886805b8d44e95b3722ec9d.csv)

- Free: Has a no cost, professional and/or enterprise plans with a cost.
- Paid: Single time payment.
- Subscription: Monthly or yearly pricing without a free plan option, they may or may not offer a free trial.

**Design Guidelines**

| Material Design (Google) | Fluent Design (Microsoft) | Carbon Design (IBM) | Acorn (Firefox) | Atlassian Design |
| --- | --- | --- | --- | --- |
| Primer Brand UI / Product UI (GitHub) | Polaris web components (Shopify) | MUI | Orbit (Kiwi.com) | Intergalactic (Semrush) |
| Apple Human Interface Guidelines | Figma Design | Bootstrap 5 | Tailwind CSS | Uber Design |
| Mailchimp Design | Salesforce Lightning Design | Helpscout Design | US Web Design System | Porsche Design System |
| Gestalt (Pinterest) | Capital One | Intuit Design | Spectrum (Adobe) | AWS Amplify UI Kit |
| Airtable Apps UI Kit | Ant Design | Chakra UI | Codex Design (Wikimedia) | Penpot Design System |

[UML Diagrams](Development%20Guidelines/UML%20Diagrams%202c0de6de888680c2ad8cfad704d19194.csv)

[Database Types](Development%20Guidelines/Database%20Types%202c0de6de888680bf894ac58bde19e6fe.csv)

- Relational: Organizes data into rows and columns (tables) that are linked by keys.
- Non-Relational (NoSQL): Designed for specific data models and stores data in flexible schemas that scale easily for modern applications.

[Programming Languages](Development%20Guidelines/Programming%20Languages%202c1de6de888680048a49f4f9b01e7dd8.csv)

[Frameworks and tools.](Development%20Guidelines/Frameworks%20and%20tools%20227de6de8886804fa114cfcf8ca00df8.csv)

1. **Ecosystem** - Has features for almost all requirements, from database management, web applications, data, sessions and security, cloud services, micro services, endpoints APIs and more.
2. **Environment** - Has features for a great variety of requirements, APIs, services, functions, macros and tools, micro services and more.
3. **Engine** - Has already implemented and developed features for an easy implementation of its dedicated purpose.
4. **Full Stack** - Has features for processing a visual and logical application.
5. **Back End** - Has features for processing logic of an application.
6. **Front End** - Has features for processing the interaction of an application.
7. **Database** - Has features for data storage.

[Service Providers](Development%20Guidelines/Service%20Providers%202c0de6de888680d0b5a8d5b4729bee9d.csv)