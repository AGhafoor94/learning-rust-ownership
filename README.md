# Learning about Rust Ownership

## Stack
- Stores values in order it gets them and removes the values in the opposite order.
- Last in, first out (popping off the stack).
- Must have a known fixed size.
- Can store the pointer on the stack (known fixed size).

## Heap
- Must request a certain amount of space.
- Operating system finds an empty spot in the heap big enough.
    - Marks it at being used
    - Returns a pointer (address of that location)
- Called "Allocating on the heap" or just "allocating".
