# Format for final presentation and report

The presentation and report are oportunities for you to demonstrate what you have done for the final project. The format as such is not very formal but here are some guidelines that you can use as a starting point. 

- Should we include code? *Not unless it adds some value in the presentation or report. It is very unlikely you can walk through your code in your presentation..*
- How many plots should we generate? *No set number here, if your question is answered by a plot you would show it in the presentation. If you made more plots along the way to answer your question or to decide what statistical methods to use, you would include these intermediate plots/results in your written report*
- Can the presentation and report be different? *Yes, think of the presentation as a much more concise version of the report*

## Presentation
*As a reminder, presentations will happen in the last week of classes (16th, and 18th April)*
Please sign up with your group members and what date you would like to present [in this googlesheet](https://docs.google.com/spreadsheets/d/1rcntCkf8IrnFF9K223Wnrebo3lPDZTDvUI6nWv2vnGY/edit#gid=1673004311) by Friday, 12th April. 

### Before presentation
- Please upload your presentation (any format such as .ppt, PDF) onto [this box.com folder](https://rice.app.box.com/f/494cefad6e0747be90545d9704913b98) by noon on the day you will present. 

### Presentation format
Aim for a 6 to 8 minute presentation + 2 minutes of questions. *If you have more complex project and would like more time, please email us! Or you can spillover and take 2 mins extra since we have 10 mins spare time after 6 groups present if transitions are smooth*

- (1 m /intro) Make sure to explain what your data is about (+ how many rows x columns you have)
- (2 m /questions) Explain the questions you were trying to answer and why they are interesting
- (2 m /methods) Walk people through how you answered them (methods, if applicable)
- (2 m /results) What you found from your analysis

You don't need to include code in your slides and focus more on the story and results (*unless they add some value*)

After all the presentations, you will all vote for your favorite presentations on the Ed discussion (ranked choice of 3!). Most voted group gets +2 bonus points

## Written report
You can follow the format of a research paper for the report. You have to use .qmd format to generate the report.
- (Abstract) Summarize your whole report
- (Intro) Explain your dataset and choice of questions. Highlight any parallel research papers using similar data etc. you used for inspiration here for context
- (Methods) How you went about answering these questions. You can use your best judgement here, but focus more details on the statistical part rather than the data wrangling part.
	- You can structure the question, method and result for each question if that layout makes more sense!
 	- Make sure you explain the choice of statstical method here along with any references that pointed you in this direction
- (Results) Include plots and statistical outputs in tables or any format of your choosing including as outputs of R chunks
	- Plots should be well annotated with clear labels and a text legend summarizing the figure so that the figure is self standing for the most part.
 	- Make sure that the statistical output includes what is being tested for (in plain english rather than statspeak) 

You don't need to show the code in the report unless it adds some particular value for a certain chunk (using `echo: true` for particular chunks). We will go into your `.qmd` source code if necessary to look at the code.

*You will upload both the final report - `.html` (use if you have interactive plots) or `.pdf` along with the source code `.qmd`*. 

----
# Here's the announcement with the format for the final projects!


Hello! Hope you had a restful spring break. It is time now to start planning for your **final projects**. 

## What's the project?
This is an opportunity for you to use all the R and plotting skills you learnt so far and some of the stats that we shall cover soon on any dataset of your choice to answer interesting questions. You will present your work in a final presentation to the class (6 m present + 3 min questions)    

## Timeline
- Take the next 1 week to meet with your groups and brainstorm ideas
- You will submit one paragraph to explain what questions you will answer and what dataset you have chosen for this ()
- You will have 2 weeks to work on your final projects : 1st Apr to 15th April
- Presentations will happen on the last week of classes. 16th - 19th April ; + 1/2 sessions outside of class hours
- Final reports are due on 26th April (*middle of exams period*)

## Proposal format
For the proposal, you can discusss with your team and chose either of these two options for datasets. It would be ideal to propose one main idea + 1/2 more half-baked/sub-ideas that you discussed _just in case one of them looks promising!
Note that the answer to your questions should **involve some data-wrangling, plotting, and statistical testing** (t-tests/correlation/regressions etc.)
- **Scientific data** / bringing your own data (self-generated / from other lab members / scientific data from any published paper of interest / journalistic data of scientific rigour/interest)
	- Propose **2 questions** to answer. _For example, you could extend or improve the statistics used in a paper.._
 	- If you are unsure of what scientific data means, just try your luck by proposing multiple ideas / drop all 3 of us an email/canvas message! (_it is subjective.._)
 - **Other data** sources (_more like hobby analysis/ sports data /data from Tidytuesday etc._)
 	- Propose **3 questions**! 
 - Do post on the [discussion board](https://edstem.org/us/courses/51883/discussion/) if you had extra ideas that you are willing to _lend_ to other teams! **+1 bonus point** if any team uses your extra ideas 😄
 	- Do indicate on the post (credits : myself / team) depending on who generated the idea so we allocate the bonus accordingly! 	

You can come ask for **ideas/feedback during office hours** too!

## Groups vs individual?
If you want to work with your own data and your team isn't too keen on this, you can always do the project individually. Just make this clear to your group and submit the proposal individually from the group's proposal.
You can change groups or reorganize as you wish, all we need is that you make the group on [canvas](https://community.canvaslms.com/t5/Student-Guide/How-do-I-create-a-group-as-a-student/ta-p/280) when submitting the proposal and we will assume that's the group doing the final project together!

## Grading rubric
Here's how the projects shall be **graded**. Each point here corresponds to 1% of the final grade.
- 10 points for the **in-class presentation** (_use any format: google slides, ppt, use quarto only if you are adventurous!_)
	- Interesting question: 2 points
	- Good choice of methods: 2 points
	- Good visuals: 2 points
	- Clarity of presentation: 2 points
 	- Answering questions: 2 points 

- 10 points for **written report** (_in quarto: submit the rendered `.html` file which is what we will grade + also include the `.qmd`_)
	- Through with all necessary details: 2 points
	- visual clarity and layout of information: 2 points
	- Statistical support to arguments: 4 points
	- Detailed references/attributions: 2 points
- +2 bonus points for audience choice of best presentation! (_voting on Ed discussion!_)

Note that _the maximum points will be capped at 20 including bonuses_
The grade here will apply alike to all the team members. Please do indicate contributions at the end of the written report. In extreme cases if someone on the team hasn't contributed to a reasonable extent, you can email the instructor for redressal.

-----

## Project/data ideas

**Project ideas / where to get datasets from**
- [Tidytuesday](https://github.com/rfordatascience/tidytuesday) challenges give data and let you explore. You can find good examples solutions
	- Glance of a few TidyTuesday [visualizations](https://github.com/jack-davison/TidyTuesday) over time
	- Ex: Building [simple models](https://juliasilge.com/blog/intro-tidymodels/) from NFL data
- Spotify : [data](https://github.com/rfordatascience/tidytuesday/tree/master/data/2020/2020-01-21); ideas - [podcast episode](https://www.tidytuesday.com/15); 
- List of [free datasets](https://blog.journeyofanalytics.com/50-free-datasets-for-data-science-projects/) for inspiration
	- kaggle.com [datasets](https://www.kaggle.com/datasets)
 - If you are a basketball/sports enthusiast, you can consult @Sam in office hours for any ideas 😃

Ideas from [datacamp](https://www.datacamp.com/blog/r-project-ideas) : Apart from popular topics (such as [Exploring the NYC Airbnb Market](https://www.datacamp.com/projects/1354), [Visualizing COVID-19](https://www.datacamp.com/projects/870), [Clustering Heart Disease Patient Data](https://www.datacamp.com/projects/552), or [Predict Taxi Fares with Random Forests](https://www.datacamp.com/projects/496)) that are traditionally analyzed in various data science schools, here, you'll also find numerous fresh and curious ones. Feel free to explore them more in-depth: (_visit the datacamp link for hyperlinks and search for these datasets outside the datacamp website)_

- Rise and Fall of Programming Languages
- A Text Analysis of Trump's Tweets
- Degrees That Pay You Back
- The Impact of Climate Change on Birds
- [A Visual History of Nobel Prize Winners](https://www.datacamp.com/projects/309)
