# Python 3 parser using TemplateString actions

This is the [Antlr4 Python3 grammar](https://github.com/antlr/grammars-v4/tree/master/python/python3)
in a proposed syntax that uses TemplateString actions.
https://github.com/antlr/antlr4/pull/4345

An ANTLR4 grammar for Python 3 based on version 3.6 of 
[The Python Language Reference](https://docs.python.org/3/reference/grammar.html).

This grammar has been tested against the Python 3's 
[standard library](https://hg.python.org/cpython/file/3.6/Lib), 
the contents of the asyncio folder there is included in the examples section.

Note that there are two grammars here, one for Java and other for Python3
target. Target of grammars are mentioned at the top of the grammar.
This grammar contains embedded code that handles
the insertion of `INDENT` and `DEDENT` tokens. The embedded code,
located inside the `NEWLINE` lexer rule as well as the `@lexer::members`
section is well documented, so people trying to port this grammar to
another target should not have much difficulty.

### Targets working

| Target | Status |
|---|---|
| Cpp | Yes |
| CSharp | Yes |
| Dart | _not yet_ |
| Go | Yes |
| Java | Yes |
| JavaScript | Yes |
| Python3 | Yes |
| TypeScript | _not yet_ |
|---|---|
