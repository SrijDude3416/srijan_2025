---
layout: post
title: Sprint 1 - Verify Tools
description: Verifying Tools and Software for Sprint 1
type: collab
courses: {'csa': {'week': 3}}
comments: True
categories: ['Collaboration']
---

----------------- Checking git version -----------------
```
Input: git --version
Output: git version 2.34.1
```
----------------- Checking ruby version -----------------
```
Input: ruby -v
Output: ruby 3.0.2p107 (2021-07-07 revision 0db68f0233) [x86_64-linux-gnu]
```
----------------- Checking python version -----------------
```
Input: python --version
Output: Python 3.10.9
```
----------------- Verifying Jupyter Kernels -----------------
```
Input: jupyter kernelspec list
Output: Available kernels:
  python3    /home/dudeamabobby/nighthawk/srijan_2025/venv/share/jupyter/kernels/python3
  java       /usr/local/share/jupyter/kernels/java
```
Verifying creation of project environment variables
```
Input: echo "Repos home dir: /home/dudeamabobby/nighthawk"
Output: "Repos home dir: /home/dudeamabobby/nighthawk"
```
```
Input: echo "Project dir: $project_dir/srijan_2025"
Output: "Project dir: $project_dir/srijan_2025"
```
```
Input: echo "Posts dir: $project/_posts"
Output: "Posts dir: $project/_posts"
```
```
Input: echo "Notebooks dir: $project/_notebooks"
Output: "Notebooks dir: $project/_notebooks"
```
```
Input: echo "Repo: https://github.com/nighthawkcoders/srijan_2025.git"
Output: "Repo: https://github.com/nighthawkcoders/srijan_2025.git"
```
Verifying configuration of GitHub 
```
Input: git config --global --list
Output: user.email=srij.0504@gmail.com
user.name=SrijDude3416
```
