Unit 1 – Lesson 1  
**Topic:** Shell Purpose & Navigation  
**Level:** Beginner (No prior knowledge required)  

---

## Instructions
Complete the tasks below using your terminal (Bash, PowerShell, or similar).  
Submit the following:
- A basic shell script called `shell_intro.sh`
- Terminal screenshots or output logs
- A reflection file: `reflection.txt`

---

##  Task 1: What Is a Shell?

Open your terminal and run:
```bash
echo "The shell is my translator to the OS"
Run the following commands:
```
### Task 2 : Navigate File
```bash
pwd            # Print the current working directory
ls             # List files and folders
cd Documents   # Move into the Documents folder (or any folder that exists)
cd ..          # Move back one level
 ```
### Task 3: Create Your First Shell Script
In your terminal, create a file called shell_intro.sh:

```bash

nano shell_intro.sh
```
Inside the file, type the following:

```bash
#!/bin/bash
# My first shell script

echo "Welcome to the shell"
pwd
ls
```
Save and exit (CTRL + O, Enter, then CTRL + X in nano).

#### Make it executable:

```bash
chmod +x shell_intro.sh
```
Run it:

```bash
./shell_intro.sh
```
### Task 4: Reflect

- Create a file named reflection.txt and answer the following:
- What is the purpose of a shell?
- What did you learn by running shell commands?
- How was using the terminal different from clicking through folders?

### Submission Checklist
 1. shell_intro.sh
 2. Terminal output logs or screenshots
 3. reflection.txt
