# PHP Array Key Type Handling Pitfalls

This repository demonstrates a common, yet subtle, bug in PHP related to how it handles array keys.  PHP's loose typing can lead to unexpected behavior when using both string and integer keys that are numerically equivalent.  This often results in data being overwritten and causes hard-to-debug logic errors.

The `bug.php` file shows examples of this unexpected behavior with `var_dump()` and `isset()`.  The `bugSolution.php` file offers solutions for mitigating these issues.

## How to Reproduce

1. Clone this repository.
2. Run `bug.php` using a PHP interpreter.
3. Observe the output and compare it to the expected behavior.  The solution file shows how to resolve this issue and achieve the expected behavior.