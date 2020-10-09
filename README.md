# Qualtrics SFDC Hacktoberfest

### Purpose
Git can be very HARD to learn. This repository provides an easy way to begin understanding Git, specifically within the context of contributing to a simple website. The tutorials should be structured in a way that minimize the need for previous web development experience and should be fairly understandable for beginners.

### Prerequisites
- [x] Visual Studio Code installed (https://code.visualstudio.com/download)
- [x] Git installed (https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

### Terminal Basics
For Windows users, (Guy and Scott...) you'll need to find some tutorials about using things like Git bash or Git for Windows since these commands don't natively work inside of Command Prompt or Powershell. Or you could get adventurous with Windows Subsystem for Linux (WSL). ***Or*** you could just dust off your company-issued laptop..?

For everyone else, open up the Terminal application.

By default, when opening up a new terminal window, you will be placed in your computer's Home directory. This is denoted by the ~ (tilde) on the same line as your blinking cursor.

By running the  command ```ls```, you can *list* the folders and files that are in the current directory (folder). This is used a lot, just remember that ```ls``` is just shorthand for *list*. If you run that, you should see a lot of folders, including Desktop, Documents, Downloads, etc.

We are going to put the Git project inside of our Documents folder, so to jump into that folder, you need use the ```cd``` command, which is short for *change directory*. So, to move into your Documents folder, you'll run

```
cd Documents
```

If you run the ```ls``` command again, you should see the contents of your Documents folder, which would be the same as what's in that folder if you were accessing it via Finder

To *clone* this git project onto you computer, you'll use the ```git clone``` command. This command needs to be provided with a URL so that it knows what code repository it's pulling from. The green **Code** button on the top of this page should give you the link to use. The following command has that link included:

```
git clone https://github.com/qualtricssfdc/hacktoberfest2020.git
```

After it finishes cloning the repo, you can list the files in the directory again to verify that the **hacktoberfest2020** directory has been created.

### Exploring the Project
Open Visual Studio Code. There should be an option to open a folder. Navigate to the **hacktoberfest2020** that we put inside your Documents folder and click Open.

You should see the project tree on the left hand side. The index.html file is the main file that is displayed when you visit https://qualtricssfdc.github.io/hacktoberfest2020/. There is also a README.md file in there as well, that is actually **THIS** page that you are reading right now. So meta... Once contributions have already begun being submitted, there will probably be other folders and such inside of the project as well. Understanding where files are in relation to eachother is important, especially if you want to make links between pages and such. Just take a minute to get familiar with project structure.

## Tutorials
*Work in progress...*
