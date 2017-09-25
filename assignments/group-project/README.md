---
title: Group Project
currentMenu: assignments
---

## Purpose
* demonstrate your web application development chops
* introduce the application development process

## Learning objectives
When you are done, you will be able to 
* Plan and design a small web application
* Work effectively as a member of a small, self-directed development team
* Apply your web development skills as you construct the application

## Teamwork

Individuals have the option of pitching a project to the class.  

If necessary, the instructor will make team assignments. 

Projects are **strongly encouraged** to have from three to five team members. Having partners greatly increases your chances of succeeding.

## Deliverables

Students are required to produce the following artifacts in a project web site and a project repository. I recommend that students use the GitHub README associated with their project repo as a project "web site" to contain their non-code project deliverables.

| Deliverable | Minimum Required | Stretch goal |
|-------------|-----------------|--------------|
| Elevator pitch | Three sentences in README | N/A|
| Brief  | Sections in README | N/A|
| Project web page | Repo README | Github pages single page|
| Wireframes  | Hand-drawn diagrams scanned to repo README | Online wireframe tool |
| Page flow diagram | Hand-drawn diagrams scanned to repo README | Online wireframe tool |
| User Stories | In README at end of design sprint | <ol style="padding:1.5rem"><li>User stories maintained and updated as project proceeds</li><li>User stories tracked to completion in issue tracker</li></ol>|
| Tests | Test plan document | <ol style="padding:1.5rem"><li>Testing results tracked in Issue tracker</li><li>Some unit tests in repo</li><li>Some end-to-end tests in repo</li></ol>|
| Code | Stored in repo, available for download and execution on TF machine | Downloadable & deployed to onlne environment |
| Issue Tracker | Team member assignments kept up to date | Features requests, test failures, and bug reports tracked and tied to commits | 
| Technical presentations and code walkthroughs | group demos to TF and instructor | N/A |
| Project presentation and demo  | group demos to TF and instructor | N/A |

See below for details about each of these deliverables.

# Schedule

| Week | Deliverable |
|------|-------------|
|1| Team members and mentor selected <br>Slack channel & project repo created<br>Elevator pitch & brief is ready in repo README
|2| Wireframes, page flows, and user stories<br>Preliminary team member tasks in issue tracker<br>Branch strategy documented
|3| Second sprint: Prototype underway<br>Team tasks up to date in issue tracker|
|4| Prototype & project repo review with TF complete<br>main branch contains release baseline<br>Issue tracker tasks reviewed by TF |
|5| Third sprint: MVP underway<br>User stories updated | 
|6| Product demos & group presentations |

# Deliverables

## Elevator pitch 

A three-sentence statement succinctly presents:

* Who the customer is
* What their unmet need or goal is
* How the product meets the need


## Brief

The brief is a short (one page) summary of your web site. It sets the guiding principles of the site. It is a contract between the client and the team. 

For this project, it defines the shared goal among the team. 

At a minimum, it includes answers to the following questions:

* What are aims of the web site ( e.g. to increase traffic, increase product awareness, generate more sales, offer e-commerce, advertise a new product or service)
* Who is the target audience? What are the demographics (e.g. children, adults, social class, income levels, location, etc.)
* How will your target audience be accessing your site – via their phones, tablets or desktops?
* What look and feel or emotional reaction should the site evoke? Identify a few sites that look like what you want your site to look like.

See more at: http://www.methodandclass.com/article/how-to-write-a-brief-for-a-web-site#sthash.3ZulFUY1.dpuf

## Wireframes 
## Page flow diagram
## Initial User Stories

For all three of these topics, see the article [User Stories, Wireframes, and Page Flows](user_stories_wireframes_page_flows.md)

## Tests

A test plan is required. This can be a simple markdown document or section of your README that says, "We'll use manual testing to verify our scenarios" with a table of results.

Automated unit tests of models are a stretch goal. We'll be covering this in class, so you can apply what you learn in your project.

Automated end-to-end tests of controllers are a stretch goal, but we won't be covering this in class.

## Code

You are expected to structure your code using best practices based on the most complicated project in class in your chosen language and stack.

You must check in all code and merge it to master for it to be considered for review and grading. We recommend that you tag release configurations. That is, when it is time for your interim demo, you will be asked for a tag on master. Your TF & instructor will check out that tag, build your project, and evaluate it.

We recommend developer branching. Frequent commits are your friend. Frequent pushes of code to your own branch on github allow your teammates, mentor, and instructor to see your code and help you.

We would like to see associating items in your issue tracker with commits. When you finish committing your work and merge it to main, use the appropriate technique to clost the issue you are working on.

We do not recommend forking or the use of pull requests on this project.

## Technical presentations and code walkthroughs

You will demo as a group to your TF and your instructor several times during the project. At minumum, your team will demo at the end of each two-week sprint.

These demos will be focused and limited to about a half-hour per team. 

Each member is expected to be able to describe the project as a whole and it's archtecture. 

Each member is expected to be able to do a detailed walkthrough of their own code and describe the boundaries of their responsibilties.

Members are not responsible for describing the internal operation of other team members' code.

## Project presentation and demo

There will be a "demo" of your project to the rest of the class. This will be very short (5-10 minutes only) and can be presented as your team decides (one presenter, multiple presenters, etc.) We do not recommend fancy powerpoint presentations, just your repo and your app. 

It must cover at minimum:
* The elevator pitch and your most important user stories
* A demonstration of your app proving that it satisfies the elevator pitch and implements the user stories
* A breakdown of who was responsible for what aspect of the project
* A brief commentary on what worked well and what challenges the team ran into.
* One or two examples of code that the team is particularily proud of.

This demo is a dress rehearsal for how you might use this project in your interviews.