<p align = "center" draggable=”false” ><img src="https://user-images.githubusercontent.com/37101144/161836199-fdb0219d-0361-4988-bf26-48b0fad160a3.png" 
     width="200px"
     height="auto"/>
</p>



# <h1 align="center" id="heading">:wave: Welcome to MLE Cohort 10 (October 2022)!</h1>

Welcome to MLE! :tada: Follow these steps to get your development environment teed up and aligned to the rest of the class.  This will ensure that we can hit the ground running this Tuesday! :running:


## :rocket: Let's Get Started! 

<details>
  <summary>Windows</summary>


* Install [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install) using Powershell

```powershell
wsl --install -d Ubuntu-20.04
```
* Install [Windows Terminal](https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701?activetab=pivot:overviewtab) (You can even make it your [default!](https://devblogs.microsoft.com/commandline/windows-terminal-as-your-default-command-line-experience/))
* Install [Ubuntu](https://www.microsoft.com/en-us/p/ubuntu/9pdxgncfsczv?activetab=pivot:overviewtab)

Give it a test drive! 

![WindowsTerminal](https://user-images.githubusercontent.com/72572922/160048214-37f08855-8b29-4c13-9d25-e0f69806f752.jpg)

Continue by installing the following tools using [Windows Terminal](https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701?activetab=pivot:overviewtab) to setup your environment. When prompted, make sure to add `conda` to `init`.

| Tool | Purpose | Command                                                                                           |
| :-------- | :-------- | :------------------------------------------------------------------------------------------------ |
| :snake: **Anaconda**  | Python & ML Toolkits | `wget https://repo.anaconda.com/archive/Anaconda3-2021.11-Linux-x86_64.sh` <br> `bash Anaconda3-2021.11-Linux-x86_64.sh` <br> `source ~/.bashrc` |
| :octocat: **Git**  | Version Control | `sudo apt update && sudo apt upgrade` <br> `sudo apt install git-all`   |
</details>

<details>
  <summary>Linux (Debian/Ubuntu)</summary><br>

Open terminal using <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>T</kbd>. Enter the following commands in terminal to setup your environment. When prompted, make sure to add `conda` to `init`.
| Tool | Purpose | Command                                                                                           |
| :-------- | :-------- | :------------------------------------------------------------------------------------------------ |
| :snake: **Anaconda**  | Python & ML Toolkits | `wget https://repo.anaconda.com/archive/Anaconda3-2021.11-Linux-x86_64.sh` <br> `bash Anaconda3-2021.11-Linux-x86_64.sh` <br> `source ~/.bashrc` |
| :octocat: **Git**  | Version Control | `sudo apt update && sudo apt upgrade` <br> `sudo apt install git-all`   |
</details>

<details>
  <summary>macOS Intel</summary><br>

Open terminal using <kbd>⌘</kbd>+<kbd>Space</kbd> and type `terminal`. Enter the following commands in terminal to setup your environment. When prompted, make sure to add `conda` to `init`.
| Tool | Purpose | Command                                                                                           |
| :-------- | :-------- | :------------------------------------------------------------------------------------------------ |
| :snake: **Anaconda**  | Python & ML Toolkits | `wget https://repo.anaconda.com/archive/Anaconda3-2021.11-MacOSX-x86_64.sh` <br> `bash Anaconda3-2021.11-MacOSX-x86_64.sh` <br> `source ~/.bashrc` |
| :octocat: **Git**  | Version Control | `sudo apt update && sudo apt upgrade` <br> `sudo apt install git-all`   |
</details>

<details>
  <summary>macOS ARM</summary><br>

To leverage the Mx chip from Python, you must use a special Python distribution called [Miniforge](https://github.com/conda-forge/miniforge). 
Open terminal using <kbd>⌘</kbd>+<kbd>Space</kbd> and type `terminal`. Enter the following commands in terminal to setup your environment.

Miniforge can be installed using Homebrew or from the source. We suggest trying Homebrew option first.

### Option 1 Homebrew

The next steps require [`homebrew`](https://brew.sh/) installed. To install Homebrew, follow the link and copy/paste the installation command into a terminal window. Once you have installed Homebrew, restart the terminal window. 

Install the `xcode-select` command-line utilities by typing the following command in the terminal

`xcode-select --install`

After running the commands from the table, when prompted, initiate your conda base environment by running `conda init`.
| Tool | Purpose | Command                                                                                           |
| :-------- | :-------- | :------------------------------------------------------------------------------------------------ |
| :snake: **Miniforge**  | Python & ML Toolkits | `brew install miniforge` |
| :octocat: **Git**  | Version Control | `sudo apt update && sudo apt upgrade` <br> `sudo apt install git-all`   |


### Option 2 From the Source

After running the commands from the table, when prompted, initiate your conda base environment by running `conda init`.
| Tool | Purpose | Command                                                                                           |
| :-------- | :-------- | :------------------------------------------------------------------------------------------------ |
| :snake: **Miniforge**  | Python & ML Toolkits | `chmod +x ~/Downloads/Miniforge3-MacOSX-arm64.sh` <br> `sh ~/Downloads/Miniforge3-MacOSX-arm64.sh` <br> `source ~/miniforge3/bin/activate` |
| :octocat: **Git**  | Version Control | `sudo apt update && sudo apt upgrade` <br> `sudo apt install git-all`   |
</details>

## <img src="https://octodex.github.com/images/original.png" width=40px/> Finally, make sure that GitHub is ready to roll

If you don't already have one, make an account on [Github](https://github.com/)

<details>
  <summary>Viewing the Repositories</summary><br>

Login and click on the top right user icon, then go to `repositories`. 

<p align="center">
  <img src="https://user-images.githubusercontent.com/37101144/162326947-3bfb4451-9854-41e8-9014-a02ed1322d66.png">
</p>
</details>


<details>
  <summary>Creating a New Repository</summary><br>

When viewing the respository page, click on `New` and proceed to create your repo.

<p align="center">
  <img src="https://user-images.githubusercontent.com/37101144/162327218-e1429ab2-2b24-4822-95bf-4411c2eb4a84.png">
</p>
<hr>

**Filling Respository Details**

Create the repository by inputting the following:
* `Repo name`
* `Repo description`
* Make repo `public`
* Add a `README`
* Add `.gitignore` (Python template)
* Add `license` (choose MIT)

Then click `Create Repository`.

<p align="center">
  <img src="https://user-images.githubusercontent.com/37101144/162327471-262a0931-c188-4976-8185-e70c4d108f71.png">
</p>

</details>

### That's it for now!  And so it begins.... :)
