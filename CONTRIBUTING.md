# How to contribute

You want to contribute?  
First off, thanks for your interest in contributing
to one of PILZ's open source projects. :+1:
  
With this document we try to provide you with a set of guidelines to 
successfully contribute to our projects.  
However, if you think that something is missing or if you think that something 
is incorrectly or badly explained, feel free to open a pull request to improve
this document.

## Code of Conduct
We expect everyone who wants to participate in our projects to uphold our
[Code of Conduct](CODE_OF_CONDUCT.md)!


## Reporting a Bug
Like many other projects on GitHub, we track bugs as 
[GitHub issues](https://guides.github.com/features/issues/).
If you want to report a bug, please open an issue on the correct repository and
use our [issue template](ISSUE_TEMPLATE.md) to provide all necessary 
information.  
The following sections shortly describe the different information which should
be included in the issue description. 

**Please note:** The information requested, are important for us to 
understand and reproduce the issue and, consequently, to help you.

### What package and/or repository versions are you using?
At first, you should tell us the versions of all PILZ-ROS packages you 
are using. You can check the version of the installed PILZ-ROS packages with the 
following terminal commands:  
```
dpkg -l ros-melodic-pilz*
dpkg -l ros-melodic-prbt*
```
  
**Note:**  
If you are using `kinetic`, please substitute `melodic` with `kinetic`.
  
If you are building from source, tell us for each PILZ-ROS
repository you are building, which version/commit id you are using.  

### Steps to reproduce bug
The step by step description, enables us to easily reproduce the bug with 
our hardware which, in turn, is key in fixing the bug.
Try to be as specific as possible. If it possible, try to reduce the scenario 
which produces the bug, to the absolute minimum. 
In other words, try to minimize the number of bugs,
needed to reproduce the bug.

### Expected behavior
Tell us what you would expect to happen. This information allows us to verify,
if it is an actual bug or maybe just a misunderstand of some functionality.
Furthermore, this information allow us, to ensure that the fixed system
behaves as expected by the user.

### Observed behavior
Tell us what is happening on your system in case of the bug. 
Sometimes, it is not so easy to
understand what exactly the error is. The observed behavior allows, us to
easier understand what went wrong and where you think the error lies.

### Logfiles
To gain a complete picture of the system as a whole, we need a lot of 
information. You can provide us with the information needed, by copying the
logging output from the terminal on which your ROS system runs into the 
issue description.  
  
**Please note:** Do not forget to fence the logging output in the issue
description with three backticks at the beginning *and* the end of the 
logging output, to ensure that the logging output format remains intact.

### Reference to test
If possible you should provide us with a test, which allows us 
to reproduce the bug and check if the bug is fixed.

## Adding features/ fixing things
TODO

  
  
  
To all people contributing/participating:  
Thanks! :heart: :muscle:  
  
Your PILZ ROS Team


