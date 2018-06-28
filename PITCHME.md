# git and GitHub 

An explanation of version control and tooling with git and GitHub

---

### Version Control System (VCS)

- Tracks the history of changes as people and teams collaborate on projects together. 
- Keeps versions of your code. Ex: Saving a word document.

1. Which changes were made?
2. Who made the changes?
3. When were the changes made?
4. Why were changes needed?
---

### git

- `git` is a distributed VCS.
- **Every developer's working copy of the code is also a repository that can contain the full history of all changes**
---

### Important terms

#### Repository
- `git` project. Directory with `.git` folder
-  The entire collection of files and folders associated with a project, along with each file’s revision history. 

#### Commit
- The file history appears as snapshots in time called commits (like a picture), which are linked together and can be separated in branches
- Each commit log has who made the commit, when, what and why they were made. **You provide why/what**
- Rule of thumb: commit what you wouldn't want to lose.

- Commit message should be 
  - < 50 words
  - A present tense action verb (`Add`/`Update`) followed by what was changed
---
<img width="722" alt="screen shot 2018-06-28 at 12 51 11 pm" src="https://user-images.githubusercontent.com/11183523/42048696-00129346-7ad2-11e8-8c83-e8eec3b9701d.png">
---

### Important terms (cont'd)

#### Branch
- A list of commits in a separate unit.
- 'Branching out'.
- Each branch should have a singular purpose.
- Usually for a feature or fix.

---

### Basic git Commands
Command | Usage | Description |
------------ | ------------- | ------------------- |
`git init` | `git init` | Initializes new repository in the current directory (adds `.git` folder)|
`git clone` | `git clone https://github.com/sirMerr/git-ppt.git` | Makes a copy of a remote repository locally (to your computer)|
`git add` | `git add .`, `git add fileA src/fileB.js` | Add current state of file(s) to staging |
`git commit` | `git commit -m 'Update README.md` | Anything that’s been staged with `git add` will become a part of the snapshot with git commit |
