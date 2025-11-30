# Commands
A simple list of Linux commands I learn. Keep entries short and clear.

## Template
- Command: name
- Purpose: one short sentence
- Syntax: basic form
- Example: one or two practical examples
- Notes: tips / common flags

---

## ls
- Command: ls
- Purpose: list directory contents
- Syntax: ls [options] [path]
- Example: ls -lah ~
- Notes: -l long listing, -a show hidden files, -h human-readable sizes

## cd
- Command: cd
- Purpose: change current directory
- Syntax: cd [dir]
- Example: cd ~/projects
- Notes: cd - returns to previous directory; cd ~ goes to home

## chmod
- Command: chmod
- Purpose: change file permissions
- Syntax: chmod [mode] file
- Example: chmod 644 file.txt
- Notes: Use octal (e.g., 644) or symbolic (e.g., u+rwx). Use chown to change owner.

## grep
- Command: grep
- Purpose: search for patterns in files
- Syntax: grep [options] pattern file
- Example: grep -n "TODO" -R .
- Notes: -R recursive, -n show line numbers. Consider ripgrep (rg) for speed.

## find
- Command: find
- Purpose: find files and directories
- Syntax: find [path] [expression]
- Example: find . -type f -name "*.log" -mtime -7
- Notes: Combine with -exec or xargs to run commands on results.


End of file