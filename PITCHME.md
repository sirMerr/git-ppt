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

---
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

#### Branch
- A list of commits in a separate unit.
- 'Branching out'.
- Each branch should have a singular purpose.
- Usually for a feature or fix.
---

### Basic git Commands
*Note: Each command usually comes with their own options*

Command | Usage | Description |
------------ | ------------- | ------------------- |
`git init` | `git init` | Initializes new repository in the current directory (adds `.git` folder)|
`git clone` | `git clone https://github.com/sirMerr/git-ppt.git` | Makes a copy of a remote repository locally (to your computer)|
`git status` | `git status` | Displays untracked, changed or staged files (status of repo) |
`git add` | `git add .`, `git add fileA src/fileB.js` | Add current state of file(s) to staging |
`git commit` | `git commit -m 'Update README.md` | Anything that’s been staged with `git add` will become a part of the snapshot with git commit |
`git pull` | `git pull` | Update local repository with changes from remote one. Usually used when teammate makes changes and you want to receive them in your working directory |
`git push` | `git push` | Pushes new commits to remote repository |

---

### Activity: Install git and play with a repository
- https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
- Add a `README.md` (info about your repository for anyone to read) or any other file
- Commit the file

---

### GitHub

- GitHub hosts repositories for you, so you and others can access them from anywhere.
- It's a collaborative platform
- Allows you to have docs/wiki, make issues (log features/bugs), pull requests and more
---

### Activity: Make a GitHub account and push your local repo to GitHub
- https://github.com/
- <img width="833" alt="screen shot 2018-06-28 at 4 16 44 pm" src="https://user-images.githubusercontent.com/11183523/42058558-cea9c5e6-7aee-11e8-81ae-4bf32bb551f1.png">
- <img width="806" alt="screen shot 2018-06-28 at 4 17 22 pm" src="https://user-images.githubusercontent.com/11183523/42058552-cd7e8904-7aee-11e8-9543-2d3839887fb4.png">

---
### Activity: Make a GitHub account and go through GitHub Learning labs
- https://lab.github.com/

### Final Activity - Make a PR to this powerpoint repo
- Make a pull request to the repository below with your name and GitHub info in the `README.md` using either GitHub or the command line
- https://github.com/sirMerr/git-ppt
