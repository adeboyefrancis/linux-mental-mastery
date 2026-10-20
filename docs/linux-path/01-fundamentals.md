# Day 01: Linux Fundamentals ( File Systems, Permissions, Bash )

> **Time:** ~45 min · **Level:** Beginner/Intermediate/Advanced
> **Prerequisites:** [Day NN-1](day-NN-1.md) (or "none")

## Goal
- Refresh Linux Concepts around the Red Hat Enterprise distro to align with current job role
- Build Mental model and improve troubleshooting and problem solving skills

## Concepts
Leveraging File Permission concept to enhance a secured linux/selinux environment to build a robust least principle environment

Core Permission types: Octal (421) , Symbolic (rwx)
Usage:

```bash
chmod u+x src/app.sh        # symbolic: add execute for the owner
chmod 755 src               # octal: rwx for owner, r-x for group and others
chmod 644 docs/notes.txt    # octal: rw- r-- r--
chmod go-rwx docs           # symbolic: remove all access for group and others

#Using stat command to review file permission
stat -c '%a %A %n' <file-name> <file-name>
```

## Worked example
A realistic mini-scenario built up step by step, with Expected output.

## Common mistakes
| Mistake | Why it fails | Fix |
|---------|--------------|-----|

## Exercises
### Easy
### Medium
### Hard
Each exercise: task, input/constraints, and **Acceptance criteria**.

### Break it
A short script containing 1-3 bugs. The learner finds and fixes them.

## Solutions
<details>
<summary>Easy</summary>

(solution walk-through; full scripts live in `solutions/day-NN/`)

</details>

## Self-check
5 quick questions. Answers collapsed in `<details>`.

## Cheat sheet
The 5-10 commands or syntax forms from this lesson.

## Further reading
- [Title](url): one line describing what you will learn there.

**Next:** [Day NN+1](day-NN+1.md
