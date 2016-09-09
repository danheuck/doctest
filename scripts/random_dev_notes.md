- test compile speeds of expression decomposition - with and without specialization for const char*

- fix unary/binary assertion macros...

- think about the expression decomposition static asserts
    - the static assert should use the c++11 feature if possible
    - also remove the static assert from the operator<< detection trait

- fix color of successful expressions when printing everything with --success
    - maybe add color scheme support...

- signed/unsigned comparison trouble in assertions

- integrate patreon

- examples
    - removing everything with -dt- from the command line - https://github.com/onqtam/doctest/issues/20
    - using the fast assertions
    - a test in a header in one binary with multiple cpp files

- write tests for the library itself
    - macros should evaluate expressions only once
    - macros should work with noncopyable types

- better docs
    - char ptr comparison - not what u'd expect
    - not just for c++98
    - updated compile time benchmarks (and include linux!)
    - list the subcases as a major selling point on the main page - after the expression decomposition macro stuff
    - faq - why macros - http://accu.org/index.php/journals/2064
    - FAQ - how is it different from Catch (or what is lacking)
    - faq - why c++
    - FAQ - static libraries - also mention https://github.com/pthom/doctest_registerlibrary
    - default options should be mentioned
    - mention the new asserts
    - for power users - separate headers
    - post the traffic screenshot in the FAQ - "how epic was the initial release"

post in reddit for 1.1!











how to deal with pull requests for the main branch instead of the dev branch
- http://stackoverflow.com/questions/9135913/merge-pull-request-to-a-different-branch-than-default-in-github
- git fetch origin pull/ID/head:BRANCHNAME