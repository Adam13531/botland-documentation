# Bot Land Documentation

## Prerequisites

1. Have [git properly configured](https://help.github.com/en/github/getting-started-with-github/set-up-git) on your machine.
1. [Fork](https://help.github.com/en/github/getting-started-with-github/fork-a-repo#fork-an-example-repository) this repository.
1. [Clone](https://help.github.com/en/github/getting-started-with-github/fork-a-repo#step-2-create-a-local-clone-of-your-fork) your fork.
1. [Download](https://github.com/Adam13531/botland-documentation/releases/latest) the Bot Land documentation editor.

## Editing

1. Edit the documentation using the Bot Land documentation editor.
1. Review your changes using the *Export* button at the top right of the editor.
1. Save the archive containing your changes.

## Submitting

**Changes made outside of the editor may be rejected. If you can't edit something in the editor or you encounter a problem, please open an issue.**

1. Create a new branch in your fork.
1. Paste the modified files.
1. Push the new branch to your fork.
1. [Submit a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) with your changes.
1. Optionally ping Adam on [Discord](https://discord.gg/BotLand) to tell him that you've made a change (Adam13531#3531).

## Troubleshooting

If you have any new issues, please [report them](https://github.com/Adam13531/botland-documentation/issues/new).

### A Git-related issue pops up at launch

For example, this error:

> git@github.com: Permission denied (publickey).  
> fatal: Could not read from remote repository.
>  
> Please make sure you have the correct access rights  
> and the repository exists.

For me, this showed up when using CMD on Windows. To fix it, I had to launch the application from `bash` with `ssh-agent` running. This probably indicates an issue with your Git configuration though, for which [this guide](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup) may help.
