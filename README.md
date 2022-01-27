# afmsc2022
Adams Family MSc Assignment 2022

## Table of Contents

  * [Table of Contents](#table-of-contents)
  * [Preamble](#preamble)
    + [Scrum Master](#scrum-master)
    + [Product Owner](#product-owner)
  * [Project Deadline](#project-deadline)
  * [Project Specification](#project-specification)
  * [Considerations](#considerations)
  * [Useful Links](#useful-links)
  * [Risk Register](#risk-register)
  * [Tenants of Design](#tenants-of-design)
  * [Social Contract](#social-contract)
  * [Branching Strategy](#branching-strategy)

## Preamble

This is the online repository for the <<Team Name>>. Summary of project requirements should go here.


Our product will be delivered using an Agile methodology that embraces the DevOps culture. Please note that our culture embraces change and these documents are treated as living, breathing artefacts that will be continuously updated.

### Scrum Master
Dalimol Abraham

### Product Owner
Bubashankushan

### Team Members
 * Aishwaryalakshmi Arumugam
 * Aravind Rajesh Kanna
 * Bubashankushan
 * Dalimol Abraham
 * Rohit Mishra
 * Ron Greego Raju

Lecturer: Paul Greaney

  
### Project Deadline
Friday, 8 April 2022 and 23:59

## Project Specification  
<!-- <team must agree specifications here - below are samples for discussion purposes>     -->
    Clean and simple design
    User access levels (client, administrator)
    Includes at least one self developed api and one webservice
    To be run over Amazon AWS

    Frameworks
    Database
    Database persistence technology
    Define the buisness Requirements
    Named queries and database triggers for security
    Regex for cleansing and validation of data before sending to the database.

## Useful Links

    DC Slack: https://app.slack.com/client/T84LE6L6R/C02PPKA8728
    Jira: https://addams-family.atlassian.net/jira/software/projects/AF/boards/1
    GitHub: https://github.com/devopslecturer/afmsc2022
    Project close out presentation: 

### More Information
For more information visit our other sections
| Section  | Description  |
| --- | --- |
| Process  | Describes the companies process  |
| Project Log  | Log of project activities  |
| Costings  | Overview of the project cost  |
| Architecture  | Outlines the architecture  |
| Environments  | Overview of the environment set-up  |
| DR Plan  | Disaster Recovery Plan and procedures  |
| Requirements  | Overview of the requirements for the project  |
| SLAs  | Service level agreements  |
| Risk Management  | How we manage risk  |
| Security  | Overview of security  |
| Project Log  | Team log for the project  |

## Risk Register

These are the current Risks on the project, re-aligned on a weekly basis

    Infrastructure proving to be a real problem, may block being able to release software
    Team is finding itself to be running short on time due to other work and study commitments
    No PO feedback on software
    Unknown technology choices has led to a lot of upskilling required
    Changing / ambiguous requirements
    Talk of the company being bought out has raised concerns
    Lack of rights for toolsets chosen has hindered progress and ability to deliver

## Tenants of Design
<pick from the sample sections below and add your own>
    Dedication to clean, secure, performant and self documented code
        code Frameworks used
        code coverage tool used
        Secure code: Regex for cleansing and validation, Named queries and database triggers
        performance testing tool to be used
    Documentation / code commenting (javadoc)/separate branch
    Datastore for persistance
    Testing:
        Unit testing
        integretation testing
        UA
    Environments:
        staging and production
        tight configuration management for consistency and reproducibility
        automated creation and deployments
        integrated and automated pipeline (commit -> test -> deploy)
    Github version control:
        branches used
        version/release management
    Agile project management methods/principles (jira)

## Social Contract

### Meetings

    Stand-ups will occur on Monday, 11:00 to 11:15.
    The order that people give their updates will be based on Aishwaryalakshmi Arumugam, Aravind Rajesh Kanna, Bubashankushan, Dalimol Abraham, Rohit Mishra, Ron Greego Raju of those present at the meeting.
    Updates will be in the form: What I've done, What I plan to do, Impediments
    Sprint planning will occur every other <<day and time>>.
    Please add and update items within Jira prior to the sprint planning session.
    Sprint retro will occur once a month, <<Date and time>>.
    The order that people present their sprint retro updates will be based on alphabetical order of those present at the meeting.
    Points raised in the sprint retro will be noted and posted on the slack channel by the Scrum Master.
    Backlog refinement?
    Task estimation will be done using Story Points (Fiboinacci/Poker). 
    Come prepared to meetings.
    Be on time for Stand Ups and meetings.
    Mobile phones on silent.
    Everyone has equal voice and valuable contribution.
    Keep your language and tone professional at all times.
    Be honest.

### Communication

    Slack is the preferred method of communication.
    If a demonstration is required use Loom, record the session and upload to the Slack channel.
    No Slack communications between "22:00 to 09:00 GMT".
    Raise a problem as soon as you see it.
    Respect each other and understand differences in knowledge.
    All team documents are to be created using Markdown language and shared on GitHub.
    There are no silly questions, if you don’t understand, ask.
    Share success stories.
    Focus on the positives.
    Don’t make assumptions.
    Don’t interrupt and cut another person off while they are talking.
    Listen when someone is talking, don’t interject.
    Zero tolerance for bullying.
    Communication in this order: 
     * Aishwaryalakshmi Arumugam
     * Aravind Rajesh Kanna
     * Bubashankushan
     * Dalimol Abraham
     * Rohit Mishra
     * Ron Greego Raju
    Agile way of working.
    If are assigned a job, take ownership of it and keep it up to date.
    Stick to your agreed working patterns. Let the team know when you are late or going early.
    Keep JIRA board updated at all times.
    Update the Scrum Board as you progress the story i.e. don’t update at standup.
    Don't be afraid to ask for help.
    Don't be afraid to give constructive critism, as long as it is constructive.
    Solve roadblocks within the team. If the impediment can’t be solved within the team then give it to the Scrum Master.

## Other

    Sprints will start <<check with lecturer>>.
    The Scrum Master role rotates each week, the schedule is available on the on the process section
    The Product Owner role rotates each week, the schedule is available on the on the process section
    Jira will be used for task management and planning.
    Each member of the team will work <<? story points>> per week, unless they are on vacation.

### Branching Strategy
 * Main
 * Develop
 * Feature

### Estimating Story Points Within Jira

The teams team's velocity is calculated by dividing the the number of points burned each sprint divided by no of sprints. The Velocity chart from Jira (below) is used for this calculation.

The teams current story point velocity is "<Choose the number!>".
