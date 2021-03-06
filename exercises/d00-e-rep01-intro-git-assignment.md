Reproducibility: Git and Our Curriculum
================
Zachary del Rosario
2020-06-24

*Purpose*: Git is a powerful tool to manage our work, but it can be
confusing at first. Here we will read some introductory materials about
Git, and use the software to download and set up the exercises for the
course.

*Reading*: [Automated Version
Control](https://swcarpentry.github.io/git-novice/01-basics/index.html),
complete the steps in [Setting Up
Git](https://swcarpentry.github.io/git-novice/02-setup/index.html)

*Note*: For the steps in the reading, I recommend using the Terminal in
RStudio. This should help ensure you have access to Git.

*Topics*: version control, git setup, working with our exercises, ssh
keys

*Note*: If you’re reading this file in RStudio, you can Shift + Click
(CMD + Click) to follow a link.

# Windows-specific Instructions

<!-- -------------------------------------------------- -->

If you are on a Windows computer, you will need to complete some
additional steps. Please follow [these
instructions](https://github.com/zdelrosario/data-science-curriculum/blob/master/exercises/e-windows-gitbash.md)
before continuing.

# Set Up SSH Key

<!-- -------------------------------------------------- -->

Before you can “clone” (download) the repository of exercises, you’ll
need to set up `ssh` with GitHub. Follow these instructions to [add an
SSH
key](https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)
to your account. This will allow you to work with GitHub without typing
in your password.

*Note*: This can be a bit confusing if you’ve never worked with SSH
before; *please do ask questions* if you are stuck\!

# Downloading Our Exercises

<!-- -------------------------------------------------- -->

Using RStudio, we will download a local copy of your assigned repo (I
will send you a link to this repository):

  - Open your assigned repo, and click the “Clone” button. This should
    be of the form `username-2020-03`; for instance, mine would be
    `zdelrosario-2020-03`. Make sure you have “SSH” selected, and click
    the “clipboard” button to copy the `git@github:...` url.

  - Open the `Terminal` tab

![Terminal](./images/rep01-terminal.png)

  - Use the change directory (`cd`) command to change to where you want
    to copy `username-2020-03`, and use the `git clone` command to copy
    the repository.

  - *Note*: I recommend creating a `Git` directory on your computer in
    an easy-to-find location (say Home or Documents), and that you put
    `username-2020-03` there. (*Note*: My repo name is a little
    different in the image below; the important part is that it matches
    your `username` and ends in `git`.)

![Clone](./images/rep01-clone-cli.png)

  - Great job\! Now you have all the assignment exercises for the
    course\!

*Aside*: Note that *Git* and *GitHub* are two different things\! *Git*
is a version control tool, while *GitHub* is a service that uses Git
where you can host repositories. For instance,
[GitLab](https://about.gitlab.com/) is another service where you can
host Git repositories.

<!-- include-exit-ticket -->

# Exit Ticket

<!-- -------------------------------------------------- -->

Once you have completed this exercise, make sure to fill out the **exit
ticket survey**, [linked
here](https://docs.google.com/forms/d/e/1FAIpQLSeuq2LFIwWcm05e8-JU84A3irdEL7JkXhMq5Xtoalib36LFHw/viewform?usp=pp_url&entry.693978880=e-rep01-intro-git-assignment.Rmd).
