## Welcome to our project development blog

Here you can follow the ongoing work with our bachelor project regarding active patient response schemas for healthcare consultations. The members of the project are Kristian Andersen Hole and Jakob Halsteinslid Manne. We are both final year computer engineering students at the Western Norway University of Applied Sciences where we are currently specializing in mobile and web applications. 

The project is a self produced idea that has been developed at the Digital Healthcare Lab at our university. The project will be integrated with AVANS healthcare systems. The center for rehabilitation at Haugland will contribute with testing and providing feedback regarding the functionallity of the application.

***

## 24.05.17 Mobile Version

Although we have focused on this while developing the project there where still some glitches on the HS-Viewer project that had to be fixed so that it can be viewed on smaller screen sizes. In particular we had to fix the LinearScale. 

## 21.05.17 Writing 

In the last week we have mainly been focusing on writing the draft of the report. This requires a lot of work, so we doubt if we will be able to do any major changes to the project. There are still a few things that remain, but hopefully we will be able to fix them in the time left. 



## 14.05.17 Additional changes 

As the project is coming close to and end we have mainly focused on creating some additional changes to HS-designer and HS-Viewer. These changes include: 
- Internationalization for text in both norwegian and english
- Session storage in the HS - Viewer so that when a user refreshes the webpage the answers will still appear. 
- We have added mandatory questions functionality, so that each questions registered with this functionality will have to be answered before a submission of the schema can be done. 
- In the HS-Designer one can upload a Logo to the schema. 

## 08.05.17 HS-Designer Work

We are now finished creating the visual representaton of the dependancy in the HS-Designer. There are only some questions that give dependancy "functionality" though, but we are statisfied with the result. Every question can be dependant of one of more quetions. 

<img src="https://github.com/KaHole/group3-project-progress/blob/master/dependant.png?raw=true" height="400" width="auto" >

## 05.05.17 Testing 

Although we are writing tests as we program, we have started to create intergration tests for the whole project. These tests are written in phantomjs and will test that each of the components, HS-Designer, HS-server and HS - Viewer will work well together. The tests are not done as we need to get a better understanding of how PhantomJS works. 

## 01.05.17 New Questions

We have now added some new questions to the Hs Designer. We have added a date question where one can register a valid date. In the HS-designer we have also implemented the drawbox question, but there are some work do be done her. We have also created the LinearScale question type where one selects a radiobutton in a range 0-10 where there is a start text and end text before and after the last radiobutton. There where some work to be done here, because we also had to create the XML model for the question and create the visual representation of the LinearScale question in the HS - Viewer. 

## 25.04.17 Prototype HS-Designer. 

We thought that it would be nice to see how the HS-Designer project is looking visually. 
When clicking the pluss button a new question will appear. One can also change the background color of the schema. In addition one can change the title and add a description for the project. 

<img src="https://github.com/KaHole/group3-project-progress/blob/master/schema.png?raw=true" height="400" width="auto" >


## 20.04.17 - Dependency functionality 

In this week we have mainly focused on developing the Dependancy funtionality. This has been a challenging task since we had to change the XML model as the last dependancy XML model did not fit our needs. We have also started to create the dependancy functionality in the HS-designer, but we are not quite sure how we are going to present it visually yet. 

In addition to the "normal dependancy" we have also created an external dependancy value. This value is located at the testserver and when a question with this dependancy is displayed in the HS-Viewer, it will lookup the value at the testserver. 


## 09.04.17 - Schema Designer Progress

After we finished developing the prototype for the HS-Viwer we started to create the prototype for the HS-Designer. This was a bit more challenging task for us since it requires more functions that the other components of the project. We have now created a basic schema where one can add questions which are the same that can be viwed in the HS-Viwer. The next task for us will be to develop more complex functions for the HS-Designer such as the dependancy functionality. We are not planning to work that much in the Easter. 

## 29.03.17 - Prototype

We have now developed a functioning prototype for the HS-Viewer, which is the component that are to display the schemas. Our program will now take an XML schema from the testserver and display it as a webpage schema that the user can interact with. We have added these functionalities: Short text, long text, dependant questions, radio buttons, checkboxes and dropdown and pain chart drawing. In the future we will add more functionalities. When the user has submitted his/hers response the webpage will output XML with the response that can be stored in an external storage (Avans healthcare journal) for instance. We have also worked on our pre - project report. 

Here is a link to the prototype: <https://kahole.github.io/hs-viewer/>



## 15.03.17 - Development progress 

In the last couple of weeks we have been developing the structure of the schemas by experimenting with different XML sctructures. We have also had several meetings with the development team at Avans as well as our superviser at HVL. We have bagan writing our pre project report that we also are going to present for our class.

The project now consists of three seperate projects that communicate with each other; HS-Designer - HS-TestServer - HS-Viewer. 
Here is a picture of how a radiobutton question is defined in XML. 

<img src="https://github.com/KaHole/group3-project-progress/blob/master/XML schema.jpg?raw=true" height="400" width="auto" >

## 17.02.17 - Meeting with Avans at the Haugland Rehabilitation Centre

<img src="https://github.com/KaHole/group3-project-progress/blob/master/jaobboat.jpg?raw=true" height="400" width="auto" >

Today we went on a trip with our two bachelor supervisors to Haugland Rehabilitation centre where we had a productive meeting. We took the fery in the morning (08.00) and arrived at Askvoll some hours later where we met the CEO of Avans. After a quick drive we arrived at Haugland where we got a guided tour and ate lunch. Then followed a three hour meeting where we discussed the project and how Haugland could participate in it. We dicided that they would provide us with forms and other functionalities that they want to be included in the program. After the meeting we ate dinner and tok the fery home and arrived in Bergen in the evening (20.45). The next task for us is to schedule a meeting with the developer at Avans in order to begin developing the program. 

-Jakob and Kristian

## 03.02.17 - Initial Schetches and Startup Meeting

![alt tag](https://github.com/KaHole/group3-project-progress/blob/master/InitialScetches.jpg?raw=true)
Today we had our first meeting together where we discussed how we could develop the application. We also wrote down questions that we are going to ask our partners. The questions are regarding the technology that AVANS has used when building their patient journaling system. On the 17th of Februrary we are going to travel to Dale to visit the Haugland rehabilitation centre alongside the CEO of Avans and our local bachelor supervisor at HVL. We have decided to draw more detailed scetches that we are going to present at the meeting in order to get feedback from the other participants of the project. After this are we hopefully ready to commence initial development of the application. 

-Jakob and Kristian

03.02.2017
