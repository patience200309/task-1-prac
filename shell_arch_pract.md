
# Shell Architecture: Hands-On Application

## Instructions:
Complete the following practical tasks in your terminal. Submit the following as part of your assignment:
- A shell script named `shell_architecture_practice.sh`
- Screenshots or terminal output logs showing each task
- Any config files you modified (e.g., `.bashrc` or `.zshrc`)
- A reflection file (`reflection.txt`). In your reflection file, you must write down what you have learned. Structure it this way

---
## Task 1: Exploring Shell History
- Use `history`, `!`, and `fc` to demonstrate recalling and editing past commands.
- Use a one-liner with `^` to modify and replay the last command.

## Task 2: Command Type Identification
- Write a script that uses `type`, `which`, and `command` to identify if a given input is a built-in, keyword, or external command.

## Task 3: Job Control Exercise
- Start a long-running process (e.g., `sleep 1000`) in the background.
- Use `jobs`, `fg`, `bg`, and `kill` to manage the job.
- Demonstrate pausing and resuming a job.

## Task 4: Redirection and Pipeline Mastery
- Create a pipeline that:
  - Reads from a file
  - Filters specific lines
  - Sorts and counts them
  - Redirects standard output and errors into separate files

## Task 5: Using Shell Variables
- Write a script to:
  - Define shell and environment variables
  - Export them
  - Use them in conditional logic
  - Demonstrate `readonly` and `unset`

## Task 6: Observability Tools
- Use the following tools to inspect and manage shell processes:
  - `ps`, `pgrep`, `top`, `kill`
  - `lsof` to inspect file descriptors
  - `strace` to trace a shell script

## Task 7: Multi-Shell Experiment
- Run the same navigation or script command in two shells (e.g., `bash` and `zsh`).
- Document any differences you observe in behavior.

## Task 8: Shell Extensibility Setup
- In your `.bashrc` or `.zshrc`:
  - Add 2 custom aliases
  - Create a shell function
  - Enable at least one plugin (e.g., oh-my-zsh)
- Reload the config with `source` and test your customizations

## Task 9: Script Debugging
- Create a script with intentional logic errors.
- Use `bash -n` and `set -x` to debug and correct it.
- Document the debugging steps in a short note.

---

## Submission Checklist
- [ ] `shell_architecture_practice.sh`
- [ ] Output logs or screenshots
- [ ] `.bashrc` / `.zshrc` 
- [ ] `reflection.txt` 


