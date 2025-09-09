# PCB Projects

This repository contains all PCB designs used on the UMSAE Formula Electric team!

## Cloning The Repository

- If you do not have git installed, please download it [here](https://git-scm.com/downloads).
- Clone the repository using the git command line interface (CLI) by typing the command `git clone git@github.com:UMSAE-Formula-Electric/electrical.git`.
- Alternatively, you can install [GitHub Desktop](https://desktop.github.com/).

# Altium Designer - Installation & Setup

Altium Designer is the primary tool used to design our PCBs. If you do not have Altium installed, Please contact the ESO to get a license and any information to get Altium up and running on your computer. Once you've been added, you should receive an email with your login. It is recommended that you sign in to [altium.com](https://www.altium.com/) and change your password.

The team orders our boards through [JLCPCB](https://jlcpcb.com/). 

### Download

Altium is available for download on their [downloads page](https://www.altium.com/products/downloads). You will be prompted to log in, so make sure you have your account set up first! Download the lastest version. Most versions are backwards compatible, so it is not essential to stay completely up to date but it is recommended to always use the latest major release.

- Refer to the Altium Tutorial for the best install settings

## Version Control

We want to have consistent naming schemes and version control! Here are some rules to follow, and how to use this repository:

### Branches
- `main` -> This branch contains the working version of the boards. At any given time, you should be able to clone this branch and send all the files off to JLC to order the boards with no issues

If you want to make a change to a PCB, follow these steps:
1. Clone this repo by by typing the command `git clone git@github.com:UMSAE-Formula-Electric/electrical.git`
2. Type `git checkout main` in the command line to switch to the main branch
3. Type `git fetch && git pull` to ensure you have the most up to date main branch, including changes from any other members
4. Now, understand which PCB you want to change (this helps with our branch naming convention)
5. Create a new branch with following naming convention (WIP):

- ePBR*CAR-YEAR*_*INSERT-BOARD-NAME*

- For example: `ePBR26_ACU_Controller`

6. Create the branch by typing: `git checkout -b INSERT_YOUR_BRANCH_NAME`
7. Then type: `git push -u origin INSERT_YOUR_BRANCH_NAME`
- This allows GitHub to track the branch you made locally on your computer
8. Make your changes ...
- Once you're happy with your changes follow these steps to get them on GitHub:


- WIP
