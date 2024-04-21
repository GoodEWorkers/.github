# Contribute with Good eWorkers
Hello 🌠 Thanks for reading through our contribution guide ! 

We try to keep things simple for now and are open to suggestions and will improve things as we grow. 
If you want to contribute here a few rules on how to do so in our repositories. 

## Why ? 
We want our history to be easy to follow and read through for everyone, therefore before doing 
any change the first step is to create an issues. You can create the issue either in our github management tool
or directly in the repository in which you want to do a change. 

## Commits
### Conventional Commits: Organized Commit History

Commit messages provide a short description of code changes. Here's our convention:


- Type: What kind of change was made (e.g., "feat", "fix", "docs")
- Scope: The GitHub issue number related to the change (e.g., "#15")
- Subject: A concise description of the change

Example: `feat (#48): Add volunteer signup form`

#### Benefits:
- Easy-to-read commit history
- Clear connection to issues for context

## Branch management

### Github flow
For small projects and unless stated otherwise we use Github flow to contribute

#### Branch naming convention 

- Main Branch: The code that is always ready for release (should be stable).
- Feature Branches: Created from `develop` for each new feature or fix. Name them like this: `feature/<brief-description>.` Example: `feature/add-search-bar`
- Hotfix Branches: Created from `main` for critical bug fixes. Name them like this: `fix/<brief-description>` Example, `fix/payment-form-error`



[![](https://mermaid.ink/img/pako:eNqNj7EKwzAMRH8laE7p7rmlH9DVi2optkltB0UeSsi_16UhSwlU03F370ALuEIMBnzUm-AUbO7auZJS1F_9EMwudAOjVuEzEp2UMc1bM7AbS9XD_GB15xLG_LUSi-f_d6CHRjSc2ivLJ7GggRNbME0SymjB5rX1sGq5v7IDo1K5hzoRKl8iesEEZsDnvLtXilpkM9c3EYllgg?type=png)](https://mermaid.live/edit#pako:eNqNj7EKwzAMRH8laE7p7rmlH9DVi2optkltB0UeSsi_16UhSwlU03F370ALuEIMBnzUm-AUbO7auZJS1F_9EMwudAOjVuEzEp2UMc1bM7AbS9XD_GB15xLG_LUSi-f_d6CHRjSc2ivLJ7GggRNbME0SymjB5rX1sGq5v7IDo1K5hzoRKl8iesEEZsDnvLtXilpkM9c3EYllgg)

## Pull Requests (PRs): Collaboration in Action
Pull Requests are how to propose changes and get team feedback:
1. Create a feature branch out of main
2. Test thoroughly and create a merge request into main. This usually triggers our CI pipeline that will do basic checks and deploy a preview environement of your code
3. Assign one or multiple members of the team on the pull request for review. 
4. Once approved you can merge the pull request to main. 
5. Ensure that after deployment by the CD pipeline everything still works in production

## Resources
- [Git & GitHub Basics](https://learngitbranching.js.org/)
- [Github exercise](https://docs.github.com/en/get-started/start-your-journey/hello-world)
- [Conventional Commits](https://www.conventionalcommits.org/)
- [Github flow](https://www.alexhyett.com/git-flow-github-flow/)
