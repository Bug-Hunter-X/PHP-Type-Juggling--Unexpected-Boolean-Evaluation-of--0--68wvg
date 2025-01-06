# PHP Type Juggling Bug

This repository demonstrates a common pitfall in PHP related to type juggling and boolean evaluation.  The `bug.php` file contains code that unexpectedly evaluates the string "0" as false in a boolean context. This is because PHP's loose type comparison performs implicit type conversion, leading to counter-intuitive results.

The solution, provided in `bugSolution.php`, illustrates how to use strict comparison (`===`) to avoid this unexpected behavior and ensure accurate evaluations.