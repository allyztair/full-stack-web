# Full-Stack Web Developmemt

_04 - 20 - 2024 | Nerisse Allyztair M. Ramirez_

## HyperText MarkUp Language

- Heading Element `<h1></h1>`, `<h2></h2>`, `...`
- Paragraph Element `<p></p>`
- Void Element `<hr />`, `<br />` does not need closing tag.
- List Elements `<ul>`, `<ol>`, `<ul>`
- Anchor Element `<a href=""></a>`
- Image Element `img src="url" alt=""/>`

## Multi-Page Websites

**Computer File Path**

1. Absolute File Path
2. Relative File Path

Webpages

## Cascading Syle Sheet (CSS)

**Three ways to add CSS**

- Inline: `<html style="background: blue></html>"`
- Internal: `<style>html { background: blue }</style>`
- External: written in seperate file.

**CSS Selectors**

- selecting by element
- Class Selector: `.className`
- ID Selector: `#idName`
- Attribute selector: `p[draggable="false"]`
- Univeral selector: `*`

**CSS Colors**

**Font Properties**

**_Font Size_**

- 1px (pixel) - 1/96th inch, static
- 1pt (point) - 1/72nd inch, static
- 1em - 100% of parent, relative size
- 1rem - 100% of root, relative size

**_Font Weight_**

- normal bold - keywords
- lighter bolder - relative to parent
- number - 100-900

**_Font Family_**

- Typeface - research more about this
- generic font type - backu-up font
- use <" "> when a font's name uses a space

**_Text Align_**

- **The CSS Box Model**

- padding
- margin
- border-width

**Content Division Element**
`<div></div>` - invisible box

**Pesticide Chrome Extension**

## git

**Version Control**

- `cd` - change directory
- `ls` - list `ls -l`, `ls -a`, `ls -h`, `ls -la`(combination).
- `touch` - to create a file.
- `git init` - to initialized git.
- `git status` - to see what's currently inside the staging area.
- `git add` - to add the changes to the staging area.
- `git commit -m` - a message to track the changes that was made. _ALWAYS USE PRESENT TENSE_.
- `git log` - to see the commit that was made.
- `clear` - to clear the terminal.
- `git checkout` - to go back to the last position of our local repository when commit is done.
- `git diff index.html` - to check the difference between the current version of the file and the last save point.
- `git checkout` - to roll back to the previous version.

## GitHub

**Remote Repository**

- `git remote add origin` - to transfer all the commits from the local repository to the remote repository.
  - _origin_ is the name of the remote repository.
- `git push -u <remote name> <branch name>` - pushes local repository to remote repo.
  - _bascially links up local repo to remote repo_.
  - _main_ is the default branch of all the your commits.

**.gitigniore**

- _stuff that don't want to be commited on an opem platform like GitHub_
- Sample Files:
  - secret passwords
  - API Keys
  - OS generated files
- use wildcards `*.txt` -- _research this_

**CLoning**

- `git clone <url>` - to craeata a local copy of a remote repo.

**Branching and Merging**

- `git branch <branch name>` - to create a branch.
- `git branch` - to see the branches.
  - `*main` - asterisk means you're currently on that branch.
- `git checkout <branch name>` - to switch branch.
- `git merge <branch name>` - to integrate features or fixes from a feature branch into the main branch.

**Forking and Pull Requests**

- _Forking_ - a common practice that allows you to create a personal copy of someone else's project under your own GitHub account.
- _Pull Request_ - enables developers to propose changes, collaborate on code improvements, and maintain high-quality software projects through thorough review and discussion.

## Terminologies

- Property
- Value
- Syntax
- Method
- Function
- Typeface
