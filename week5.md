# week 5
## Task 1.1
Pipes (|) allow the output of one process to become the input of another, enabling multiple programs to work together efficiently. For example, ps aux | sort -k4 -r | head -10 demonstrates process cooperation by listing running processes, sorting them by memory usage, and displaying only the top results. Redirection (>, >>, 2>) allows standard output and standard error to be written into files, which is useful for logging and debugging. Together, pipes and redirection support modular design and efficient data flow between programs.
