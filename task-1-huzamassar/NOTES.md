# Terminal Log — Project 1

Real commands executed, in order, with actual output.

```bash
$ mkdir -p app/logs
$ touch app/config.conf
$ echo "Started" > app/logs/server.log

$ pwd
/home/claude/project1-linux-basics

$ ls -R app
app:
config.conf
logs

app/logs:
server.log

$ mv app/logs/server.log app/logs/server.bak

$ ls -l app/config.conf
-rw-r--r-- 1 root root 0 Sep 26 23:58 app/config.conf
```

## Notes on each command

- `mkdir -p app/logs` — creates `app` and nested `app/logs` in one shot; `-p` makes parent dirs automatically and doesn't error if they already exist.
- `touch app/config.conf` — creates an empty placeholder file (or updates its timestamp if it already exists).
- `echo "Started" > app/logs/server.log` — `>` overwrites the file with the given text (redirection).
- `pwd` — prints the absolute path of the current directory ("GPS coordinate").
- `ls -R app` — recursively lists everything under `app/`.
- `mv app/logs/server.log app/logs/server.bak` — renames the log to a `.bak` file (mv = rename or relocate).
- `ls -l app/config.conf` — long listing shows permissions (`rw-r--r--`), owner, group, size, and timestamp.
