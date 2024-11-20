raft [![Build Status](https://github.com/hashicorp/raft/workflows/ci/badge.svg)](https://github.com/hashicorp/raft/actions)
====

raft is a [Go](http://www.golang.org) library that manages a replicated
log and can be used with an FSM to manage replicated state machines. It
is a library for providing [consensus](http://en.wikipedia.org/wiki/Consensus_(computer_science)).

The use cases for such a library are far-reaching, such as replicated state
machines which are a key component of many distributed systems. They enable
building Consistent, Partition Tolerant (CP) systems, with limited
fault tolerance as well.

## Building

If you wish to build raft you'll need Go version 1.16+ installed.

Please check your installation with:

```
go version
```
