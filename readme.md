# Younglings

## What it is?

This is a [Badger Way - Dev Edition](https://docs.google.com/presentation/d/1RniEJbkB1BQCe4_NZMUnIx_1kgV4dfPN0wx6-aZ_Q0M/edit?usp=sharing) exercise for non technical people to create awareness about the Red Badger development process.

## Pre requisites

- [ ] An account on [GitHub](https://github.com/)
- [ ] [GitHub Desktop](https://desktop.github.com/) installed in your machine and linked to your GitHub account
  - _To link your GitHub Desktop with your account, please follow this [instructions](https://help.github.com/desktop/guides/getting-started-with-github-desktop/authenticating-to-github/)_
- [ ] [Visual Studio Code](https://code.visualstudio.com/download) installed in your machine

## Instructions

- Please _clone_ this repo to your _Desktop_ folder using the following URL `https://github.com/redbadger/younglings.git` ![](./instructions/clone.gif)
- On GitHub Desktop create a new branch with your first and lastname in lowercase ![](./instructions/new-branch.gif)
- Please, navigate to [`src/template`](../src/template) folder and copy and paste changing its name to your first and lastname

  - `template` ---> `paul-roper`

- Add your details to the business card ![](./instructions/design.png)

- Push your changes and you can see it on the following enviroment
  ```
  https://younglings-<BRANCH_NAME>.s3-eu-west-1.amazonaws.com/index.html
  ```
  Just replace <BRANCH_NAME> with the name of the branch you created earlier

- Go back to https://github.com/redbadger/younglings.git

- You should see a "recently pushed branches" section. Click the "Compare & pull request" button to open the pull request

![](./instructions/create-pr.png)

- Fill in the title and description and mark the pull request as "ready for review" by using a label

![](./instructions/pr.png)

- Review someone else's business card and when you're happy with the changes, change the label to "ready for branch test"

- Test the business card using the URL provided earlier. If everything looks okay, change the label to "ready for merge test"

- Merge the pull request using the button at the bottom of the page

![](./instructions/merge.png)

- Once the build finishes, you'll see the business card here:

  ```
  https://younglings-staging.s3-eu-west-1.amazonaws.com/index.html
  ```

- When everyone has finished putting their business cards together, we'll do a release to production. When the build finishes, the business cards can be found here:

  ```
  https://younglings-production.s3-eu-west-1.amazonaws.com/index.html
  ```
