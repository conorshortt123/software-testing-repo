# Test Plan

## The Pixel Wizard

**Prepared by:**</br>
**Conor Shortt**

12/05/2020

## TABLE OF CONTENTS
 **1.0** INTRODUCTION</br>
 **2.0** OBJECTIVES AND TASKS</br>
 **2.1** Objectives</br>
 **2.2** Tasks</br>
 **3.0** SCOPE</br>
 **4.0** Testing Strategy</br>
 **4.1** Unit Testing</br>
 **4.2** System and Integration Testing</br>
 **4.3** Performance and Stress Testing</br>
 **4.4** User Acceptance Testing</br>
 **4.5** Batch Testing</br>
 **4.6** Automated Regression Testing</br>
 **4.7** Beta Testing</br>
 **5.0** Test Schedule</br>
 **6.0** Control Procedures</br>
 **7.0** Features to Be Tested </br>
 **8.0** Features Not to Be Tested</br>
 **9.0** Resources/Roles & Responsibilities</br>
 **10.0** Schedules</br>
 **11.0** Risks/Assumptions</br>
 **12.0** Tools</br>

## 1.0 INTRODUCTION
This test plan describes the testing approach that we will take to drive the testing of the 2D side-scrolling platformer, "The Pixel Wizard". Inspired by the likes of ‘Salt and Sanctuary’,
‘Shovel Knight’, and ‘Fancy Pants’, with elements from ‘Skyrim’ (mainly in the way the
player character and enemy characters attack). The artwork will be inspired mainly by Shovel
Knight, which uses mainly pixel art to create its characters and world. The gameplay will be
inspired by ‘Salt and Sanctuary’ and ‘Dark Souls’ and ‘Skyrim’, which will see the player
navigate progressively difficult levels with a wizard type character that uses magic as in
‘Skyrim’. Each level will have several enemies that the player must defeat to progress. Each
level will also have a boss that the player must defeat to progress to the next level. Each level
will contain pickups for the player, such as health pickups to replenish the player’s health. This document includes multiple headings:

**Objectives and Tasks:**

Describe objectives supported by the test plan, such as defining tasks and responsibilities, communication medium, document to be used as a service level agreement, etc.

**Testing strategy:**

There will be multiple testing strategies used such as Unit testing, system and integration testing, performance and stress testing, user acceptance testing, batch testing, automated regression testing, and beta testing.

**Test schedule:**

A test schedule is contained in this document that lays out a timeline, for the tests that will be carried out, the team that should be carrying out the test, start date and deadline date.

**Control procedures:**

The procedures to be followed when an incident is encountered is outlined in the "Problem Reporting Document". Problems should be documented in a separate document called "Appendix".

When making modifications to the software the "Change Request Document" should be used.

**Features to be tested:**

All software features and combinations of software features that will be tested will be outlined here. Such as user interface, control schemes, game mechanics, etc.

**Features not to be tested:**

All software features and combinations of software features that won't be tested and the reasons for not testing them will be outlined here.

## 2.0 OBJECTIVES AND TASKS

### 2.1 Objectives

The objective of the test plan is to verify that the functionality of "The Pixel Wizard" works according to the specifications.

The test will execute and verify the test scripts, identify, fix and retest all high and medium severity defects per the entrance criteria, prioritize lower severity defects for future fixing via CR.

The final product of the test is twofold:</br>

A production ready game;</br>
A set of stable scripts that can be reused for UAT and unit testing.

### 2.2 Tasks

*There will be multiple tasks involved in this test plan, including:*

**Testing** - All the tests to be carried out. There will be seven testing methodologies to be carried out as part of making a production ready game. These tests are unit testing, system and integration testing, performance and stress testing, user acceptance testing, batch testing, automated regression testing, and beta testing.

**Post-Testing** - Tasks will be carried out after testing, any bugs or glitches reported in the Problem Reporting Document will be fixed by the developers and changes in the Change Request will be made.

