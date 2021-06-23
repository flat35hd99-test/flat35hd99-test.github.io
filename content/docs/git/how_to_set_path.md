---
title: How to Set Path
---

# How to Set Path

**This pages is for user of Github Desktop on Windows10.**

## Find where is GIt
Open file explorer and find path looks like below
`C:\Users\username\AppData\Local\GitHubDesktop\app-2.9.0\resources\app\git\cmd`

`username` and `app-2.9.0` is different by every user.

Have you found `git.exe` ?

next, we set environment variable.

## Edit Environment Variable.

1. `Windows + S` and input `environment variable` and Enter.(in japanese, `システム変数の...`)
2. Open Environment Variables(環境変数)
3. Click below
![which system or user](/git/env_edit.png)
4. Add the path.(新規)
![where is](/git/env_edit_2.png)
5. Open new terminal, type `git`, and Enter.

Finished !
