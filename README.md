# Development References

Not conclusive, not complete, but a nice way of sharing everything I've seen.

Contributions are open, as I am not able to write down every possible tool.

## Contents

1. [Documentation Approach](#documentation-approach)
2. [General Description](#general-description)
3. [Requirement Description](#requirement-description)
4. [Design and Architecture](#design-and-architecture)
5. [Development Phase](#development-phase)
6. [Testing Phase](#testing-phase)
7. [Deployment, Maintenance and Support](#deployment-maintenance-and-support)
8. [Parameters](#parameters)

## Documentation Approach

1. Overview, summary, abstract. Explain what the project is, use a brief amount of words to describe the main objective, what it will do and solve.
2. Purpose of this document. Providing a shared and established sets for guidance and fundamentals at all steps of development.
3. Scope of this document. Serves only as technical documentation and planning resolve, does not include all artifacts or elements.

## General Description

Main purpose, objective, inspiration and problem to solve.

Desired result and outcome, scope of the project and use case.

Resource Planning, indicate what technology and tools will be used for the development stage.

## Requirement Description

1. **Functional Requirements.** The main structure of what features the project will have.
2. **Specification of Functional Requirements.** Specification of each feature, going into full detail about how the entire process around it will work. Define all functions of software, data objects, flow of data, overall behavior of the working system, minimal constraints and special characteristics.
3. **Performance Requirements.** Optimization and best practices for coding and developing.
4. **Interface Requirements.** System limitations and necessities.
5. **Design Constraints.** Limitations of packages and tools depending on the scope and specifications.
6. Review of requirements for improvement and refinement.

## Design and Architecture

Modeling, designing the UI/UX and software architecture is a core part of the development cycle, defining how things should interact, communicate, look and feel.

Only one tool should be used for each purpose. In the case of available diagrams, highlighted ones are prioritized and required, however, it is suggested to make them only if they provide useful insight that couldn’t be acquired with the required ones. All of them can be used freely.

## Development Phase

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

Unless an interactive implementation or tool needs to be specified, **Obsidian** is the main documentation tool, alongside GitHub for better version and project management..

Testing data must be included in the development phase for easier testing implementations, as such, data collection and analysis is required if it can be done within the software.

## Testing Phase

Once the first development phase ends, the secondary development phase can start, in which testing is the main focus, however this testing leads to code corrections, regression and more, as such, development must still be done, but with a higher emphasis on testing and reporting results in. Testing data analysis is done at this phase to determine if the performance and interface requirements are met/

Reports of each version must be correctly done and kept logged and tracked. Design a common template for a specific type of test, fill it in, validate the input, results and create a conclusion that will further improve the secondary development phase.

There is a series of steps to follow in order to guarantee a successful testing phase:

1. **Planning:** Effort, scope and resources, types of tests.
2. **Design:** Step by step, input and output specification, expected result, details of each test.
3. **Pre-Test:** Define which tools will be used and set up the testing environment.
4. **Execution:** Evaluate each test carefully, report any and all findings.
5. **Regression:** Fix errors and details for the next version.
6. **Continuous Progress:** Repeat all steps according to the requirements.

## Deployment, Maintenance and Support

Set everything up to work in a real environment, all keys, files, configurations and everything that needs to be changed for a production environment, publish and utilize the software until any new problems or errors occur, keep in check and document each error for a future update, as well as any new implementation or change that may be needed, maintain the service up and available, log and report each finding and suggestion, additions and update support for following versions.

## Parameters

Established coding languages, frameworks, patterns, models, programs and more are offered here:

### Development Cycle Models

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
| **Component Based** | Each piece of software is created independently in small components. | Modularity, Abstraction, Encapsulation, Reusability, Separation of Concerns. | Extensive documentation and rigor for each component. | Large and scalable platforms and frameworks. |
| **Test Driven** | Unit tests are written first, then enough code to pass and careful refactoring. | Cleaner code, faster debugging, excellent test coverage and easy maintenance. | Initial slowdown, steeper learning curve, bias towards test induced code. | High reliability with clear requirements on defined infrastructure or frameworks. |
| **Acceptance Test Driven** | Acceptance criteria are defined collaboratively beforehand. | Tangible and quick, non wasteful progress. | Constant communication for all decisions before initializing any new requirement. | Relevant high scale projects with regulatory alignments. |
| **Behavior Driven** | Top level descriptions of usage and functionalities. | Improved communication, focused on the user experience. | Slow and superficial documentation, development and testing. | Agile environments on customer-first applications. |
| **Domain Driven** | Long lived large scale sophisticated workflow systems and business. | Methodical, maintainable and scalable code. | Resource intensive, steeper learning curve and high initial investment. | Long lived, enterprise grade suites and systems. |

### UI/UX Tools

| Name | Platform | Pricing | Tool Description | Usage |
| :--- | :--- | :--- | :--- | :--- |
| **Figma** | Web, Windows, macOS | Free | General purpose, highly functional, extensible and accessible | UI/UX |
| **Framer** | Web, Windows, macOS | Free | Software design oriented, various pre-made components, ease of use. | UI/UX |
| **Penpot** | Web | Free | | UI/UX |
| **Mockup** | macOS | Free | | UI/UX |
| **Marvel** | Web | Free | | UI/UX |
| **UXPin** | Web | Free | | UI/UX |
| **Webflow** | Web, Windows, macOS | Free | | UI/UX |
| **Flowmapp** | Web | Free | | UI/UX |
| **VisualSitemaps** | Web | Free | | UI/UX |
| **Justinmind** | Windows, macOS | Free | | UI/UX |
| **StarUML** | Windows, macOS | Paid | | Modeling |
| **JetUML** | Windows | Free | | Modeling |
| **Modelio** | Linux, Windows | Free | | Modeling |
| **PlantUML** | Web | Free | | Modeling |
| **yEd** | Linux, Windows, macOS | Free | | Modeling |
| **draw.io** | Linux, Web, Windows, macOS | Free | | Modeling |
| **Miro** | Web | Free | | Modeling |
| **Fluig** | Web | Free | | Modeling |
| **Whimsical** | Web | Free | | Modeling |
| **Visual Paradigm CE** | Web | Free | | Modeling |
| **LucidChart** | Web | Free | | Modeling |
| **Wireframe.cc** | Web | Subscription | | Modeling |
| **Balsamiq** | Web | Subscription | | Modeling |
| **Origami Studio 3** | macOS | Free | | UI/UX |
| **Adobe XD** | Windows, macOS | Subscription | | UI/UX |
| **Axure** | Web | Free | | UI/UX |
| **Proto.io** | Web | Subscription | | UI/UX |
| **Sketch** | macOS | Subscription | | UI/UX |
| **Applet** | Web | Free | | UI/UX |

- *Free*: Has a no cost, professional and/or enterprise plans with a cost.
- *Paid*: Single time payment.
- *Subscription*: Monthly or yearly pricing without a free plan option, they may or may not offer a free trial.

### Database Types

| Name | Type | Features |
| :--- | :--- | :--- |
| **Hierarchical** | Non-Relational | Uses a tree-like structure to organize data. Each record has a single parent, and the relationships are a hierarchy. |
| **Network** | Relational | Multiple relationships between records. The model uses a graph-like structure to connect records and enable complex relationships. |
| **Cloud** | Non-Relational | Hosting solution given by a third-party provider. Offers database-as-a-service (DBaaS) to eliminate physical data center setups. |
| **On-Premise** | Relational | All the software, infrastructure, and management are maintained locally. With large-scale enterprises, the storage grows to a local data center over time. |
| **Centralized** | Relational | Stored and managed in a single physical location. The centralized repository is available to other devices through a network, which enables data sharing across an organization. |
| **Distributed** | Non-Relational | Store information across different physical sites. |
| **Operational** | Relational | An operational database manages and controls the basic operations within a business. It collects data directly from the source in real time, providing a view of daily transactions. |
| **Analytical** | Relational | Analytical databases offer a unified view of all business data. Essential for planning, reporting, and making decisions (OLAP). |
| **Graph** | Non-Relational | Optimized for managing relationships between data points. It structures data as nodes, edges, and properties. |
| **Key-Value** | Non-Relational | An efficient database that stores data as key-value pairs. Every key is a unique identifier for a corresponding value. |
| **Document** | Non-Relational | Every document uses a format such as JSON or XML to represent data. Highly flexible and suitable for modern app development. |
| **Time-Series** | Non-Relational | Works with timestamped data. Ideal for collecting and processing data over time, such as monitoring or scientific research. |

- Relational: Organizes data into rows and columns (tables) that are linked by keys.
- Non-Relational (NoSQL): Designed for specific data models and stores data in flexible schemas that scale easily for modern applications.

### Design Guidelines

| Material Design (Google) | Fluent Design (Microsoft) | Carbon Design (IBM) | Acorn (Firefox) | Atlassian Design |
| --- | --- | --- | --- | --- |
| Primer Brand UI / Product UI (GitHub) | Polaris web components (Shopify) | MUI | Orbit (Kiwi.com) | Intergalactic (Semrush) |
| Apple Human Interface Guidelines | Figma Design | Bootstrap 5 | Tailwind CSS | Uber Design |
| Mailchimp Design | Salesforce Lightning Design | Helpscout Design | US Web Design System | Porsche Design System |
| Gestalt (Pinterest) | Capital One | Intuit Design | Spectrum (Adobe) | AWS Amplify UI Kit |
| Airtable Apps UI Kit | Ant Design | Chakra UI | Codex Design (Wikimedia) | Penpot Design System |

### UML Diagrams

| Name | Relevance | Type |
| :--- | :--- | :--- |
| **Use Case** | High | Behavioral |
| **Class** | High | Structural |
| **Sequence** | High | Behavioral |
| **Activity** | Medium | Behavioral |
| **Communication** | Medium | Behavioral |
| **Timing** | Low | Behavioral |
| **State Machine** | Low | Behavioral |
| **Profile** | Low | Structural |
| **Interaction Overview** | Medium | Behavioral |
| **Component** | High | Structural |
| **Composite Structure** | Medium | Structural |
| **Deployment** | Low | Structural |
| **Package** | Medium | Structural |
| **Object** | Medium | Structural |

### Programming Languages

| Name | Paradigm | Typing | Memory Management | Domain |
| :--- | :--- | :--- | :--- | :--- |
| **JavaScript** | Functional, Imperative, OOP | Dynamic, Strong, Weak | Automatic | Back-End, Front-End, Native |
| **Python** | Functional, Imperative, OOP, Scripting | Dynamic, Strong | Automatic | Automation, Back-End, Data Science, Machine Learning, Scripting |
| **Java** | Imperative, OOP | Static, Strong | Automatic | Back-End, Native, System |
| **C++** | Generic, OOP, Procedural | Static, Strong | Hybrid | Critical, GameDev, High-performance, System |
| **C#** | OOP | Static, Strong | Automatic | Back-End, GameDev, System |
| **PHP** | OOP, Procedural | Dynamic, Weak | Automatic | Back-End |
| **Swift** | Functional, OOP | Static, Strong | Automatic | System |
| **Ruby** | OOP | Dynamic, Strong | Automatic | Back-End, Scripting |
| **SQL** | Declarative | Dynamic | N/A | System |
| **Go** | Concurrent, Imperative | Static, Strong | Automatic | Back-End, System |
| **R** | Functional | Dynamic, Weak | Automatic | Data Science |
| **Kotlin** | Functional, OOP | Static, Strong | Automatic | Back-End, Native |
| **Groovy** | OOP, Scripting | Dynamic, Strong | Automatic | Automation, Back-End, System |
| **Elixir** | Concurrent, Functional | Dynamic, Strong | Automatic | High-performance, System |
| **Rust** | Functional, Imperative | Static, Strong | Hybrid | Critical, High-performance, System |
| **Dart** | Functional, OOP | Static, Strong | Automatic | Native |
| **TypeScript** | Functional, Imperative, OOP | Static, Strong | Automatic | Back-End, Front-End, Native |
| **Scala** | Functional, OOP | Static, Strong | Automatic | Data Science |
| **Objective-C** | OOP | Dynamic, Weak | Automatic | System |
| **Perl** | OOP, Procedural | Dynamic, Weak | Automatic | Automation, Scripting, System |
| **Lua** | Procedural, Scripting | Dynamic, Strong | Automatic | GameDev, System |
| **Haskell** | Functional | Static, Strong | Automatic | Data Science, Scripting |
| **COBOL** | Imperative, Procedural | Static, Strong | Manual | System |
| **Lisp** | Functional | Dynamic, Strong | Automatic | Data Science |
| **Julia** | Functional, Imperative | Dynamic, Strong | Automatic | Data Science, High-performance |
| **Shell Scripting** | Imperative, Procedural | Dynamic, Weak | N/A | Automation, System |
| **Assembly** | Imperative | Strong | Manual | Critical, High-performance, System |
| **Erlang** | Concurrent, Functional | Dynamic, Strong | Automatic | System |
| **MATLAB** | Procedural | Dynamic, Strong | Automatic | Data Science |
| **F#** | Functional | Static, Strong | Automatic | Data Science |
| **Carbon** | Generic, OOP, Procedural | Static, Strong | Hybrid | System |
| **Zig** | Imperative, Procedural | Static, Strong | Manual | System |

### Frameworks and Tools

| Technology | Language | Description | Usage | Platform |
| :--- | :--- | :--- | :--- | :--- |
| **React.js** | CSS, HTML, JavaScript | Web user interfaces with states. | Front-End | Web App |
| **Vue.js** | CSS, HTML, JavaScript | Progressive web user interfaces with reactivity. | Front-End | Web App |
| **Angular** | CSS, HTML, JavaScript | Single Page Application | Front-End | Web App |
| **Svelte** | CSS, HTML, JavaScript | Web user interfaces reactivity. | Front-End | Web App |
| **SolidJS** | CSS, HTML, JavaScript | Optimized web user interfaces. | Front-End | Web App |
| **Alpine** | CSS, HTML, JavaScript | Rugged, minimal tool for composing behavior directly in your markup. | Front-End | Web App |
| **Inferno** | CSS, HTML, JavaScript | Insanely fast, React-like library for high-performance UIs. | | |
| **Docusaurus** | CSS, HTML, JavaScript, Markdown | Web framework for building documentation sites. | Front-End | Web App |
| **Lume** | CSS, HTML, JavaScript | Static Site Generator for Deno. | Front-End | Web App |
| **Fresh** | CSS, HTML, JavaScript | Small, fast and extensible full stack web framework built on Web Standards. | Front-End | Web App |
| **Qwik** | CSS, HTML, JavaScript | Web framework delivering instant loading web applications at any size. | Front-End | Web App |
| **Marko** | CSS, HTML, JavaScript | Re-imagines HTML as a language for building dynamic and reactive UIs. | Front-End | Web App |
| **Astro** | CSS, HTML, JavaScript | Island based development environment integrated with various frameworks. | Environment | Server, Web App |
| **Bun** | JavaScript | Fast, all-in-one JavaScript, TypeScript & JSX toolkit. | Environment | Server, Web App |
| **Deno** | JavaScript | Open source runtime for JavaScript, TypeScript, and WebAssembly. | Back-End | System |
| **Hono** | JavaScript | Small, simple, and fast web framework built on Web Standards. | Back-End | Server |
| **Webpack** | JavaScript | Legacy module bundler for packaging projects into optimized browser files. | Front-End | Bundler |
| **Vite** | JavaScript | Framework based, native ESM server built upon Rollup and esbuild. | Front-End | Bundler |
| **Parcel** | JavaScript | Build tool designed for a zero-configuration experience. | Front-End | Bundler |
| **esbuild** | JavaScript | Quick bundler, minifier, and transpiler used as a high-speed component. | Front-End | Bundler |
| **Turbopack** | JavaScript | High-performance bundler developed by the Vercel team. | Front-End | Bundler |
| **Rollup** | JavaScript | Specialized bundler focused on small and efficient output bundles. | Front-End | Bundler |
| **Babel** | JavaScript | JavaScript Transpiler. | Front-End | Bundler |
| **Node.js** | JavaScript | Cross-platform runtime for servers, web apps, and command line tools. | Back-End | Server |
| **Express** | JavaScript | Minimalist REST API server. | Back-End | RESTful |
| **Fastify** | JavaScript | Optimized REST API server. | Back-End | RESTful |
| **Nest JS** | JavaScript | Flexible enterprise grade server applications. | Back-End | On Top Server |
| **oak** | JavaScript | Middleware framework for handling HTTP requests (Deno, Node, Bun). | Back-End | Server |
| **Next.js** | CSS, HTML, JavaScript | Simple React complete applications with server side processing. | Full Stack | Server, Web App |
| **Remix** | CSS, HTML, JavaScript | Simple standardized React web application framework. | Full Stack | Server, Web App |
| **Nuxt** | CSS, HTML, JavaScript | Simple Vue complete applications with server side processing. | Full Stack | Server, Web App |
| **Analog** | CSS, HTML, JavaScript | Simple Angular complete applications with server side processing. | Full Stack | Server, Web App |
| **SvelteKit** | CSS, HTML, JavaScript | Simple Svelte complete applications with server side processing. | Full Stack | Server, Web App |
| **Jinja2** | CSS, HTML, Python | Templating engine with embedded content. | Front-End | Templates |
| **PyJSX** | HTML, JavaScript, Python | Module for writing JSX code within Python. | Front-End | Web App |
| **Django** | CSS, HTML, Python | Complete Python web applications (models, views, templates). | Full Stack | Server, Templates, Web App |
| **Django REST Framework** | Python | Complete Python web toolkit for JSON APIs. | Back-End | RESTful |
| **Flask** | Python | Simple Python web applications and server side processing. | Back-End | WSGI |
| **FastAPI** | Python | High performance asynchronous REST APIs. | Back-End | ASGI |
| **Thymeleaf** | CSS, HTML, Java | Server side natural templating engine. | Front-End | Templates |
| **Apache FreeMarker** | CSS, FTL, HTML, Java | Presentation layer templating engine. | Front-End | Templates |
| **Spring** | Groovy, Java, Kotlin | Full ecosystem of tools and frameworks for myriad purposes. | Ecosystem | Multiple |
| **Grails** | Groovy | Groovy-based web framework for JVM built on top of Spring Boot. | Back-End | On Top Server, RESTful, Server |
| **Micronaut** | Groovy, Java, Kotlin | Servers, services and tools with modular efficiency. | Environment | Server, System |
| **Quarkus** | Groovy, Java, Kotlin | Kubernetes-native cloud-first containerized environments. | Back-End | On Top Server, Server, System |
| **ASP.NET Core** | C# | Web framework with various client and server side alternatives. | Full Stack | Server, Templates, Web App |
| **Blade** | CSS, HTML, PHP | Templating engine for embedding PHP (Laravel). | Front-End | Templates |
| **Laravel** | HTML, PHP | MVC web framework. | Back-End | Server |
| **Livewire** | CSS, HTML, PHP | Dynamic reactivity web apps built on Blade and Laravel. | Full Stack | Server, Web App |
| **Inertia.js** | JavaScript, Multiple | Multi-platform hybrid SPAs bridging front end and back end. | Full Stack | Hybrid, Server, Web App |
| **Hotwire** | HTML, Ruby | SSR Web UI templating for SPA reactivity. | Front-End | Templates |
| **Ruby on Rails** | CSS, HTML, JavaScript, Ruby | MVC web framework. | Full Stack | Server, Web App |
| **Phoenix** | Elixir | MVC web framework with SPA UI SSR. | Full Stack | Server, Templates, Web App |
| **Fiber** | Go | Fast HTTP engine, performant and quick. | Back-End | Server |
| **Gin** | Go | API web framework with fast performance. | Back-End | Server |
| **Beego** | Go | Enterprise application server development. | Back-End | RESTful, Server |
| **Rocket** | Rust | Fast, type safe, secure web application framework. | Back-End | RESTful |
| **Actix Web** | Rust | Micro HTTP framework for web applications. | Back-End | Server |
| **Unreal Engine** | Blueprints, C++, Python | Epic Games 3D production and game engine. | Engine | Desktop, Game, Native |
| **Flutter** | Dart | Google’s open source cross platform framework for native apps. | Front-End | Desktop, Native, Web App |
| **Godot** | C#, GDScript | Open source 2D and 3D game engine. | Engine | Desktop, Game, Native, Web App |
| **Android SDK** | Java, Kotlin, XML | Native mobile Android apps development. | Front-End | Native |
| **Jetpack Compose** | Kotlin | Declarative UI toolkit for Android; cross platform support possible. | Front-End | Hybrid, Native |
| **React Native** | JavaScript | Facebook’s cross platform framework for native apps. | Front-End | Hybrid, Native, Web App |
| **Unity** | C# | Multi-purpose game engine. | Engine | Desktop, Game, Native, Web App |
| **Ionic** | CSS, HTML, JavaScript | WebView integrated native apps (React, Angular, Vue). | Front-End | Hybrid, Native |
| **Flame** | Dart | Flutter based 2D modular game engine. | Engine | Desktop, Game, Native, Web App |
| **Kivy** | Python | Cross platform GUI apps; codebase single. | | |
| **Tkinter** | Python | Tcl/Tk based desktop GUI toolkit. | Front-End | Desktop |
| **.NET MAUI** | C# | Cross platform open source native and desktop apps. | Full Stack | Desktop, Native |
| **Electron** | CSS, HTML, JavaScript | Embedded native desktop applications using web libraries. | Front-End | Desktop, Hybrid |
| **Tauri** | CSS, HTML, JavaScript, Kotlin, Rust | Embedded Rust binaries with web stack for desktop apps. | Full Stack | Desktop |
| **Avalonia UI** | C# | Cross platform UI framework with WPF for desktop/embedded. | Full Stack | Desktop |
| **Qt** | QML | Libraries and APIs for powerful UI and core functionality. | Ecosystem | Hybrid, Multiple, System |
| **Firebase** | Multiple | BaaS with tools for various categories. | Environment | Multiple, Web App |
| **Supabase** | JavaScript, SQL | Open source BaaS alternative to Firebase. | Environment | Multiple, Web App |
| **MySQL** | SQL | Relational database management system. | Database | System |
| **MariaDB** | SQL | Open source improved RDBMS. | Database | System |
| **SQLite** | SQL | Lightweight embedded database. | Database | Native |
| **SQL Server** | SQL | Enterprise relational database management system. | Database | Server |
| **PostgreSQL** | SQL | Object-relational database management system. | Database | Server, System |
| **MongoDB** | JSON | NoSQL document database. | Database | System |
| **DynamoDB** | JSON | Serverless NoSQL AWS database. | Database | Hybrid, System |
| **Neo4j** | Cypher | Graph database for complex relationships. | Database | Hybrid, System |
| **Redis** | Redis CLI | In-memory key value store. | Database | System |
| **Cassandra** | CQL | Distributed NoSQL optimized for heavy workloads. | Database | System |
| **InfluxDB** | Flux | Time series database for metrics and monitoring. | Database | System |
| **Scikit-learn** | Python | Library for classical and simple machine learning. | Engine | Multiple, System |
| **Tensorflow** | JavaScript, Python | Google’s open source ML toolkit with scaling. | Engine | Multiple, Server |
| **PyTorch** | Python | Facebook’s ML framework; flexible and cross platform. | Engine | Hybrid, Server |
| **OpenCV** | C++, Java, JavaScript, Python | Library for computer vision and image processing. | Engine | System |
| **Keras** | Python | High level neural network API for Tensorflow. | Engine | Hybrid, System |
| **gRPC** | Multiple | Agnostic remote procedure call framework. | Back-End | Hybrid, Server |
| **Socket.IO** | JavaScript, Multiple | Real time bidirectional communication (WebSockets). | Back-End | Hybrid, Web App |
| **Selenium** | C#, Java, JavaScript, Python, Ruby | Automating web applications for testing/admin tasks. | Engine | Testing, Web App |
| **Cypress** | JavaScript | Fast, modern test automation for end-to-end testing. | Engine | Testing, Web App |
| **Appium** | C#, Java, JavaScript, Python, Ruby | Cross-platform mobile testing (native, hybrid, web). | Engine | Testing |
| **Katalon Studio** | Groovy, Java, Kotlin | All-in-one test automation for web, API, mobile, desktop. | Engine | Testing |
| **JUnit** | Java | Unit-testing framework for Java applications. | Engine | Testing |
| **NUnit** | C# | Unit-testing framework for .NET applications. | Engine | Testing |
| **Robot Framework** | Java, Python | Keyword-driven automation for acceptance testing/RPA. | Engine | Testing |
| **Cucumber** | Java, JavaScript, Kotlin, Ruby | BDD framework enabling tests in natural language. | Engine | Testing |
| **Mocha** | JavaScript | Feature-rich testing framework for Node.js applications. | Engine | Server, Testing |
| **Protractor** | JavaScript | End-to-end testing designed for Angular apps. | Engine | Testing |
| **Playwright** | C#, JavaScript, Python | Modern, fast automation for web applications. | Engine | Testing |
| **Serentiy BDD** | Java | Supports BDD and provides clear detailed reports. | Engine | Testing |
| **Fitnesse** | C#, Java | Web-based wiki-style framework for acceptance testing. | Engine | Testing |
| **XCTest** | Objective-C, Swift | Apple’s native testing for iOS and macOS. | Engine | System, Testing |
| **Espresso** | Java, Kotlin | UI testing for Android applications. | Engine | Native, Testing |
| **TestNG** | Java | Powerful testing framework with parallel execution. | Engine | Testing |
| **JBehave** | Java | BDD framework for Java. | Engine | Testing |
| **Lagom** | Java, Scala | Building reactive microservices. | Engine | Testing |
| **WireMock** | Java | Tool for simulating HTTP-based APIs. | Engine | Testing |
| **PyTest** | Python | Unit, integration, and functional testing in Python. | Engine | Testing |
| **Vwo Test** | | Visual testing platform focusing on no-code. | Engine | Testing |
| **Selendroid** | Java, Ruby | Mobile test automation for Android. | Engine | Native, Testing |
| **Telerik Test Studio** | C#, JavaScript | Automation tool for web, desktop, and mobile. | Engine | Testing |
| **Calabash** | Ruby | Cross-platform mobile automation with Cucumber. | Engine | Testing |
| **Concordion** | HTML, Java | Lightweight framework for BDD in Java. | Engine | Testing |
| **Minitest** | Ruby | Unit testing in Ruby. | Engine | Testing |
| **Detox** | JavaScript | End-to-end mobile UI testing for React Native. | Engine | Testing |
| **TestCafe** | JavaScript | Node.js-based framework without WebDriver. | Engine | Testing |
| **Puppeteer** | JavaScript | API to control Chrome or Firefox over DevTools. | Engine | Testing |
| **WebDriverIO** | JavaScript | Progressive automation for modern web/mobile apps. | Engine | Testing |
| **Jest** | JavaScript | Testing framework ensuring correctness of JS codebase. | Engine | Testing |
| **Jasmine** | JavaScript | Framework for testing JS; browser and Node.js. | Engine | Testing |
| **Spock** | Groovy, Java | Testing and specification framework. | Engine | Testing |
| **Maestro** | YAML | End-to-end testing for Mobile and Web apps. | Engine | Testing |
| **Gauge** | Multiple | Open source framework for acceptance tests. | Engine | Testing |
| **Nightwatch.js** | JavaScript | End to end testing on desktop & mobile browsers. | Engine | Testing |
| **Selenide** | Java | Framework powered by Selenium WebDriver. | Engine | Testing |
| **Takio** | JavaScript | Node.js library to automate Chromium/Firefox. | Engine | Testing |
| **PHPUnit** | PHP | Unit testing framework for PHP. | Engine | Testing |
| **XCUITest** | Objective-C, Swift | Appium driver for iOS automation. | Engine | Testing |
| **Geb** | Groovy | Combines WebDriver with jQuery-style selection. | Engine | Testing |
| **QUnit** | JavaScript | Designed for unit and integration front-end testing. | Engine | Testing |
| **RSPec** | Ruby | Behaviour Driven Development for Ruby. | Engine | Testing |
| **Reqnroll** | | Cucumber-style BDD for .NET. | Engine | Testing |
| **MSTest** | C# | Microsoft Testing Framework for .NET. | Engine | Testing |
| **Behave** | Python | Behavior-driven development, Python style. | Engine | Testing |

1. *Ecosystem* - Has features for almost all requirements, from database management, web applications, data, sessions and security, cloud services, micro services, endpoints APIs and more.
2. *Environment* - Has features for a great variety of requirements, APIs, services, functions, macros and tools, micro services and more.
3. *Engine* - Has already implemented and developed features for an easy implementation of its dedicated purpose.
4. *Full Stack* - Has features for processing a visual and logical application.
5. *Back End* - Has features for processing logic of an application.
6. *Front End* - Has features for processing the interaction of an application.
7. *Database* - Has features for data storage.

### Service Providers

| Name | Description | Pricing | Service Area |
| :--- | :--- | :--- | :--- |
| **Amazon Web Services (AWS)** | Provides the largest collection of on-demand cloud computing resources, APIs, and managed services. | Usage | Cloud Hosting, IaaS, Managed Services |
| **Google Cloud Platform (GCP)** | Offers scalable public cloud infrastructure and specialized services for data analytics and containerization. | Usage | Cloud Hosting, Containers, Data Analytics |
| **Microsoft Azure** | Provides cloud services built for enterprise, hybrid, and proprietary systems integration. | Usage | Cloud Hosting, Hybrid Hosting, IaaS |
| **DigitalOcean** | Provides virtual private servers (Droplets) and managed infrastructure with a focus on simplicity and ease of use. | Subscription | Deployment, Managed Services, VPS |
| **Linode (Akamai)** | Offers high-performance Linux virtual machines (VMs) and supporting cloud infrastructure. | Subscription | VMs, VPS |
| **Vercel** | Offers high-performance Linux virtual machines (VMs) and supporting cloud infrastructure. | Usage | Front-End Hosting, Static Hosting |
| **Netlify** | A platform for static sites and serverless functions, featuring automatic build and deployment from Git. | Usage | Serverless Functions, Static Hosting |
| **GitHub Pages** | A static site hosting service integrated directly with Git repositories for simple web publishing. | Subscription | Front-End Hosting, Static Hosting |
| **Hostinger** | Provides budget-focused shared hosting, managed WordPress, and virtual private server packages. | Subscription | Static Hosting, VPS |
| **EAS Hosting** | A service integrated with Expo for deploying web projects, API routes, and server functions to the edge. | Usage | API, Front-End Hosting |
| **Supabase** | An open-source Backend-as-a-Service (BaaS) that provides managed PostgreSQL, Auth, and real-time APIs. | Usage | BaaS, DB Provider, Real-Time Data |
| **Heroku** | A managed Platform-as-a-Service (PaaS) that handles server operations, allowing focus on code deployment. | Subscription | Deployment, PaaS |
| **Firebase** | Google's BaaS offering for web and mobile development, including NoSQL database and authentication. | Usage | BaaS, Containers, DB Provider, Deployment, PaaS |
| **Render** | A unified cloud platform for hosting web services, databases, and Docker containers with automatic scaling. | Subscription | DB Provider |
| **MongoDB Atlas** | The official cloud service for managed MongoDB (NoSQL) document databases. | Usage | DB Provider |
| **PlanetScale** | A serverless MySQL platform offering sharding, scalability, and non-blocking database branching. | Subscription | BaaS, DB Provider |
| **Neon** | A serverless PostgreSQL solution designed for cost-efficiency by separating storage and compute. | Usage | BaaS, DB Provider |
| **Twilio** | Provides APIs for programmatic communication including SMS, Voice, and Video services. | Usage | API |
| **Redis Cloud** | The managed service for the high-performance Redis Key-Value and in-memory data structure store. | Usage | DB Provider |
| **SendGrid** | An API specializing in the reliable delivery of transactional and marketing emails. | Volume | API |
| **Stripe** | A platform for developers to accept and manage online payments, subscriptions, and payouts. | Transaction | API |
| **Auth0** | An identity management platform that provides authentication and authorization services via API. | Volume | API |
| **Google Maps Platform** | Provides APIs for integrating detailed maps, location data, and routing services into applications. | Usage | API |
| **Algolia** | An API that provides instant, typo-tolerant search-as-a-service for applications. | Volume | API |
| **Datadog** | A unified platform for monitoring, logging, and performance metrics across the entire application stack. | Subscription | API |
| **Sentry** | Real-time error tracking and performance monitoring for capturing and analyzing application exceptions. | Volume | API |
| **Infinityfree** | A provider offering completely free, basic shared web hosting with support for PHP and MySQL. | Usage | Back-End Hosting, Front-End Hosting |