## 3.0 SCOPE

**General**</br>
There are multiple components in this project that should be tested:

**Front-End**

The front end of the game is the collective interfaces that the user must navigate through to begin the game. The main menu will be tested first, "Play Game", "Settings", "Load Game", "Delete Game", and "Exit Game" should all be tested individually.

**Control Mechanisms**

Control mechanisms should also be tested. Each individual control as well as combinations of multiple controls in multiple scenarios should be tested.

**Tactics**

<!--List here how you will accomplish the items that you have listed in the "Scope" section. For
example, if you have mentioned that you will be testing the existing interfaces, what would be the
procedures you would follow to notify the key people to represent their respective areas, as well as
allotting time in their schedule for assisting you in accomplishing your activity?-->

To accomplish the general tests I have highlighted in scope, I will assemble a team of testers and create a schedule so that each test is done incrementally. To assemble my team I would first email each respective member with a link to a Microsoft teams call, were we will thoroughly discuss and write up a schedule for each member of the team.

## 4.0 TESTING STRATEGY

<!--Describe the overall approach to testing. For each major group of features or feature combinations,
specify the approach which will ensure that these feature groups are adequately tested. Specify the
major activities, techniques, and tools which are used to test the designated groups of features.
The approach should be described in sufficient detail to permit identification of the major testing
tasks and estimation of the time required to do each one.-->

The tests will execute and verify the test scripts, identify, fix and retest all high and medium severity defects per the entrance criteria, prioritize lower severity defects for future fixing.

There are multiple methods of testing that will be used. Each method will have it's own team of testers who will develop a Test Plan, which they will prepare, review, rework until it is adequate. A set of test cases/scripts will also be developed, and then the test method will be executed.

All features will be tested individually using Unit Testing, Unit Testing is a level of software testing where individual units/ components of a software are tested. The test team will be allotted 3 days to write up their unit tests.

A feature that will be tested using System Integration Testing (SIT) is all of the interfaces of the game as a whole. The test team will be allotted 2 days to execute these tests.

Performance testing will be used to determine how well the game runs, using metrics such as response time, fps (frames per second), if the application uses the minimum amount of resources necessary to run, etc. The test team will be allotted 4 days to execute these tests.

Stress testing will be used to put the game under a high load and determine how it performs when pushed to it's limit. Stress testing usually maxes out the CPU and/or GPU to determine the upper limits of capability. The test team will be allotted 1 day to execute these tests.

User acceptance testing will be used to determine if the game is accepted by the customer as a valid piece of software. UAT is probably the most essential method of testing, as they are the people who will use the software on a daily basis. The game will be verified by a team of users to make sure it can handle required tasks in real-world scenarios, according to specifications. The users that are testing the game will be allotted 1 week to thoroughly test each feature.

Automated regression testing will be used to test a component of the software that has been changed, along with all it's dependencies.

Beta testing will be utilized to release the game to the public. Beta Testing of a product is performed by "real users" of the software application in a "real environment".

### 4.1 Unit Testing

**Definition:**

UNIT TESTING is a level of software testing where individual units/ components of a software are tested. The purpose is to validate that each unit of the software performs as designed. A unit is the smallest testable part of any software. It usually has one or a few inputs and usually a single output. Each function or class should be tested individually, and tests will be written for each. Each statement will be executed at least once.

**Participants:**

&emsp;**Department:** Game Developers

&emsp;**Team:** Conor Shortt, Blaine Burke, Aaron Moran

**Methodology:**

Each unit of the game will be tested, this includes all UI function such as the menu, options menu, volume control, etc. The in-game mechanics and features will also be tested, this includes the health bar, character controls, enemy mechanics, pickups, bosses etc.

Conor Shortt: Testing menu screen interface, including play game, settings, load game, delete game, exit game
Aaron Moran: Testing player control scheme, and player mechanics.</br>
Blaine Burke: Testing enemy behavior, enemy health, health pickups.

