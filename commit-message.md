# Commit

## Message

```
Fix buffer overflow

Apply new security policy requirements

- fix: buffer overflow on standard input, it caused security issues
- refactor: main entry point to work with the new input mechanism
```

- First line: Subject, must answer WHAT is commit about
- Second line: blank line, important to separate subject from body of the message (needed for tools)
- Message Body: is a detailed explanation
  - **can** use **bullet points**
  - **must** use **imperative mood** (ex: fix, not fixed)
  - **must** answer **WHAT** and **WHY** a change was necessary, optionally consequences
  - **DO NOT** include **HOW** the commit does it, code itself must explain that

[reference](https://medium.com/@steveamaza/how-to-write-a-proper-git-commit-message-e028865e5791)

## TODO

more references

more detailed description

example referring issues in issue tracker
