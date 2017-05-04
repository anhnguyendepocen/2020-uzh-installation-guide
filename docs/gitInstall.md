# Installing Git and Setting Up Accounts

Git is a Version Control System (VCS) that has gained a lot of traction among the programming community.
We will want to use version control to keep track of the files we write, and the changes we make to them.

During the course we will show you how to host some of your work on GitHub and the Economics Department's internal GitLab server.
You will need to setup accounts for each of these:

* Please [register](https://github.com/join) for a [GitHub](https://github.com/) account
* Sign into the [Economics Department's GitLab server](https://econgit.uzh.ch/). Use your UZH shortname and your web-access password (think OLAT). You will need to access "Econ Git" while on-site at UZH or whilst using a UZH VPN if you are off-site.


## Installation Guide

### Windows Users

 Get the latest versions of:

 * [msysgit](http://msysgit.github.io), and
 * [TortoiseGit](http://code.google.com/p/tortoisegit/wiki/Download)

 After installing these programs use Windows Explorer to go to a folder that contains some documents (any folder) and right click on it.
 You should see some additional items - "GitBash" and "TortoiseGit" appear in the context menu upon right-clicking.



###  Mac Users

On MacOS, download and install Git from [here](http://git-scm.com/download/mac).
Also install the command-line auto-completion script, as described [here](https://git-scm.com/book/en/v1/Git-Basics-Tips-and-Tricks#Auto-Completion).


### Linux Users

Follow the steps documented [here](https://git-scm.com/download/linux) to install on Linux from the terminal.


## Verifying your install

We will need to make Git accessible from the command line. Windows and Mac users will need to follow the steps on the page "Modifying Path Settings." Linux users will already have git accessible from the command line.

To verify your installation, type the following command in a terminal and press the return key:

       git

You should get a bunch of output that begins with:

        usage: git [--version] [--help] [-C <path>] [-c name=value]
       [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
       [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
       [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
       <command> [<args>]