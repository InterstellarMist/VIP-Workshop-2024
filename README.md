# VIP-Workshop-2024
Research laboratory workshop files for the Video and Image Processing Lab (VIP)  of the National Institute of Physics (NIP-UPD).

## GitHub Basics
Changes in a repository are always tracked. This is useful when multiple people are working on the same workspace editing at the same time.
Unlike google docs or other live collaboration software, the approach to git follows a structure. 

Add changes (git add) -> Finalize changes (git commit) -> [Optional] Synchronize changes from online repository (git pull)

Here the a [link](https://docs.github.com/en/get-started/quickstart/hello-world) for a github quickstart guide. Additionally, this is not covered in this workshop but 
[this](https://www.freecodecamp.org/news/introduction-to-git-and-github) shows how to work on files locally then upload then synchronize 
them automatically on GitHub.

![](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fimages.edrawmax.com%2Fwhat-is%2Fgitflow-diagram%2F1-git-flow-process.png&f=1&nofb=1&ipt=566e51f4964dfa2f25b67a28f962180798a48efe186b819ab751041e56a9d711&ipo=images)
[Image Source](https://www.edrawmax.com/article/gitflow-diagram.html)

The flowchart above shows the typical flow of a repository. Changes are usually done in other branches before merging to the main branch that serves as the release for the public.
Branches are not fixed and the use depends on the workflow but typically there is a 'development' branch that shows minor incremental changes that still get tracked like bug fixes or part of a feature.
These branches are typically not available to the public as further testing is required for the code to be stable. Once the changes in this branch are considered to be done then it can finally be 
merged to the 'main' branch for the final release.

For a basic overview, we will be doing this from the GitHub website and the GitHub desktop app for a convienient user experience. Experienced users may opt to do this in shell.

## Requirements
- Create GitHub account
- Download [GitHub Desktop](https://desktop.github.com)

### Uploading Files
From GitHub website, 

1. Click on the `Add File > Upload Files` then upload necessary files
2. Add a descriptive text on the changes made i.e. `added github workshop files`
3. Make sure to toggle the make a new `Create a new branch for this commit and start a pull request`. Then create a name for this branch. This takes you to the pull request page.
(It is good practice to make changes in another branch then merge it with the main branch after)
4. Put a title then click `Make Pull Request`. This allows to administrator to review changes before pushing changes to the main branch.
5. Wait for the pull request to be approved.

### Downloading the repository
Using GitHub Desktop,

1. Sign in using GitHub account
2. Click `Clone a repository from the Internet`, go to URL tab and input the repository link `https://github.com/InterstellarMist/VIP-Workshop-2024.git`

Using git CLI, `git clone https://github.com/InterstellarMist/VIP-Workshop-2024.git`
