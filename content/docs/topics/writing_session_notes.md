# Writing Session notes

[![hackmd-github-sync-badge](https://hackmd.io/gz7dYhjUQZy0EV8xrJHalg/badge)](https://hackmd.io/gz7dYhjUQZy0EV8xrJHalg)


## The goal of write-up (blog post and then manuscript)
- We want to create a 'guide'
- Here's what you can do with github, take them or leave them. (And the drawbacks too!)
- Make sure we are highlighting limitations by our background in ecoevo (e.g., our reliance on R).  These are the hurdles specifically in EcoEvo. And make specific recs. (e.g., PI can make GitHub issues on their student's code). 
- Journal considerations: Methods in EcoEvo
- And GitHub isn't the 'end all be all'
- Take the elements of GitHub that work for you, but this can be done on many platforms
- can accompany a data science course
- How's github fit into your workflow?
- How github would be helpful (or not) for different user profiles 
- Present some obstacles and how to overcome.
- User group, visuals, (e.g., writing manuscript on github not for everyone)
- Example repos for different use cases (to be used as templates when forked)
- Focusing on big or small github projects? Maybe this is part of the user group example? Introducing the github ecosystem with may different elements!
- How do we differentiate from other github papers (e.g., Jenny Bryans). "Here's how you can use github for collab". Don't need to get into details of git. Here is how you can 
- Potential data sources https://peter.solymos.org/, https://steffilazerte.ca  
**Blog ideas**
- Methods in EcoEvo has a blog: https://methodsblog.com/


**Journal ideas**
- _Journal of Statistics and Data Science Education_ Reproducibility Special issue: https://nhorton.people.amherst.edu/call_reproducibility.pdf 
From their call for papers: Topics in the special issue that align with our proposal: Incorporating source code (version) control systems, Developing and implementing documentation and code standards, Supporting collaboration
**September 15, 2021 (deadline for submissions)**
- _Methods in EcoEvo_ publishes lots of 'guides' https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.13652
- elife (Prof. Eisen gave plenary and is editor of this journal) https://elifesciences.org/ They require preprints published before review
- Rio: https://riojournal.com/
- TREE: https://www.cell.com/trends/ecology-evolution/aims (requires =< 3 authors)
- Ecological Informatics: https://www.sciencedirect.com/journal/ecological-informatics/about/aims-and-scope

### GitHub and R in EcoEvo
In EcoEvo Github use is predicated on an understanding in R. This close connection has some benefits, but other programming languages are frequently used by researchers (e.g. Python, Julia). Lots of ways to use GitHub that are independent from R. We have in this hackathon a definite focus on R tools for interacting with GitHub, but sometimes the issues we present at 'Github' issues might be more about the ways that we interact with Github (i.e. through R vs. bash shell)

### Idea for a figure/algorithm
Flow chart that can guide us in what we need to learn to get the most out of gitHub in this moment
- Focus on learning how to submit issues;
- 4 different people that might want to use GitHub: first time learner, PI, individual researcher who is going to do this all, person who wants to advance their workflow using github (i.e. learn a bunch of new things!)
- Make a table/figure: Here are the alternative tools for collab / version control, Check marks for what github does vs. google docs vs. zenodo vs. edit-save-attach
- Table of "pain points" and solutions or strategies for overcoming these pain points.
- Github as an ecosystem figure?

^This reminds me of the RStudio "learner personas" which might serve as a model: https://rstudio-education.github.io/learner-personas/


## A few of pain points to using GitHub
### 1. The GitHub learning curve (technical skills)
_Learning to use Github requires time, but the payoff is worth it._
- Time vs. effort examples or analyses to demonstrate the payoff can help drive the point home to convince people to learn these tools
- New job? Interdisciplinary collab? May have to be prepared for working with version control software.
- What's the minimum github knowledge that you need to know to start using github
- And, if you make a mistake, you can always undo it!

### 2. Reluctance to do science openly (cultural reluctance)
_Fear of scooping or sharing data also feeds into reluctance due to worries of intellectual property._
- suggestion: to keep the repository private until publication, then make it public
- suggestion: make use of github licenses to indicate that material on github is citable!
- And journals (e.g., AGU-related journals) require data/code sharing and they don't consider it 'shared' unless there's a working DOI For it.
- But publishing data/code on github is not a 'one shot' aka eminem approach (thanks for this, Emma)
- Addressing ways to share links to private code for reviewers or collaborators without making everything public would be helpful for this


### 3. publishing code and data for peer review
- GitHub definitely helps with this process, but it's still a pain point.  How can we share private link for peer review, that has a citable DOI, but will DOI update (Zenodo does a great job at this)

---

### How to decide what to archive/host in GitHub
Need to make decisision for what to host on GitHub, and when to post publicly vs. privately

### Top-down vs. bottom-up resistance
_Is reluctance to use git related to how entrenched you are in what you do (e.g. senior researchers)?_
- being introduced to git in undergrad or as junior researchers seems to be easier or at least more common
- A lot of what senior researchers would use git(hub) to do (issues, pull requests, code review etc.) can actually be done via the browser without having to learn git commands. Kind of a minimal effort way to participate in open science.
- Convincing people to spend time learning new skills when their workflow is already working for them is hard, especially in a publish or perish type of culture that does not allow for "unproductive" (heavy quotation marks here) time;
- Issues with researcher/professor and student reluctance have been pointed out in other fields (e.g. in education, with respect to the application of evidence-based methods in teaching and learning). We should also follow this with arguments or proposed solutions to these issues; 

### Idea for a 'github survey'
- Can we do a search for field (i.e. animal behavior vs. ecology research)
- Journals to go through and see who shares code
- Ratio btwn web of science articles and tag per field (proxy for research effort)

Other resources:
https://bioceed.uib.no/dropfolder/sites/bioSTATS-and-R/DataManagement/GitTutorial.html

In our slack channel, Eric mentioned a new use case to include in manuscript: using github issues to organize and respond to reviewer comments on a manuscript. See example [here](https://github.com/BrunaLab/HeliconiaDemography/issues?q=is%3Aissue+label%3A%22reviewer+comment%22+)

https://colauttilab.github.io/Readings/BES-Reproducible-Code.pdf
