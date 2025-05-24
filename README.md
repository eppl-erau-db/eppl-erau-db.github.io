# EPPL WEBSITE


## Contributing to the Website

Active EPPL members are welcome to contribute to the lab website. Note that as soon as you push to the master branch repo, the website will build and publish automatically, thanks to GitHub Actions. You can find the submissions to the Google form for website submissions in Google Drive, specifically at the following location:  EPPL/7.website/Website Form (File responses)/Website Form (Responses). It's best to run the website locally before pushing. To do so, I would recommend using a Linux machine (or WSL) because it is a lot easier. Please see the following subsections for:
- Running Locally
- To-Do

## Running locally

1. Clone the repository and made updates as detailed above.
   
    If you are unaware, you can use the following commands to clone the repo, get into its directory, and edit using VS Code:
    ```bash
    git clone https://github.com/eppl-erau-db/eppl-erau-db.github.io.git'
    cd eppl-erau-db.github.io.git
    code .
    ```
1. Make sure you have ruby-dev, bundler, and nodejs installed
    
    On most Linux distributions and [Windows Subsystem Linux](https://learn.microsoft.com/en-us/windows/wsl/about), the command is:
    ```bash
    sudo apt install ruby-dev ruby-bundler nodejs
    ```
1. Run the following command to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.

    ```bash
    bundle install
    ```

1. Run the following command to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

    ```bash
    jekyll serve -l -H localhost
    ```
1. You can then click the link in the terminal to open the local website it just built.

Here are all the commands combined for your reference
```bash
git clone https://github.com/eppl-erau-db/eppl-erau-db.github.io
cd eppl-erau-db.github.io
sudo apt install ruby-dev ruby-bundler nodejs
bundle install
jekyll serve -l -H localhost
cd eppl-erau-db.github.io
sudo apt install code
code .
```

NoteL If you are running on Linux it may be necessary to install some additional dependencies prior to being able to run locally: `sudo apt install build-essential gcc make`

## Website To-Do

The following is a list of things that have to get done for website updating and development:

1. Take the project descriptions from the form responses and update them for each project. 
1. Ensure all the profile pictures are up to date.
1. Fix the color of the links in project pages to the same as the about page. 
1. Add a post about something interesting this semester. 
1. Add a post about a new technology.
1. Add people's homepages.
---
<div align="center">
    
![pages-build-deployment](https://github.com/academicpages/academicpages.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)
[![GitHub contributors](https://img.shields.io/github/contributors/academicpages/academicpages.github.io.svg)](https://github.com/academicpages/academicpages.github.io/graphs/contributors)
[![GitHub release](https://img.shields.io/github/v/release/academicpages/academicpages.github.io)](https://github.com/academicpages/academicpages.github.io/releases/latest)
[![GitHub license](https://img.shields.io/github/license/academicpages/academicpages.github.io?color=blue)](https://github.com/academicpages/academicpages.github.io/blob/master/LICENSE)

[![GitHub stars](https://img.shields.io/github/stars/academicpages/academicpages.github.io)](https://github.com/academicpages/academicpages.github.io)
[![GitHub forks](https://img.shields.io/github/forks/academicpages/academicpages.github.io)](https://github.com/academicpages/academicpages.github.io/fork)
</div>
