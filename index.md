# GT Marketplace

###### Group 2: Alex Puckhaber, Andrew Harris, Dilip Paruchuri, Thien Dinh-Do, Caden Farley


### Introduction

#### Executive Summary
The GT Marketplace is a secure application for Georgia Tech students to post items that they would like to sell and exchange with other students. The purpose of this application is founded from the fact that many students throw away items that others are willing to buy and need. This application aims to provide a bridge for these two types of students to communicate. The GT Marketplace will only allow Georgia Tech students to access the application through verification of GTID and Georgia Tech email during registration. The GT Marketplace itself will have the following features: a home page with a display of all the available items, a page that displays the users items and allows the user to edit or delete items they have posted, a filter search page to search for specific items, and messages page that will allow a user to send an email to a specific user to contact them about an item.

#### Definitions and Acronyms
| Acronym | Definition |
| ------ | ------ |
| GT Marketplace | Georgia Tech Marketplace |
| Evolution | Version of the project that is being worked on |
| Maven | 	Builds java projects as well as maintains additional jars and dependencies the system requires |
| Spring Boot | Creates standalone applications that will run independent of an external web server |
| Google Cloud Datastore | Highly scalable NoSQL database for building applications |
| POM | Project Object Model |


### Management Structure

#### Project Lifecycle
The lifecycle for the project at the top level will take an Evolutionary prototyping life cycle. The initial goal will be to develop a basic evolution that contains the basic functionalities of the GT Marketplace. Then, additional features will be added to the basic evolution during phases of the project.  Additional features that will be added include the following: edit/delete functionality of items, adding new items, filter search for specific items, and email functionality.. Between each evolution, there will be an intensive testing and integration phase to ensure the GT Marketplace functions at the top level. At the individual level, the project will follow a Waterfall prototyping lifecycle. Each person will be tasked with a portion of the application, and will be responsible for developing requirements, designing the framework, implementing the design, verifying the functionality, and maintaining the code.

#### Roles and Responsibilites
| Roles | Responsibilities |
| ------ | ------ |
| Project Manager | Make sure milestones are being accomplished in a timely fashion. Delegates tasks to individuals best suited and skilled to complete them. Adjust project schedule and goals as needs and external factors relating to the project change. |
| Planning and Tracking Lead | Compare the progress of the project to the projected project timeline. Work with the project manager to adjust the project schedule if needed. Make estimations on how long each task is supposed to take. |
| Requirements Lead | Develop top level requirements for the project and individual requirements for the individual tasks. Submit the requirement definition assignment document upon completion. Adjust requirements based on time and feasibility as project progresses. |
| Design Lead | Develop the master design for the web application. Communicate the design to each team member so that the team has unified vision. Adjust initial design plan as needed taking into individual/consumer feedback and time constraints. |
| Implimentation Lead | Ensure that the application being developed is satisfying the requirements set. Hold code reviews with the team to make sure all members know how each aspect of the project works. Make sure that all code is being documented, commented, and developed in the most efficient way possible. |
| Quality Assurance Lead | Develop test cases to ensure the functionality of the developed code. Ensure the teams is using the best industry-acceptable practices. Make sure that the team is meeting expectations and deadlines. |

#### Communication
For the duration of the project, the team will meet weekly Sundays at 2pm to discuss the progress for the week, code reviews, timeline changes, errors, etc. This formal weekly meeting will be either in-person (meet at CULC) or virtual (discord call) depending on the team’s availability for that week. Towards the end of the project, the team will be meeting twice a week with the second meeting time to be scheduled later.

Informal communication will take place through our teams Discord channel. The channel will be used for reminders, quick questions, clarifications, etc. For communicating with a single team member, it is up to the individuals how they will want to contact each other and set up meeting times.

For formal weekly meetings, meeting minutes will be taken and a master document with all the meeting summaries will be available to all team members. For informal meetings, a quick update will be given about the informal meeting at that week’s formal meeting and will be documented then.


### Risk Management

#### Risk Identification
| Risk | Probability | Severity | Description |
| ------ | :-----: | :-----: | ------ |
| Individual Schedules | HIGH | HIGH | Team members each have different schedules which might conflict with project deadlines |
| Communication Issues | MEDIUM | HIGH | Team might have communication issues regarding the scope of each individual’s work |
| Learning Curves (Ramp Up Periods) | HIGH | LOW | Each member of the team will need to ramp up with the specified platforms for the project (i.e. SpringBoot, Maven, etc) |
| Poor Code Quality | MEDIUM | HIGH | Each individual might have different coding standards which might lead to poor documentation and errors when code is taken over by another member |
| Unpredictable Circumstances | LOW | LOW | Extenuating family circumstances, medical emergencies, and other incidents may occur which will cause the workload to be distributed to other members of the project |

