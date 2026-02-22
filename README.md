# Development References

Not conclusive, not complete, but a nice way of sharing everything I've seen. Contributions are open, as I am not able to write down every possible tool.

This is the DevRef, a development reference document I wrote to help me manage the different elements and tools that I found useful and interesting, to either help development or expand your own knowledge set.

## Contents

1. [Documentation Approach](#documentation-approach)
2. [Requirement Description](#requirement-description)
3. [Design and Architecture](#design-and-architecture)
4. [Development Phase](#development-phase)
5. [Testing Phase](#testing-phase)
6. [Deployment, Maintenance and Support](#deployment-maintenance-and-support)
7. [Parameters](#parameters)

## Documentation Approach

How one thinks about the documentation of a project, shapes the project itself, the accessibility, scalability, quality and many other characteristics, as such, we must be careful with what approach we create documentation, usually, any complex and extensive document must have these three introductory elements.

1. **Overview, summary or abstract**: Explain what the project is, use a brief amount of words to describe the main objective, what it will solve and how.
2. **Extent of the document**: Provide a shared and established set of guidance and fundamentals for all steps of development.
3. **Scope**: Determine how the documentation is structured, and if it may include some or all artifacts and elements, how they'll be included and small specifications for the access and relevance of each one.

This defines the approach that any part of the documentation should have, despite the tools used for it, documentation must remain accessible and agnostic, so anyone at any moment can glance at the important details they need and get a good idea of how a system works.

## Requirement Description

There are three main types of requirements that can be further subdivided into five types, these being:

1. **Functional Requirements.** The main structure of what features the project will have.
2. **Specification of Functional Requirements.** Specification of each feature, going into full detail about how the entire process around it will work. Define all functions of software, data objects, flow of data, overall behavior of the working system, minimal constraints and special characteristics.
3. **Performance Requirements.** Optimization and best practices for coding and developing.
4. **Interface Requirements.** System limitations and necessities.
5. **Design Constraints.** Limitations of packages and tools depending on the scope and specifications.

It is important to constantly review requirements to assess if they are adequate and fulfill correctly the user necessities, whilst also trying to improve them.

## Design and Architecture

Modeling, designing the UI/UX and software architecture is a core part of the development cycle, defining how things should interact, communicate, look and feel.

Only one tool should be used for each purpose, keeping things simple and organized, if possible, try to use more than one or keep a constant single source of information. In the case of available diagrams, highlighted ones are prioritized, however, it is suggested to make them only if they provide useful insight that couldn’t be acquired from the previous ones. All of them can be used freely if the need is met.

## Development Phase

Establish what tools and technologies will be used for the development of the project, excluding IDEs or other development software that varies per person, explain the main purpose of each tool, it’s integration and goal within the project. References to services, repositories, online project spaces and providers must be included.

A repository which clearly establishes the main tools and technology used, that updates automatically, is enough, otherwise, included specifications should be coding languages, frameworks, services, key components, plugins, add-ons, and every main piece of software that needs to be tracked, with their respective versions and source.

Code, APIs and other such documentation must be made with the following guidelines in mind, usually as comments or dosctrings, in the case of any additional specifications one should follow whilst developing a project, they must be done independently:

- *Intention*: Document the intention of the code and why it is the way it is, not how it works.
- *Inline*: Use inline comments on any complex segments, to distinguish sections and improve readability.
- *Consistency*: Code documentation is different in each language, so specify a common format and guidelines, usage of certain tools, and guarantee coherence.
- *Version Control*: Keep well documented each commit and keep accessibility to older documentation.
- *Clarity*: Specify the possible incomes, outcomes, errors, intended usage and anything that might be of use.
- *Levels*: Design documentation for an external level first, user friendly, thought of as a walk-through of the project, whenever it is needed for people lacking most technical knowledge.
For a medium level, API, Classes and Functions that may be used as standalone options or outside the main scope of the project.
For an internal level, each main component and sub-component must be clearly documented.

A recommended list of coding documentation checks, they can be adjusted to the projects content:

- [ ]  Normalized naming conventions and structures.
- [ ]  Explanation comments without redundancy.
- [ ]  Detailed docstrings.
- [ ]  Prerequisites and environment setups.
- [ ]  Comprehensible, user friendly README.
- [ ]  Tool configurations.
- [ ]  Changelogs for each main update.
- [ ]  Code reviews with documentation updates.

Unless an interactive implementation or tool needs to be specified, **Obsidian** is the best suggestion for an extensive documentation tool, alongside GitHub for better version and project management.

Testing data should be included in the development phase for easier testing implementations, as such, data collection and analysis is convenient if it can be done within the development phase.

## Testing Phase

Once the first development phase ends, the secondary development phase can start, in which testing is the main focus, however this testing leads to code corrections, regression and more, as such, development should still be done, but with a higher emphasis on testing and reporting results in. Testing data analysis is done at this phase to determine if the performance and interface requirements are met.

Reports of each version must be correctly done and kept logged and tracked. Design a common template for a specific type of test, fill it in, validate the input, results and create a conclusion that will further improve the secondary development phase.

There is a series of steps to follow in order to guarantee a successful testing phase:

1. **Planning:** Effort, scope and resources, types of tests.
2. **Design:** Step by step, input and output specification, expected result, details of each test.
3. **Pre-Test:** Define which tools will be used and set up the testing environment.
4. **Execution:** Evaluate each test carefully, report any and all findings.
5. **Regression:** What errors and details to consider for the next version.
6. **Continuous Progress:** Repeat all steps according to the requirements until they are fulfilled, then progressively do more tests alongside updates to the software if needed.

## Deployment, Maintenance and Support

Set everything up to work in a real environment, all keys, files, configurations and everything that needs to be changed for a production environment, publish and utilize the software until any new problems or errors occur, keep in check and document each error for a future update, as well as any new implementation or change that may be needed, maintain the service up and available, log and report each finding and suggestion.

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

| Name | Platform | Pricing | Usage |
| :--- | :--- | :--- | :--- |
| **[PlantUML](com/)** | Web | Free | Modeling |
| **[Fluig](https://www.fluig.cc/home)** | Web | Free | Modeling |
| **[Whimsical](https://whimsical.com/)** | Web | Free | Modeling |
| **[LucidChart](https://www.lucidchart.com/pages/es)** | Web | Free | Modeling |
| **[Miro](https://miro.com/)** | Web | Free | Modeling |
| **[JetUML](https://www.jetuml.org/)** | Windows | Free | Modeling |
| **[Modelio](https://www.modelio.org/index.htm)** | Linux, Windows | Free | Modeling |
| **[yEd](https://www.yworks.com/products/yed)** | Linux, Windows, macOS | Free | Modeling |
| **[draw.io](https://draw.io)** | Linux, Web, Windows, macOS | Free | Modeling |
| **[StarUML](https://staruml.io/)** | Windows, macOS | Paid | Modeling |
| **[Astah](https://astah.net/downloads/)** | Windows, macOS, Linux | Paid | Modeling |
| **[Balsamiq](https://balsamiq.com/)** | Web | Subscription | Modeling |
| **[Penpot](https://penpot.app/)** | Web | Free | UI/UX |
| **[Marvel](https://marvelapp.com/)** | Web | Free | UI/UX |
| **[UXPin](https://www.uxpin.com/)** | Web | Free | UI/UX |
| **[Flowmapp](https://www.flowmapp.com/)** | Web | Free | UI/UX |
| **[VisualSitemaps](https://visualsitemaps.com/)** | Web | Free | UI/UX |
| **[Axure](https://www.axure.com/)** | Web | Free | UI/UX |
| **[Mockup](https://getmockup.app/)** | macOS | Free | UI/UX |
| **[Origami Studio 3](https://origami.design/)** | macOS | Free | UI/UX |
| **[Justinmind](https://www.justinmind.com/)** | Windows, macOS | Free | UI/UX |
| **[Figma](https://www.figma.com/)** | Web, Windows, macOS | Free | UI/UX |
| **[Framer](https://www.framer.com/)** | Web, Windows, macOS | Free | UI/UX |
| **[Webflow](https://webflow.com/?r=0)** | Web, Windows, macOS | Free | UI/UX |
| **[Sketch](https://www.sketch.com/)** | macOS | Subscription | UI/UX |
| **[Proto.io](https://proto.io/)** | Web | Subscription | UI/UX |
| **Adobe XD** | Windows, macOS | Subscription | UI/UX |

- *Free*: Has a no cost, professional and/or enterprise plans with a cost.
- *Paid*: Single time payment.
- *Subscription*: Monthly or yearly pricing without a free plan option, they may or may not offer a free trial.

### Database Types

| Name | Type | Features |
| :--- | :--- | :--- |
| **Analytical** | Relational | Analytical databases offer a unified view of all business data. Essential for planning, reporting, and making decisions (OLAP). |
| **Centralized** | Relational | Stored and managed in a single physical location. The centralized repository is available to other devices through a network, which enables data sharing across an organization. |
| **Network** | Relational | Multiple relationships between records. The model uses a graph-like structure to connect records and enable complex relationships. |
| **On-Premise** | Relational | All the software, infrastructure, and management are maintained locally. With large-scale enterprises, the storage grows to a local data center over time. |
| **Operational** | Relational | An operational database manages and controls the basic operations within a business. It collects data directly from the source in real time, providing a view of daily transactions. |
| **Cloud** | Non-Relational | Hosting solution given by a third-party provider. Offers database-as-a-service (DBaaS) to eliminate physical data center setups. |
| **Distributed** | Non-Relational | Store information across different physical sites. |
| **Document** | Non-Relational | Every document uses a format such as JSON or XML to represent data. Highly flexible and suitable for modern app development. |
| **Graph** | Non-Relational | Optimized for managing relationships between data points. It structures data as nodes, edges, and properties. |
| **Hierarchical** | Non-Relational | Uses a tree-like structure to organize data. Each record has a single parent, and the relationships are a hierarchy. |
| **Key-Value** | Non-Relational | An efficient database that stores data as key-value pairs. Every key is a unique identifier for a corresponding value. |
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
| **Sequence** | High | Behavioral |
| **Activity** | Medium | Behavioral |
| **Communication** | Medium | Behavioral |
| **Interaction Overview** | Medium | Behavioral |
| **Timing** | Low | Behavioral |
| **State Machine** | Low | Behavioral |
| **Class** | High | Structural |
| **Component** | High | Structural |
| **Composite Structure** | Medium | Structural |
| **Object** | Medium | Structural |
| **Package** | Medium | Structural |
| **Deployment** | Low | Structural |
| **Profile** | Low | Structural |

### Programming Languages

| Name | Paradigm | Typing | Memory Management | Domain |
| :--- | :--- | :--- | :--- | :--- |
| **[JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)** | Functional, Imperative, OOP | Dynamic, Strong, Weak | Automatic | Back-End, Front-End, Native |
| **[Python](https://www.python.org/)** | Functional, Imperative, OOP, Scripting | Dynamic, Strong | Automatic | Automation, Back-End, Data Science, Machine Learning, Scripting |
| **[Java](https://dev.java/)** | Imperative, OOP | Static, Strong | Automatic | Back-End, Native, System |
| **[C++](https://isocpp.org/)** | Generic, OOP, Procedural | Static, Strong | Hybrid | Critical, GameDev, High-performance, System |
| **[C#](https://learn.microsoft.com/en-us/dotnet/csharp/)** | OOP | Static, Strong | Automatic | Back-End, GameDev, System |
| **[PHP](https://www.php.net/)** | OOP, Procedural | Dynamic, Weak | Automatic | Back-End |
| **[Swift](https://www.swift.org/)** | Functional, OOP | Static, Strong | Automatic | System |
| **[Ruby](https://www.ruby-lang.org/)** | OOP | Dynamic, Strong | Automatic | Back-End, Scripting |
| **SQL** | Declarative | Dynamic | N/A | System |
| **[Go](https://go.dev/)** | Concurrent, Imperative | Static, Strong | Automatic | Back-End, System |
| **[R](https://www.r-project.org/)** | Functional | Dynamic, Weak | Automatic | Data Science |
| **[Kotlin](https://kotlinlang.org/)** | Functional, OOP | Static, Strong | Automatic | Back-End, Native |
| **[Groovy](https://groovy-lang.org/)** | OOP, Scripting | Dynamic, Strong | Automatic | Automation, Back-End, System |
| **[Elixir](https://elixir-lang.org/)** | Concurrent, Functional | Dynamic, Strong | Automatic | High-performance, System |
| **[Rust](https://www.rust-lang.org/)** | Functional, Imperative | Static, Strong | Hybrid | Critical, High-performance, System |
| **[Dart](https://dart.dev/)** | Functional, OOP | Static, Strong | Automatic | Native |
| **[TypeScript](https://www.typescriptlang.org/)** | Functional, Imperative, OOP | Static, Strong | Automatic | Back-End, Front-End, Native |
| **[Scala](https://www.scala-lang.org/)** | Functional, OOP | Static, Strong | Automatic | Data Science |
| **[Objective-C](https://developer.apple.com/documentation/objectivec)** | OOP | Dynamic, Weak | Automatic | System |
| **[Perl](https://www.perl.org/)** | OOP, Procedural | Dynamic, Weak | Automatic | Automation, Scripting, System |
| **[Lua](https://www.lua.org/)** | Procedural, Scripting | Dynamic, Strong | Automatic | GameDev, System |
| **[Haskell](https://www.haskell.org/)** | Functional | Static, Strong | Automatic | Data Science, Scripting |
| **[COBOL](https://www.ibm.com/docs/en/cobol-zos/6.5.0)** | Imperative, Procedural | Static, Strong | Manual | System |
| **[Lisp](https://common-lisp.net/)** | Functional | Dynamic, Strong | Automatic | Data Science |
| **[Julia](https://julialang.org/)** | Functional, Imperative | Dynamic, Strong | Automatic | Data Science, High-performance |
| **[Shell Scripting](https://www.gnu.org/software/bash/manual/)** | Imperative, Procedural | Dynamic, Weak | N/A | Automation, System |
| **[Assembly](https://www.nasm.us/)** | Imperative | Strong | Manual | Critical, High-performance, System |
| **[Erlang](https://www.erlang.org/)** | Concurrent, Functional | Dynamic, Strong | Automatic | System |
| **[MATLAB](https://www.mathworks.com/products/matlab.html)** | Procedural | Dynamic, Strong | Automatic | Data Science |
| **[F#](https://fsharp.org/)** | Functional | Static, Strong | Automatic | Data Science |
| **[Carbon](https://docs.carbon-lang.dev/g)** | Generic, OOP, Procedural | Static, Strong | Hybrid | System |
| **[Zig](https://ziglang.org/)** | Imperative, Procedural | Static, Strong | Manual | System |

### Frameworks and Tools

| Technology | Language | Description | Usage | Platform |
| :--- | :--- | :--- | :--- | :--- |
| **[React.js](https://react.dev/)** | CSS, HTML, JavaScript | Web user interfaces with states. | Front-End | Web App |
| **[Vue.js](https://vuejs.org/)** | CSS, HTML, JavaScript | Progressive web user interfaces with reactivity. | Front-End | Web App |
| **[Angular](https://angular.dev/)** | CSS, HTML, JavaScript | Single Page Application | Front-End | Web App |
| **[Svelte](https://svelte.dev/)** | CSS, HTML, JavaScript | Web user interfaces reactivity. | Front-End | Web App |
| **[SolidJS](https://www.solidjs.com/)** | CSS, HTML, JavaScript | Optimized web user interfaces. | Front-End | Web App |
| **[Alpine](https://alpinejs.dev/)** | CSS, HTML, JavaScript | Rugged, minimal tool for composing behavior directly in your markup. | Front-End | Web App |
| **[Inferno](https://infernojs.org/)** | CSS, HTML, JavaScript | Insanely fast, React-like library for high-performance UIs. | Front-End | Web App |
| **[Docusaurus](https://docusaurus.io/)** | CSS, HTML, JavaScript, Markdown | Web framework for building documentation sites. | Front-End | Web App |
| **[Lume](https://lume.land/)** | CSS, HTML, JavaScript | Static Site Generator for Deno. | Front-End | Web App |
| **[Qwik](https://qwik.dev/)** | CSS, HTML, JavaScript | Web framework delivering instant loading web applications at any size. | Front-End | Web App |
| **[Marko](https://markojs.com/)** | CSS, HTML, JavaScript | Re-imagines HTML as a language for building dynamic and reactive UIs. | Front-End | Web App |
| **[Astro](https://astro.build/)** | CSS, HTML, JavaScript | Island based development environment integrated with various frameworks. | Environment | Server, Web App |
| **[Bun](https://bun.sh/)** | JavaScript | Fast, all-in-one JavaScript, TypeScript & JSX toolkit. | Environment | Server, Web App |
| **[Deno](https://deno.com/)** | JavaScript | Open source runtime for JavaScript, TypeScript, and WebAssembly. | Back-End | System |
| **[Hono](https://hono.dev/)** | JavaScript | Small, simple, and fast web framework built on Web Standards. | Back-End | Server |
| **[Webpack](https://webpack.js.org/)** | JavaScript | Legacy module bundler for packaging projects into optimized browser files. | Front-End | Bundler |
| **[Vite](https://vitejs.dev/)** | JavaScript | Framework based, native ESM server built upon Rollup and esbuild. | Front-End | Bundler |
| **[Parcel](https://parceljs.org/)** | JavaScript | Build tool designed for a zero-configuration experience. | Front-End | Bundler |
| **[esbuild](https://esbuild.github.io/)** | JavaScript | Quick bundler, minifier, and transpiler used as a high-speed component. | Front-End | Bundler |
| **[Turbopack](https://turbo.build/pack)** | JavaScript | High-performance bundler developed by the Vercel team. | Front-End | Bundler |
| **[Rollup](https://rollupjs.org/)** | JavaScript | Specialized bundler focused on small and efficient output bundles. | Front-End | Bundler |
| **[Babel](https://babeljs.io/)** | JavaScript | JavaScript Transpiler. | Front-End | Bundler |
| **[Node.js](https://nodejs.org/)** | JavaScript | Cross-platform runtime for servers, web apps, and command line tools. | Back-End | Server |
| **[Express](https://expressjs.com/)** | JavaScript | Minimalist REST API server. | Back-End | RESTful |
| **[Fastify](https://www.fastify.io/)** | JavaScript | Optimized REST API server. | Back-End | RESTful |
| **[Nest JS](https://nestjs.com/)** | JavaScript | Flexible enterprise grade server applications. | Back-End | On Top Server |
| **[oak](https://oakserver.github.io/oak/)** | JavaScript | Middleware framework for handling HTTP requests (Deno, Node, Bun). | Back-End | Server |
| **[Next.js](https://nextjs.org/)** | CSS, HTML, JavaScript | Simple React complete applications with server side processing. | Full Stack | Server, Web App |
| **[Remix](https://remix.run/)** | CSS, HTML, JavaScript | Simple standardized React web application framework. | Full Stack | Server, Web App |
| **[Nuxt](https://nuxt.com/)** | CSS, HTML, JavaScript | Simple Vue complete applications with server side processing. | Full Stack | Server, Web App |
| **[Analog](https://analogjs.org/)** | CSS, HTML, JavaScript | Simple Angular complete applications with server side processing. | Full Stack | Server, Web App |
| **[SvelteKit](https://kit.svelte.dev/)** | CSS, HTML, JavaScript | Simple Svelte complete applications with server side processing. | Full Stack | Server, Web App |
| **[Fresh](https://fresh.deno.dev/)** | CSS, HTML, JavaScript | Small, fast and extensible full stack web framework built on Web Standards. | Front-End | Web App |
| **[Meteor](https://docs.meteor.com/about/build-tool)** | CSS, HTML, JavaScript | A full-stack JavaScript platform for developing modern web and mobile applications. | Full Stack | Hybrid, Web App, Native |
| **[Jinja2](https://jinja.palletsprojects.com/)** | CSS, HTML, Python | Templating engine with embedded content. | Front-End | Templates |
| **[PyJSX](https://github.com/tomasr8/pyjsx)** | HTML, JavaScript, Python | Module for writing JSX code within Python. | Front-End | Web App |
| **[Django](https://www.djangoproject.com/)** | CSS, HTML, Python | Complete Python web applications (models, views, templates). | Full Stack | Server, Templates, Web App |
| **[Django REST Framework](https://www.django-rest-framework.org/)** | Python | Complete Python web toolkit for JSON APIs. | Back-End | RESTful |
| **[Flask](https://flask.palletsprojects.com/)** | Python | Simple Python web applications and server side processing. | Back-End | WSGI |
| **[FastAPI](https://fastapi.tiangolo.com/)** | Python | High performance asynchronous REST APIs. | Back-End | ASGI |
| **[Thymeleaf](https://www.thymeleaf.org/)** | CSS, HTML, Java | Server side natural templating engine. | Front-End | Templates |
| **[Apache FreeMarker](https://freemarker.apache.org/)** | CSS, FTL, HTML, Java | Presentation layer templating engine. | Front-End | Templates |
| **[Spring](https://spring.io/)** | Groovy, Java, Kotlin | Full ecosystem of tools and frameworks for myriad purposes. | Ecosystem | Multiple |
| **[Grails](https://grails.org/)** | Groovy | Groovy-based web framework for JVM built on top of Spring Boot. | Back-End | On Top Server, RESTful, Server |
| **[Micronaut](https://micronaut.io/)** | Groovy, Java, Kotlin | Servers, services and tools with modular efficiency. | Environment | Server, System |
| **[Quarkus](https://quarkus.io/)** | Groovy, Java, Kotlin | Kubernetes-native cloud-first containerized environments. | Back-End | On Top Server, Server, System |
| **[ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/)** | C# | Web framework with various client and server side alternatives. | Full Stack | Server, Templates, Web App |
| **[Blade](https://laravel.com/docs/blade)** | CSS, HTML, PHP | Templating engine for embedding PHP (Laravel). | Front-End | Templates |
| **[Laravel](https://laravel.com/)** | HTML, PHP | MVC web framework. Provides a complete ecosystem for web development. | Back-End | Server |
| **[Symfony](https://symfony.com/)** | PHP | Build scalable, high-performance web applications with reusable components. | Full Stack | Server, Web App |
| **[Livewire](https://livewire.laravel.com/)** | CSS, HTML, PHP | Dynamic reactivity web apps built on Blade and Laravel. | Full Stack | Server, Web App |
| **[Inertia.js](https://inertiajs.com/)** | JavaScript, Multiple | Multi-platform hybrid SPAs bridging front end and back end. | Full Stack | Hybrid, Server, Web App |
| **[Hotwire](https://hotwired.dev/)** | HTML, Ruby | SSR Web UI templating for SPA reactivity. | Front-End | Templates |
| **[Ruby on Rails](https://rubyonrails.org/)** | CSS, HTML, JavaScript, Ruby | MVC web framework. | Full Stack | Server, Web App |
| **[Phoenix](https://www.phoenixframework.org/)** | Elixir | MVC web framework with SPA UI SSR. | Full Stack | Server, Templates, Web App |
| **[Fiber](https://gofiber.io/)** | Go | Fast HTTP engine, performant and quick. | Back-End | Server |
| **[Gin](https://gin-gonic.com/)** | Go | API web framework with fast performance. | Back-End | Server |
| **[Beego](https://github.com/beego/beego)** | Go | Enterprise application server development. | Back-End | RESTful, Server |
| **[axum](https://docs.rs/axum/latest/axum/)** | Rust | Web application framework that focuses on ergonomics and modularity. | Back-End | Server |
| **[Rocket](https://rocket.rs/)** | Rust | Fast, type safe, secure web application framework. | Back-End | RESTful |
| **[Actix Web](https://actix.rs/)** | Rust | Micro HTTP framework for web applications. | Back-End | Server |
| **[Unreal Engine](https://www.unrealengine.com/)** | Blueprints, C++, Python | Epic Games 3D production and game engine. | Engine | Desktop, Game, Native |
| **[Unity](https://unity.com/)** | C# | Multi-purpose game engine. | Engine | Desktop, Game, Native, Web App |
| **[Godot](https://godotengine.org/)** | C#, GDScript | Open source 2D and 3D game engine. | Engine | Desktop, Game, Native, Web App |
| **[Android SDK](https://developer.android.com/)** | Java, Kotlin, XML | Native mobile Android apps development. | Front-End | Native |
| **[Jetpack Compose](https://developer.android.com/compose)** | Kotlin | Declarative UI toolkit for Android; cross platform support possible. | Front-End | Hybrid, Native |
| **[Flutter](https://flutter.dev/)** | Dart | Google’s open source cross platform framework for native apps. | Front-End | Desktop, Native, Web App |
| **[React Native](https://reactnative.dev/)** | JavaScript | Facebook’s cross platform framework for native apps. | Front-End | Hybrid, Native, Web App |
| **[Ionic](https://ionicframework.com/)** | CSS, HTML, JavaScript | WebView integrated native apps (React, Angular, Vue). | Front-End | Hybrid, Native |
| **[Flame](https://flame-engine.org/)** | Dart | Flutter based 2D modular game engine. | Engine | Desktop, Game, Native, Web App |
| **[Kivy](https://kivy.org/)** | Python | Cross platform GUI apps; codebase single. | Front-End | Desktop, Native |
| **[Tkinter](https://docs.python.org/3/library/tkinter.html)** | Python | Tcl/Tk based desktop GUI toolkit. | Front-End | Desktop |
| **[.NET MAUI](https://dotnet.microsoft.com/en-us/apps/maui)** | C# | Cross platform open source native and desktop apps. | Full Stack | Desktop, Native |
| **[Electron](https://www.electronjs.org/)** | CSS, HTML, JavaScript | Embedded native desktop applications using web libraries. | Front-End | Desktop, Hybrid |
| **[Tauri](https://tauri.app/)** | CSS, HTML, JavaScript, Kotlin, Rust | Embedded Rust binaries with web stack for desktop apps. | Full Stack | Desktop |
| **[Avalonia UI](https://avaloniaui.net/)** | C# | Cross platform UI framework with WPF for desktop/embedded. | Full Stack | Desktop |
| **[Qt](https://www.qt.io/)** | QML | Libraries and APIs for powerful UI and core functionality. | Ecosystem | Hybrid, Multiple, System |
| **[MySQL](https://www.mysql.com/)** | SQL | Relational database management system. | Database | System |
| **[MariaDB](https://mariadb.org/)** | SQL | Open source improved RDBMS. | Database | System |
| **[SQLite](https://www.sqlite.org/)** | SQL | Lightweight embedded database. | Database | Native |
| **[SQL Server](https://www.microsoft.com/en-us/sql-server/)** | SQL | Enterprise relational database management system. | Database | Server |
| **[PostgreSQL](https://www.postgresql.org/)** | SQL | Object-relational database management system. | Database | Server, System |
| **[MongoDB](https://www.mongodb.com/)** | JSON | NoSQL document database. | Database | System |
| **[DynamoDB](https://aws.amazon.com/dynamodb/)** | JSON | Serverless NoSQL AWS database. | Database | Hybrid, System |
| **[Neo4j](https://neo4j.com/)** | Cypher | Graph database for complex relationships. | Database | Hybrid, System |
| **[Redis](https://redis.io/)** | Redis CLI | In-memory key value store. | Database | System |
| **[Cassandra](https://cassandra.apache.org/)** | CQL | Distributed NoSQL optimized for heavy workloads. | Database | System |
| **[InfluxDB](https://www.influxdata.com/)** | Flux | Time series database for metrics and monitoring. | Database | System |
| **[Scikit-learn](https://scikit-learn.org/)** | Python | Library for classical and simple machine learning. | Engine | Multiple, System |
| **[Tensorflow](https://www.tensorflow.org/)** | JavaScript, Python | Google’s open source ML toolkit with scaling. | Engine | Multiple, Server |
| **[PyTorch](https://pytorch.org/)** | Python | Facebook’s ML framework; flexible and cross platform. | Engine | Hybrid, Server |
| **[OpenCV](https://opencv.org/)** | C++, Java, JavaScript, Python | Library for computer vision and image processing. | Engine | System |
| **[Keras](https://keras.io/)** | Python | High level neural network API for Tensorflow. | Engine | Hybrid, System |
| **[gRPC](https://grpc.io/)** | Multiple | Agnostic remote procedure call framework. | Back-End | Hybrid, Server |
| **[Socket.IO](https://socket.io/)** | JavaScript, Multiple | Real time bidirectional communication (WebSockets). | Back-End | Hybrid, Web App |
| **[Selenium](https://www.selenium.dev/)** | C#, Java, JavaScript, Python, Ruby | Automating web applications for testing/admin tasks. | Engine | Testing, Web App |
| **[Cypress](https://www.cypress.io/)** | JavaScript | Fast, modern test automation for end-to-end testing. | Engine | Testing, Web App |
| **[Appium](https://appium.io/)** | C#, Java, JavaScript, Python, Ruby | Cross-platform mobile testing (native, hybrid, web). | Engine | Testing |
| **[Katalon Studio](https://katalon.com/)** | Groovy, Java, Kotlin | All-in-one test automation for web, API, mobile, desktop. | Engine | Testing |
| **[JUnit](https://junit.org/)** | Java | Unit-testing framework for Java applications. | Engine | Testing |
| **[NUnit](https://nunit.org/)** | C# | Unit-testing framework for .NET applications. | Engine | Testing |
| **[Robot Framework](https://robotframework.org/)** | Java, Python | Keyword-driven automation for acceptance testing/RPA. | Engine | Testing |
| **[Cucumber](https://cucumber.io/)** | Java, JavaScript, Kotlin, Ruby | BDD framework enabling tests in natural language. | Engine | Testing |
| **[Mocha](https://mochajs.org/)** | JavaScript | Feature-rich testing framework for Node.js applications. | Engine | Server, Testing |
| **[Playwright](https://playwright.dev/)** | C#, JavaScript, Python | Modern, fast automation for web applications. | Engine | Testing |
| **[Fitnesse](http://fitnesse.org/)** | C#, Java | Web-based wiki-style framework for acceptance testing. | Engine | Testing |
| **[XCTest](https://developer.apple.com/documentation/xctest)** | Objective-C, Swift | Apple’s native testing for iOS and macOS. | Engine | System, Testing |
| **[Espresso](https://developer.android.com/training/testing/espresso)** | Java, Kotlin | UI testing for Android applications. | Engine | Native, Testing |
| **[TestNG](https://testng.org/)** | Java | Powerful testing framework with parallel execution. | Engine | Testing |
| **[JBehave](https://jbehave.org/)** | Java | BDD framework for Java. | Engine | Testing |
| **[Lagom](https://www.lagomframework.com/)** | Java, Scala | Building reactive microservices. | Engine | Testing |
| **[WireMock](https://wiremock.org/)** | Java | Tool for simulating HTTP-based APIs. | Engine | Testing |
| **[PyTest](https://docs.pytest.org/)** | Python | Unit, integration, and functional testing in Python. | Engine | Testing |
| **[Vwo Test](https://vwo.com/testing/)** | | Visual testing platform focusing on no-code. | Engine | Testing |
| **[Telerik Test Studio](https://www.telerik.com/teststudio)** | C#, JavaScript | Automation tool for web, desktop, and mobile. | Engine | Testing |
| **[Concordion](https://concordion.org/)** | HTML, Java | Lightweight framework for BDD in Java. | Engine | Testing |
| **[Minitest](https://docs.seattlerb.org/minitest/)** | Ruby | Unit testing in Ruby. | Engine | Testing |
| **[Detox](https://wix.github.io/Detox/)** | JavaScript | End-to-end mobile UI testing for React Native. | Engine | Testing |
| **[TestCafe](https://testcafe.io/)** | JavaScript | Node.js-based framework without WebDriver. | Engine | Testing |
| **[Puppeteer](https://pptr.dev/)** | JavaScript | API to control Chrome or Firefox over DevTools. | Engine | Testing |
| **[WebDriverIO](https://webdriver.io/)** | JavaScript | Progressive automation for modern web/mobile apps. | Engine | Testing |
| **[Jest](https://jestjs.io/)** | JavaScript | Testing framework ensuring correctness of JS codebase. | Engine | Testing |
| **[Jasmine](https://jasmine.github.io/)** | JavaScript | Framework for testing JS; browser and Node.js. | Engine | Testing |
| **[Spock](https://spockframework.org/)** | Groovy, Java | Testing and specification framework. | Engine | Testing |
| **[Maestro](https://maestro.mobile.dev/)** | YAML | End-to-end testing for Mobile and Web apps. | Engine | Testing |
| **[Gauge](https://gauge.org/)** | Multiple | Open source framework for acceptance tests. | Engine | Testing |
| **[Nightwatch.js](https://nightwatchjs.org/)** | JavaScript | End to end testing on desktop & mobile browsers. | Engine | Testing |
| **[Selenide](https://selenide.org/)** | Java | Framework powered by Selenium WebDriver. | Engine | Testing |
| **[Takio](https://taiko.dev/)** | JavaScript | Node.js library to automate Chromium/Firefox. | Engine | Testing |
| **[PHPUnit](https://phpunit.de/)** | PHP | Unit testing framework for PHP. | Engine | Testing |
| **[XCUITest](https://developer.apple.com/documentation/xctest)** | Objective-C, Swift | Appium driver for iOS automation. | Engine | Testing |
| **[Geb](https://www.gebish.org/)** | Groovy | Combines WebDriver with jQuery-style selection. | Engine | Testing |
| **[QUnit](https://qunitjs.com/)** | JavaScript | Designed for unit and integration front-end testing. | Engine | Testing |
| **[RSPec](https://rspec.info/)** | Ruby | Behaviour Driven Development for Ruby. | Engine | Testing |
| **[Reqnroll](https://reqnroll.net/)** | | Cucumber-style BDD for .NET. | Engine | Testing |
| **[MSTest](https://github.com/microsoft/testfx)** | C# | Microsoft Testing Framework for .NET. | Engine | Testing |
| **[Behave](https://behave.readthedocs.io/)** | Python | Behavior-driven development, Python style. | Engine | Testing |
| **[JMeter](https://jmeter.apache.org/)** | Java | Performance, load, and functional testing for web services. | Engine | Testing, Web App |

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
| **[Amazon Web Services (AWS)](https://aws.amazon.com/)** | Provides the largest collection of on-demand cloud computing resources, APIs, and managed services. | Usage | Cloud Hosting, IaaS, Managed Services |
| **[Google Cloud Platform (GCP)](https://cloud.google.com/)** | Offers scalable public cloud infrastructure and specialized services for data analytics and containerization. | Usage | Cloud Hosting, Containers, Data Analytics |
| **[Microsoft Azure](https://azure.microsoft.com/)** | Provides cloud services built for enterprise, hybrid, and proprietary systems integration. | Usage | Cloud Hosting, Hybrid Hosting, IaaS |
| **[DigitalOcean](https://www.digitalocean.com/)** | Provides virtual private servers (Droplets) and managed infrastructure with a focus on simplicity and ease of use. | Subscription | Deployment, Managed Services, VPS |
| **[Linode (Akamai)](https://www.linode.com/)** | Offers high-performance Linux virtual machines (VMs) and supporting cloud infrastructure. | Subscription | VMs, VPS |
| **[Vercel](https://vercel.com/)** | Offers high-performance Linux virtual machines (VMs) and supporting cloud infrastructure. | Usage | Front-End Hosting, Static Hosting |
| **[Netlify](https://www.netlify.com/)** | A platform for static sites and serverless functions, featuring automatic build and deployment from Git. | Usage | Serverless Functions, Static Hosting |
| **[GitHub Pages](https://pages.github.com/)** | A static site hosting service integrated directly with Git repositories for simple web publishing. | Subscription | Front-End Hosting, Static Hosting |
| **[Hostinger](https://www.hostinger.com/)** | Provides budget-focused shared hosting, managed WordPress, and virtual private server packages. | Subscription | Static Hosting, VPS |
| **[EAS Hosting](https://expo.dev/eas)** | A service integrated with Expo for deploying web projects, API routes, and server functions to the edge. | Usage | API, Front-End Hosting |
| **[Supabase](https://supabase.com/)** | An open-source Backend-as-a-Service (BaaS) that provides managed PostgreSQL, Auth, and real-time APIs. | Usage | BaaS, DB Provider, Real-Time Data |
| **[Heroku](https://www.heroku.com/)** | A managed Platform-as-a-Service (PaaS) that handles server operations, allowing focus on code deployment. | Subscription | Deployment, PaaS |
| **[Firebase](https://firebase.google.com/)** | Google's BaaS offering for web and mobile development, including NoSQL database and authentication. | Usage | BaaS, Containers, DB Provider, Deployment, PaaS |
| **[Render](https://render.com/)** | A unified cloud platform for hosting web services, databases, and Docker containers with automatic scaling. | Subscription | DB Provider |
| **[MongoDB Atlas](https://www.mongodb.com/atlas)** | The official cloud service for managed MongoDB (NoSQL) document databases. | Usage | DB Provider |
| **[PlanetScale](https://planetscale.com/)** | A serverless MySQL platform offering sharding, scalability, and non-blocking database branching. | Subscription | BaaS, DB Provider |
| **[Neon](https://neon.tech/)** | A serverless PostgreSQL solution designed for cost-efficiency by separating storage and compute. | Usage | BaaS, DB Provider |
| **[Twilio](https://www.twilio.com/)** | Provides APIs for programmatic communication including SMS, Voice, and Video services. | Usage | API |
| **[Redis Cloud](https://redis.io/cloud/)** | The managed service for the high-performance Redis Key-Value and in-memory data structure store. | Usage | DB Provider |
| **[SendGrid](https://sendgrid.com/)** | An API specializing in the reliable delivery of transactional and marketing emails. | Volume | API |
| **[Stripe](https://stripe.com/)** | A platform for developers to accept and manage online payments, subscriptions, and payouts. | Transaction | API |
| **[Auth0](https://auth0.com/)** | An identity management platform that provides authentication and authorization services via API. | Volume | API |
| **[Google Maps Platform](https://mapsplatform.google.com/)** | Provides APIs for integrating detailed maps, location data, and routing services into applications. | Usage | API |
| **[Algolia](https://www.algolia.com/)** | An API that provides instant, typo-tolerant search-as-a-service for applications. | Volume | API |
| **[Datadog](https://www.datadoghq.com/)** | A unified platform for monitoring, logging, and performance metrics across the entire application stack. | Subscription | API |
| **[Sentry](https://sentry.io/)** | Real-time error tracking and performance monitoring for capturing and analyzing application exceptions. | Volume | API |
| **[Infinityfree](https://www.infinityfree.com/)** | A provider offering completely free, basic shared web hosting with support for PHP and MySQL. | Usage | Back-End Hosting, Front-End Hosting |
| **[Deno Deploy](https://deno.com/deploy)** | Singular simple platform to host JavaScript and TypeScript applications. | Subscription | Back-End Hosting, Front-End hosting |
| **[Zeabur](https://zeabur.com/)** | Deployment platform for full-stack applications with automatic scaling and Git integration. | Usage | Deployment, PaaS |
| **[Tencent Cloud](https://www.tencentcloud.com/)** | Comprehensive suite of global cloud computing services including IaaS and AI solutions. | Usage | Cloud Hosting, IaaS, Managed Services |
| **[OVHcloud](https://www.ovhcloud.com/)** | European cloud provider offering bare metal, hosted private cloud, and public cloud solutions. | Subscription | Cloud Hosting, IaaS, VPS |
| **[Cloudflare](https://www.cloudflare.com/)** | Provides web security, content delivery network (CDN), and serverless computing services. | Subscription | API, Serverless Functions, Static Hosting |
| **[Another Web Service](https://container-hosting.anotherwebservice.com/)** | Cloud platform specialized in simplified container hosting and web service deployment. | Subscription | Containers, Managed Services |
| **[Linode (Akamai)](https://www.linode.com/)** | High-performance SSD Linux servers for a variety of cloud-based applications and workloads. | Subscription | VMs, VPS |
| **[Red Hat](https://www.redhat.com/)** | Enterprise open-source solutions including hybrid cloud infrastructure and container orchestration. | Subscription | Containers, PaaS |
| **[Salesforce](https://www.salesforce.com/)** | Cloud-based software as a service (SaaS) and platform as a service (PaaS) for customer relationship management. | Subscription | PaaS, Managed Services |
| **[JFrog](https://jfrog.com/)** | Binary repository and software supply chain platform for DevOps and continuous delivery. | Subscription | Managed Services, Deployment |
| **[Hetzner](https://www.hetzner.com/)** | Reliable web hosting and cloud server provider known for high-performance hardware and cost efficiency. | Usage | Cloud Hosting, IaaS, VPS |
| **[IBM Cloud](https://www.ibm.com/cloud)** | Full-stack cloud platform including public, private, and hybrid environments with enterprise focus. | Usage | Cloud Hosting, IaaS, PaaS |
| **[Alibaba Cloud](https://www.alibabacloud.com/)** | Leading cloud computing company providing a comprehensive suite of global cloud services. | Usage | Cloud Hosting, IaaS, Managed Services |
| **[Oracle Cloud](https://www.oracle.com/cloud/)** | Generation 2 enterprise cloud offering integrated IaaS, PaaS, and managed database services. | Usage | Cloud Hosting, IaaS, DB Provider |
| **[Apollo](https://www.apollographql.com/pricing)** | API Orchestration Platform for AI Agents, Web, and Mobile Apps. | Usage | API |
| **[SonarQube](https://www.sonarqube.org/)** | Self-managed tool for continuous inspection of code quality and security analysis. | Subscription | Managed Services, Deployment |
| **[ArgoCD](https://argoproj.github.io/cd/)** | Declarative GitOps tool for automating the deployment of applications to Kubernetes. | Usage | Deployment, Orchestration |
| **[Kubernetes](https://kubernetes.io/)** | Open-source system for automating deployment, scaling, and management of containerized apps. | Usage | Containers, Orchestration |
| **[Helm](https://helm.sh/)** | A package manager that simplifies the definition, installation, and upgrade of K8s apps. | Usage | Managed Services, Orchestration |
| **[Ansible](https://www.ansible.com/)** | IT automation tool that automates configuration management and application deployment. | Subscription | Deployment, Managed Services |
| **[Terraform](https://www.terraform.io/)** | Tool for building, changing, and versioning cloud infrastructure using configuration files. | Usage | IaC, Deployment |
| **[Grafana](https://grafana.com/)** | Multi-platform analytics and interactive visualization web application for metrics and logs. | Subscription | Observability |
| **[Prometheus](https://prometheus.io/)** | Systems monitoring and alerting toolkit with a multi-dimensional data model. | Usage | Observability |
| **[Elastic Stack](https://www.elastic.co/)** | Set of tools used for search, analysis, and visualization of data in real-time. | Usage | Observability, Data Analytics |
| **[New Relic](https://newrelic.com/)** | Cloud-based software that helps monitor the performance of web apps and infrastructure. | Usage | API, Observability |
| **[Jenkins](https://www.jenkins.io/)** | Open-source automation server used to automate the building, testing, and delivery of code. | Usage | CI/CD, Deployment |
| **[GitLab](https://about.gitlab.com/)** | Web-based Git repository manager providing wiki, issue-tracking, and CI/CD pipeline features. | Subscription | CI/CD, Deployment |
| **[Docker](https://www.docker.com/)** | Set of platform as a service products that use OS-level virtualization to deliver software in containers. | Subscription | Containers, Deployment |
| **[Podman](https://podman.io/)** | A daemonless container engine for developing, managing, and running OCI containers. | Usage | Containers, Deployment |
| **[Vagrant](https://www.vagrantup.com/)** | A tool for building and managing virtual machine environments in a single workflow. | Usage | Virtualization, Managed Services |
| **[Snyk](https://snyk.io/)** | Developer-first platform that finds and fixes vulnerabilities in dependencies and containers. | Usage | SCA, Containers |
| **[Trivy](https://trivy.dev/)** | A fast, comprehensive security scanner for vulnerabilities in container images and file systems. | Usage | SCA, Containers |
| **[HashiCorp Vault](https://www.vaultproject.io/)** | Secures, stores, and tightly controls access to tokens, passwords, certificates, and API keys. | Subscription | Secrets Management |
| **[OWASP ZAP](https://www.zaproxy.org/)** | An open-source tool that performs dynamic security testing against your running web applications. | Usage | AppSec, Testing |
| **[Checkmarx](https://checkmarx.com/)** | Enterprise-grade static analysis tool that identifies security vulnerabilities in your source code. | Subscription | AppSec, Managed Services |
| **[Wiz](https://www.wiz.io/)** | Cloud-native security platform that scans your entire cloud infrastructure for risks and leaks. | Subscription | Cloud Hosting, Observability |
| **[Gitleaks](https://github.com/gitleaks/gitleaks)** | Lightweight tool used to detect and prevent hardcoded secrets like passwords and keys in Git repos. | Usage | Secrets Management |
| **[Koyeb](https://www.koyeb.com/)** | Serverless platform that allows you to deploy Docker containers, web apps, and APIs. | Usage | Back-End Hosting, Containers, PaaS |
| **[Aiven](https://aiven.io/)** | Open-source data platform providing databases like MySQL, PostgreSQL, and Redis | Usage | DB Provider, Managed Services |
