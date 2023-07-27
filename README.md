# Python 3 parser using TemplateString actions

This is the [Antlr4 Python3 grammar](https://github.com/antlr/grammars-v4/tree/master/python/python3)
in a proposed syntax that uses TemplateString actions.
https://github.com/antlr/antlr4/pull/4345. The advantage of this syntax is to offer a
less kludgy alternative to [target-agnostic format](https://github.com/antlr/antlr4/blob/dev/doc/target-agnostic-grammars.md)
for a common syntax across targets.

### Targets working

| Target | Status |
|---|---|
| Cpp | Yes |
| CSharp | Yes |
| Dart | Yes |
| Go | Yes |
| Java | Yes |
| JavaScript | Yes |
| Python3 | Yes |
| TypeScript | Yes |
