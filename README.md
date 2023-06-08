# CF-STRESS

CF Stress is a highly customizable, no-code tool to stress test Codeforces problems.

You control all the parameters of the generator without writing a single line of code. Feeling lazy and want to pin down the error to an array of length 5? You can do that by adjusting the flags passed to the generator. Feeling adventurous and want to test your logic on test cases of length 1000? There's an option for that too. There's also a builtin diff checker for when you want to compare the output of large test cases. You can also seamlessly copy the input/output to your local machine.

Just plug in your submission ID and wait for the ticket to be processed.

It also has support for non-unique answers and interactive problems. The testcases are generated using testlib, the framework that's used to create the original test set.

``If this proves to be useful, I'll add more features, such as user accounts to view tickets in one place, emailing the user on successful completion of the ticket, better concurrency support to handle multiple tickets, revamped UI, etc.``
