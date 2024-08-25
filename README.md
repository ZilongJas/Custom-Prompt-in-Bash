# Custom Bash Prompt
---------------------
## Overview
This project customizes your Bash prompt to display time in AM/PM format and removes long prompts that you may have, with a clean design.

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

## Setup
1. **Backup Existing Configuration:** ```cp ~/.bashrc ~/.bashrc.backup```

2. **Download the prompt to your local machine:** ```git clone https://github.com/ZilongJas/Custom-Prompt-in-Bash.git```

3. **Apply the Custom Prompt:** ```source ~/custom_bash_prompt/custom_prompt.sh >> ~/.bashrc```
(Make sure it is under the same path as you cloned it in)

4. **Apply the changes immediately:** ```source ~/.bashrc``` (or close your terminal and start a new one)

## Revert changes
1. ```mv ~/.bashrc.backup ~/.bashrc```

