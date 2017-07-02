---
layout: post
title: "Add an existing project on Github"
description: Add your existing project on Github for online collaboration
category: how-to
headline: Add project to github
tags: [Github, Add project on Github]
comments: false
share: true
---
Learning a new platform is never comfortable, one of the reasons why we find many people running away from trying to learn GitHub. Our suggestion? Ease it in! GitHub is currently the largest online forum of collaborative works that exists in the world, or simply put a place you can’t happen to ignore if you belong to the technical world.

Here are a few simple steps to get you started on adding an existing project on GitHub.

1. (Assuming you have a GitHub account already functioning) Click on the little ‘+’ button on the top right and select ‘New Repository’.
2. You avoid a few errors, leave files like README/license/gitignore for after you have successfully pushed your project.
3. Open Git Bash and change your current working directory to the local project.
4. Initialize the local directory as a Git repository. Type the following on the prompt: `git init`.
5. Add the files in your new local repository. It prepares them for the first commit. Type the following on the prompt: `git add .`.
6. Commit the files that you've staged in your local repository.Type the following on the prompt: `git commit -m "First commit"`. “First commit” is just a string which appears along with your commit. You can omit this or type in whatever string you want to view there.
7. At the top of your GitHub repository's Quick Setup page, click to copy the remote repository URL.
8. Type the following to the prompt: `git remote add origin <remote repository URL>` where `<remote repository URL>` is the URL you copied in the previous step.
9. Type the following on the prompt: `git remote -v`. This verifies the new remote URL.
10. To push changes in your local repository to GitHub, type the following on the prompt: `git push origin master`.

And, you are all done!
Here are a few basic videos to get you started with GitHub. Happy learning!
[https://thenewboston.com/videos.php?cat=80](https://thenewboston.com/videos.php?cat=80)

