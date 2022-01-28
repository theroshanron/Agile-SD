## Overview
- How software projects and testing is handled in Agile Environments.
- Process definition and requirement for the project in Agile environment and SDLC(Software development Life cycle)
- Understand JIRA tools for project/test management.
- Edge test cases, defect life cycles, types of testing.
  - Edge test cases is out of box thinking and understand the process of defect life cycle.
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
- Use epics to plan features across multiple Sprints
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
- Add acceptance criteria discussed within agile team.
- Product owner needs to make sure that right component(team), version and epic is added to the story.
- Story goes to the backlog and from there we can add multiple issues(modules for the login page) related to single epic:
  - Edit boxes creation, description about login page, login page footer links, virtual keyboard implementation in login page, login in submit with drop down.
  - Account summary section, Recent activity, Pre-populate data into account selections, footer cards and welcome section with name in the dashboard.

## Backlog refinement
- Add the acceptance criteria, error handling and validation to the story.
  - Create edt boxes and add error handling like invalid information
    - Special characters are not allowed
  - Add story point to the story based on complexity
- Overview of detailed requirement analysis, splitting large item into smaller ones and estimation of new items.

## Creating sub-tasks 
- Create sub-tasks in story to assign who will develop what (Developing, Manual testing, designing the UI, backend and automation)
- Easier for project owner to track the status of story.
- Sub-task should follow the acceptance criteria of story
  
## Sprint 
- Released deadlines get broken into multiple short deadlines using stories known as sprint (1-2 weeks) 
- Keep the last sprint for review and testing
- Timeboxed iteration of continuous development cycle 
- Within a sprint, planned work has to be completed by the team and made to be review.
- Backlog refinement meeting should occur 1 week before the next sprint (Adding acceptance criteria and Wireframe etc.)
- Plan backlog refinement meeting in mid of the week before the next sprint.


### Sprint planning 
- Check within the team how many resources we have for the week, holidays, and availability of members considering leave, sick leaves as well.
- Plan a sprint by adding backlog issues to sprint board during the sprint meeting.
- Make sure that all stories has the story points (estimation as in number of resources / week in some cases)
- Story point act as velocity of the sprint and estimate shown on sprint board helps in estimating how many issues(stories) can be added to the story
- Issues needs to be added from backlog to the sprint board based on the priority
- Add sprint goal and start the sprint with duration (start date / end date)

## Scrum board
- To do, In Progress and Done column.
- Columns can be customized from the project settings.
- Make sure to update the status of stories before the sprint meeting. 
- Sub-tasks should be moved to done whereas story goes to in progress for QA by product owner.
- Daily huddle to discuss the status based on the board (15 mins)
- Confirmation and tracking on active sprint.

## Creating Bugs and checking Sprint reports
- We can check the report in graphical way which shows the pattern of story point and how long it took to achieve.
- Reports are created after sprint is closed.
- Bugs can be created as an issue same as story/task creation.
  - Go to issues and then click create where issue type is Bug.
  - Add complete description on how the bug can be reproduced
  - Add priority and fixed version number
  - Add the epic link / story.

## Sprint retrospective
- Discuss what went well in the sprint and what did not go well in the sprint
- Scrum master presents everything on the board
- Discuss the reason behind why something did not go well and make a case study
  - Find out if grooming and refining were done right.
  - If something happened due to dependency on resources and tech stacks.
  - Come up with rectification idea/ action item so that it does not get repeated
  - Make a note of all the pain points and action item associated with it in the documentation.

## Kanban boards
- Does not have sprint board.
- All the backlog item exists in the to-do status and we can work on the demand and deadline basis.
- Create new project and then Kanban software development(JIRA software) or kanban board as template(JIRA cloud).
- Backlog/To-do, Selected for development, In Progress and Done are the statuses on board.
- Everything exist on one board and it is less used by the team.
  
## QA to come up with the test cases
- Verify if the right data / information is available
- Functional testing
- Conditional testing
- UI testing
- Browser / Platform testing

## Define tests when project backend is designed by APIs
- Communication between backend and frontend by chunks of code.
- If the frontend tech changes, sometimes we will need to change the code for backend as well.
  - To make it independent, now we use API.
  - Value is JSON / XML.
- API response and database response both needs to be tested if we are getting actual value.
  - Done by API testing.
- Understand the architecture of application before writing any test cases.
- Multiple requests at the same time slows the fetching from API due to server load or server can fail too giving null response.
  - This comes under performance and load testing.
  - Define all type of performance test benchmarks
  - Jmeter and Loadrunner are some of the tools for performance testing
- Selenium web testing logins to the system from frontend and checks for all the functionalities.
  - Selenium automaton test requires coding and reports the response from API server.
