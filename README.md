# Frankentext

Author: Benjamin Hasforth
For my C programming course at DTU

Requirements:
In this assignment we had the following assignments
Embed the book into a string.

Replace each non-printable character with a space

Read tokens delimited by “ ?!” and store them in an array named tokens.

At the same time update a successor table that tracks which token depends on which token (succs).

There must be no copy of a token in the array and tokens are case-sensitive.

ruin! and ruin are different tokens.

Generate random sentences:

Select a random token that starts with a capital letter and continue appending random successors from the successor table until we encounter a token that ends a sentence.
