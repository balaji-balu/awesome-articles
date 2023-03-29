


**processes**: Processes are isolated from each other, run concurrent to one another and communicate via message passing. Processes are not only the basis for concurrency in Elixir, but they also provide the means for building distributed and fault-tolerant programs. When a message is sent to a process, the message is stored in the process mailbox.

**Tasks**: Tasks build on top of the spawn functions to provide better error reports and introspection 

### Eco-system:

**[Cowboy](https://github.com/ninenines/cowboy)**: Small, fast, modern HTTP server for Erlang/OTP. Phoenix uses these underneath for web server functions.
