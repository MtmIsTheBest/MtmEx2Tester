# How to use

## So what's it testing
 - [x] All test files located in the `in` folder (assuming there's a matching output file in the `out` folder)
 - [x] Testing `partA`
 - [ ] Testing `partB`
 - [ ] Automagically generates random tests
 - [ ] Automagically fetches tests with edge cases from the internet


## Prerequisites
1. Python3.6+ (`sudo apt install python3 python3-pip` on Ubuntu)
2. `termcolor` library (you can install it by typing `pip install termcolor`)
3. Have a few test files

## Folder structure
You must have the following folder structure to be able to run the tester

project:
  ex2_tester.py
  hw2.py
  tests:
    in:
      test1.txt
      test2.txt
      ...
    out:
      out1.txt
      out2.txt
      ...
    