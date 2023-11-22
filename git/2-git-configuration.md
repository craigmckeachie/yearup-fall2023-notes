# Configure Git

1. Open the command line.
1. You can be in any directory to run the following commands because they are global git configuration settings.
1. Set your username:

   ```
   git config --global user.name "FIRST_NAME LAST_NAME"
   ```

1. Set your email address:

   ```
   git config --global user.email "MY_NAME@example.com"
   ```

   > Use the same email you used when creating your Github account

1. Configure `main` as the default branch name for new repositories instead of `master`.

   ```bash
   git config --global init.defaultBranch main
   ```

   > This change will occur for any new git repositories you initialize on your computer but will not affect existing repositories initialized before the command was run.

1. Push to the default branch when remote is indicated but no branch is provided.

   ```sh
   git config --global push.default current
   ```

1. `--set-upstream` on default push when no upstream tracking exists for the current branch

   ```
   git config --global push.autoSetupRemote true
   ```

   Prevents this issue:

   ```
   fatal: The current branch feature/my-cool-branch has no upstream branch.
   To push the current branch and set the remote as upstream, use

      git push --set-upstream origin feature/my-cool-branch
   ```

   For more details read [this article](https://dev.to/this-is-learning/this-new-git-push-config-will-save-you-lot-of-frustration-27a9#:~:text=It%20will%20set%20in%20your,automatically%20set%20the%20default%20upstream.)

1. To verify the settings were set correctly.

   ```
   git config --list --show-origin
   ```

   > Add the `--show-origin`` flag to see the file where the configuration settings are stored


   1. Editors
   ```
   git config --global merge.tool vscode
   git config core.editor code --wait
   git config diff.tool vscode
   ```
