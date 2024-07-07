

# GITHUB Documenation
<p align="center">
 
  <button class="button">:blush:  Git Tutorial</button>
  <button>:weary:  For Beginners</button>
  <button>:heart:  Clearly Explained</button>
  <button>:boom:  60+ useful commands</button> 
</p>

## Description
I have shared some important commands of GIT that will be helpful throughout your job life :D

## Initialize Git Repository
- `git init`
  - Initializes an empty Git repository.

## Remove Local Git Repository
- `rm -rf .git`
  - Removes the local Git repository.

## Add Specific File
- `git add <file name>`
  - Adds a specific file to the staging area.

## Add All Files from Current Folder
- `git add .`
  - Adds all files in the current folder to the staging area.

## Commit Changes
- `git commit`
  - Opens an integrated text editor to write a commit message.
- `git commit -m "commit message"`
  - Commits changes with a single-line message.

## Check Git Commit Details
- `git log`
  - Shows commit details with author, date, and time.

## Check New Changes
- `git show`
  - Displays new changes.

## Check Tracked Files
- `git ls-files`
  - Lists files being tracked by Git.

## Remove Specific File from Working Directory
- `rm filename.ext`
  - Removes a specific file (Git Bash command).

## Remove Unwanted Changes from a File
- `git checkout -- filename.ext`
  - Discards changes in a specific file.

## Check Available Help Options
- `git help log`
  - Shows help options for Git commands.

## Git Commands with Help Options
- `git log --oneline --graph --decorate --all`
  - `--oneline`: Displays information in one line.
  - `--graph`: Shows asterisks-based graph denoting branching hierarchy.
  - `--decorate`: Indicates which commits belong to which branches.
  - `--all`: Provides history for all branches in the repository.

## Git Aliasing
- `git config --global alias.hist "log --oneline --graph --decorate --all"`
  - Creates an alias `hist` for the command `log --oneline --graph --decorate --all`.

## Check Available Config List
- `git config --global --list`
  - Lists all global configurations.

## Use Git Alias
- `git hist`
  - Uses the alias `hist` to run `log --oneline --graph --decorate --all`.

## Check History for a Specific File
- `git hist -- filename`
  - Shows history for a specific file using the `hist` alias.

## Rename File in Git
- `git mv filename.ext newname.ext`
  - Renames a file in the repository.

## Remove File Completely from Repository
- `git rm filename.ext`
  - Removes a file from the repository (needs to be committed to take effect).

## Handle Deleted Files
- `git add -u`
  - Updates the index to delete the file.

## Addition and Deletion of Files
- `git add -A`
  - Adds new files and deletes removed files in the Git index.

## Ignore Files from Being Tracked
- Create a `.gitignore` file and specify the file names or patterns (e.g., `*.ext` for all files with a specific extension).
  - Example:
    ```
    *.log
    node_modules/
