# dotfilesPC

Docs of cloned dotfiles [here](https://github.com/mathiasbynens/dotfiles). 

Cloning the repo using GitHub Desktop and trying to run
```
source bootstrap.sh
```
 on Bash for Windows 10 resulted in this error: *$'\r': command not found*. Cloning the repo with Git in Windows results in Windows-style line endings in the files, which error in the Ubuntu-based Bash shell. The solution is to clone the files from within the shell, which in this case was:

```
git clone https://github.com/mathiasbynens/dotfiles.git
```

## Usage

1. Open Bash shell
2. cd to dotfiles repo and run:
```
source bootstrap.sh
```
