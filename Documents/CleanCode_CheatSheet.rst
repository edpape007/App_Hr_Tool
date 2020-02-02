=====================
Clean Code Cheatsheet
=====================

1. Principal of Least Astonishment
==================================

"What you expect is what you get"

2. Law of Demeter
=================

"Writing shy code" A module should only know its direct dependencies.

3. You Ain't Gonna Need It (YAGNI)
==================================

"Everything can be done later" Implement only what has an immediate benefit. If in doubt, decide against the effort.

4. Dependency Inversion Principle (DIP)
=======================================

Depend on abstractions, not on concretions.

5. Single Responsibility Principle (SRP)
========================================

A class should have one, and only one, reason to change.

6. Beware of Optimizations!
===========================

"Premature optimization is the root of all evil" -Donald Knuth

These efforts often lead to code which is not readable or understandable.

7. Liskov Substitution Principle (LSP)
======================================

Derived classes must be substitutable for their base classes.


8. Open/Closed Principle (OCP)
===============================

Class behavior should be extendable without modification.
