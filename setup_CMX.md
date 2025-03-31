# How to set up CMX for MacOS
For any one who is now to CMX, here is the tech stack you need to install, and step by step how to set up a CMX sample web site.

!!!NOTE!!!
This tutorial is made in MacOS but some steps are common and usable for windows

## Overview
This file discript how to setup cmx and what software you should install to setup cmx.

## Requirement
### Must
- node.js V14
- npm
- nvm (for install node.js old version)
- git
- github account access for cmx private project

### Optional
- [homebrew](https://brew.sh/)
- [chocolatey](https://chocolatey.org/)
- cnpm (for china region to speed up node package download)

## Installation
Install Requirement with package manager:
1. Install requirment software.
    ``` bash
    $ brew install npm nvm nodejs git
    ```

2. Install and apply node.js V14 with nvm.
    ``` bash
    $ nvm install 14
    $ nvm use 14
    ```
3. Download cmx sample project with git.
    !!!NOTE!!!
    You need to have account access to cmx project first
    ``` bash
    $ git clone https://github.com/IntimexTechnicalTeam/CMX4-GreatTang
    ```
4. Go in to project folder and install all depandency.
    ``` bash
    $ cd CMX4-GreatTang
    $ npm install 
    ```

    If you are in the region of china, can use the alternative replacement of npm, cnpm to speet up the download:
    ``` bash
    $ npm install -g cnpm --registry=https://registry.npm.taobao.org
    $ cnpm install
    ```

5. Once all depandency is install now you can run the project and brows it on the browser.
    ``` bash
    $ npm run dev
    ```
6. Open the browser and forword to 
    http://localhost:8080
