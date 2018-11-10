# The R Inferno
Welcome to this repository. This is one exrcise of the [Workshop: "Developing skills in R"](https://www.su.se/deep/english/about-us/events/workshop-developing-skills-in-r-1.402004), [here](https://deepskillsr.github.io/) more info about the Workshop. In this exercise we will re-write [The R Inferno book](https://www.burns-stat.com/pages/Tutor/R_inferno.pdf) written by [Patrick Burns](https://www.burns-stat.com/) in RMarkdown.  
If you want to contribute to this new editions. follow the instructions:
- First of all you need to have access to this repository (if you don't already have it, ask to the teachers).
- Clone this repository, and create a new branch (name it your_name_br). 
- Chose a chapter of the book and re-write it in RMarkdown, The name should be Ch_X_your_name (Use the chuck for the R code, add also other image ...).
- Knit your RMarkdown file.
- Modify the _site.yml file, add two line at the end:
```
    - text: "Ch_X"
      href: Ch_X_your_name.html
```
- Add the files created  to the staging area. 
- Commit the changes and push it.
- Check how it look (maybe change something and re-upload the files).
- If you are happy of your work, go back to the master branch.
- pull the last version of the repository.
- merge your branch with the master.

Now, if you have done all of this, you are able to use Git, RMarkdown and create a Website.
