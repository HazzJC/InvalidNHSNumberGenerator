Invalid NHS Number Generator
[➡️ Click here to use the live tool ⬅️](https://hazzjc.github.io/InvalidNHSNumberGenerator/index.html)

A simple, single-file web tool for generating 10-digit numbers that are guaranteed to fail the official NHS number checksum validation.

This tool is designed for developers, testers, and anyone working with NHS systems who needs syntactically plausible but definitively invalid NHS numbers for testing purposes. Using these numbers prevents the accidental use of a real patient's identifier in a non-production environment.
How it Works

The validity of an NHS number is determined by a checksum algorithm applied to the first nine digits to derive the tenth (the check digit). This tool works by:

1.  Generating a random 9-digit prefix.
2.   Calculating the correct check digit that would make the number valid.
3.   Deliberately choosing a different digit to append as the check digit
4.   Presenting the final 10-digit number, which is now guaranteed to be invalid, along with an explanation of why it fails the validation check.

How to Use
1. Directly in a Browser
Simply open the index.html file with any modern web browser.

2. Hosted on GitHub Pages
This tool is hosted on GitHub Pages. You can access the live version at:
https://hazzjc.github.io/InvalidNHSNumberGenerator/index.html