### 4.2 System and Integration Testing

**Definition:**

System Integration Testing is defined as a type of software testing carried out in an integrated hardware and software environment to verify the behavior of the complete system. It is testing conducted on a complete, integrated system to evaluate the system's compliance with its specified requirement. All modules of the game should be completely integrated in advance of doing this testing.

**Participants:**

&emsp;**Department:** Game Developers

&emsp;**Team:** Mary Brown, John Trayers, James McDuff

**Methodology:**

The game will be tested as a whole with this testing method.

All team members will write scripts for the integrated test.

### 4.3 Performance and Stress Testing

Performance testing will be used to determine how well the game runs, using metrics such as response time, fps (frames per second), if the application uses the minimum amount of resources necessary to run, etc. Stress testing will be used to put the game under a high load and determine how it performs when pushed to it's limit. Stress testing usually maxes out the CPU and/or GPU to determine the upper limits of capability.

**Participants:**

&emsp;**Department:** Game Developers

&emsp;**Team:** Patrick Bateman, Lex Luthor, Johnny John

**Methodology:**

To test performance, different systems with varying hardware specifications will be used to test how well the game runs in different areas. Such as load times, frames per second, input lag, etc.

To stress test the game, it will be put under load by instantiating 100 - 1000 enemies to see how well the game runs under immense load.

Patrick and Lex will execute performance testing as it will have to be done on multiple systems, and Johnny will execute stress testing as it relatively fast.

### 4.4 User Acceptance Testing

The game will be verified by a team of users to make sure it can handle required tasks in real-world scenarios, according to specifications.

User acceptance testing will be used to determine if the game is accepted by the customer as a valid piece of software. UAT is probably the most essential method of testing, as they are the people who will use the software on a daily basis.

**Participants:**

&emsp;**Department:** Testers

&emsp;**Team:** Mike Quinn, Darragh Watts, Laura Charles

**Methodology:**

A set of test steps, execution conditions and expected results developed for a each area of the game, such as to exercise a particular program path or to verify compliance with a specific requirement. Each user gives feedback which is compiled into a document, and then analyzed later.

### 4.5 Automated Regression Testing

<!--Definition:
Regression testing is the selective retesting of a system or component to verify that modifications
have not caused unintended effects and that the system or component still works as specified in the
requirements.-->

Regression testing is the selective retesting of a system or component to verify that modifications
have not caused unintended effects and that the system or component still works as specified in the
requirements

**Participants:**

&emsp;**Department:** Developers and Testers

&emsp;**Team:** Tom Barry, Terry Cruise, Joshua Baker

**Methodology:**

Each member of the team will be assigned a different component/module that has been modified. The automated tests will be run. If the output is not accepted by the tester then the developers will begin fixing any bugs/issues.

### 4.6 Beta Testing Participants:

Beta Testing of a product is performed by "real users" of the software application in a "real environment" and can be considered as a form of external User Acceptance Testing.

Beta version of the software is released to a limited number of end-users of the product to obtain feedback on the product quality. Beta testing reduces product failure risks and provides increased quality of the product through customer validation.

It is the final test before shipping a product to the customers. Direct feedback from customers is a major advantage of Beta Testing. This testing helps to tests the product in customer's environment.

**Participants:**

&emsp;**Department:** End users (customers)

&emsp;**Team:** Tim Jones, Bobby Brown, Charlie Chaplin

**Methodology:**

The beta testing will run for a few weeks. Data is gathered by each member of the team and most of the issues or feedback is collected from Beta testing will be implemented in future versions of the product. Beta testing also concentrates on the quality of the product, but gathers users input on the product and ensures that the product is ready for real time users.  

## 5.0 TEST SCHEDULE

<!--Include test milestones identified in the Software Project Schedule as well as all item transmittal
events.
Define any additional test milestones needed. Estimate the time required to do each testing task.
Specify the schedule for each testing task and test milestone. For each testing resource (that is,
facilities, tools, and staff), specify its periods of use.-->

