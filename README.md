# erasmus-sds
Application that allows erasmus students to easily fill out their learning agreement using data provided by themselves, as well as pre-programed information regarding the courses and faculties at Politechnika Poznanska. The project consists of a Web application, programmed in C# (more particularly .net core 2.2) and HTML/CSS, in an MVC pattern. All the information regarding the courses, learning agreements and faculty is stored in a SQLite database, stored within the project itself.

## Roles and Responsibilities
Describe the role and responsibilities of each member of the team here.

Iva Bacani (Product Owner) is responsible for:
 - Creating and defining Product Backlog items
 - Ordering the Product Backlog items
 - Explaining the Product Backlog items to the rest of the team

Hakan Duran (Scrum Master/Development team) is responsible for:
 - Schedule the Scrum meetings
 - Helping the team understand the Scrum framework, and what it entails
 - Provide support to the Development team with the creation of increments of "Done"

Dias Antayev and Tomas Taborda (Development Team) are responsible for:
 - Provide a potencially releasable Increment of "Done" at the end of the Sprint
 - Implementing the functionalities defined in the Sprint Backlog
 - Testing the created product


## Communication strategies
Communication through WhatsApp, as well as a meeting once a week at the university, during a convenient time for all team members.

## Instalation manual
In order to run our system, you need to have .net core 2.2 installed on your computer. If you dont already have it in your machine, it can be found in this link: https://dotnet.microsoft.com/download/dotnet-core/2.2

After this is instaled, you can download the zip file found in our master repository, and then unzip it.

When the file is unzipped, all you have to do is run the project! This can be done in two different ways:

  - If you have Visual Studio 2019 installed in your computer, you can simply open the "SDSErasmusPlatform.sln" file, and then run the "LearningAgreementServer project through Visual Studio.
  - You can also use a terminal/command line to run the project! In order to do this, you need only to move to the directory of the project (SDSErasmusPlatform/LearningAgreementServer/) and execute the command "dotnet run". If everything went according to plan, the server will then be up and running, and you can access it using the url "https://localhost:5000/" or "https://localhost:5001/". 
  
The application has been tested to be compatible with Google Chrome (Version 74.0.3729.169) and Mozilla Firefox (Version 67.0). It may, however, be functional in other versions of these browsers, or even in completely different browsers.
  
After this, you can begin the creation of your learning agreement using our intuitive form.
Good luck in your studies!!!

## Development Work done so far
Below will be a list of the software functionalities, divided by team member worked in their development.

Dias Antayev:
 - Creation of the html version of the learning agreement layout.

Hakan Duran:
 - Creation of the design and color-scheme of the Application.

Tomás Taborda:
 - Creating the database with a table for Courses, one for Faculties, one for Comments and another for already filled out Learning Agreements (and corresponding Models);
 - Filling the database with Courses and Faculties of Politechnika Poznanska;
 - Creating the base MVC structure;
 - Creation of the several views, controllers and forms used to receive the information of the user (as well as the baskets and mechanisms used to select the courses for the learning agreement), both for incoming and outgoing students;
 - Integration of the html version of the learning agreement layout (filling the fields with the inputs provided by the user);
 - Creation of the "How to use" view and controller;
 - Creation of the Comment-related views and controllers ("CourseList" and "Comments");
 - General testing of the application and its functionalities;
 - Added views and controllers allowing saving and loading of filled learning agreements to database, using a seed-based system. 