- UI testing can be automated with frontend automation testing tools like Selenium

## How to think out of box for Testing 
- Success and failure message with functional testing adding conditions.
- Get as much as domain knowledge you can get for the project working on.
- Test if everything at backend is working same as frontend
- Test API cases and API to API calls.
- If API fails because Often any technical problem arises, use the concept of disaster recovery
  - Roll back the process, update the log and notify with an alert.
- Prepare test cases to check for the trap
  - Zero balance but tries to make the credit card payment is one test case
  - You have 400 balance and payment needs to be made is 500 comes under test scenario
  - You have to pay 400 and you are trying to pay 800 is one test scenario
  - Account is closed or flagged but you are trying to make a payment is one of the test cases.

## Test Scenario, case and steps
- Scenario: Password reset functionality 
- Test case 1: 
  - Invalid email
    - Throws an error and email for reset not sent.
- Test case 2: 
  - Valid email and password
- Test case 3: 
  - Reset link expired.
- Test case 4:
  - Password guideline not followed.
- Test case 5:  
  - Logged in with new password and logs out from all the device with logged in from old password.

- Steps: 
  - Login to the landing page and click forgot password.
  - Enter valid email and submit.
  - Repeat the above step and check the first link received for reset whether it's expired or not.
  - Enter the password and submit, if there is an error message:
    - Match the password following the guidelines.

## Xray App in JIRA
- Install Xray plugin in JIRA for testing using Apps section in cloud version.
- Configure the project after Xray is installed.
- Select the project so that we can add Xray issue types.
  - Click on Add Xray Issue types
  - Test, Precondition, Test set, Test plan, Test Execution and Sub-test execution are issue types.
  - Create a Test case and add the summary.
  - Test is a sequence of steps coupled with conditions, test inputs and expected results
  - Add test type: Manual or automatic.
  - Add the steps and what to perform in description.
    - Add action
    - Add data 
    - Add expected results.
    - We can also attach images/screenshot of steps as well in the JIRA test steps.
  - Add test preconditions (Opens an issue type)
  - Create a Test set (Opens and issue type), add summary and description.
    - Include what type of test case will be included.

### Importance of Xray 
- We can create multiple test cases and add to 1 test sets using add existing test case.
- Create Test plans for any specific release.
  - Number of regression tests that needs to be test thoroughly before the release.
  - Create a test plan in JIRA as an issue and add the test cases which needs to be test thoroughly before the release.
    - Add the summary and description.
    - Add the existing test cases.
    - We can also include a test set instead of test cases.
    - Once the test plan is ready, start testing the test cases with test execution.

### Test Execution
- Click on create test execution and add the summary.
- Add fixed versions and test environment.
  - Looks similar to test plan.
- Click on run button and proceed with all the test steps to execute.
- Select the test status from passed, executed and failed.
- We can also see the overall execution status from the top.
- We can assign different steps to different assignee for the test execution.
- All the test execution result gets added to test plan automatically because we create test execution from test plan window.
- Test run shows the status of test from execution.
- We can also add our test cases to our user story with LINK issue(tested by, related to)

## Software Testing Life Cycle
- Testing is standardized and has life cycle just as software development.
- Requirement analysis.
  - Test planning.
    - Test Case development.
      - Test environment setup.
        - Test execution.
          - Test closure.

- The requirement Traceability Matrix is prepared at test case development cycle.
  - Industry accepted format for tracking requirements where each test case is mapped with the requirements.
  - It helps in tracking backward and forward traceability.
- Test plan is prepared by the test lead or senior QA in agile team.
- Testing is just not limited to finding bugs and has a wider scope and required from the beginning of the project.
- Use diagram or prototype for requirement gathering analysis

### Test planning
- Define test strategy in the document and it contains the plan related to all testing activities  which needs to be done to deliver a product.
- This document is prepared after the analysis of requirements.
- It contains what to test and what cannot be tested(like third party API or app included), tools required for testing, environment, infrastructure required for testing.
- Staffing and training needs.
- Testing duration.
- What are the risk and contingencies plan for those risks.

### Test case development 
- In Agile, testing happens in every sprint. 
  - Test cases are prepare for the modules/ sprint and not the whole product.
- In waterfall model, the whole product is delivered once at a time and testing occurs before the delivery(unit, integration, functional)
  - Test case development and testing environment is setup before the product delivery.
  - Test cases are prepare for the complete product.
- Software testing life cycle  was introduced in waterfall model.
- Requirement analysis and test planning is constant and occurs before every sprint.
- Prepare test cases and test data before every story.
  
