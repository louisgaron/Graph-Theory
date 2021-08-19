# Graph-Theory


Part 2 (iii)
A regular expression is a special sequence of characters that helps you match or find other strings or sets of strings, using a specialized syntax held in a pattern. Regular expressions are 
widely used in UNIX world. The Python module re provides full support for Perl-like regular expressions in Python. The 're' module raises the exception re.error if an error occurs while 
compiling or using a regular expression. There are various characters, which would have special meaning when they are used in regular expression.

To recognize a regular language, all you need is a lookup table, or a finite-state automaton.

Non-regular languages are basically those that are not described by regular grammars. They need more sophisticated machines than FSAs to recognize them, up to a Turing machine for an unrestricted language.

The 'MATCH' function attempts to match RE pattern to string with optional flags.
Syntax: re.match(pattern, string, flags=0)
•	Pattern: The regular expression to be matched.
•	String: This would be search to match the pattern at the beginning of the string.
•	Flags: You can specify different flags.
The ‘SEARCH’ function searches for first occurrence of RE pattern within string with optional flags
Syntax: re.search(pattern, string, flags=0)
•	Pattern: The regular expression to be matched.
•	String: This would be search to match the pattern at the beginning of the string.
•	Flags: You can specify different flags.

N.B.
Python offers two different primitive operations based on regular expressions: match checks for a match only at the beginning of the string, while search checks for a match anywhere in the string.

The ‘SUB’ function also know as Search and Replace, method replaces all occurrences of the RE pattern in string with repl, substituting all occurrences unless max provided. This method returns modified string.
•	Pattern: The regular expression to be matched.
•	String: This would be search to match the pattern at the beginning of the string.
•	Max: Maximum count of substituting all the occurrences found.


