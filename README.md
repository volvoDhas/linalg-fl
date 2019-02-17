# linalg-fl
A (minimal) linear algebra library for fl

## Background
fl is a framework that packages a strongly typed functional language, an efficient implementation of Ordered Binary Decision Diagrams (OBDDs), a SAT solver, symbolic simulation and the necessary visuzalization.
More information on fl can be found in this (private) github repo https://github.com/cjhseger/VossII

## Main intent of this project
To enable work realated to my research, this project aims to develop a linear numerical computation library for the fl framework.

## Repo structure

|_lib	-> core library logic  
|_test	-> flunit test framework & unit-tests for the library  

## Testing & quality

As a measure of the library's quality, a decent set of unit tests have been written. (Unit) test automation is enabled by a lightweight framework flunit (test/flunit.fl) custom-built for this purpose

### Minimal versioning guidelines
Prepend commit messages with 
*repo	 - repo structure changes  
*feature  - feature additions  
*fix	 - comment enhancements, minor & major (bug) fixes  
*test	 - test cases  
*refactor - noteworthy refactoring  
