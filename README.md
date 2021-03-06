<!-- Used for back to top link -->
<div id="top"></div>

<!-- Insert badges here. See https://shields.io/ -->
![GitHub](https://img.shields.io/github/v/tag/Fonze81/VSCode-recommended-extensions?style=for-the-badge&logo=github)
![GitHub](https://img.shields.io/github/release-date/Fonze81/VSCode-recommended-extensions?style=for-the-badge&logo=github)
![GitHub](https://img.shields.io/github/last-commit/Fonze81/VSCode-recommended-extensions?style=for-the-badge&logo=github)
![GitHub](https://img.shields.io/github/commit-activity/m/Fonze81/VSCode-recommended-extensions?style=for-the-badge&logo=github)
![GitHub](https://img.shields.io/github/repo-size/Fonze81/VSCode-recommended-extensions?style=for-the-badge&logo=github)
![GitHub](https://img.shields.io/github/license/Fonze81/VSCode-recommended-extensions?style=for-the-badge)

![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

# VSCode Recommended Extensions

<details>
    <summary>Table of Contents</summary>
    <ol>
        <li><a href="#about-the-project"> 📝 About The Project</a></li>
        <li><a href="#project-status"> 🚧 Project Status</a></li>
        <li><a href="#technologies"> 🔰 Technologies</a></li>
        <li><a href="#prerequisites"> 💻 Prerequisites</a></li>
        <li><a href="#installation"> 🚀 Installation</a></li>
        <li><a href="#step-by-step"> 🚶 Step by step</a></li>
        <ul>
            <li><a href="#clone-remote-repository">Clone remote repository</a></li>
            <li><a href="#create-workspace">Create a Workspace</a></li>
            <li><a href="#vscode extensions">Installation of recommended VSCode Extensions</a></li>
        </ul>
        <li><a href="#license"> 📝 License</a></li>
    </ol>
</details>

<!-- Used for Table of Contents link -->
<div id="about-the-project"></div>

## 📝 About The Project

Repository template with a VSCode Workspace and recommended extension list

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>

<!-- Used for Table of Contents link -->
<div id="project-status"></div>

## 🚧 Project Status

**v0.1.0**  Under construction....

**v0.0.0**  Clone repository [GIT repository template v0.1.0](https://github.com/Fonze81/GIT-repository-template/releases/tag/0.1.0)

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>

<!-- Used for Table of Contents link -->
<div id="technologies"></div>

## 🔰 Technologies

The following tools were used in building the project.

<!-- For more badges see: https://github.com/Ileriayo/markdown-badges -->
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>

<!-- Used for Table of Contents link -->
<div id="prerequisites"></div>

## 💻 Prerequisites

Before starting, you will need to have the following tools installed on your machine:

![Git](https://img.shields.io/static/v1?label=Git&message=^v2.33.1.windows.1&color=blue&style=flat-square&logo=git)

![GitHub](https://img.shields.io/static/v1?label=GitHub%20Desktop&message=^v2.9.14%20x64&color=blue&style=flat-square&logo=github)

![Visual Studio Code](https://img.shields.io/static/v1?label=Visual%20Studio%20Code&message=^v1.66.2%20x64&color=blue&style=flat-square&logo=visual-studio-code)

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>

<!-- Used for Table of Contents link -->
<div id="installation"></div>

## 🚀 Installation

Clone the Github remote repository by running the command

```bash
git clone https://github.com/Fonze81/VSCode-recommended-extensions
```

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>

<!-- Used for Table of Contents link -->
<div id="step-by-step"></div>

## 🚶 Step by step

<!-- Used for Table of Contents link -->
<div id="clone-remote-repository"></div>

### Clone remote repository

<details>

Open a terminal window and run the command `git --version` to verify that it is installed.
If an error is returned, there are a few ways to install Git on Windows. The most official build is available for download on the Git website. Just go to https://git-scm.com/download/win and the download will start automatically.

> ![Git](./images/git-icon_14px.svg) [**Git**](https://git-scm.com/) is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

To update Git to the latest version run the command

```bash
git update-git-for-windows
```

Git comes with a tool called git config that lets you get and set configuration variables that control all aspects of how Git looks and operates. See [First-Time Git Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

```bash
git config --global user.name '<your-username>'
git config --global user.email <your-email>
```

Go to that project's directory. In the terminal window run the command:

```bash
cd C:/Users/user/VSCode-recommended-extensions
```

Create a new subdirectory named .git that contains all of your necessary repository files \- a Git repository skeleton. Run the command:

```bash
git init
git status
```

Downloaded the source code from the [GIT repository template v0.1.0](https://github.com/Fonze81/GIT-repository-template/releases/tag/0.1.0). Unzipped the zip file and copied the contents to the local repository.

Start tracking these files and do a initial commit.

```bash
git add .
git commit -m 'Initial commit'
git branch -M main
```

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>

</details>

<!-- Used for Table of Contents link -->
<div id="create-remote-repository"></div>

### Create a remote repository

<details>

Go to [Github](https://github.com/) and create a new remote repository.
Download [GitHub Desktop](https://central.github.com/deployments/desktop/desktop/latest/win32) and install it

Open the Github Desktop software, log in, select your local repository (File > Add local repository...) and then upload it to the remote repository (Repository > Push).

> ⚠️ Cannot upload directly from Git due to token authentication requirement. See [token authentication requirements for git operations](https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/)

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>

</details>

<!-- Used for Table of Contents link -->
<div id="create-workspace"></div>

### Create a Workspace

<details>

Check that [VSCode]( https://code.visualstudio.com/) is installed using the command `code --version`. If it's not installed, [download](https://code.visualstudio.com/docs/?dv=win) and install

> ![Visual Studio Code](./images/vscode-icon_14px.svg) [**Visual Studio Code**](https://code.visualstudio.com/) is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages (such as C++, C#, Java, Python, PHP, Go) and runtimes (such as .NET and Unity)

In [VSCode]( https://code.visualstudio.com/) open the folder of this repository, and save the Workspace

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>

</details>

<!-- Used for Table of Contents link -->
<div id="vscode extensions"></div>

### Installation of recommended VSCode Extensions

<details>

VSCode has [extensions](https://marketplace.visualstudio.com/VSCode) that enable additional languages, themes, debuggers, commands, and more. VS Code's growing community shares their secret sauce to improve your workflow. In this workspace, the following extensions were added (not mandatory):

<!-- Table -->
Extension | Decription
--: | :--
![Dracula Official](https://img.shields.io/visual-studio-marketplace/v/dracula-theme.theme-dracula?label=Dracula%20Official) | A dark theme for many editors, shells, and more
![Material Icon Theme](https://img.shields.io/visual-studio-marketplace/v/PKief.material-icon-theme?label=Material%20Icon%20Theme) | Get the Material Design icons into your VS Code
![Git Graph](https://img.shields.io/visual-studio-marketplace/v/mhutchie.git-graph?label=Git%20Graph) | View a Git Graph of your repository, and perform Git actions from the graph

![markdownlint](https://img.shields.io/visual-studio-marketplace/v/DavidAnson.vscode-markdownlint?label=markdownlint) | Markdown linting and style checking for Visual Studio Code
![Badges](https://img.shields.io/visual-studio-marketplace/v/idleberg.badges?label=Badges) | Snippets to quickly insert Shield.io badges into HTML, Markdown, reStructuredText or Textile documents


https://img.shields.io/visual-studio-marketplace/v/aaron-bond.better-comments?label=Better%20Comments
Better Comments
https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments
Improve your code commenting by annotating with alert, informational, TODOs, and more!

https://img.shields.io/visual-studio-marketplace/v/alefragnani.Bookmarks?label=Bookmarks
Bookmarks
https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks
Mark lines and jump to them

https://img.shields.io/visual-studio-marketplace/v/GitHub.vscode-pull-request-github?label=GitHub
GitHub Pull Requests and Issues
https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github
Pull Request and Issue Provider for GitHub

https://img.shields.io/visual-studio-marketplace/v/yzane.markdown-pdf?label=Markdown%20PDF
Markdown PDF
https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf
Convert Markdown to PDF

https://img.shields.io/visual-studio-marketplace/v/esbenp.prettier-vscode?label=Prettier%20-%20Code%20formatter
Prettier - Code formatter
https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
Code formatter using prettier

<!-- Link to top -->
<!-- <p align="right"><a href="#top">back to top</a></p> -->

</details>

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>

<!-- Used for Table of Contents link -->
<div id="license"></div>

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>
