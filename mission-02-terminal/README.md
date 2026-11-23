# Mission 2 — Become comfortable with the Terminal
## 1. Task / objective
Practise basic Terminal operations, safe file management, flags and pipes, and package-manager concepts.
## 2. Work completed
### Task 2.1 — Basic operations
| Operation / command | What it does | What I observed |
|---|---|---|
| `pwd` | Displays the absolute current-directory path. | It confirmed the repository location in Terminal. |
| `ls` | Lists visible entries in the current directory. | Mission folders and README files were shown. |
| `ls -l` | Shows a detailed listing. | Permissions, owner-related fields, size and date were visible. |
| `cd ..` | Moves to the parent directory. | The location changed one directory level upward. |
| `mkdir` | Creates a directory. | A new practice folder could be created safely. |
| `touch` | Creates an empty file or updates timestamps. | An empty text file appeared. |
| `cp` | Copies a file. | The copy kept the original file unchanged. |
| `mv` | Moves or renames a file. | The copied file could receive a new name/location. |
| `cat` | Displays a file's contents. | The original text content appeared in Terminal. |

### Task 2.2 — Safe practice
The `terminal-practice` folder contains `practice.txt` with two lines and `practice-backup.txt`, a renamed copy of a backup.

- Replacing a file's contents overwrites existing data, while appending text adds at the end and keeps earlier text.
- Copying creates another file while leaving the source in place; moving changes a file's location or name and removes it from the old location.
- `pwd` shows where the shell is currently working.
- Listing is useful for finding names and checking what files and folders exist.

### Task 2.3 — Flags and pipes
`ls -l` adds details, `ls -la` also includes hidden entries, and `ls -lah` uses readable sizes. The normal listing was shortest. A pipe, `|`, sends the first command's standard output into the second command. For example, `ls -lah | head -n 5` sends a detailed listing to `head`, which prints only the first five lines.

### Task 2.4 — Package managers
Homebrew is installed in this environment, version 7.0.11. Package managers keep software, versions and updates organized, which makes installing and updating tools more consistent. I did not install or remove anything.

## 3. Commands / tools used
`pwd`, `ls`, `ls -l`, `ls -la`, `ls -lah`, `cd`, `mkdir`, `touch`, `cp`, `mv`, `cat`, `printf`/text-editor append operations, `head`, `brew --version`, `brew list`.
## 4. My understanding
Commands perform exact file operations, so work should stay inside a controlled repository. Flags modify command behavior and pipes connect the output of one command to the input of another.
## 5. Difficulties faced
No major difficulties.
## 6. How I resolved them
Not applicable.
## 7. Evidence / files
`terminal-practice/practice.txt`, `terminal-practice/practice-backup.txt`, and this README.
## 8. Commit details
Commit: `Complete Terminal and file management mission`; pushed to GitHub.
