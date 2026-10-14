# debug_log.md
# Author: [Kaden Brenning]

## Bug 1
Error type: KeyError
File + line: week8_buggy.py on line 13
What the error means: A key error means that a key does not exist, but has been called.
What I told the duck: For each record in records, Add to the variable total the 'amount' section of records.
What I tried: Added a debug line to print the record currently being run. This debug line showed a typo in the first line of records.
How I fixed it: added an "n" to the typo "amout"

## Bug 2
Error type: TypeError
File + line: week8_buggy.py and line 18.
What the error means: A str cannot be compared to an int
How I fixed it: changed the '1000' str to an 1000 int

## After Fixing Both Bugs
Final output: 
Total: $5150.00 across 3 records
True
Did pytest pass? Yes

## AI Literacy Reflection
Did I use AI? No, I was able to locate the issues by using the rubber duck debugging method.

## What I learned
First I learned what a KeyError is, and how to use the rubber duck debugging method to locate it. Second I learned what a TypeError is, and how easily this error can be made.