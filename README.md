# Coding guidelines
These coding guidelines are meant to be used as a base for LLM code editors. Mention this readme in your repository readme or LLM instructions.

## General
- better to fail early in code than try to work from a bad state
- do not use default values where we actually don't want them
- do not use unneccesary comments that only repeat what was already said in the code
- do not keep commented out code, unless there is also a clarifying reason
- do not maintain both async and sync versions of the same method unless there is a good reason
- use try-catch only when you can do something useful with the exception
- use expression bodied members when reasonable for properties and property-like methods, keep the '=>' on the new line
- optimize usings statements in the tops of file, make sure they are sorted alphabetically

## Formatting
- all files should be in UTF-8 encoding without BOM, with CRLF line-breaks
- use trailing comma for the last property, if properties are on separate lines
- use file-scoped namespaces
- fix formatting when changing code, not very strict though
- comments should have a space after the slashes
