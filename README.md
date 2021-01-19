# Graph Theory Project 2021

### Due: last commit on or before April 30<sup>th</sup>, 2021


These are the instructions for the assessment for Graph Theory in 2021.
This assessment contains a number of components but overall it is worth 100% of the marks for the module.
All aspects of the project will be covered during the semester.
You should complete and commit the different parts of the project following the timelines indicated by the lecturer during the semester.
Please also read the **[Using git for assessments](https://github.com/ianmcloughlin/using-git-for-assessments/raw/master/using-git-for-assessments.pdf)** document which applies to this project.
As always, you must also follow the code of student conduct and the policy on plagiarism.

To start, you must fork this repository in GitHub by clicking the Fork button on the top right or by [clicking here](https://github.com/theory-algos-project/fork).
You should take the URL of your version of the repository, which should look something like `https://github.com/your-username/theory-algos-project`, and immediately submit it using the form on the Moodle page.
You must also set your repository to **private** and add `ianmcloughlin` as a **collaborator**.
You should then clone that repository to your own machine and start working on the project as described below.
You should make regular, appropriate commits to your repository and push these to GitHub.
The last commit you make and push to GitHub before the deadline will form your submission.
There is no problem if you want to keep working on your repository after the deadline, but there is no guarantee that that work will be graded.

### What to do

In this project you must write a program in the Python programming language to search a text file using a regular expression.
Your program must take the name or path of the file as a command line argument and output the lines matching the regular expression.
The program must be coded from scratch.
You cannot use any external libraries other than what is included in Python, and you cannot use the `re` package included there.
Your program must run using Python 3.
You must also include tests which run upon `python script.py --test` being called, as will be described in lectures.

### Your README
You should overwrite this README with your own work.
The README must at least contain the following items.

- A **description** of your repository and its contents, pitched at a knowledgeable outsider.
- **Instructions** stating how to run and test your program.
- An **explanation** of Thompson's construction and why it is important.
- **Answers** to each of the following three questions, up to 500 words each:
    - Why can't we reverse the SHA512 algorithm to retrieve the original message from a hash digest?
    - Can you design an algorithm that, given enough time, will find input messages that give each of the possible 512 bit strings?
    - How difficult is it to find a hash digest beginning with at least twelve zeros?
    


### Marking scheme

The following marking scheme will be used to mark your submission out of 100%.
The examiner's overall impression of your submission may influence marks in each individual component.
It is important that your submission provides direct evidence of each of the items listed in each category.
For instance, your commit history should demonstrate and provide evidence that you had a pragmatic attitude to completing the assessment.
Likewise, your submission should have references in it to demonstrate that you considered the literature and the work of others.
  

| Weight | Category | Description |
|---|---|---|
|25% | Research | Evidence of research performed on topic; submission based on referenced literature, particularly academic literature; evidence of understanding of the documentation for any software or libraries used. |
|25% | Development | Environment can be set up as described; code works without tweaking and as described; code is efficient, clean, and clear; evidence of consideration of standards and conventions appropriate to code of this kind. |
|25% | Consistency | Evidence of planning and project management; pragmatic attitude to work as evidenced by well-considered commit history; commits are of a reasonable size; consideration of how commit history will be perceived by others. |
|25% | Documentation | Clear documentation of how to create an environment in which any code will run, how to prepare the code for running, how to run the code including setting any options or flags, and what to expect upon running the code. Concise descriptions of code in comments and README. |
