## Overview
- How software projects and testing is handled in Agile Environments.
- Process definition and requirement for the project in Agile environment and SDLC(Software development Life cycle)
- Understand JIRA tools for project/test management.
- Edge testcases, defect life cycles, types of testing.
  - Edge testcases is out of box thinking and understand the process of defect life cycle.
- Query language basics

## Project to work on: Credit card online banking
- How to use JIRA tool for this project management
- Features to develop:
  - Develop login module 
  - Credit card and dashboard
  - Profile
  
## Set up JIRA account and create Agile Scrum 
- Visit JIRA on Atlassian https://www.atlassian.com/software/jira
- Enter the email address and the site account which you would like to have
  - e.g: XYZ.atlassian.net
  - You can also continue with the Gmail account.
  - Select the purpose of use and integrate apps if needed while setting up.
  - Invite the team by entering their email address.
  - Select the way of managing the project like Kanban, Scrum or Bug tracking 
  - Company managed or team managed option type and then add the Project name which automatically ads the Key.
  - Go through all the options in left menu side to explore.

## Epic
- Known as features/requirements that needs to be achieved
- Epics are large work items broken down into a set of stories. 
  - Story
  - Task
  - Sub-task
- User story is a smallest unit of work in an agile framework
  - A chunk of work units to achieve the epic goal.
  - Used to articulate how a piece of work will deliver a particular value back to the customer.
  - Often expressed in a simple sentence structured as follows.
  - "As a [person], [I want to], [so that]

### Create Epics and story
- Use epics to plan features across multple Sprints
- Click Create issue and then select the issues as Epic under the project.
- Click Create issue and then select the issues as Story and add the description as well as other details.
  - Link the story to epic with the dropdown in field epic link and add priority, labels etc.
  - Newly created stories goes to backlog in Scrum.

## Components and Release Versions
- We can create a component by clicking on Components in the left hand side on local server and right hand side on JIRA software cloud.
  - Add the team, description and assignee.
- In the left hand side, click on Releases to start creating release version.
  - Add name, start/end date and description.
  - Link the stories to releases by adding fix version field.

## User story description to reflect business value
- As a client, I should be able to enter my email/username and password in the login page so that I can login.
- Add acceptance critera discussed within agile team.
- Product owner needs to make sure that right component(team), version and epic is added to the story.
- Story goes to the backlog and from there we can add multiple issues(modules for the login page) related to single epic:
  - Edit boxex creation, description about login page, login page footer links, virtual keyboard implementation in login page, login in submit with drop down.
  - Account summary section, Recenty activity, Prepopulate data into account selections, footer cards and welcome section with name in the dashboard.