# Exercises of Chapter 1

* 1.1

By "ls -ldi" and check the inodes of the two files in different dirs, we can verify it.

* 1.2

The two processes in the example are 851 and 854, and process 852 and 853 should be running simultaneously.

* 1.3

Because the string pointer argument passed to perror is not allowed to be modified.

C passes all arguments by value, the strerror function couldn't modify this value even if it wanted to.

* 1.4

2^31/3600/24 => about 24855 days, which is about 68 years. So it would have been flowed in 2038.
?
?

* 1.5

2^31/100/3600/24 => about 248 days