**Milestones:**

&emsp;**Week One**
* Write up test plan, test cases, and execute unit testing. (Duration 5 days total)
* System integration testing will be completed in 3 days.
* **Resources and Facilities:** Three team members, two allocated to unit tests, one to system integration. Team members also require laptops/pcs to perform tests.

&emsp;**Week Two**
* Write up test plan, test cases, and execute performance testing. (Duration 3 days total)
* Stress testing should take no more than two days to execute and compile results.
* **Resources and Facilities:** Three team members, two allocated to performance tests, one to stress testing. Team members also require laptops/pcs to perform tests.

&emsp;**Week Three**
* Begin user acceptance testing. (Duration 5 days)
* Analyze changes made to software and begin automated regression testing. (Duration 3 days)
* **Resources and Facilities:** Three team members, two allocated to UAT tests, and one to automated regression testing. Team members and users also require laptops/pcs to perform tests. Tests will be performed on company grounds.

&emsp;**Week Four and Five**
* Begin beta testing (Duration two weeks)
* Multiple customers will be given access to beta test the game. Their feedback and data is collected.
* **Resources and Facilities:** Multiple team members, to collect all data and feedback and also to help users if they have any problems.

## 6.0 CONTROL PROCEDURES

Problem Reporting

An incident logging procedure is applied when a problem is reported. The tester fills in a "Problem Report Document", which is then collected and stored on a database. When the particular testing is done, the documents are analyzed by developers and they can then begin resolving issues.

Change Requests

If a change is to be made, a "Change Request Form" is to be filled out and submitted. The lead tester will review and potentially sign off on the changes. To make a change to the game it must keep with the general theme. If the change affects another aspect of the game, this aspect must be highlighted in the form.

## 7.0 FEATURES TO BE TESTED

* Menu Interface
* Options Interface
* In-Game UI
* In-Game mechanics. (physics, control scheme, etc)
* Enemy behavior


## 8.0 RESOURCES/ROLES & RESPONSIBILITIES

**Management:**

&emsp;**Lead Developers:**</br>
&emsp;&emsp;Conor Shortt (Dev) oversee test case compilation for Unit Testing</br>
&emsp;&emsp;Bobby Lee (Dev) oversee test case compilation for Integration Testing</br>
&emsp;&emsp;Tim Jones (Dev) oversee test case compilation for Performance and Stress Testing</br>
&emsp;&emsp;Mary Brown (Dev) oversee test case compilation for User Acceptance Testing</br>
&emsp;&emsp;John Murphy (Dev) oversee test case compilation for Automated Regression Testing</br>
&emsp;&emsp;Dave Doherty (Dev) oversee distribution of beta version of software for Beta Testing</br>

&emsp;**Operations Staff:**</br>
&emsp;&emsp;Maria Smith (Lead Operations Director) organize and acquire testing facilities and tools.</br>

**Users:**

&emsp;**User Acceptance Testers:**</br>
&emsp;&emsp;Mary Brown (User) compile Test Cases for Acceptance Testing</br>
&emsp;&emsp;John Jones (User) compile Test Cases for Acceptance Testing</br>
&emsp;&emsp;Timmy Smith (User) compile Test Cases for Acceptance Testing</br>

&emsp;**Beta Testers:**</br>
&emsp;&emsp;All end users who test the game and provide feedback.</br>


## 9.0 SCHEDULES

For each testing cycle, a strict regime of deliverable documents must be followed. These documents include:

- Test Plan
- Test Cases
- Test Incident Reports
- Test Summary Reports

For any change requests the following documents must also be delivered:

- Change request form

## 10.0 RISKS/ASSUMPTIONS

High risk assumptions are allocated time per testing cycle, for example system integration testing may be difficult to complete in 3 days and may require a delayed delivery, or if necessary increased nights shift/overtime to deliver the product for the required date.

## 11.0 TOOLS

