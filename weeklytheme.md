# Object Oriented Principles
Encapsulation

	Access restriction—Private methods/vairables

	Namespaces/Scopes

Inheritance

	An object inherits properties and behaviors from another.

Polymorphism

	Poly—morph

	Refers to the ability of different objects to respond to the same message in different ways.

# Operators
% Modulo, calculates remainder

Bit Wise

& And

| OR

^ XOR

<< Shift bits left

>> Shift bits right

Comma Operator

a = (b = 3, b + 2)

Then,
a = 5
b = 3

# Databases
## ACID

Atomicity

All or none

Consistency

Will not invalidate the data structure constraints

Isolations

One process will occur after another. No conflicts.

Durability

A complete transaction will not be lost in the event of a power loss, crash, or error etc.

## Normalization

First Normal Form

It should only have single (atomic) valued altributes/cp;umns
 Values sotred in a column should be the same domain
 All the columns in a table should have unique values
And the order in which data is stored does not matter

Second Normal Form

It should be in the first normal form
And it should not have partial dependency

Third Normal Form

It is in the second normal form
It does not have Transitive Dependency

BCNF

Boyce and Codd Normal Form
3NF, but split into multiple tables to make 3NF work


# Multithreading
Multiprocessing -

Multiple Processors/CPUs executing concurrently

Multitasking - Multiple tasks/processes running concurrently on a single CPU. Does so by switching between tasks frequently.

Multithreading—Multiple parts of the same program running concurrently. In this case, we go a step further and divide the same program into multiple parts/threads and run those threads concurrently.

Concurrency -The ability to do more than one thing at a time.

# Searching Algorithms
Dijkstra’s Algorithm

Shortest path to any node form starting node.

Uniform Cost Search

Shortest path to goal node. Less memory space required compared to Dijkstra’s.
