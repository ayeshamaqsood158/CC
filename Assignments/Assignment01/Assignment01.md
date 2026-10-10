# Assignment 01: Git, Gitea, GitHub, Git LFS, and GitHub Pages



**Name:** Ayesha Maqsood 

**Registration Number:** FA24B1-SE-042 

**GitHub Username:** ayeshamaqsood158 

**Date:** 10 October 2026




## Task 1: Install Gitea and Push a Repository from the Ubuntu Server

- Installed Docker and Docker Compose on the Ubuntu server.

- Cloned the instructor's Gitea setup repository and started Gitea and PostgreSQL using `docker compose up -d`.

- Configured Gitea with PostgreSQL database settings and created an administrator account.

- Created a local Git repository named Àssignment01`on the Ubuntu server.

- Initialized Git, created a `README.md`with student information, and committed it.

- Generated a Gitea Personal Access Token and added the Gitea remote.

- Pushed the repository to Gitea successfully.



## Task 2: Push the Same Repository to GitHub

- Created an empty public GitHub repository named Àssignment01`.

- Added GitHub as a second remote in the same local repository.

- Verified  both remotes (`gitea`and `github`).

- Pushed the `main`branch to GitHub successfully.



## Task 3: Track Three Large Files with Git LFS

- Initialized Git LFS and configured tracking for `.bin`files.

- Created three files larger than 100 MiB each:

  - `large-file-1.bin`(101 MiB)

  - `large-file-2.bin`(102 MiB)

  - `large-file-3.bin`(103 MiB)

- Staged and committed the files, then pushed them to GitHub using Git LFS.

- Verified that all three files were tracked by Git LFS.



## Task 4: Create a Portfolio or CV with GitHub Pages

- Created a public GitHub repository named àyeshamaqsood158.github.io`.

- Developed a portfolio website using HTML (ìndex.html`) and CSS (`styles.css`).

- Included required sections: About Me, Education, Skills, and Projects.

- Deployed the site using GitHub Pages (Deploy from branch: `main`, `/ (root)`).

- Verified the live site at: [https://ayeshamaqsood158.github.io/](https://ayeshamaqsood158.github.io/)




## Repository Links

- **Gitea Repository:** http://192.168.83.129:3000/admin/Assignment01

- **GitHub Assignment01 Repository:** https://github.com/ayeshamaqsood158/Assignment01

- **Live Portfolio:** https://ayeshamaqsood158.github.io/
