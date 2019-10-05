 Project2 - Gossip Simulator

This code contains the implementation of the gossip protocol and its sum aggregation application - push sum.

Team Members:
Rishab Lokray: 9357-3447s
Gloria Nazareth: 8221-8035

Requirements: 
Elixir needs to be installed in the system

Installation and Configuration
Need to configure the mix.exs file to make an executible

Command to execute:
escript project2 <numberOfNodes> <topology> <algorithm>
<topology> - full, line, rand2D, honeycomb, randomhoneycomb, 3Dtorus
<algorithm> - gossip, pushsum

The code contains the success scenario of Gossip and Push sum implementation.

Different Topologies implemented are as follows:
Full Topology: Each actor is connected to every actor apart from itself.
Line Topology: Each actor is connected to two other actors except those on the extreme ends contain one neighbor
Random 2D Topology: Each actor is assigned a random x and y co-ordinate. Each actor is then connected to every actor within the distance of 0.1. 
HoneyComb Topology: Here each actor is connected to at max 3 neighbors or min 1 2 neighbors on the basis of its position in the honeycomb structure.
Random HoneyComb Topology: Its similar to honeycomb structure, with an extra random node connected to each node
3D Torus Topology: This is a 3D grid and the actors are connected to 6 other actors.


If [available in Hex](https://hex.pm/docs/publish), the package can be installed


Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/gossip_test](https://hexdocs.pm/gossip_test).

