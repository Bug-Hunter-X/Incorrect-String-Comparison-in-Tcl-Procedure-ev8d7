# Incorrect String Comparison in Tcl

This repository demonstrates a common error in Tcl: using the numeric comparison operator `==` instead of the string comparison operator `eq` when comparing strings.  This can lead to unexpected behavior and incorrect results.

## Bug Description

The `badproc` procedure uses `==` to compare strings.  This will perform a numeric comparison, potentially leading to unexpected results (e.g., "10" and 10 will be considered equal).

## Solution

The correct approach is to use the `eq` operator for string comparisons.

## How to Run

1.  Clone this repository.
2.  Use a Tcl interpreter (e.g., wish) to run the provided Tcl files.