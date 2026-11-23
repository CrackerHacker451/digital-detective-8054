# Mission 4 — How programs run
## 1. Task / objective
Run a simple Python program and compare compiled and interpreted execution.
## 2. Work completed
Created `hello.py`, which prints `Hello from Python`, and compared compilers with interpreters.

### Compiler/interpreter comparison
| Point | Compiler | Interpreter |
|---|---|---|
| When translation/execution happens | Source is translated before execution. | Instructions are read and carried out while execution proceeds. |
| Typical output | A build artifact or executable is produced. | It produces program behavior/output directly. |
| One example | C compiler producing a native executable | CPython executing Python source |
| One advantage | Repeated execution does not require source translation each time. | Changes can often be tested quickly with less build setup. |

A compiler translates source code into another form before the program is run. An interpreter executes instructions at runtime. Real implementations can mix compilation and interpretation, so these are useful concepts rather than a rule that every language must fit exactly.
## 3. Commands / tools used
`python3 hello.py` ran the program. VS Code or another text editor was used to create the source file.
## 4. My understanding
Interpreted Python reads Python instructions through an implementation such as CPython. Compilation happens ahead of execution for languages or implementations that use it. Both approaches aim to turn source instructions into behavior.
## 5. Difficulties faced
No major difficulties.
## 6. How I resolved them
Not applicable.
## 7. Evidence / files
`hello.py` and this README.
## 8. Commit details
Commit: `Compare compilers and interpreters`; pushed to GitHub.
