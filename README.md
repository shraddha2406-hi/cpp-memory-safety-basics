C++ Memory Safety Basics

About

This project demonstrates an out-of-bounds array access in C++ and how to prevent it.

Bug

Using "i <= 3" in a loop for an array of three elements accesses an invalid index because the valid indexes are 0, 1, and 2.

Fix

Changing the condition to "i < 3" ensures that the loop accesses only valid array indexes.

What I Learned

This example helped me understand array bounds, undefined behavior, and the importance of writing safer C++ code.
