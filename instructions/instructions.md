# The final project

There is no one way to do all of this, but if you feel as though you can go further, you probably can, and you should. 

The project will have several deliverable stages to keep us on track, according to the [schedule](../about/schedule). _Changes to that master schedule supercede any dates below._

1. 15% **Project proposal**. Discussed [below](#initial-proposals)
2. 5% **Project proposal (final revision)**. Discussed [below](#final-proposals).
3. 20% **Project status report**. Discussed [below](#project-status-report).
4. 45% **Written component - report and presentation files**. Discussed [below](#report-and-presentation-files).
5. 15% **Presentations**. Discussed [below](#report-and-presentation-files).

## A note on ambition

Ambition will be considered when grading the written component and results. 

The goal of the project is not to simply take a pre-cleaned dataset and run a basic analysis. You should collect data, from one or many sources, and combine them into a usable, clean dataset. Consider the depth of your analysis as you gather and clean this data. 

As a silly example: Are you just gathering data about the height and weight of a sample of individuals and looking at the correlation of these two variables? That level is not sufficient for the end goal of this project. You would be better off using this data to predict the gender of an individual, given height and weight entered by a user, and using the data to make these predictions. 

Always ask yourself if you can take your analysis one step further. If you answered yes, go for it! Use your data to extract information, gather this information, and draw conclusions. 

## Initial proposals

**Full instructions are [here](project_initial).**

- General idea: The question are you interested in, the data you need to acquire, the variables you'll use, and the  plan for how you'll analyze it (what methods you'll try and why you think they apply to your problem), considerations about how data might impact that.
- Treat this document as if it is public facing, and a proposal for which you would like research funding. That is, the proposal document should be polished (both in visual formatting and editing) for external audiences.
- Graded on: question viability, creativity, finance application, plan sketch, writing quality. 

### Initial proposal instructions

In the project repo, modify the README as a group. Use the template below and fill it in. 

1. The research question should be precise (NOT VAGUE), the hypothesis clear, and the metrics well defined. Thorough mechanical 
1. The necessary data should be realistically acquirable over our shorter time frame. There are a lot of data resources [on the website](about/resources.html#resources-tutorials-and-data), including FRED, [ourworldindata.com](ourworldindata.com), SEC's EDGAR. 

  > # Research Proposal: < Title >
  > 
  > By X, Y, and Z
  >
  > ## Research Question
  >
  > This section should cover:
  > 1. What do we want to know or what problems are we trying to solve? As in ASGN 5, you should list (1) the "bigger" question/debate/problem you're interested in, and also (2) the specific research question(s) you'll actually try to answer. 
  >     - The research question will be smaller in scope than the big picture question. But the answer to your specific research question should _shed light_ on the bigger question (although it likely won't conclusively answer it).
  >  
  >     - The answer to your specific research question should _shed light_ on the bigger question (although it likely won't conclusively answer it).
  > 2. What are our hypotheses?
  > 3. What are our metrics of success? 
  >
  > ## Necessary Data
  >
  > This section should cover:
  > 1. What does the final dataset need to look like (mostly dictated by the question and the availability of data):
  >      - What is an observation, e.g. a firm, or a firm-year, etc.
  >      - What is the sample period?
  >      - What are the sample conditions? (Years, restrictions you anticipate (e.g. exclude or require some industries)
  >      - What variables are absolutely necessary and what would you like to have if possible?
  > 1. What data do we have and what data do we need?
  > 2. How will we collect more data? 
  > 1. What are the raw inputs and how will you store them (the folder structure(s) for each input type). 
  > 1. Speculate at a high level (not specific code!) about how you'll transform the raw data into the final form.
  
Acknowledgment: We are effectively answering questions 1.1-1.3 and 2.1-2.3 from [DS100](https://www.textbook.ds100.org/ch/01/lifecycle_students_1.html) in this proposal.  

## Final proposals

- Graded on: The improvement from the prior version, how feedback was incorporated, and current status

## Project status report

- General idea: You've now acquired the key data and finished most of the data cleaning. 
- Purpose: Needs to show progress and that you're on track!
- _Ideal deliverable_: A notebook file with nice data sections describing data source(s) and how you got/cleaned the data. This section could go straight into your final report if it's polished enough. 
- **Actual deliverable** A notebook file that
    - describes (short bullet points) your data sources,
    - outlines (numbered list, broad steps, not minutia) how you acquired the data (for many groups, the downloading is in a separate file), got the data into python, and if you found any issues with the data you cleaned up (again, possibly a different file)
    - includes a bullet point list of your main observations from your EDA
    - shows your exploratory data analysis (EDA) (tables and figures and whatnot, does not need to be pretty or formatted)
    
## Report and Presentation Files

On the due date (listed in the schedule), your repo should be cleaned and polished for publication. That means it should be cleaned of excess and random files, and that folders are sensible (data, temporary, code), the readme helps me/the TA/future visitors explore your repo easily. Your folder structure is up to you and will respond to the nature of your particular project, but I should be able to easily find
- Your final report 
- Your presentation file
- The code used to scrape and download data (and if you click-and-download anything, a link to the source) can be separate files, and the code used to load, clean, merge, and explore the data. 

### What should my final report jupyter file look like?

- Your file should look like a nice report as if built in word, except that it also contains code to produce tables and figures. _(Some students are in the habit of submitting jupyter files that have no visibile output. Don't do that here! We should be able to see the results in the file!)_
- The code itself should be minimal and clean.
- The structure of any two reports can vary as is dictated by their purpose, goals, and steps. But, it should contain:
    - Start with a summary (goal and main findings in one paragraph)
    - An introduction section that motivates why your project is interesting and outlines your approach
    - A data section that describes your data sources, the steps you used to acquire and clean the data (a good idea: refer to your code file that does all this), and some of the key insights and observations from your EDA
    - An analysis section that explains and shows your steps leading to the main results and tables. 
        - Take care to explain why figures and tables lead you to your conclusions. 
        - Make sure to also carefully describe the methods you are using and why they are appropriate for the question to be answered. 
        - Summarize and interpret your results (including visualization). 
        - Provide an evaluation of your approach and discuss any limitations of the methods you used. 
        - Describe any surprising discoveries that you made and future work.
    - A short 1-2 paragraph conclusion.
    
Obvious caveats for grading: Form matters, check grammar, and cite work you build on. **Plagarism is not acceptable.** 

### What should the presentation file look like?
    
You can present a powerpoint, a jupyter file, or [jupyter slides](https://medium.com/@mjspeck/presenting-code-using-jupyter-notebook-slides-a8a3c3b59d67) (nice!). I'll leave it up to your group to present in the manner you consider most effective for your project. 

Each group will have 15 minutes to present your project, so build your presentation file accordingly. Try to avoid "speed talking" to make the time work. Less is more, usually. Sadly, 15 minutes won't be enough to show everything you did, so focus on big picture details rather than on the syntax of line 89 of your code.

A presentation's structure is tailored even more to its material than a report is, so what your slides show is up to you. Be creative, and have fun. Try to convey to myself and your peers why the question is interesting, describe plainly your approach and why it approach makes sense, what your main analytical findings are, and what you concluded from the exercise. Don't be afraid to "market yourselves": If you didn't something impressive (tons and tons of data, or an impressive scraper, or a great model), work that in (but tastefully). 

Obvious caveats for grading: Form matters, check grammar, and cite work you build on. **Plagarism is not acceptable.** 

### **Presentations**

I'll discuss scheduling later.

- You have 15 minutes
- Everyone should contribute
- There will be Q&A (from myself)
- Teach your classmates and myself something! Strive for clarity and making something about it memorable.

