# PCB Projects

This repository contains all PCB designs used on the UMSAE Formula Electric team!
(Missing Discharge PCB as it is being developed)

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

### Making PCB Changes
- `main` -> This branch contains the working version of the boards. At any given time, you should be able to clone this branch and send all the files off to JLC to order the boards with no issues

If you want to make a change to a PCB, follow these steps:
1. Clone this repo by clicking the "Clone repository from the internet" button:
<img width="546" height="477" alt="image" src="https://github.com/user-attachments/assets/01de67c9-e776-4948-b0b8-adc451016200" />

<br>
<br>

2. Search for the "electrical" repository:
<img width="615" height="234" alt="image" src="https://github.com/user-attachments/assets/fdbc84b9-dea9-4017-90d7-ad3ea961463d" />


<br>
<br>

3. Make sure your file path is to a hard drive / ssd on your computer (usually a C: or D: drive):
<img width="590" height="83" alt="image" src="https://github.com/user-attachments/assets/1b89c1c5-fd7f-4d44-a57d-c4b42ec691f9" />


<br>
<br>

- For the next steps you'll need to use our branch naming convention ...

#### Branch Naming Convention
`PCB_NAME_20XX_name_revXX`

Branch Name Components:
- PCB_NAME -> Name of the PCB you want to make changes to
- 20XX -> year of the board change
- name -> your first name (because GitHub usernames aren't that helpful lol)
- revXX -> the revision number of your change

Example: `PCB_VCU_2025_caleb_rev01`

4. Click the current branch button. Once you know which PCB you want to change, create a new branch with following naming convention:
<img width="862" height="578" alt="image" src="https://github.com/user-attachments/assets/3a27807b-f1c8-454f-9d31-804d835ae4f2" />


<br>
<br>

5. Once you've made your branch click the "Publish branch" button:
<img width="922" height="128" alt="image" src="https://github.com/user-attachments/assets/a51dfc35-d6f0-4bbf-b94b-9248b1a08185" />


<br>
<br>


6. Now make your your changes!

Once you're happy with your changes follow these steps to get them on GitHub ...

### Saving your work!
1. Check that you are on your branch!! The "current branch" section should have your branch name and not someone elses / main:
<img width="602" height="962" alt="image" src="https://github.com/user-attachments/assets/fe217de0-eada-4460-8ce6-46cc30e88720" />

<br>
<br>

2. Check all the files that you changes:
<img width="306" height="680" alt="image" src="https://github.com/user-attachments/assets/857cc3b6-c871-4ddd-907a-21620f9d212e" />

<br>
<br>

3. Fill out a commit message with info related to the board changes you made:
<img width="264" height="221" alt="image" src="https://github.com/user-attachments/assets/2f3032e2-3ac5-48e2-9c5b-e2e8b1aa52df" />

<br>
<br>

4. Commit your changes! (Hit the blue button in prev pic)
5. Click "Push origin" to push it to GitHub!
<img width="661" height="211" alt="image" src="https://github.com/user-attachments/assets/494a9259-8110-4ea2-95b9-e48b9b5ec476" />











