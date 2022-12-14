# Life as Code
A description of how I organise my life.

## Why have life as code?
I want to document how and why I codify various aspects of my life. I feel that codifying something allows for easier evolution and improvement, and ultimately increase my hapiness.

## Principles
### Start simple and refactor
Start with the simplest possible approach and make sure I follow the process. Only refactor when needed, but when it's time don't be lazy and refactor properly.

### Security first
Don't compromise on security. Especially don't publically share any personal or sensitive information.

## Ways of Working
1. Add and takes notes in issues. This is where notes and thoughts can go before they are formalised.
2. Document finalised information in source control.

## Documents
### Todo List
The todo list is my primary mechanism for getting things done, which is why I am codifying it first. It will be in a private repository as it will likely contain some personal and sensitive information. The format will be as follows:

todo.yml:
```
---
todo:
- buy the milk
- mow the lawn
- (aug 4, 3pm) haircut
...
```
Reason for choosing this format are:
- YAML was chosen because I will be editing this file often and it requires some structure (an ordered list). YAML is a widely used structure language and I believe it is optimised for brevity which makes it ideal for a file I edit often.
- I'm using a single list to keep with my principle of starting simple. I also believe that my hapiness is increased when the is a convergence between what I want to do and what I need to do - this makes me want a single list that includes both "chores" and "leisure activities". For example I don't just want to play games all the time, I actually want to take out the trash because I love having a clean house that doesn't smell.

Notes:
- Todo items with dates will just be inserted in rough order following the principle of keeping simple first.

### Routines
This document is important as it facilitates me continuously improving my daily life.

I will use markdown for this file because it is descriptive and content based, but I don't care too much about the appearance

routine.md:
```
---
## Morning:
Get up on time. Running late in the morning makes me play catch up the whole day so make sure I get ahead!
```
