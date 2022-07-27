# Regular Expressions in Python: #
## Metacharacters: ##
A metacharacter is a character that has a special meaning during pattern processing.</br>
Some metacharacters and their descriptions are follow:</br>
Symbol        |Name           |Description
------------- | ------------- | ----------
  [ ]          | Square Brackets  | Square brackets specifies a set of characters you wish to match.
  .            | Period  | A period matches any single character (except newline '\n').
  ^  | Caret  | The caret symbol ^ is used to check if a string starts with a certain character.
  $  | Dollar  | The dollar symbol $ is used to check if a string ends with a certain character.
  \*  | Star  | The star symbol * matches zero or more occurrences of the pattern left to it.
  \+  | Plus    | The plus symbol + matches one or more occurrences of the pattern left to it.
  ?  | Question Mark  | The question mark symbol ? matches zero or one occurrence of the pattern left to it.
  {}  | Braces  | Consider this code: {n,m}. This means at least n, and at most m repetitions of the pattern left to it.
  \|  | Alternation  | Vertical bar \| is used for alternation (or operator).
  ( )  | Group  | Parentheses () is used to group sub-patterns.
  ### Special Sequences ###
  Expression  | Description
------------- | -------------
\A  | Matches if the specified characters are at the start of a string.
\b  | Matches if the specified characters are at the beginning or end of a word.
\B  | Matches if the specified characters are not at the beginning or end of a word.
\d  | Matches any decimal digit. Equivalent to [0-9]
\D  | Matches any non-decimal digit. Equivalent to [^0-9]
\s  | Matches where a string contains any whitespace character. Equivalent to [ \t\n\r\f\v].
\S  | Matches where a string contains any non-whitespace character.
\w  | Matches any alphanumeric character (digits and alphabets). Equivalent to [a-zA-Z0-9_].
\W  | Matches any non-alphanumeric character. Equivalent to [^a-zA-Z0-9_]
\Z  | Matches if the specified characters are at the end of a string.
