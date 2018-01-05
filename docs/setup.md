# Setup

This page contains brief instructions on how to install the core applications that we will use in this course. During the course, these tools will be introduced slowly, and you will not be expected to become proficient in all or even most of these tools.

You can install them all at once, or gradually over the course. Feel free to play around with any of these tools

1. [GitHub Repository Manager](#1-github-repository-manager)
2. [Atom Text Editor](#2-atom-text-editor)
3. [Slack Team Messenger](#3-slack-team-messenger)
4. [Tableau Visualization Platform](#4-tableau-visualization-platform)
5. [Google OpenRefine Data Scrubber](#5-google-openrefine-data-scrubber)

---

## IMPORTANT NOTE

Some of the following passages refer to your 'Terminal', to access it, follow the directions for your operating system...

**(Windows)**

Go to your 'Start Menu', then the' Windows PowerShell' folder, and click Windows PowerShell.

*FOR ADMIN PRIVILEGES:* If you need admin privileges, instead of left-clicking, **RIGHT-CLICK** the 'Windows PowerShell' application and Choose 'Launch as Administrator' (or something like that). Enter your password when prompted.

**(OSX)**

Go to your Applications folder, then the Utilities folder. Then, click the 'Terminal' application.

*FOR ADMIN PRIVILEGES:* <br> If you need admin privileges, start your command with 'sudo'. For example, `fakecommand --fake-option "some/fake/path"` would become `sudo fakecommand --fake-option "some/fake/path"`. You will be asked to enter your password, and then the command will run.

To learn the basics of command line, try the [free course at Codecademy](https://www.codecademy.com/)!

---

## 1 GitHub Repository Manager

1. [Sign up for a GitHub Account](https://github.com)
2. [Install GitHub Desktop](https://desktop.github.com/)

---

## 2 Atom Text Editor

1. [Install Atom](https://atom.io/)
2. Configure Atom
    1. Either [follow this configuration guide](http://www.marinamele.com/install-and-configure-atom-editor-for-python)
    2. Or follow the TLDR summary below...


3. **(OSX ONLY)** Then restart Atom and click 'Hack on the Init Script' at the Welcome Guide (or go to the File menu and choose 'init script'), and paste the following on the last line...
```coffee

process.env.PATH = ['/usr/local/bin/', process.env.PATH].join(':')
```

4. Then restart Atom, open the Preferences windows. Click the 'Editor' tab. Scroll down and Tab Length to 4 spaces and click Automatic PEP8 Validation

---

## 3 Slack Team Messenger

1. [Download and install](https://slack.com/downloads/) a copy of Slack messenger (or use their web interface)
2. Register an account at our course's Slack channel, [hacking-history.slack.com](https://hacking-history.slack.com/).

* For those interested, you can also register an account with the main Digital Humanities slack channel, [hacking-history.slack.com](https://digitalhumanities.slack.com/)

---

## 4 Tableau Visualization Platform

1. [Sign up for a student account](https://www.tableau.com/academic) (assuming you are a student), and then follow the instructions to install Tableau Desktop.
2. You will be able to use a 14-day trial, during which they will contact you with details for free access for a *full year.*

---

## 5 Google OpenRefine Data Scrubber

1. Head to [OpenRefine](http://openrefine.org/) and download the application.
2. You have to manually move the application to the location where you want to install it.

---
