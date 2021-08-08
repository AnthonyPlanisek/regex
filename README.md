# Regular Expression email verification

A regular expression is a method used in programming for pattern matching. Regular expressions provide a flexible and concise means to match strings of text. For example, a regular expression could be used to search through large volumes of text and change all occurrences of "night" to "day"

## Summary

"^[a-zA-Z0-9+_.-]+@[a-zA-Z0-9.-]+$" - this regex will be used to identify if a user has inputted a valid email address

## ^
matches the starting of the sentence.

## [a-zA-Z0-9+_.-]
matches one character from the English alphabet (both cases), digits, “+”, “_”, “.” and, “-” before the @ symbol.

## +
indicates the repetition of the above-mentioned set of characters one or more times.

## @
matches itself.

## [a-zA-Z0-9.-]
matches one character from the English alphabet (both cases), digits, “.” and “–” after the @ symbol.

## $
indicates the end of the sentence.

Anthony Planisek https://github.com/AnthonyPlanisek
