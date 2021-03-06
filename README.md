[![Build Status](https://dev.azure.com/stuebersystems/Websites/_apis/build/status/docs/doc.ezcastpro.en?branchName=main)](https://dev.azure.com/stuebersystems/Websites/_build/latest?definitionId=133&branchName=main) ![Deployment Status](https://vsrm.dev.azure.com/stuebersystems/_apis/public/Release/badge/2cc87afa-9a3b-472b-8a3c-3eca48b22dd6/31/35)

# EZCast Pro Documentation

This is the English documentation for [EZCast Pro](https://doc.ezcastpro.eu). The documentation is Open Source and we have implemented it using [MkDocs](https://www.mkdocs.org) and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material). 

## Install MkDocs for Windows

1. Install [Python](https://www.python.org). Go to the [Python downloads](https://www.python.org/downloads/) page and download the latest version for Windows. 

2. Launch the installer and follow the on-screen instructions.

3. Run the command prompt as Administrator.

4. Enter the command `python --version` and `pip --version` to check the Python installation. In both cases a version number should appear as an output in the command prompt.

5. Enter the command `pip install mkdocs mkdocs-material` to install the *MkDocs* Python package and the *Material for MkDocs* theme.

6. Final test: Enter the command `mkdocs --version`. A version nummer in the command prompt will let you know if everything has been installed correctly.

## Clone Repository

This repository is a Git repository. To clone the repository to a local commputer you will need a Git client. Either install [Git for Windows](https://gitforwindows.org/) and use the command prompt or install one of the many GUIs. We recommend [GitHub Desktop](https://desktop.github.com) or [SourceTree](https://www.sourcetreeapp.com).

1. Create a local directory for the documentation e.g. `c:\docs\ezcastpro`.

2. Open the command prompt and change to directory `c:\docs\ezcastpro`.

3. Enter the command `git clone https://github.com/stuebersystems/doc.ezcastpro.en.git` to clone the repository.

## Download Repository as Zip Archive

If you don't want to use Git you can even download the repository as a Zip Archive:

1. Open the URL `https://github.com/stuebersystems/doc.ezcastpro.en` in your web browser

2. Click on the `Clone or download` button then select `Download ZIP`.

3. Extract the Zip Archive to a local folder, e.g. `c:\docs\ezcastpro`.

##  Using MkDocs

You have installed Python and MkDocs, cloned the repository or downloaded it as a Zip Archive. Now you can generate the documentation locally on your computer:

1. Start the command prompt and change to the directory `c:\docs\ezcastpro`.

2. Enter the command `mkdocs build`. The documentation will be regenerated.

3. To display the result, enter the command `mkdocs serve` and open the URL `http://127.0.0.1:8000` in your Web browser.

The table of contents can be found in the `mkdocs.yml` file and the individual chapters are in the `docs` subdirectory. 

## Can I help?

Yes, that would be much appreciated. The best way to help is to post a response via the Issue Tracker and/or submit corrections via a Pull Request.

## Code of Conduct

The [ST??BER SYSTEMS Code of Conduct](https://www.stueber.co.uk/code-of-conduct.php) was adopted in this project.
