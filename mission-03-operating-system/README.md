# Mission 3 — Understand the operating system
## 1. Task / objective
Explore OS details, processes, storage, paths and permissions.
## 2. Work completed
### Task 3.1 — System information
| Information | What it tells me | Privacy-safe observation |
|---|---|---|
| Operating system | Identifies the platform and kernel environment. | macOS/Darwin 27.2.1 was observed. |
| Current account identity | Shows who is running the shell. | The account name was redacted. |
| Available and used storage | Shows root-volume usage. | 926 GiB capacity; 487 GiB available; 224 GiB used (6% of the reported total shown). |
| System activity snapshot | Shows briefly active processes and resource use. | A process snapshot was inspected using the process tools. |

### Task 3.2 — Processes
A process is a running program or system task. The PID column gives each process a process identifier. Examples include the Terminal shell and a background system service.

### Task 3.3 — Paths and permissions
The absolute path begins at the root of the filesystem, while a relative path starts from the current folder.
- Absolute example: `/Users/[redacted]/.../digital-detective-8531/mission-02-terminal/terminal-practice`
- Relative example: `mission-02-terminal/terminal-practice` from the repository root.

For a normal text file in `terminal-practice`, owner permissions are commonly `rwx` for a directory and `rw-` for a regular text file. Owner `r` allows reading, `w` allows editing, and `-` for execute means the text file is not marked executable.

| Permission | Meaning | Example |
|---|---|---|
| r | Read contents | Opening a text file |
| w | Write/change contents | Editing a text file |
| x | Execute/run or traverse | Running a script or entering a directory |

### Task 3.4 — OS responsibilities
| Responsibility | Explanation | Example |
|---|---|---|
| Process management | Starts, schedules and stops running programs. | Switching among browser and editor processes |
| Memory management | Allocates and recovers memory for programs. | Loading a document in memory |
| Device management | Coordinates hardware through system interfaces. | Sending keyboard and display data |
| File management | Organizes, opens and protects stored files. | Creating and locating a repository file |
| User interface/shell | Provides a way for people to interact with the OS. | Desktop or Terminal commands |
| Security and permissions | Controls access and restricts protected actions. | Read/write permission on a text file |

## 3. Commands / tools used
`uname`, `sw_vers`, `whoami`/account lookup, `df -h`, `ps` or Activity Monitor, `pwd`, `cd`, `ls -l`.
## 4. My understanding
The OS is a manager between applications and hardware. Processes, memory, devices, files, interfaces and security rules are connected responsibilities rather than isolated features.
## 5. Difficulties faced
No major difficulties.
## 6. How I resolved them
Not applicable.
## 7. Evidence / files
Privacy-safe notes and permission examples in this README.
## 8. Commit details
Commit: `Document operating system and file management`; pushed to GitHub.
