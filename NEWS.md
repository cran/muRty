muRty 0.3.1
===========

Very minor changes
------------------

-   Added additional unit tests;
-   Added descriptions to all functions;
-   Removed references to `lpsolve` from some of the files;
-   Removed some of the unnecessary assignments & checks within functions.

muRty 0.3.0
===========

General changes
---------------

-   Added the `by_rank` argument which allows users to obtain ranked
    results;

-   The `algo` argument has been added together with `clue` as
    dependency, allowing users to take advantage of Hungarian algorithm
    which is usually faster than the LP approach;

-   Note that even though the `solve_LSAP` function from `clue` is used
    for the Hungarian algorithm (which uses the `maximize` argument), the
    `objective` argument has not changed.

muRty 0.1.2
===========

-   First version on CRAN.
