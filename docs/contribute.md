# Contributing and Collaboration on GitLab

!!! note "Objectives📍"

    - fork
    - merge requests
    - gitlab for project management


## Forking and merge requests

Sometimes you want to contribute to a project on gitlab but you don't have write access. This is usually the case if you are not added as a member to the project. Even if the project is public, you cannot contribute to it without opening a `merge request`. The same is true for your own repos: you can make them public, people can `clone` them but they cannot change something on the project without asking you first through a `merge request`. 

**Like mentioned before, even if you are a member of the project and work together with your collaborators, it is always a good idea to work with `merge requests` to foster communication and avoid a ton of conflicts.** We highly advise you to ALWAYS work with branches and merge requests!

To open a `merge request` on a repo where you don't have write access to, you first need to `fork` this project. You'll find the `fork` button on the upper right in the respective gitlab repo. Forking a project means copying a remote repository from another user as a remote repository under your username. 


!!! question "Task 14"

    - Go to [this repo](https://gitlab.com/julia-pfarr/choice_rtt) on GitLab
    - fork the project
    - clone your forked project
    - make a change and push it back to your forked project 
    - open a `merge request` on the original project:
        - go to the [original repo](https://gitlab.com/julia-pfarr/choice_rtt)
        - click on `merge requests` on the left sidebar
        - select your repo and branch as `source branch` and as `target branch` select the original repo and branch 
    - on the original repo you should see a new merge request. Now the owner of the original repo can review it and decide to approve and merge it, or not. 

    This is how your collaborative workflow on GitLab should look like, even if every collaborator has access. 

![merge request](_media/merge_request.png)    


## GitLab for project managing

GitLab is actually more than just a code development platform. It has so many additional functions. Under the section `Plan` you can manage tasks (`issues` and `issue board`), keep track of important `milestones` and assign `issues` to `milestones`. You can write a comprehensive `wiki` to store important information about the project (e.g., links to other important resources such as data repo, document meeting minutes etc.). 

You can also do automated testing of your code (`continuous integration`/`CI`), build packages or container for apps and `deploy` them to e.g., [docker](https://www.docker.com/). 

It allows you to do a bunch of other stuff which is related to project analytics which is mostly used in industry and exceeds the goals of a science project in academia.

## THE END

## optional/reading/further materials

- YouTube is full of Git/GitLab/GitHub videos for all kinds of levels and features!!! For example: Brainhack [Git introduction](https://youtu.be/fBgxmpk9C4I?si=im33MV2V0PV8uM0k) or [GitHub CI](https://youtu.be/VibDC49ZAJE?si=587WHWe1nZQzHIay)
- Git cheat sheet by [gitlab](https://about.gitlab.com/images/press/git-cheat-sheet.pdf) or [github](https://education.github.com/git-cheat-sheet-education.pdf)
- [Atlassian tutorials](https://www.atlassian.com/git/tutorials) and [cheat sheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)
- Troubleshooting: [Oh shit git](https://ohshitgit.com/) or [Dangit git](https://dangitgit.com/) (are the same, but the latter is without swearing)
- [Git branching](https://learngitbranching.js.org/?locale=de_DE)
- [Git GUIs](https://git-scm.com/downloads/guis) 
- [Advanced Git commands](https://www.atlassian.com/git/tutorials/advanced-overview)
- [NOWA workshops](https://sfbs.pages.uni-marburg.de/sfb135/nowa/nowa.site/tutorial/)
- really, just type anything you want to know about Git in YouTube and you'll find a tutorial for it. 