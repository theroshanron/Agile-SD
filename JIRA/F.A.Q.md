### If you find a bug in the production, how to make sure that the same bug is not introduced again?
- We will do the regression testing to make sure that same bug does not occur and can add automation testing.

### What do you when the developer denies that you filed is a bug?
- Provide business documentation reference to support why existing functionality is not per the design.
- Involve product owner/ Business analyst.
- If Bug is not reproducible then provide the screenshots of the bug, give timestamp.
- Provide test data used for replicating the issue.

### What has been one of the greatest challenges while doing regression testing
- Test data issue.
- Improper selection of regression test cases might skip a major regression defect to be found.

### Difference between functional testing and non-functional testing
- Functional testing verifies that features/system working as expected according to requirements.
- Non-functional requirements tells how well the system does it within design and resources constrainment.

### Enlist some of the key challenges that are faced while performing software testing.
- Data issues.
- Environment available.
- Using the right set of tools.

### Different level of testing?
- Unit testing. (Developer)
- Integration testing. (Team of developers)
- System testing. (Product owner)
- Acceptance testing. (Done by end user or client)

### Drawbacks of Agile implementation / methodology 
- Sprints are usually very deadline constrained.
- Documentation is not the priority.
- Frequent changes in requirements.

### Approach to have a high priority release to be delivered in a very short time.
- Run Automation suites.
- Run Unit tests.
- Manual testing on igh level priority business test cases.

### Example of high priority and low severity
- Wrong brand logo image in Application.

### What is Test plan?
- A document that consists of scope, approach, resources, and outline of the testing project as well as the activities for tracking the progress of the project.

### What should be the reaction if a project had been working got sudden changes in it's deadline.
- Discuss the opportunities of increasing QA resources or partial product delivery
- Hold the QA sign off if not satisfied with quality of product which eventually stops the release date.
- Be open to thoughts if it can be delivered with QA sign off covering all test cases.

### Difference between sanity testing and smoke testing
- Sanity testing is performed after receiving a software build, with minor changes in code, or functionality, to ascertain that the bugs have been fixed
- Smoke testing is a special case of testing performed on software build to check the critical functionalities of the program.

### Ad hoc and Exploratory Testing
- Ad hoc testing includes learning the application first and then proceeding with the testing process.
- Exploratory testing form of testing includes learning the application while testing

### Daily activities of a member of automation tester.
- Running smoke suite on a daily basis and sending the mail about health of applications to stakeholders.
- Verify defects assigned and take appropriate action
- Work on manual and automation for the stories in Current sprint.

### How to select regression test cases 
- Include the test that verify core features of the application
- Include test cases for functionalities that have undergone recent changes.
- Include test cases that have frequently yielded bugs.

### First action to perform as a tester when application throws any weird errors.
- Check the console logs in developer tools for error.
- Check the network tab for error or json/js related to the project to find out the status.
  - Check if any responses are failed.
- Verify application logs to understand the actual issue.

### How to solve conflict with the peer QA on any technical aspects
- Arguments should be limited to certain extent with peer and with reasons why you are correct.
- Include the team and discuss the conflict with larger audience to take open suggestions.
- Accept any decision made by the team in the meeting with a smile.

### How to decide if test case is not ideal candidate for automation
- Tests which are highly dependent on data with frequent changes every time.
- Tests which cannot be automated due to technical challenges
- Tests which are unstable due to complex nature of application

### Difference between Retesting and regression testing.
- Regression testing is to ensure that changes have not affected the unchanged part.
- Regression testing is not carried out for specific defect fixes.
- Retesting is done to make sure that the test cases which failed in last execution are passed after the defects are fixed.