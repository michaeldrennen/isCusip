# isValidCusip
A simple php function to determine if the given CUSIP validates according to it's checksum digit. The function isn't optimized, but coded in an attempt to make it more readable/understandable.

This code is based on the pseudocode available here: https://en.wikipedia.org/wiki/CUSIP#Check_digit_pseudocode

You can read all about what a CUSIP is on that wikipedia page, but in summary a CUSIP is a 9 character designation assigned to financial instruments (like mortgage backed securities).

The first 8 characters are the designation, and the 9th character is a checksum digit.
