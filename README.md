Invalid NHS Number Generator

A simple, single-file web tool for generating 10-digit numbers that are guaranteed to fail the official NHS number checksum validation.

This tool is designed for developers, testers, and anyone working with NHS systems who needs syntactically plausible but definitively invalid NHS numbers for testing purposes. Using these numbers prevents the accidental use of a real patient's identifier in a non-production environment.

How it Works

The validity of an NHS number is determined by a checksum algorithm applied to the first nine digits to derive the tenth (the check digit). This tool works by:
(Described at https://www.datadictionary.nhs.uk/attributes/nhs_number.html) 

    Generating a random 9-digit prefix.
    Calculating the correct check digit that would make the number valid.
    Deliberately choosing a different digit to append as the check digit.
    Presenting the final 10-digit number, which is now guaranteed to be invalid, along with an explanation of why it fails the validation check.

How to Use

Simply download the InvalidNHSNumberGenerator.html file and open it with any modern web browser.
