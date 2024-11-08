# Custom Bash Prompt
___
## Overview
This project customizes your Bash prompt to display time in AM/PM format and removes long prompts that you may have, with a clean design.
___
*SIMPLE VERSION: Just copy and paste the PS1 code from my file and put it in ~/.bashrc by `nano ~/.basharc` (nano is a text editor, and .bashrc is your bash config file) scroll down & shift + ctrl + v to paste onto a new line. To preview it, just paste it in the terminal since it will reset back to normal once your terminal is closed.*
___
### BEFORE: ![before](/images/before.png) 
### AFTER: ![before](/images/prompt.gif) 

## List of Requirements
1. **Operating System:**
A Unix-like operating system such as:
	- Linux (e.g., Ubuntu)

2. **Shell:**
The script is designed for the default Bash.
	- Only update bash: ```sudo apt update``` THEN ```sudo apt install --only-upgrade bash```
	- Check your bash version: ```bash --version```
  	- Recommended Bash Version: 4.0+

3. **Git:**
Git must be installed to clone the repository.
	- Ubuntu/Debian: ```sudo apt install git```

4. **Text Editor:**
Any text editor to modify configuration files if needed.
	- Nano (Recommended)
	- Check if you have nano installed: ```nano --version```
	- if not installed: ```sudo apt install nano```
	- use nano to customize your welcome message (see comments inside "custom_prompt.sh")
	- ```nano ~/Custom-Prompt-in-Bash/custom_prompt.sh```

## Setup
1. **Backup Existing Configuration:** ```cp ~/.bashrc ~/.bashrc.backup```

2. **Download the prompt to your local machine:** ```git clone https://github.com/ZilongJas/Custom-Prompt-in-Bash.git```

3. **Apply the Custom Prompt:** ```echo "source ~/Custom-Prompt-in-Bash/custom_prompt.sh" >> ~/.bashrc```
(Make sure it is under the same path as you cloned it in)

4. **Apply the changes immediately:** ```source ~/.bashrc``` (or close your terminal and start a new one)

## Revert changes
1. ```mv ~/.bashrc.backup ~/.bashrc```