### Test environments
- Code deployed on the server.
- Database(also exists on the server) from where the data is being accessed by the application code on frontend.
- Jenkins tools used to deploy with git and for testing.
- A dev sub-domain is used for testing in stage.
  - dev.abc.com   
- Make sure environment is ready before application gets ready for the deployment.
- Analyse all the story in the sprint grooming for testing and ask questions what kind of test environment needed.
- It decides the software and hardware conditions under which a product is tested.
- Use different branch to push and deploy the code for different features.
- Multiple QA environments(at least 5) are needed for the big projects so that different team can test different features at one time.

### Requirement Traceability Matrix
- Test the developed product based on the requirements of client.
- Create multiple test cases for all the requirements
- Mapping needs to be done for the test cases and the requirements to find out which test cases is for what requirement using matrix.
- Every environment should have at least one test case.
- Write negative test cases as well and map it to the requirements
- Backward and forward compatibility tracking can be done to find out the relevant cases.
- This is outgoing in the agile environment and tested at the end of sprint.
- Forward traceability is mapping of requirements to the test cases and backward traceability is mapping of test cases to the requirements.

### Test execution and Closure activities
- Execute all the test cases that have been prepared for the functionalities
- Report the bug for correction and retest it after the resolve.
- Monitor all the bugs in a document.
- Do regression tests around the bugs.
- Provide the screenshots or screen recording of how to reproduce the bug.
- Once the product is delivered, we do the test closure.
  - Ensure test completion: If something is missing, report it back in next sprint meeting after two weeks.
  - Handover test artifacts: Create automation tests and handover to the clients.
  - Project Retrospectives: What went well in the last release and what needs to be improved or any push back received.
  - Archive test work products: Save the test data, if needed in later stage for testing or tracing when something breaks.


## Defect life cycle 
- Troubleshoot when application does not work:
  - Check in network tab or browser console logs (in Google developer tools)
    - Check for the request in network call and preview the error code with parameters
    - We can also hit the url in postman to check the response from API.
    - Check for the logs in console tab for issues at frontend validation.
    - Every action taken on the page generates a log.
  - Check in App server logs.
    - Check for event action based on the timestamp.
  - Clean cache and cookies to try
  - Debug and understand the error first before reaching out to developer

## Create defect with complete details of bug 
- Steps to re-produce the error page
- Provide test data information
- Provide expected result to see the change.
- Steps to reproduce:
  - Navigate, select and verify
  - Test data.
  - Credentials.
  - Expected results.
- Timestamp to provide when you found the error.
- Screenshot of your system when error occurred.
- Troubleshoot thoughts.

## Severity and Priority
- Severity is to what extent the defect can affect the application.
- Severity defines the functional of application
  - Critical
  - Major
  - Medium
  - Low
- Priority is the order in which a defect should be fixed.
- Priority defines the necessary and how quickly it needs to be fixed
  - It can be categorized as low, medium and high
- It requires complete knowledge of the domain and requirements of the stakeholders to understand the severity and priority.

### Defect Triage 
- A process to analyse the defect, it's severity and priority by defect owners.
  - Valid but won't fix 
  - Defects due to environment.
  - Not reproducible
  - Valid known

## Smart way of retesting the defect 
- Do regression testing around the defects.
- Check all the existing functionalities to find out if any new bug has not occurred.
- Test all the cases again before validating the defect functionality resolution.
- Automate most of the testing for test cases.
  
## Types of testing:
- Regression tests: 
  - Process of testing changes to application to make sure that the existing functionalities still work with the new changes.
  - Recommended before every release and majorly done with the automation right before the end of sprint.
  - Automate every test cases with the automation script.
  - It is used for test cases with frequent defects like functionalities critical and integration test cases.
- Smoke / sanity tests:  
  - Smoke test development and regression test development are related and similar
  - The only difference is in depth scope(less for smoke tests) and duration of running the tests(less than 5 minutes).
  - It runs after every build and consists of all critical tests (After every commit)
  - All critical tests are done like loading of home page and done with the automation after every commit using the tools like Jenkins.
- Component testing: 
  - It is a method where testing of each component in an application is done separately.
  - It is done in isolation from rest of the system depending on the development life cycle model.
- Integration testing: 
  - A type of testing where software modules are integrated logically and tested as a group.
- End to end tests:   
  - Complete and integrated software is tested to evaluate the system's compliance with the specified requirements.
- Exploratory testing: 
  - Unscripted QA techniques used to discover unknown issues during and after the software development process.

## Verification and validation
- Verification: 
  - Process of evaluating work products of a development phase to determine whether they meet the specified requirements for that phase.
- Validation:
  - Process of evaluating software during or at the end of the development process to determine whether it satisfies the specified business requirements
  - Accept or reject the functionalities.