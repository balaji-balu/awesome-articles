### [16 June 2023]
Valgrind
NASA power of 10

### [4 June 2023]

[Zulip](https://zulip.com/) - Slack Alternative

[SupaDemo](https://supademo.com/) - Transform your workflow into an interactive demo, instantly.
Supademo is the fastest way to create interactive product demos or guides. Share or embed in support docs, websites or in your favorite tools. For free.

[Mastadon](https://joinmastodon.org/) - Social networking that's not for sale.
Your home feed should be filled with what matters to you most, not what a corporation thinks you should see. Radically different social media, back in the hands of the people.

### [2 June 2023]
[Little things and big things: lessons for building large systems. Peter van Roy @Code BEAM Lite Sto](https://www.youtube.com/watch?v=h8sE3Ai8Dsk)
Youtube

### [3 May 2023]
[Bootlin](https://bootlin.com/docs/) - formerly free electrons. Free training materials and conference presentations from Bootlin, covering kernel, real-time, Android, embedded Linux system and device driver development.

[500 lines or less](https://aosabook.org/en/)

### [2 May 2023]
[freeRTOS](https://www.freertos.org/index.html): open source Real-time operating system for microcontrollers

awesome books on open source applications and their design/architecture

[Teach Tech Together](https://teachtogether.tech/en/index.html) : 

[Software design by example in javascript](https://third-bit.com/sdxjs/)

[Javascript for data science](https://third-bit.com/js4ds/)

[Research software engineering using python](https://merely-useful.tech/py-rse/index.html)



### [25 Apr 2023]
[Port](https://www.getport.io/) - [Backstage](https://backstage.io/) Alternative. Internal Platform UI. [Video from devops toolkit](https://www.youtube.com/watch?v=ro-h7tsp0qI)

### [12 Apr 2023]
[swirlai newsletter](https://www.newsletter.swirlai.com/): . visual

### [11 Apr 2023]

FURPS+ : 
FURPS is an acronym representing a model for classifying software quality attributes (functional and non-functional requirements):

- **Functionality** - Capability (Size & Generality of Feature Set), Reusability (Compatibility, Interoperability, Portability), Security (Safety & Exploitability)

- **Usability** (UX) - Human Factors, Aesthetics, Consistency, Documentation, Responsiveness

- **Reliability** - Availability (Failure Frequency (Robustness/Durability/Resilience), Failure Extent & Time-Length (Recoverability/Survivability)), Predictability (Stability), Accuracy (Frequency/Severity of Error)

- **Performance** - Speed, Efficiency, Resource Consumption (power, ram, cache, etc.), Throughput, Capacity, Scalability

- **Supportability** (Serviceability, Maintainability, Sustainability, Repair Speed) - Testability, Flexibility (Modifiability, Configurability, Adaptability, Extensibility, Modularity), Installability, Localizability

Cross functional requirements:
- sometimes called as Non-functional requirements
- also called as architecture drivers
- quality attributes (in software architecture in practice book)

### [7 Apr 2023]

[Refactoring Databases](), Book
- is a simple change to a database schema that improves its design while retaining both its behavioral and informational semantics. 
- In other words you cannot add new functionality or break exisiting functionality nor can you add new data or change the meaning of existing data. 
- a database schema includes both structural aspects, such as table and view definitions, and functional aspects, such as stored procedures and triggers.
- 
k8s, [init containers](https://kubernetes.io/docs/concepts/workloads/pods/init-containers/) : specialized containers that run before app containers in a Pod. Init containers can contain utilities or setup scripts not present in an app image.

[Atlas](https://atlasgo.io/), open-source schema migration tool : Running Schema migrations

Working in Small Batches
- part of [Devops Process capabilities](https://cloud.google.com/architecture/devops/devops-process-working-in-small-batches)
- Small batches permit us to deliver results faster, with higher quality and less stress.
- [faster feedback](https://queue.acm.org/detail.cfm?id=2945077) is the biggest win 
- architecture, code, database: all together deployed as single unit 
- encourages experimentation
- ci, cd pipelines support small batches approach
- refactoring databases in small batches: small and simple change
- easy to undo changes 
- supports evolutionary architecture thinking
- Select small stories, implement, deploy, test fast

### [6 Apr 2023]

[Martin Fowler on adding slacks in planning](https://martinfowler.com/bliki/Slack.html)

[Slack: Art of Agile Development, 2nd edition](https://www.jamesshore.com/v2/books/aoad2/slack), James Shore

[Anti-patterns of event driven architecture](https://www.linkedin.com/pulse/anti-patterns-event-driven-architecture-arpit-jain/), Arpit Jain

[Event-driven architecture style](https://learn.microsoft.com/en-us/azure/architecture/guide/architecture-styles/event-driven), Microsoft Azure

### [5 Apr 2023]

**Microsoft rearchitect the client app**

[source](https://techcommunity.microsoft.com/t5/microsoft-teams-blog/microsoft-teams-advantages-of-the-new-architecture/ba-p/3775704?ck_subscriber_id=2077780040)

+ Fluent UI
+ Reactjs from angular
+ webview2 from Electron framework
+ Data access layer on separated worker thread + IndexDB + GraphQL Schema

### [2 Apr 2023]
[Idioms for Building Fault-tolerant Applications with Elixir • José Valim • YOW! 2021](https://www.youtube.com/watch?v=mkGq1WoEvI4)

### [1 Apr 2023]

[Scaling Mastodon](https://docs.joinmastodon.org/admin/scaling/): Scaling Mastodon servers

[Leaving the Basement](https://community.hachyderm.io/blog/2022/12/03/leaving-the-basement/) : 
Hachyderm has reached 30,000 users. A ‘small sized’ service in regard to scale. However, in the process we have hit very familiar ‘medium sized’ scale problems which caused us to migrate our services out of my basement. This is the outage report, post mortem, and high level overview of the process of migrating to Hetzner in Germany. From observation to production fixes. This is the story.
### [31 mar 2023]

[Architecure qualities](https://github.com/mtnygard/architecture-qualities) Michael Nygard, mtnygard

[Arch Pattern Cards](https://github.com/mtnygard/arch-pattern-cards) Michael Nygard, mtnygard

[Awesome CTO](https://github.com/mtnygard/awesome-cto) : Michael Nygard mtnygard

[Elixir: A guide to event handling](https://mkaszubowski.com/2021/01/09/elixir-event-handling.html), mkaszubowski.com blog: I enjoy all his articles

[Azure on Kubernetes](https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-kubernetes/) : Breden burns videos are excellent way to learn k8s

[How to use LISTEN and NOTIFY PostgreSQL commands in Elixir?](https://blog.lelonek.me/listen-and-notify-postgresql-commands-in-elixir-187c49597851) : 
How can you benefit from LISTEN and NOTIFY postgres database features in Elixir applications?


### [27 mar 2023]

**Architecture: Robustness Tactic**
- Rick Kazman [Tactics for software robustness](https://insights.sei.cmu.edu/blog/tactics-and-patterns-for-software-robustness/), SEI blog

**Microfrontends**
- vercel solutions: [microfrontends](https://github.com/vercel/examples/tree/main/solutions/microfrontends) : next.js zones, Turborepo, Design system with Tailwindcss, css modules, pages
- [changesets](https://github.com/changesets/changesets): Changesets to manage versions, create changelogs, and publish to npm. It hold two key bits of information: a version type (following semver), and change information to be added to a changelog. 
- Webpack [Module Federation](https://webpack.js.org/concepts/module-federation/) : Module federation is a strategy for building applications in a large organization with many teams that want to prioritize shipping velocity. We encourage you to research module federation as an option for helping teams build as a part of a large organization where teams may not have the opportunity to communicate and work together.

### [26 mar 2023]

**Learning Elixir**
- [Learn Elixir the hard way](https://github.com/WhiteRookPL/learn-elixir-the-hard-way) : intro to elixir, functional programming, concurrency and actor model, testing and performance evaluation
- [Concurrency and Actor Model](https://github.com/WhiteRookPL/learn-elixir-the-hard-way/blob/master/docs/concurrency-and-actor-model.md)
- [Real time communication at scale with Elixir at Discord](https://elixir-lang.org/blog/2020/10/08/real-time-communication-at-scale-with-elixir-at-discord/)

Introspection tools

- Discord's [Zen Monitor](https://github.com/discord/zen_monitor): Efficient Process.monitor replacement
- Discord's [Manifold](https://github.com/discord/manifold) : Fast batch message passing between nodes for Erlang/Elixir.

### [25 mar 2023]

🍊 [HTTP Analytics for 6M requests per second using ClickHouse](https://blog.cloudflare.com/http-analytics-for-6m-requests-per-second-using-clickhouse/)

### [23 mar 2023]

🍊 [Introducing workerd: the Open Source Workers runtime](https://blog.cloudflare.com/workerd-open-source-workers-runtime/)

[workerd](https://github.com/cloudflare/workerd) is a JavaScript / Wasm server runtime based on the same code that powers [Cloudflare Workers]().

SaaS patterns: [Single-tenant](https://samnewman.io/patterns/deployment/single-tenancy/), [Multi-tenant](https://samnewman.io/patterns/deployment/multi-tenancy/), [hybrid-tenant](https://samnewman.io/patterns/deployment/hybrid-tenancy/), Sam Newman

### [22 mar 2023]

😋 [Building ClickHouse Cloud From Scratch in a Year](https://clickhouse.com/blog/building-clickhouse-cloud-from-scratch-in-a-year), mar 2023, clickhouse team

🔶 [Building Microservices, 2nd Edition, Sam Newman](https://samnewman.io/books/building_microservices_2nd_edition/)

🥬 [Building Evolutionary Architecture](https://evolutionaryarchitecture.com/)

Software Architecture and Cost Tradeoff and Analysis ATAM, CTAM from [Software Architecture in Practice, 3rd Edition](https://resources.sei.cmu.edu/library/asset-view.cfm?assetid=30264)

🥬 Douglas Schmidt talks on [Pattern Oriented Software Architecture for concurrent and networking software](https://www.youtube.com/playlist?list=PLZ9NgFYEMxp6CHE-QQ040tlDILNcBqJnc), Youtube playlist

## I want to read this...

[Priniples of Reactive Programming using Akka Actors](https://www.reactivedesignpatterns.com/videos.html), Videos from [reactivedesignpatterns.com](https://www.reactivedesignpatterns.com)

Architecture Decision Records

[Scalable Microservices, Douglas Schmidt](https://www.youtube.com/playlist?list=PLZ9NgFYEMxp5dm-JKpo8kPuS_0d2kYjHz), Youtube playlist

ZeroMQ on [Architecture of Open Source Apllications(AOSA)](https://www.aosabook.org/en/zeromq.html)

[Scalable C](https://hintjens.gitbooks.io/scalable-c/content/index.html)

[Elixir School, Concurrency](https://elixirschool.com/en/lessons/intermediate/concurrency)


## Articles I liked ... 
[Basics - ZeroMQ Guide](https://zguide.zeromq.org/docs/chapter1/)

[Elixir and Kubernetes: A love story — Part 1: Setting up an Elixir Cluster
](https://david-delassus.medium.com/elixir-and-kubernetes-a-love-story-721cc6a5c7d5), Medium

[Cloud Native DevOps Explained, IBM Technology](https://www.youtube.com/watch?v=FzERTm_j2wE), Youtube video: Enjoined the simple way of explaining devops deployment pipeline - handling developer lifecycle to deployment  

[Managing Data Consistency in a microservices architecture using Sagas, Chris Richardson](https://www.slideshare.net/chris.e.richardson/microcph-managing-data-consistency-in-a-microservice-architecture-using-sagas)

[Tradeoff Analysis using ATAM, CTAM adapted to Agile](), Mark Richards, Youtube

[Measuring scalability using Fitness functions](https://www.developertoarchitect.com/lessons/lesson71.html), Mark Richards, Youtube 

[Tradeoff Analysis - Service Granularity](https://www.developertoarchitect.com/lessons/lesson145.html), Mark Richards, Youtube
