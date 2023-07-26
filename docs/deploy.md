# Building and Deploying Your Site

This process makes your MkDocs site live and accessible to people. To get started:

- **Create** a GitHub account on the [website](https://github.com/).
- **Create** a new repository on GitHub. For more information, see [Create a Repo](https://docs.github.com/en/get-started/quickstart/create-a-repo).
- **Push** your site to this new repository by typing these commands after each other in your terminal.
  ```python
  git init
  git add . //Ensure to add a space after ‘add’
  git commit -m "First commit"
  git remote add origin https://github.com/DrVickie8/MkDocsTest.git
  git push -set-upstream origin master
  ```
- **Type** in your terminal and wait for a few seconds
  ```python
  mkdocs gh-deploy
  ```
- **Create** a new file called `.gitignore`, add the newly created folder `site` as seen below and save changes.
  > _Your_ `first-project` _is the name of the folder the_ `site` _folder is in._
  > ![](https://lh5.googleusercontent.com/XCH_ToON3enQl03imHkNcicNCJasWkJjEyE_fAjZhr_azkfdRqkXEEsbQSTAzFAZXL-eP5i-Ep3JcGUayrq619Ot-2hy9dD8UFNjV184FigCVeU6VTWhtNFrpGnUtZCShjBxdncwkH4yr33mknDYHE0 align="left")
- **Repeat** the commands below.
  ```python
  git init
  git add .gitignore //Ensure to add a space after 'add'
  git commit -m "Fix: Adding .gitignore file"
  git push
  ```
- **Go** to your GitHub repository and refresh the page.
- **Scroll down** to the ‘Environment’ section and click ‘github-pages'
- **Click** ‘View deployment’, and your MkDocs site is now available.
  Here is a link to a GitHub repository and documentation site used to deploy a MkDocs site created following the instructions in this guide.
