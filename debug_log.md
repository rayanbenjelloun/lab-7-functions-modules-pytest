# debug_log.md
# Author: [Rayan Benjelloun]

## Bug 1
Error type: KeyError
File + line: File "/home/rayanbenjeloun/ism3232/module05_functions/week8_buggy.py", line 12
What the error means: dict key doesn't exist (usually typo)
What I told the duck: The total starts at 0, then looks through the dictionaries for the amount to add, it goes through one record at a time by looking up 'amount' and adds it to the total, there is a typo in the code so it cannot be added to the total.
What I tried: I added a print() to see the dictionary and check the spelling of its keys.
How I fixed it: I changed 'amout' to 'amount'

## Bug 2
Error type: TypeError
File + line:  File "/home/rayanbenjeloun/ism3232/module05_functions/week8_buggy.py", line 16, in is_over_limit
What the error means: Python cannot use > to compare an integer with a string.
How I fixed it: I removed the quotes around '1000' so python can compare the 2 integers.

## After Fixing Both Bugs
Final output: Total: $5150.00 across 3 records, True
Did pytest pass? Yes

## AI Literacy Reflection
Did I use AI? Yes
If yes -- exact prompt I used: define what the code is trying to do
What AI explained: it explained what each code does so its easier to pinpoint where the mistakes were from.
What I changed myself: With AI guidance, I corrected 'amout' to 'amount', removed the quotes around '1000', and deleted the DEBUG prints.
Can I explain every fixed line? Yes 

## What I learned
[I learned how to read code for errors and what lines of code i must put to find an error. I also learned what I need to replace those errors with and I also refined my understanding on what the definitions of the codes are.]