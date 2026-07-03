# Question 4 Explanation

- `lsof` listed open files and helped verify which files were active in the current shell session.
- `exec 3<app.log` opened the log file as file descriptor 3, and `/proc/$$/fd` showed that Linux tracks it as a process descriptor.
- Redirection commands created `stdout.txt`, `stderr.txt`, and `combined.txt` to capture standard output, standard error, and combined output.
- `ulimit -a` displayed the shell's resource limits, which influence file and process handling in the environment.
