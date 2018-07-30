## Younglings

## What it is?

This is a [Badger Way - Dev Edition](https://docs.google.com/presentation/d/1RniEJbkB1BQCe4_NZMUnIx_1kgV4dfPN0wx6-aZ_Q0M/edit?usp=sharing) exercise for non technical people to create awareness about Red Badger development process.

## Pre requisites

- [ ] An account on [GitHub](https://github.com/)
- [ ] [GitHub Desktop](https://desktop.github.com/) installed in your machine and linked to your GiHub account
  - _To link your GitHub Desktop with your account, please follow this [instructions](https://help.github.com/desktop/guides/getting-started-with-github-desktop/authenticating-to-github/)_
- [ ] [Visual Studio Code](https://code.visualstudio.com/download) installed in your machine

## Instructions

- Please _clone_ this repo to your _Desktop_ folder using the folowing URL `https://github.com/redbadger/iceberg.git` ![](./instructions/clone.gif)
- On GitHub Desktop create a new branch with your first and lastname ![](./instructions/new-branch.gif)
- Please, navigate to [`src/template`](../src/template) folder and copy and paste changing its name to your first and lastname

  - `template` ---> `paul-roper`

- Develop a Red Badger business card as per design ![](./instructions/design.png)

  - All assets (fonts and images) are linked to the HTML document so you don't need to do it
  - We set a [solutions](./src/solution) folder, if you need a hint/clue/help
  - Colours and font families are in your CSS template
  - Please, follow these requirements
    - [x] Business cards dimensions are 430px width and 300px height
    - [x] Padding on back of the card is 50px;
    - [ ] Front card font family is `proxima-nova-bold`
    - [ ] Back card font family is `sentinel-bold`

- Push your changes and you can see it on the following enviroments
  - Testing
    ```
    https://younglings-<BRANCH_NAME>.s3-eu-west-1.amazonaws.com/index.html
    ```
  - Staging
    ```
    https://younglings-staging.s3-eu-west-1.amazonaws.com/index.html
    ```
  - Production
    ```
    https://younglings-production.s3-eu-west-1.amazonaws.com/index.html
    ```
