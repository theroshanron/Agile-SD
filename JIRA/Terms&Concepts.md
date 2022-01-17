## Introduction
- A project manager and issue tracking tool for enterprise level

### Agile
- A software development methodology that is centered around helping teams get more stuff done by self-organizing their work 
- It is ever-evolving and changing. It's about constantly imporving as a team
- There are two methods:
  - **Scrum**
    - Scrum has sprints
      - A pre determined amount of time where teams determine the work to get done 
      - Stat by discussing last sprint
      - What went well and didn't go well 
      - What can we do better next sprint
      - Discuss and agree on the work to get completed before the sprint end
  - **Kanban**
    - If something new comes with an urgency like bug,
      - It will get in progress since we do not have sprint meetings
      - Stand-up meetings can be organized on a daily basis to discuss the yesterday's roadlocks and possible next roadblocks before continuing work

#### Stories and Epics
- **Story**
  - A method in Agile where a user wants something to be done for a specific reason
    - A software to do calculations for the management of bills
    - Amount of work that is fixed and will go on till the defined time in sprints
    - Also knows as user stories
- **Epic**
  - Story 1
  - Story 2
  - Story 3
  - Helps when the story gets multiple functionalities and needs to be expanded
  - Also known as parent to multiple user stories

#### Issues and Projects
- **Issues**
- Contains fields and track the progress in JIRA 
  - Description, link, client name, operating system etc. are the fields
  - Task, Stories, Bugs, Documentation are the issues
  - Issues hold the fields that contain the data and we can create our own issue types as well.
- **Projects**
- Projects are containers for issues
  - Website development, Marketing, Customer service 
    - Story, Epic, Bugs separately in each project
  - Issues live inside of the projects in JIRA
  - Projects organize things about the issues

#### Next gen Projects
- A special, simplified type of project
- Doesn't require JIRA admin permissions to create 
- Entities like issue types and statuses live inside the project
- Can be customized for project where we need custom Entities /Issues
- Fast and easy to setup and maintain.

#### Versions of JIRA
- JIRA core
  - Team project collaboration 
  - Busines-focused project management
  - Task management
- JIRA Software (JIRA core + Agile)
  - Includes Agile functionalities
  - Kanban and scrum project management
  - Software development integration and tools
- JIRA Service Desk (JIRA core + helpdesk)
  - Includes helpdesk functionalities
  - IT support and helpdesk ticketng
  - Troubleshooting management


##### Jira license options
- Cloud based or server
  - Cloud based is lower cost with subscripton model
  - Automatic updates included and support included
- Server based allows extreme customization

## JIRA for users
- Homescreen
  - System dashboard
  - Assigned to you
  - Activity stream
- At the top, we see App switcher and navigation bar
  - Your Projects, Projects, Filters, Dashboard, People and Apps appear here
- At the top right, we have search option, notification, help articles and settings

### JIRA projects
- New access from JIRA administrator
- You can star your projects to make it quickly accessible
- Each project has unique KEY which can be used to add in all issues 
- Project can be assigned to a lead 
- Options to add releases version of your Software
- We can also components for tracking 

### Creating an Issue
- Click on the create button at top or use Keyboard shortcut "C"
- A JIRA administrator can add what to appear in an issue like story, bug, task or anything custom and also the customized fields
- Red asterisk which appears in the field means it's a mandatory field to be fulfilled
- We can also add categories in the JIRA issue which is easier to identify and track later 
- Click on create and a notification appears that the issue has been created at top-right

### Searching for Issues
- We can see the recently created issues in Activity stream on dashboard
- Issues created can be seen under "Your work" as well
- Using "/" shortcut or search tab at the right top
- Use Advanced search options to search for issues using filters ike status, assignee and type
- We can apply multiple filters in search to narrow down the search
- Use JQL (JIRA query langauge) to shortcut the filter request (Atlassian document can be really helpful for the query)

### Overview of the issues 
- We can attach files, create sub-task and link an issue or the confluence
- We have options to add description, subject and other fields required
- In the activity section at the bottom, we can see comments, history and work log for the particular issue
- At the top right, we can add watchers for the issue and see the details like start / end date, reporter, assignee
- We can add categories and update the custom fields
  
### Working with filters
- Click on "Advanced search" 
- Write JQL(JIRA query language) to apply custom Filters
- We can add a name to the filter and save it to quickly access it
- Saved filters can be added to the Agile board or dashboard
  
### Scrum Agile board Overview
- Click on the left side menu and then click on the scrum board
- We can use search tab in left to search across the agile board
- Use filters on board to quickly access the status based on the selected
- Untick the existing and tick the next filter type to see the results
- 