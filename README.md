# Custom Git Bash Script

This Bash script is designed to simplify and customize common
Git operations, such as adding, committing, and pushing
changes, as well as configuring Git credentials and user
information.
It allows you to interactively set various Git-related options.

## Usage

You can use this script to perform the following tasks:

### Custom Git Add, Commit, and Push (custom-git-acp)
This function allows you to add, commit, and push changes to your Git repository.
It provides the flexibility to specify which files to add, the commit message,
and the branch to push to.
### $2
* . : Specifies git add . ...
* 'file_or_directory': 'git add <file_or_directory> ...

### $3
* Specifies the commit message

### set_credentials
* store: Stores Git credentials in the credential store.
* cache: Stores Git credentials in the cache.
`custom-git set-credentials store`

```bash
custom-git.sh custom-git-acp <file_or_directory> <commit_message>

