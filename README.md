# minigrep
we include two libs:
- std::env for command line args
- std::fs for file reading

the variable "args" gets a vector of command line arguements
    there will be three arguments:
    - args[0] is the main.rs file itself
    - args[1] is the first argument passed
      - this will be the search word we want to find
    - args[2] is the filename we want to search in