#### Mitigation Plan
1. Individual Schedules
   - Maintain a calendar with each individual’s assignments for the semesters and plan ahead for conflicts with project deadlines
   - Open communication through team discord channel in the case that a member needs to push back work for other priorities
2. Communication Issues
   - Team will meet on weekly basis where each member will give an update on their progress for the week along with next steps
   - Meetings will be primarily set to weekly, but will change to bi-weekly as needed towards the project deadline
   - Meet in smaller groups with individuals whose scope of the project overlaps to discuss integration
3. Learning Curves
   - Require each individual to have the necessary software/platforms installed within the first two weeks
   - Require each individual to go through mini tutorials and be able to navigate the software/platforms within the first two weeks
   - Discuss difficulties or technical issues during first couple of weekly meetings
4. Poor Code Quality
   - Each weekly meeting where individual displays their progress will be followed by a code review with the team
   - Generate a flow for the web application logic so that all members of the team have the same end goal in mind
   - Decide on a set of coding standards to follow until the completion of the project
5. Unpredictable Circumstances
   - Handled on a case-by-case basis
   - Help out the individual by distributing his work to the rest of team
   - Meet with that individual later to make sure progress made by the rest of the team is integrable with the individual’s work


### Planning and Control

#### Milestones
1. Project Planning and Approval
2. Software Installation and Basic Tutorials
3. Project Requirements Definitions
4. Project Task Breakdown
5. Evolution 0: Basic Project Functionality
6. Evolution 1: GT Verification for Registration
7. Evolution 2: Adding Image Upload Functionality
8. Evolution 3: Adding Filter Search Feature
9. Evolution 4: Edit/Delete Item Functionality
10. Evolution 5: Email Functionality
11. Evolution 6: Integration and Testing
12. Project Requirements/Goals Review
13. Project Completion/Presentation

