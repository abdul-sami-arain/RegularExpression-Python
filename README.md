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
Content Cell  | Content Cell
