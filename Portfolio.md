# Learning Outcomes

#### <ins> Learning Outcome 1 </ins>

####  Web Application: You design and build user-friendly, full-stack web applications. 

User friendly You apply basic User experience testing and development techniques. 
Full-stack You design and build a full stack application using commonly accepted front end (JavaScript-based framework) and back end techniques (e.g., Object Relational Mapping) choosing and implementing relevant communication protocols and addressing asynchronous communication issues.

#### What does this learning outcome mean?

For this learning outcome i need to make a full-stack application. Which means on the end of this semester i need to have a website where i did put my requirments in and a website that uses  a front and back-end language.

[Outcome 1](https://fhict.instructure.com/courses/12096/pages/ui-design-is-your-application-user-friendly)

[Outcome 1](https://fhict.instructure.com/courses/12096/pages/testing-how-to-test-in-agile-projects) 

[Outcome 1](https://fhict.instructure.com/courses/12096/pages/software-development)

#### What do i need to do?

- [x] I need to use Javascript for making my frontend. In JS i will use the framework React. I did research about React and explained why i will use React. You can find the research in this document [Research](https://github.com/ZakariaICT/CryptoTracker/blob/main/Research.md).
- [x] I need to use back-end techniques. For the backend I am using JAVA and within JAVA a framework called Springboot. For the explanation you can go to [Research](https://github.com/ZakariaICT/CryptoTracker/blob/main/Research.md). I also need to implement ORM techniques. ORM means converting data between a language and a database in my case. I will use MSSQL as my database. Because JAVA is an OOP language i can easily implement ORM in my code. Actually i already did implement this. I am creating Tables Automatically via my code.  
- [x] Also i need to use asynchronous communication in my application. This means that a user provides imformation and after this gets information back.
- I will get feedback from other people on my website to create the best user experience as possible.
- [x] Implement CRUD in my application.
- Use Websockets.

#### What have i done for this learning outcome?

##### Sprints

###### Frontend

I made a frontend homepage for my project. I am making a Crypto tracker project. On my website you can find all Crypto coins and the information about them. This is the first page you will see when visiting my website.

[Example](https://github.com/ZakariaICT/CryptoTracker/blob/main/Pictures.md)

When clicking on a coin you will see information about the coin and the decreases or increases the coin made in a specific amount of time. This is an explanation.

[Example](https://github.com/ZakariaICT/CryptoTracker/blob/main/Pictures.md)


###### ORM


So i made a Customer class in my Springboot project. In this class i am creating a table for my database with columns in it. This will create a table in the database automatically.

[Example](https://github.com/ZakariaICT/CryptoTracker/blob/main/Pictures.md)


###### What did i use?

To get the frontend like this i used JS and CSS files. I also used a bit of HTML code in my JS files to style my tables etc. 

###### API

To get all the coins and all information about the coins i used an API. This is an API from coingecko. So what I did is I got all data via an url of coingecko. Because i use this url i can fetch all data from this API. so after getting all data i picked everything i need from the API and placed this on a good spot in my HTML code. This is the information you can see on my homepage.

###### CRUD

I implemented a create function in my code. Customer can now create an acocunt on my website which will ben saved in my database. My code is made up like this:
Backend
- I made a few classes. An AccountController, Account class, AccountRepository and AccountService classes. I use all these classes for this function. in my Account class i create a table for in my database on the ORM way. So the table will be created automatically. Furthermore i made an add function in my accountController class so that i can send data from my website. 
Frontend
- I made a registration class and created a view for on my website with textboxes and labels. In this class i use my Rest API that i have made in my backend. this looks like this: "http://localhost:8080/account/add". Because of this link i can add info to the database via my backend.
- I made a delete function, a update function and a read function which works. I can now delete an account in my frontend using a REST API. Also i can update and read all accounts ass wel. To update and delete i am using another method where i can get an account by ID so that i can delete and update only the account i want.



#### <ins> Learning Outcome 2 </ins>

#### Software equality: You use software tooling and methodology that continuously monitors and improve the software quality during software development.

Tooling and methodology Carry out, monitor and report on unit integration, regression and system tests, with attention for security and performance aspects, as well as applying static code analysis and code reviews.


#### What does this learning outcome mean?

TBA

[Outcome 2]()

#### What do i need to do for this learning outcome?

- Testing my API with Postman. (Wat kan er fout gaan bij de API?)
- DOT research to security.
- Unit Tests and Integration Tests.


#### What have i done for this learning outcome?

- I create Unit Tests for my CRUD operations. I made this in my springbootapplication. This looks like this: [UnitTest](https://github.com/ZakariaICT/CryptoTracker/blob/main/Pictures.md)


#### <ins> Learning Outcome 3 </ins>

#### You choose and implement the most suitable agile software development method for your software project.

Choose You are aware of the most popular agile methods and their underlying agile principles. Your choice of a method is motivated and based on well-defined selection criteria and context analyses.

#### What does this learning outcome mean?

For this learning outcome i need to work within my group on a Agile way. This is a way to manage a project while breaking it into several phases. The phases are: concept, inception, iteration, release, maintenance, and retirement. 

[Outcome 3](https://fhict.instructure.com/courses/12096/pages/project-management-agile-why-and-how) 

[Outcome 3](https://fhict.instructure.com/courses/12096/pages/project-management-how-to-plan-in-agile-projects) 

[Outcome 3](https://fhict.instructure.com/courses/12096/pages/project-management-agile-management-tools)

#### What do i need to do for this learning outcome?

- I need to work withn Agile methods within my group. I will be using the SCRUM methode for communicating and working in the group.
- I need to make an research on why we are using SCRUM as the method in AGILE.

#### What have i done for this learning outcome?

For our project we use the Scrum method. This is a method within Agile that is characterised by cycles or stages of developmeent. We do this in sprints. We use GitHub for our schedules but also for our code. We have different branches that we work in so that the main code wont be affected and can't go wrong. Each sprint we make a sprint schedules in the begin and also a burndown chart. We make sprint schedules in GitHub but the burndownchart is made in Trello. Each sprint we have a different scrum master. Our product backlog is made in Trello, in this backlog you can find all things that need to be done for our project. Every day we start with a stand up where we discuss what we will do that day and what we want to have done.

[Product Backlog](https://trello.com/b/9dGssG81/netmatch-sprint-3-%F0%9F%94%A5-19-04-22-12-05-22)

[Sprint Backlog/Schedule](https://github.com/AnwarIbrahimi/Netmatch/projects/3)

# BurndownChart sprint 3

![chrome_s6fBrBAlNT](https://user-images.githubusercontent.com/99720725/163978383-a148ae9a-0048-47e4-823a-564b3f497e4b.png)

#### From Github to Trello

We went from Github to Trello in the middle of our project. We needed to make a burndown chart for our project because we use SCRUM in Agile. We went to do some research on how to make a burndown chart and what applications we could use to make this. We ended up with a website where we could make something like a burndown chart. After a while we came to the conclusion that this wasn't going to work for our project.

After this we talked with our Stakeholder and he gave us some advise. He said that we could ask the other group for help. So we asked the other group how they made a burndown chart. They made it in Trello, this was much easier. So we also made it in Trello. 

If you make an burndownchart you need to make a sprintbacklog in Trello so we would leave our sprint backlog in GitHub. Because of this we could not use much helpfull skills of GitHub. I learned after this decision that GitHUb has a lot of usefull skills such as:

- We can't define bugs in our project to GitHub.
- We can't see what issues are solved and which are not.
- Other people can not learn from your bugs.
- Other people in the group can't learn for the solved issues.

So we left a lot of usefull stuff because we went to Trello.

##### What did we learn?

We learned that if you use GitHub on the right way it would be a lot easier to work with in the group and it will be much nicer. Also the project would be made in a smoother way. Trello has a lot of usefull stuff aswell but I didn't know about the things GitHub provides. If we use GitHub in a proper way we would't even had to discuss issues but we could only push these to GitHub as a bug and the other people int he group could solve this.



#### <ins> Learning Outcome 4 </ins> 

#### CI/ CD: You design and implement a (semi)automated software release process that matches the needs of the project context.

Design and implement You design a release process and implement a continuous integration and deployment solution (using e.g. Gitlab CI and Docker).


#### What does this learning outcome mean?

CI/CD stands for continuous integration and continuous delivery/continuous deployment. This automates your software deleviry proces. So in my case i use Github and Github already has an extension that i can use for my CI/CD implementation. What i understand of CI is that my code will build, test and analyse as soon as i push my code to git when making a yml file. Also it makes it easier to automatically test my code because otherwise i need to do this manually. CD is the continuous deleviry. Herby i will make a docker repository where i will push my code in and make an image from this. CD helps with checking if my code is compatible for other devices such as apple or samsung and not only for windows. 

[Outcome 4]()

#### What do i need to do for this learning outcome?

- I need to implement CI in my project. I will do this  with GitHub.
- I need to implement CD in my project. I will do this with Docker.
- Container runnen in docker 
- Frontend CI/CD

#### What have i done for this learning outcome?

##### Sprint 3 

Maven.YML File:

![idea64_m3nmnCZKDD](https://user-images.githubusercontent.com/99720725/163973833-6875d682-9347-4ce6-8260-dcd5f0c6f1f8.png)

I made a maven.yml file for my CI in github. With this every time i push my code to git the code will be checked by git and it runs tests for me automatically. These tests must be made by myself in my code.

Docker push image:

![idea64_cdOZgdhvCe](https://user-images.githubusercontent.com/99720725/163974039-97ea09b6-8256-403f-a14c-e7411039df1f.png)

Once my code has been build and checked then it will be pushed to docker to create an image. This happens automatically because of the code i wrote in the picture above. This is an example for 1 image. 


#### <ins> Learning Outcome 5 </ins>

#### You recognize and take into account cultural differences between project stakeholders and ethical aspects in software development.

Recognize Recognition is based on theoretically substantiated awareness of cultural differences and ethical aspects in software engineering. Take into account Adapt your communication, working, and behaviour styles to reflect project stakeholders from different cultures; Address one of the standard Programming Ethical Guidelines (e.g., ACM Code of Ethics and Professional Conduct) in your work.


#### What does this learning outcome mean?

TBA

[Outcome 5](https://fhict.instructure.com/courses/12096/pages/group-management-can-you-work-with-people-from-other-cultures)

#### What do i need to do for this learning outcome?

- I need to explain how i work with the people in my group and how i react or give feedback to them. Also how i react to stakeholders.

#### What have i done for this learning outcome?

I did a pesonal test about what i actually am according to a few questions. This is what came out of the test:

![Personal Test](https://user-images.githubusercontent.com/99720725/164413926-b73afb26-e9c6-41f8-8408-e51a1c89399d.png)

As you can see i am a introvert person. This is what i already thought i would be. I am no the type that starts a conversation in the group so soon but i prefer to wait and join the conversation.

#### Situation in the group

We were working on our project and at the end we still had to make a bit of work. So some of us stressed because we didnt have much time left. For example me i was a bit stressed because we cant come to the Stakeholder with a not done application. When this happened we all put in a lot of work. We worked together and made the project almost done. Anwar didn't stress much and took a bit of control in the group. Timo was like me a bit stressed and wanted to make this as soon as possible. Julian was relaxed and didn't worry much about it so we were not all on the same level.

#### Other Situation

We started this project with 5 people but ended with 4. This is because 1 in our group stopped because he doesn't think he can finish this semester with a S anymore.
When this happened we were a bit dissappointed cause he had a job on his own to make but now he has stopped he couldn't finish this anymore. Also unfortune for Bart that he can't finish this semester anymore. Our group reflected on this and we reacted well on this loss. We talked about it with our Stakeholder and we came to an agreement that if we have time left we would finish the task Bart had. We all reacted the same on this situation.


#### <ins> Learning Outcome 6 </ins>

#### You analyse (non-functional) requirements, elaborate (architectural) designs and validate them using multiple types of test techniques.

Multiple types of test techniques You apply user acceptance testing and stakeholder feedback to validate the quality of the requirements. You evaluate the quality of the design (e.g., by testing or prototyping) taking into account the formulated quality properties like security and performance.


#### What does this learning outcome mean?

For this learning outcome i need to make tests affter finising my code for by example a use case. Also i need to get feedback from my teachers.

[Outcome 6](https://fhict.instructure.com/courses/12096/pages/stakeholder-analysis-who-has-a-stake-in-the-project-and-in-the-software)

#### What do i need to do for this Learning Outcome?

- I need to make user acceptance tests.
- How do i go along with feedback of stakeholders?
- DOT research. Wat zou ik ermee kunnen doen?

#### What have i done for this learning outcome?

I created a c4 diagram for my application. You can find this in my architecture document.

[Architecture Document](https://github.com/ZakariaICT/BallTickets/blob/main/Architecture.md)

#### <ins> Learning Outcome 7 </ins>

#### You analyse and describe simple business processes that are related to your project.

Simple Involving stakeholders, predominantly sequential processes with one or two alternative paths. Related Business processes during which the software that you are developing will be used (business processes that the software must support by fully or partially automating them). Business processes needed for the success of your software.


#### What does this learning outcome mean?

For this learning outcome i need to work with my gorup mates. We need to work on our project in the way a business process goes. So we need to take steps in making the application the company asked for.

[Outcome 7](https://fhict.instructure.com/courses/12096/pages/process-analysis-which-processes-are-supported-by-your-software)

#### What do i need to do for this learning outcome?

- [x] Explain what the benefit is of my idea?
- [x] Create a research document with all the questions asked in Canvas.
- [x] Use swimming lanes. Activity Diagrams

#### What have i done for this learning outcome?

##### My Idea

So for my application i am making a Crypto website where you could see different Crypto currencies such as Bitcoin and Ethereum. Of course you can see the price and all but also you can see information about the coin and how much it has increased or dipped. I made this because i myself hold Crpyto so I already had knowledge about it. What i see on each Broker (these are websites/apps that offer crypto) is that there is too much information on the website or the app and it isn't easy to go to the thing you want to see. On my website you can see the coin and if you click on it you also can see information about the coin. These coins are also filtered on popularity. My websites makes it easy for people to look at coins if they are for example in a hurry but also it makes it more clearer. 


[Questions from Canvas](https://github.com/ZakariaICT/CryptoTracker/blob/main/QuestionsLO.md)

#### <ins> Learning Outcome 8 </ins>

#### Professional: You act in a professional manner during software development and learning.

Professional manner You actively ask and apply feedback from stakeholders and advise them on the most optimal technical and design (architectural) solutions. You choose and substantiate solutions for a given problem.


#### What does this learning outcome mean?

For this learning outcome i need to ask feedback to my stakeholders and also use these feedback and implement this in my project. I myself need to come with solutions on problems in my project but the stakeholders could help a little bit.

[Outcome 8](https://fhict.instructure.com/courses/12096/pages/integrating-research-in-your-project)

#### What do i need to do for this learning outcome?

- [x] Ask and apply feedback from stakeholders.
- What did go well this semester and wwhat didn't?

#### What have i done for this learning outcome?

##### Feedpulse

I often get feedback from my teachers. I could get more feedback but i am working on it now. SO=o when i get feedback i write this down in the feedpusle. This looks like this: 
![msedge_4U9qUwcP0p](https://user-images.githubusercontent.com/99720725/171360488-dd22a30f-51f7-4ef9-9d2b-739d2d91c1ac.png)
In tese feedpusles i explain what the teacher said to me and what i need to do or what i need to change to make my code/documents better.

##### Situation 1

S: There was a moment within these sprints where i needed to make an API implementation for our project. This API would contain information about travel restrictions.    So i worked on it and while working on it i found an API that could help me. This API contains all information we needed for our project. So when i was implementing    this API i asked for help in my group because i was stuck. My groupmates helped me but also they couldnt figure out how to omplement this API because the API had an    key which had to be in our code so that we could use the information. This was a big problem because in our code we tried everything with this extra key, we put it    on different paces but it didn't work.
T: This happened in sprint 4. We thought we would be busy with this API for like 3 days but that was not the case. Because of this we needed to do something else.
A: Then we went to our stakeholder and explained what happened. Because we don't have much time left we made a suggestion to the stakeholder. We asked if we could use    our own written data so that we could move on. The stakeholder approved and said that he understands it and hopes we could move on from this and create the other      functions for our prorject. After this we applied this and luckily we are done with this function.
R: Now we got our own data on our website. These data is written in our REACT JS code. We got the data from internet, it's just common data.
R: We learned a lot about this. The biggest thing that we learned and what i have learned is that if we are stuck with a problem don't be stuck for a while and move o    on. Ask for feedback of the stakeholders or just come with a suggestion like we did on the end.

##### Semester Review






