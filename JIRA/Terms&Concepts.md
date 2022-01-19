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
- We can use Board settings, general filter and saved filter to select what to show on the board
- Where to show the issues on the board is determined by the status of the Issues
- If we click on "Complete Sprint", it asks for what to do with the pending Issues
  - Move to the new sprint 
  - All the issues Goes to the backlog of new sprint
  - We can create a Retrospective page to add the details on what to do with and completion time
  - Drag the issues from backlog to present based on the planning meeting
- In sprints, we move from left to right like In progress, Writing, Ready to QA, Editing, Final QA, Post live, Done
- We can simply drag issues from one column to another
  
### Kanban Agile board
- Similar options as Sprint board, we have search to search across the board
- Click on owner to see assigned issues to them
- We can use Quick filters(custom filters also allowed) based on issue type, status etc.
- Untick the existing and tick the next filter type to see the results
- Once the issue is moved to Done, it stays in the column for 2 weeks (can be changed by administrator)
  - Disappears from the column after the defined time period
- Difference between Kanban and Scrum boards are sprints
- Kanban boards can have backlog to add low priority issues in the backlog and add the working issues in progress
- Moves from left to right and we can use drag and drop option for the same 
- Kanban or Sprint board, both are displays for the issues in agile way
- We can use Board settings, general filter and saved filter to select what to show on the board
- Where to show the issues on the board is determined by the status of the Issues
- As a JIRA administrator, we can add the custom columns and name it accordingly, usually based on the status of the issues
  
### How next gen project works
- Create a new project
- Create next gen project
  - It does not require administrator privileges
  - Entities in next gen project only live in that project
- It has limited feature set and easier to setup 
- Add name, access level, KEY, template (SCRUM, Kanban) and click create 
- Use Roadmap to see epic and it's progress bar
- All the setup in Next gen project remains in only next gen project

### Working with Epic in classic projects
- Click Create and then select project as well as issue type to Epic
- Add summary and Epic name (Required by JIRA)
- We can create new or add existing issue to the Epic

### Working with Epic in Next gen projects
- Click Create and then select project as well as issue type to Epic
- Add summary (epic name is not required in Next gen project)
- We can see the Epic progress in Roadmap view for all of the Epic
- We can click on any EPIC and then add an existing child issue
- We can add custom issue type in next gen project under project settings

## Jira for leadership (Working with teams)
- Click on People and create the team with people who are already on JIRA
- Add image header(optional) and description for the team
- We can add link for everyone which can be knowledgeable or work as a bookmarked 
  
### Creating a Scrum board
  - Click on Projects and click on the left side arrow to create a new board
  - Click on Scrum board 
    - Board from an exisitng project or existing saved filter 
    - Add the board name 
    - Choose the project and location of the board

### Editing a scrum board
- We can click on board settings to make any edit possible
- JIRA creates a filter in the backend even if we select to create the board based on project
- We can edit the filter anytime by adding/deleting anything from status, project etc. and then save the filter 
- Click on Board settings and then column to add a column or rename te column
  - Try to use naming convention for the column based on statuses 
- We can use drag and drop option to move issue from one column to another and by default status will change
- Swimlanes shows to whom the issue is assigned
- We can save few quick filters for board as well from board settings
- We can edit the card layout like color palette

### Creating a kanban board
- Click on projects and click on the left side to create a kanban board
- Click on Kanban board
    - Board from an exisitng project or existing saved filter 
    - Add the board name 
    - Choose the project and location of the board

### Editing a agile board
- We can click on board settings to make any edit possible
- JIRA creates a filter in the backend even if we select to create the board based on project
- We can edit the filter anytime by adding/deleting anything from status, project etc. and then save the filter 
- Click on Board settings and then column to add a column or rename te column
  - We can add a column in the backlog for the issues that has not been started like "To-do" column 
  - Backlog option will appear in the hand side as well 
- We can use drag and drop option to move issue from one column to another and by default status will change
- S and T is the shortcut to move any issue from current position to the top 
- Kanban has a Release button at the top to move all the done issues to releases
  - Add a New Version name, released date and description
  - We can see the issues in the releases at the left side based on the version name 
- We can also apply advanced filter to remove the done issue from done column (Can be controlled manually based on either weekly or monthly timeline from board settings)

### Working with dashboard
- Click Dashboard
- Click on create a new dashboard and add name, description and access (Group) 
  - Make sure to click on Add when you select the group and then save the dashboard
  - Click on edit the layout and then add a gadget
  - Add filter results, activity stream or anything 
    - We can select existing filters or select new filter to narrow down the results and save it with a name
    - Use naming convention for the filter which is easier to identify
    - We will see the results in dashboard based on results matching the filter query 
  - Even after adding the filters, we can customize the columns in the dashboard
  - Use Advanced filter (JIRA query language) for the better results
  - Always share the access of all gadgets with the team as well
  
### Saving filters for the team
- We must share the filters with the team before sharing the dashboard else the team can see the dashboard but not the gadget which is filters
- Go to filters and then select the Filters
  - Click on edit and change the access to group
  - Click add and access will change from private to that group
  - Click on save and now the dashboard will be accessible to the team

### Create issues in Bulk
- Click on create issues and then import to add CSV file
  - Top line in the csv is JIRA field to match like issue type, summary, duplicate, sorting field
  - Click on next and select the project where you want to import
  - Select date format, delimiter
  - Select the field to map and then next then next
  - Click on Map field value to forcefully map to the existing field
  - Validate and then begin import
  - We can download the log and also save the configuration for future use

### Edit issues in Bulk
- Click on three little dot at right and then bulk change all issues to
- Select the issues to make change 
- Edit the value or transition of the issues
- Select value and then select next 
- Select whether to send mail for the update or not in the case of bulk edit
- Confirm and Acknowledge
- We can also edit the field where we get visual display to see what field to change
- Field we change should exist on the display or we can request the same from the JIRA administrator

### Finding reports in Jira
- Click on Project and then select one of the scum board
- Click on reports at the left side menu
- We can select any report type based on the requirement
  - Both Sprint and Agile have some difference in reports
- For Next gen project, we have Roadmap instead of the reports
- We can also generate custom report by exporting the data of issues using filters
- We can click on Excel icon to export to Excel Desktop or Excel online or we can also export CSV
- We can click on Columns and select the columns of fields to export the only current field in CSV
- From CSV, we can create our own reports and chart in Excel or Google Sheets.

## JIRA for Administrator

### Users in JIRA
- We can have unlimited users in JIRA based on what we pay for application access
- Click on settings and then user management
- We can use site access in the left side menu to invite or apporve JIRA access for the domain or users
- Click on Access request to see who has requested for JIRA access and with what role
- We can select on invite users and then select the email address, role and product access.
  - We can also add the users to existing group while inviting 
  - Role determins whether the user can just access product(basic role) or invite others as well with (trusted user role)
- Under global site permission, we can select which user or group can create next gen project under grant permission

### Projects in JIRA
- As an administrator, we can create Classic Project 
  - Add name, key and template for the project and click create
    - Templates are Scrum, Kanban or Bug tracking
    - We can also select different templates under Business category
- Click on Project settings and then details to make any changes to the name, key, project type, lead and description
  - Under people, we can invite people to the project and select their role 
  - We can use workflow to define the custom workflow for our projects 
  - Use permissions, to assign any user to the project so that they can see any issues under it
- We can use notification to select for which events or action, we should be notified
- We can also use project automation to add rules to the project based on some events and actions
- We can also connect to external developer tools 
- We can also use issue collectors to use JIRA as a service desk support 
  