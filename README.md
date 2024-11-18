# Cheatsheet

## Commands Related to a Remote Repository:
- `git clone git@github.com:USER-NAME/REPOSITORY-NAME.git`
- `git push` or `git push origin main` *(Both accomplish the same goal in this context)*

## Commands Related to the Workflow:
- `git add .`
- `git commit -m "A message describing what you have done to make this snapshot different"`

## Commands Related to Checking Status or Log History:
- `git status`
- `git log`

---

### Basic Git Syntax

The basic Git syntax is: `program | action | destination`

#### Examples:
- `git add .` is read as: `git | add | .`
(where the period represents everything in the current directory)*

- `git commit -m "message"` is read as: `git | commit -m | "message"`

- `git status` is read as: `git | status | (no destination)`