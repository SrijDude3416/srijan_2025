---
layout: post
title: Sprint 1 - Verify Hacks
description: Verifying Hacks and Knowledge for Sprint 1
type: collab
courses: {'csa': {'week': 3}}
comments: True
---

# Shell Commands:

## Version Control


#### In the development process, developers use version control. Annotate in your notes what you have learned about version control during this setup process.
- How are the files from GitHub placed on your local machine? How do you navigate to those files?
  - The files from GitHub are placed on our local machines by running `git clone <repository name>`. This command essentially makes a copy of the repository on your local computer and lets you edit then push them to a remote. 
- How are the files updated in GitHub? How do you navigate to those files?
  - The files are updated in GitHub by:
    - first making your desired changes
    - staging all your changes (can be done with vscode git integration)
    - committing the changes once you've decided which files you want to send to the GitHub servers
    - pushing all the changes to GitHub
    - to view the files that you added, you can go to your repository on `github.com` and then go to commits. It'll then show all the files that have been changed.
- How would you update your template of the portfolio_2025 repository? How would you make it more applicable to your specific course?
  - I would update my template of the portfolio_2025 repository by, first, changing the name of the repository to inclue my own information; second, changing all config.yml information to be my own; and third, adding my own information to the index and about me pages to really make the website my own. 


## Localhost vs. Deployed Server

#### Put into words the difference between viewing GitHub Pages running on your localhost machine versus running on a deployed server
- What is the localhost URL for your project? Can anyone else see what you see?
  - The localhost URL for my project is: `127.0.0.1:4100/srijan_2025/`
  - Nobody else can see what I see when I'm changing and hosting those changes on localhost because the website is being served only to my computer on its loopback address.
- What is the GitHub Pages URL for your project? Can anyone else see what you see?
  - The GitHub Pages URL for my project is: `srijdude3416.github.io/srijan_2025/`
  - Everyone can see what I see because it is being hosted on a public domain with no login restrictions

## DNS and GitHub Pages
#### DNS is the address manager for the internet. Reflect on the following questions:
- Is there a domain on your GitHub Pages?
  - There is a domain on my GitHub Pages. That domain is: `srijdude3416.github.io`
- Is the URL for your GitHub Pages different from your neighbors’ URLs? Did you change the URL? If so, when?
  - They are, that is because: first, our usernames are different meaning our domains will be different and second, our home path for our website might be different.

## GitHub Commits and GitLens Proof:
![](../../../../images/gitlensProof.png)
![](../../../../images/analytics.png)