#### Schedule
![INSERT GANTT CHART](https://user-images.githubusercontent.com/62609528/143985976-d40fb12f-a316-4970-9016-72f805c090c6.PNG)
The above Gantt chart outlines our schedule for project 2 and the intended start and end dates for the each of the milestones we developed.

#### Tracking and Control
Project schedule will be tracked weekly during our formal meetings. During these meetings, each team member will give a progress report on their accomplishments/setbacks for the week. From the report, the team will decide to accelerate or delay the project schedule accordingly.

To measure the quality and functionality of the project, the formal meetings will also include code reviews for each individual where each team member will explain their code. For quality, the team as a whole will make sure the code written by each individual is documented, commented, and efficient.

Each team member is expected to track the number of hours the expect to perform on each task. Each individual will report this at the weekly team meeting and the group will then decide if they will need to allocate more resources (manpower) to a task or not. 


### Technologies to be Used
- Google Cloud Platform
- AWS S3 Bucket
- Backend
  - Spring Boot
  - Maven
  - IntelliJ
- Frontend
  - HTML/CSS
  - Thymelead
- Database
  - Google DataStore


### User Requirements

#### Software Interfaces
1. Apache Maven								
   - Maven									
   - Version 3.8.2									
   - This system must use Maven which is a POM based project management tool. System will communicate its dependencies to Maven, which will be managed by the external software.
2. Spring Boot								
   - Version 2.5.5									
   - This system must use Spring Boot to run the application. System will communicate when it needs to build the application, and software will create that application during runtime.
3. Google Cloud Platform Datastore (Only Required Software)		
   - GCP Datastore								
   - This system must just use GCP Datastore for its database component. Communication occurs through either HTTPS or Google Cloud Interconnect & VPN. Data that will be transmitted by the system must be in the proper format of the table data structures in GCP Datastore.

#### User Interfaces
The main interface between the software product and the users will be a GUI, which will ultimately be a webpage with textboxes, checkboxes, buttons, display tables, and forms for users to fill out. The textboxes and checkboxes will be primarily for user inputs where users will specify the fields such as item title, cost, description, and category. In addition there will also be an image upload field, which will be optional. Buttons will be utilized for committing changes such as adding a new item, editing an existing item, or deleting an existing item. Additionally, the same UI elements will be used for the filter search portion of the project. The UI elements will have the same fields but different layout. As this is a web page, the main way that the user will physically communicate with the system will be through the standard keyboard and mouse setup.

#### Product Functions
- GT Marketplace will enable its users to create new ite posts with the following fields: title, description, cost, category, and an optional image upload. Once created, these items will be able to be viewed by all users on the GT Marketplace home page.
- GT Marketplace will allow its users to view all of the item posts they made in a my posts tab on the application. In this my posts tab, the users will have the option and ability to edit or delete any of their existing posts. Once edited or deleted, the changes will be reflected on the home page and the my posts page.
- GT Marketplace will only allow Georgia Tech students to register and utilize the applications services. When registering a new user, the user must enter a valid GTID and Georgia Tech email for successful registration.
- GT Marketplace will have a filter search feature which will allow any user to search for specific items from all of the item posts. The filter options will include the following: item name, item cost, item category, item min and max cost.
- GT Marketplace will have a messages page that a user can use to send an email to another user. The messages page takes in a username and email message body, and then sends the email to the intended user.

#### User Characteristics
- The intended users of this product are specifically Georgia Tech students, however the knowledge and expertise they must possess to operate the webpage will not be higher than that of general internet users. For convenience, the goal of the GT Marketplace UI design is to mimic that of existing marketplaces such as the Facebook Marketplace since general internet users would already know how to navigate in that environment. Moreover, the structure of the webpage is organized and well-labeled so that general internet users can understand what each component of the webpage does intuitively. 

#### Assumptions and Dependencies
- One assumption is that users will be utilizing one of the later web browsers versions when running the web application. If they are not, of one of the dependencies is that if they are running a much older version such as Internet Explorer 1, the intricate frontend features such as an interactive map may not be compatible.
- Another assumption is that users have Java 8, or a later version installed to be able to run the undeployed version of the LSW as a Spring Boot application. If not, the LSW will have to deployed to be hosted locally or through external services such as deployment through containers, or through Amazon Web Services or Azure.
- Apportioning of Requirements
    1. Evolution 0: Basic Project Functionality
    2. Evolution 1: GT Verification for Registration
    3. Evolution 2: Adding Image Upload Functionality
    4. Evolution 3: Adding Filter Search Feature
    5. Evolution 4: Edit/Delete Item Functionality
    6. Evolution 5: Email Functionality
    7. Evolution 6: Integration and Testing


### Project Layout
![Project 3 Flowchart drawio](https://user-images.githubusercontent.com/35010922/143979467-52e7b0f5-1272-40eb-92ab-cb8b89d6d3b7.png)

Illustrated above is a flow chart of the application layout. Each page is represented by a box and actions/conditions are represented by arrows.


###  Quality Control

#### Test Plan Quality
We will ensure that tests are comprehensive by coming up with all possible solutions. We will be sure to add multiple tests for the same feature that test in different ways so that we can be absolutely sure there are no bugs, or as few bugs as possible. 

#### Adequacy Criterion
We created all of our tests before we actually begin the testing phase. After we finish those, we will begin fixing the bugs we find. As we fix the bugs, we create new tests if our changes are substantial enough for that to be necessary. We continued testing until we are passing.

#### Bug Tracking
We utilize a Google Sheets file that we all have access to via Google Drive to track bugs and enhancement requests. There will be a column for name, description, source, status, person assigned to, and resolution. When we created new entries, we will always filled out every column so that our group members have as much information as possible.


### Test Strategy

#### Testing Process
We wrote unit tests first to make sure every function works as expected. Once each module is verified to be functional on its own, we continued to integrate testing by writing more tests that verify the interaction between modules functions as expected.
- Roles
  - Unit Testing: Caden, Dilip, Thien
  - Integration Testing: Drew, Alex 

#### Technology
We started utilzing the JUnit framework for unit testing and MockMvc for UI testing. However, towards the end, we relied more on manual testing for functionality and UI.

#### Manual Tests
Below are some of the manual test performed:
- Registration 
  - Checked if email field of registration page ended in "@gatech.edu"
  - Checked if GTID field of registration page started with "903" and has 9 digits
- Adding/Deleting/Editing Post Functionality
  - Added single title field to determine if inventoryItem was posted into the repository and displayed on the Home Page and the My Post Page
  - Performed editing and deleting on items while printing the full inventory repository is printed to the console on each action
- Filter Search
  - Each addition of inventoryItem field was tested and sorted on respective characteristics to see if the correct data was read from the object
- Email Functionality
  - Hard coded default email recipient to ensure proper delivery of email
  - Changed hard coded recipient to be th einput of text box entry


### Team Contribution
* Alex: 
  * Datastore and S3 Backend 
  * Image Upload
  * Misc. UI
* Andrew: 
  * Frontend Development 
  * Homepage UI
* Dilip: 
  * Backend Development 
  * Filter Search
  * Edit/Delete Post
  * Email Functionality
* Thien: 
  * Backend Development 
  * Email Functionality
  * Chatroom Functionality
* Caden: 
  * Overall UI
  * Login
  * Posts
  * Homepage

[Test Link](testing.md)
