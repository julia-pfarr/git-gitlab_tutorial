# Installation and Setup

## Git configuration

First: Download [Git](https://git-scm.com/downloads). After installing Git, please run these commands one after another in your terminal (it doesn’t matter in which directory you currently are) to check and complete your setup (you can just copy-paste the commands):
```
git --version
```
→ this tells you if the installation was successful by telling you the version number of git you installed.
```
git config --global user.name "Example Name"
```
→ put in your real name. You have to set the quotation marks around your name otherwise git can’t read it.
```
git config --global user.email example@example.com
```
→ choose your preferred email.
```
git config --global init.defaultBranch main
```
→ this makes sure that your default branch is main, which is currently used by most users as their default branch. Don’t worry about what it means, we will talk about that in the workshop ☺
```
git config --global core.editor ExampleEditor
```
→ this sets a default text editor when working with git. Just type in the editor you want to use. My recommendation is to use nano or vim. You don’t have to download anything, it’s already on your machine as it is a command-line editor. So, it’s super convenient for working with git, as
the git commands are also run in the command-line. It simply means that when writing commit messages you can do it in one window (i.e., your terminal) and you don't have to bother with a new window opening and making sure it's really closed etc. But of course, you can use any text editor you want. Just as an example, for making nano your gloab git-editor
type `git config --global core.editor nano`. 

```
git config --global pull.rebase false
```
```
git config --global pull.merge true
```
→ this makes sure that your merges are shown in the commit history which is nice if you just start learning to use Git. When you're more experienced, git rebase is also a very nice command (we'll learn about that in the course!).
```
cat ~/.gitconfig
```
→ checks if your configuration was successful. It should give you this output:


      [user] name = Your Name email = yourname@yourplace.org
      [core] editor = YourEditor
      [init] defaultBranch = main
      [pull] rebase = false merge = true


## GitLab account

- For this course you _must_ have an account on [gitlab.com](https://gitlab.com/). This is a different GitLab from our University GitLab which we provide through the DataHub. As our instructors Peer and Michael are not part of University Marburg, they don't have access to our University GitLab. Hence, we set up this course on gitlab.com to ensure access to EVERYONE. 
- Please set up an ssh connection to communicate with GitLab. You can follow these [instructions](https://docs.gitlab.com/ee/user/ssh.html) to do so.
- The very important part is to check if you can connect by typing `ssh -T git@gitlab.com` in your terminal. It should give you this 

```
The authenticity of host 'gitlab.com (35.231.145.151)' can't be established.
ECDSA key fingerprint is SHA256:HbW3g8zUjNSksFbqTiUWPWg2Bq1x8xdGUrliXFzSnUw.
Are you sure you want to continue connecting (yes/no)? yes
```

YES!

```
Warning: Permanently added 'gitlab.com' (ECDSA) to the list of known hosts.
```

## VSCode

I always recommend to work in [VSCode](https://code.visualstudio.com/) for various reasons. With Git it is even more convenient, as it has a built-in terminal and a built-in Git integration. What is more, you can install multiple [extension packs for Git](https://www.hatica.io/blog/git-extensions-for-vs-code/) as well as for [GitLab](https://docs.gitlab.com/ee/editor_extensions/visual_studio_code/). 

When you open VSCode you see a "brick" symbol on the left side bar. This is for installing extensions. I recommend installing the [Git Graph extension](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph) and the [GitLab Workflow extension](https://marketplace.visualstudio.com/items?itemName=GitLab.gitlab-workflow). 

You can of course use any editor you want, though. This is just a recommendation. 

