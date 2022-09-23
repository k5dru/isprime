# isprime
Very small command line program I wrote in 1999 to determine if an integer is prime

This program is stupidly straightforward. If you are using it for anything serious, I urge you go read current articles (wikipedia) on tests for primeness.

However if your needs are simple and you have a command line environment, this will tell you if the number you are interested in isprime, and if not, will find the nearest prime above and below you number.

Limits: 64-bit signed integers. The largest prime it will test is 9,223,372,036,854,775,783.

    Usage:  cc -O2 isprime.c -o ~/bin/isprime   
    ~/bin/isprime 9223372036854775781
    No, but 9223372036854775643 and 9223372036854775783 are. 

Godspeed.
