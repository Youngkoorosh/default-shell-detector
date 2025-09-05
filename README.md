# 🐚 Default Shell Detector — One-Liner Linux Challenge

Welcome to a fun and competitive Linux terminal exercise where Ali, a curious newcomer, challenges his seasoned friend Reza to a battle of shell knowledge. The goal? Discover the default login shell of the current user — using only one line of command, without ever mentioning the username explicitly.

## 🎯 Objective

Write a **single-line command** that outputs the default shell of the currently logged-in user. The command must work regardless of the username and must not include the actual username in the command.

### ✅ Example

If the current user is `reza-linux` and their default shell is `/bin/bash`, the command should output:

```
/bin/bash
```

## 🚫 Constraints

- ❌ Do not use `echo $SHELL`
- ❌ Do not hardcode or reference the username
- ❌ Do not use `awk`
- ✅ You may use any other command or pipeline learned so far

## 🧪 Hint

Explore the `/etc/passwd` file and use tools like `grep`, `cut`, or `whoami` to extract the shell field dynamically.

---

## 📤 Submission

Submit your solution as a single-line command or via a script named `solution.sh`.

---

Let Ali rise as the shell master 🧠🐧
