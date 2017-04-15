genhost
=======

This script will randomly generate hostnames by picking words from the
provided word list. 

Usage
-----

Just run the script and provide the number of hostnames you'd like to
generate:

    $ ./genhost 4
    romeo.example.com
    holiday.example.com
    jester.example.com
    spiral.example.com

All of those words will automatically be commented out in the word list
and thus removed from the pool of future names. If a hostname has the
potential to be confusing based on technical jargon (like
`email.example.com`), simply ignore it and generate a replacement.

For collaboration purposes, don't forget to commit the updated word list
back to a shared Git repository so names do not get reused:

    $ git add wordlist
    $ git commit
    $ git push
