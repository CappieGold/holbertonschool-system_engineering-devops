# Web infrastructure design

## Learning Objectives

At the end of this project, you are expected to be able to `explain to anyone`, without the help of Google:
- You must be able to draw a diagram covering the web stack you built with the sysadmin/devops track projects
- You must be able to explain what each component is doing
- You must be able to explain system redundancy
- Know all the mentioned acronyms: LAMP, SPOF, QPS

### Drawing a Web Stack Diagram
- `LAMP (Linux, Apache, MySQL, PHP/Python/Perl)`: This classic stack represents a Linux server running the Apache web server, the MySQL database, and scripting in PHP, Python, or Perl.
- `Diagram`: You can represent this in layers, with Linux at the bottom (operating system), followed by Apache (web server), MySQL (database), and PHP/Python/Perl (backend processing).

### Explaining Each Component
- `Linux`: The operating system that manages hardware resources.
- `Apache`: The web server that processes HTTP requests and serves web files.
- `MySQL`: The database management system that stores and manages data.
- `PHP/Python/Perl`: Scripting languages used to write business logic and interact with the database.

### System Redundancy
- Redundancy is the process of duplicating critical system elements to increase reliability.
- This includes backup servers, replicated databases, etc.
- The goal is to prevent a Single Point of Failure (SPOF).

### Acronyms
- `LAMP`: As mentioned above, it's a set of open-source software used to develop websites or servers.
- `SPOF (Single Point Of Failure)`: A point in a system where the failure of that point can lead to the failure of the entire system.
- `QPS (Queries Per Second)`: A performance measure that indicates the number of queries a system can handle in a second.

## Requirements

- A `README.md` file, at the root of the folder of the project, is mandatory
- For each task, once you are done whiteboarding (on a whiteboard, piece of paper or software or your choice), take a picture/screenshot of your diagram
- This project will be manually reviewed:
- As each task is completed, the name of that task will turn green
- Upload a screenshot, showing that you completed the required levels, to any image hosting service (I personally use `imgur` but feel free to use anything you want).
- For the following tasks, insert the link from of your screenshot into the answer file
- After pushing your answer file to GitHub, insert the GitHub file link into the URL box
- You will also have to whiteboard each task in front of a mentor, staff or student - no computer or notes will be allowed during the whiteboarding session
- Focus on what you are being asked:
- Cover what the requirements mention, we will explore details in a later project
- Keep in mind that you will have 30 minutes to perform the exercise, you will get points for what is asked in requirements
- Similarly in a job interview, you should answer what the interviewer asked for, be careful about being too verbose - always ask the interviewer if going into details is necessary - speaking too much can play against you
- In this project, again, avoid going in details if not asked
