# UCONN CHALLENGE 01- REFACTOR CODE

## Table of Contents
01 Challenge Requirements
02 Summary of What I Did And Thoughts On The Project
03 Screenshot of Deployed Application
04 Link to deployed application
05 Detailed notes about changes in each commit






# 01 Challenge Requirements
The user story and acceptance criteria are as follows:

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

Additional grading requirements not mentioned in the above passage:

## Grading Requirements

> **Note**: If a Challenge assignment submission is marked as “0”, it is considered incomplete and will not count towards your graduation requirements. Examples of incomplete submissions include the following:
>
> * A repository that has no code
>
> * A repository that includes a unique name but nothing else
>
> * A repository that includes only a README file but nothing else
>
> * A repository that only includes starter code

This Challenge is graded based on the following criteria: 

### Technical Acceptance Criteria: 40%

* Satisfies all of the preceding acceptance criteria plus the following code improvements:

  * Application's links all function correctly.

  * Application's CSS selectors and properties are consolidated and organized to follow semantic structure.

  * Application's CSS file is properly commented.

### Deployment: 32%

* Application deployed at live URL.

* Application loads with no errors.

* Application GitHub URL submitted.

* GitHub repository contains application code.

### Application Quality: 15%

* Application resembles mock-up provided in the Challenge instructions (at least 90%).

### Repository Quality: 13%

* Repository has a unique name.

* Repository follows best practices for file structure and naming conventions.

* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

* Repository contains multiple descriptive commit messages.

* Repository contains quality README file with description, screenshot, and link to deployed application.

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository, with a unique name and a README that describes the project.





# 02 Summary of What I Did And Thoughts On The Project
You can see detailed notes about each step I took in part 5, but as a basic summary: 

When I went to the project website at first, I found the Horiseon website already matched the provided screenshot. Therefore, my task was to clean up the html and css files WITHOUT changing the look of anything. This involved doing lots of research on what each element did and what each part of the css did, then making changes based on what I felt was redundant, unnessesary, or non-semantic. 

Many of the HTML changes involved getting rid of divs, checking elements were correct, adding missing information like alt text and head info. Many of the CSS changes involved class consolidation- I tried to get to as few classes as possible, and group information together in a logical way. 

There was no clear guidance on exactly how many comments I should be providing, so to err on the side of caution, I've decided to comment on every little thing as much as possible so as not to leave any stones unturned but also to use this project as a reference in the future. I would hope that the amount of commenting I did will be considered excessive, because it took quite a long time. I look forward to feedback on my comments to see if there were too many, not enough, or if my information was even in the right place. 

I tackled this project earnestly and ready to learn. And I feel like I learned a lot. But I feel that the expectations of the student have not been set by the teacher beyond the task requirements. What I mean by student expectations is this: I have this sinking feeling that I will get penalized for things I will have not known about. For example, this readme. The task instructions state we're meant to have a "professional" readme as part of our grading requirements, but there is no reference point for this. We can only speculate based on google research. Am I to simulate a working environment at a real company? Is this readme actually supposed to say something like "As an junior developer for the Horiseon client, my objective was to refactor existing code to improve accessibility." Am I meant to roleplay like this, or am I meant to speak bluntly about the objectives? Will I be penalized for asking these hypotheticals on this readme? Or am I permitted to speak candidly about what this actually is, a school project? 

If possible, I would like to see an example of an "A+" finished project so I can get a better idea of what to aim for in the future. This is speaking from a position of wanting to do my best, and putting the time in, and not feeling lost in terms of the work, but in terms of student expectations.   


# 03 Screenshot of Deployed Application
To be added in a future commit


# 04 Link to deployed application
To be added in a future commit


# 05 Detailed notes about changes in each commit

The assignment called for descriptive commit messages. I wasn't sure if I should put the details here or as a comment on github, or if there's some third way to do it. If you have a preference for this let me know. For now, I will list them here.

List of changes on commits

Commit 01: "Fresh start"
Cloned the files from Xandromus repository using ssh, but after I created a repository on my account and tried to push the files, it said that there were "no changes and the tree was clean" even though nothing had been pushed yet. So I moved all the files out of the folder, then pushed the blank folder.

Commit 02 "first commit"
Moved the files back into the folder, and pushed it. Github now recognized the files. So this is my first offical commit. No changes were made from the Xandromus repository.

Commit 03 "Head and Header"
Changed div elements in the header to nav
Cleaned up the li elements to look nicer
Changed the head title to be a concise, descriptive title

Commit 04 "Main section"
Changed div elements to improve semantics
Moved big image from CSS file to html
Added id to "search-engine-optimization" to get the link working
Added alt attributes to the images
Consolidated some of the CSS classes into 1 class

Commit 05 "Side section and Footer"
Changed div to aside and footer in their respective areas
Consolidated some of the CSS classes into 1 class
Added .benefit p to the CSS to make the aside formatting better match the sample image
Cleaned up unneeded tags
Reordered CSS slightly to match the html order of appearance

Commit 06 "CSS comments"
Added comments to all CSS classes to describe what their function is
Changed h2 in footer to h4 (missed that in the previous commit)
Updated the CSS to be more semantic
Updated readme to include task information











