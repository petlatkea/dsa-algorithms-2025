# Algorithms

This is a (growing) collection of simple algorithms - mostly for searching and
sorting - implemented in JavaScript.

Every algorithm is in its own module, that can be imported for use in any other JavaScript module. 

Every algorithm returns an object containing both the result (if any) of the performed calculation, whether or not it was succesful, and the number of iterations used to perform the calculation. So it should be easy to compare the performance of different algorithms, without having to resort to timers and stopwatches.

Every algorithm comes with comprehensive tests written with Mocha, and mostly using Node's built-in assert library. 

## Download and initialize

Clone or Fork this repository, and run ```npm i``` to install necessary packages (only Mocha so far)

### Run tests

To run the tests, navigate to the subfolder of the particular algorithm you want to test, and run ```npx mocha``` in that folder. E.g.

    cd linearsearch
    npx mocha

to run tests on the linear search algorithm.

## The algorithms are

* **Linear Search** - ```linearsearch/linearsearch.js```
   
  performs a linear search in an array, or array-like structure.

