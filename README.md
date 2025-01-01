This repository contains a simple Rust program that demonstrates a potential issue with mutable references. The program creates multiple mutable references to the same variable, potentially leading to data races or unexpected behavior in more complex scenarios.  The `bug.rs` file contains the problematic code, while `bugSolution.rs` offers a corrected version that avoids these issues.