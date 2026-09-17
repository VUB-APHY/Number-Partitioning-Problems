# Number Partitioning Problems (NPP)
A collection of randomly generated number partitioning problem (NPP) instances for benchmarking Ising machines and other combinatorial optimization solvers.

## Problem definition
The number partitioning problem asks: given a set of positive integers, divide it into two subsets such that the difference between the sums of the two subsets is minimized.

Each instance is characterized by two parameters:

| Parameter | Meaning |
|-----------|---------|
| `b` | Number of bits needed to represent any value in the set |
| `n` | Size of the set (number of elements) |

## Contents
This repository contains NPP instances spanning:

- `b`: 4 to 12 bits
- `n`: 16 to 1280 elements

Each instance is stored as a `.txt` file containing the integer values of the set.
