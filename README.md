# Fix My Code Challenge

Jump into an existing code base and fix it — sometimes in a familiar
language, sometimes not. The goal is not to rewrite the code, only to
fix what is broken.

## Tasks

### 0. FizzBuzz

`challenge/0-fizzbuzz.py` printed `Fizz` for every multiple of 3,
including multiples of 15, because the `i % 3` check was evaluated
before the combined `i % 3 and i % 5` check and short-circuited it.
Reordering the checks so the FizzBuzz case is tested first fixes it.
