# Dangling Pointer in Rust Vector Modification

This repository demonstrates a common error in Rust involving dangling pointers when modifying vectors using raw pointers.  The code attempts to modify a vector through a raw pointer after it's been used, leading to undefined behavior and likely panics. The solution shows how to avoid this by ensuring the vector's lifetime is properly managed.  This example highlights the importance of understanding Rust's ownership and borrowing rules when working with unsafe code.