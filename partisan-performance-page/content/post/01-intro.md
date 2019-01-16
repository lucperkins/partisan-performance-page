+++
date = "2015-12-2T14:10:00+03:00"
draft = false
title = "Introduction"
weight = 1
+++

Partisan is the the design of an alternative runtime system for improved
scalability and reduced latency in actor applications called Partisan.
Partisan provides higher scalability by allowing the application developer to
specify the network overlay used at runtime without changing application
semantics, thereby specializing the network communication patterns to the
application. Partisan reduces message latency through a combination of three
predominately automatic optimizations: parallelism, named channels, and
affinitized scheduling. We implement a prototype of Partisan in Erlang and
demonstrate that Partisan achieves up to an order of magnitude increase in
the number of nodes the system can scale to through runtime overlay
selection, up to a 34.96x increase in throughput, and up to a 13.4x reduction
in latency over Distributed Erlang.