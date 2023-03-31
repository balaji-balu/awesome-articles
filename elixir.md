


**processes**: Processes are isolated from each other, run concurrent to one another and communicate via message passing. Processes are not only the basis for concurrency in Elixir, but they also provide the means for building distributed and fault-tolerant programs. When a message is sent to a process, the message is stored in the process mailbox.

**Tasks**: Tasks build on top of the spawn functions to provide better error reports and introspection 

**[Supervisor](https://hexdocs.pm/elixir/Supervisor.html)**:
- [Supervisor principles](https://erlang.org/documentation/doc-4.9.1/doc/design_principles/sup_princ.html) Erlang documentation

[GenServer](https://hexdocs.pm/elixir/GenServer.html): A behaviour module for implementing the server of a client-server relation. 
[elixir-lang on GenServer](https://elixir-lang.org/getting-started/mix-otp/genserver.html)

GenStage: 

Agent:

Flow
(Module)

Registry: A local, decentralized and scalable key-value process storage.

### Eco-system:

[PoolBoy](https://elixirschool.com/en/lessons/misc/poolboy) : You can easily exhaust your system resources if you do not limit the maximum number of concurrent processes that your program can spawn. Poolboy is a widely used lightweight, generic pooling library for Erlang that addresses this issue.

[Broadway](https://hexdocs.pm/broadway/introduction.html): is a library for building concurrent and multi-stage data ingestion and data processing pipelines with Elixir. Broadway pipelines are concurrent and robust, thanks to the Erlang VM and its actors. Built on top of GenStage.

**[Cowboy](https://github.com/ninenines/cowboy)**: Small, fast, modern HTTP server for Erlang/OTP. Phoenix uses these underneath for web server functions.

Peerage: connecting the nodes

livebook: jupyter like notebooks written in elixir

[Partisan](https://github.com/lasp-lang/partisan): 

### Read
Book: [Erlang in Anger](https://www.erlang-in-anger.com/) Free
