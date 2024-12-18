# Data Race in Rust Using Raw Pointers

This repository demonstrates a common, yet subtle, error in Rust: a data race using raw pointers and unsafe code.  Improper handling of memory can lead to crashes, unexpected behavior, and security vulnerabilities.  The example code highlights this issue and shows how to correct it.  Proper use of safe Rust patterns is crucial to avoiding these risks.  This repository includes both an example showcasing the error and a solution illustrating how to use safe Rust practices to avoid it.

## Running the code:

To run the buggy code and see the unexpected behavior:
1. Clone this repository.
2. Run `rustc bug.rs`
3. Run `./bug`

To run the corrected code:
1. Run `rustc bugSolution.rs`
2. Run `./bugSolution`