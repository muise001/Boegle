[see the site!](boegle.herokuapp.com)

**Published articles on Boegle**
[On the Oba Site](https://www.oba.nl/nieuws/meesterproef2018.html)
[On the HvA news site](https://hvana.nl/lees/5452/studenten-maken-een-google-voor-boeken-en-historisch-amsterdam)

# Meesterproef Emiel 
The past five weeks we've created a great application. First of all I want to give some credit to my team [Desley](https://github.com/DesleyAalderink), [Victor](github.com/velomovies) and [Chana](https://github.com/niyorn) for the amazing time and hard work. If I look back at these five weeks, I'd say I was the team leader. I took alot of initiatives to plan and host meetings, get everyone together to talk about what went well and what went wrong. When Mark came to see our project for the first time I presented it to him and was presented by the team to take the lead while talking with the Oba-press. Fortunately everyone felt comfortable enough to speak up when they disagreed on something and we as a team would discuss the posibilities. 

You're going to notice me writing alot about the team in these next few chapters. That is because we did so much with the team. Some of us did stuf together or helped eachother out when they were stuck. No-one did one particular thing.

## Week one
#### To team or not to team
Aventually Desley and me wanted to work together. We did somem brainstorming and concepting together. But because We, Chana and Victor sat in the same room together. We figured that it won't harm anyone to brainstorm together. We did this to create more ideas. Around Thursday we decided to merge everyone together in one team called Boogle. We did this because all our ideas looked alike.

As a team we thought about our first concept. What should be in it and why. We used the MoSCoW technique to prioritise what needed to be done

## Week two
#### Learning goals
In this week we made great steps. We did alot of research on the user, the api and the endless possibilities. We made designs (the're shown in the process-book). We also set "learning goals" for ourselfs. We decited to all work on our weaker points.
My "Learning goals" were :
 - Learning to gain better understanding in CSS
   - Using CSS Variables
   - Using CSS Transitions
   - Using CSS Animations
   - Using less CSS
 - Learning more about ES6
   - Arrow functions
   - modules
   - for each
   - object oriented programming
 - Learning github
   - Big team projects
   - Solving merge-conflicts
   - Learning the flow
 - Research
   - Stop using W3Schools as source
   
After we all wrote down our learning goals. We gave everyone individual tasks. I was responsible for:
 - Company style
 - Animations
 - CSS
 - JS Parser (we scrapped that idea later on the project)

#### Designing the web
When we were finally done with thinking about "learning goals", We made designs. Each and everyone of us had to design the website to his likings. 

Because our time exited out of four men, we needed a particular set of coding conventions on wich we all felt comfortable using. 

#### Learning CSS
In week two I did alot of research on CSS. I've watched videos about 60fps animations and how to animate. Also I've browsed alot on codepen to get information and inspiration out of the projects I saw. While looking at these projects I learned alot about "perspective, transform-origin, "will-transform" and 3D Css". 
 
<img src="https://github.com/muise001/Boegle/blob/develop/readme_assets/IMG_9530.jpg" alt="Research on 60fps animations">

I Also leaned that drawing the thing you want to animate from state-to-state helps you understand how it should work. By drawing and looking carefully to the picture you see what changes in the state

<img src="https://github.com/muise001/Boegle/blob/develop/readme_assets/IMG_9529.jpg" alt="a sketch of the loader design">
[Click here to see the loader](https://codepen.io/muise001/pen/zaGKjd)

## Week three
#### Meeting Mark
In the third week of our project we finally get to meet Mark. Mark is the client for whom we're creating this product. I made a presentation to inform Mark about all the progress we already made during the past two weeks. Also I was experimenting with more and more animations. I made the animations of the homepage for the book, the sidemenu and the loader. 

![early version of the Zoek 'n Boek application](readme_assets/earlyVersion.PNG)

#### Argument
Also I had this big argument with Victor about what should be the content of the book and why. My vision was that the form on the sites homepage should follow the patterns of a physical book. Victor thought that it would be better to make the form more like the web-pattern of filling in a form. A ferm and long discussion followed. Offcourse this was all friendly with a touch of passive-agressive-ness.

## Week four
#### Form Designs
In week four I styled the form. It had to be more "booky". That was actually the word we used for it. 

Design 1. - Playful, colourful, oval form input designs
![Form design 1](https://github.com/muise001/Boegle/blob/develop/readme_assets/form%20design%201.png)

Design 2. - Formal, "booky", classic design
![Form design 2](https://github.com/muise001/Boegle/blob/develop/readme_assets/form%20design%202.png)

Eventough our target audience we're more the playfull kind, we chose design two. We did had a little discussion about that but with 3 votes against mine, we had to choose design two. The arugment was: "It looks like a book, it animates like a book so the form should't look like a focking lollypop". After that argument, the descision was unanimous. 

#### The Test
At the end of the week we put our design to the test. We've tested with five childern (around 12/13 years old) of our target audience. They didn't even notice the hard work in styling and animation. I then thought about Dieter Rams who once said "Great design is invisible". And it was. We were amazed how quickly the childeren navigated through our application. That was great to see. After the test I called the team together for a meeting and wrote down all the "bad" feedback:
- Doelgroep = Jeugd of none (wegens fout API) 
- Slider
  - Krijgt mousedown (voor constante feedback)
  - Min = 50 of minder
  - Max = 500 of meer
  - Begint met animatie
  - Moet meer opvallen
- Titel, auteur en taal overruled een hoop
- Form vragen moeten "vragender"
- Placeholder moet òf meer placeholder-achtig òf verdwijnen na :focus
- Knoppen onderin moeten een animatie krijgen
- Kleur van de tekst moet veranderen als de kleur van de kaft verandert
- Resultatenknop
  - Font-weight moet hoger
  - background-color moet worden verandert
  - moet meer opvallen
  - animeren na het kunnen tonen van resultaten
- Cutsom Select moet scrollen na het openen om de mogelijk tot scrollen te verduidelijken
- State 4 naar 2 na gebruik slider gaat kapot door het verkeerd verwijderen van class "none"
- Er moet een terugknop komen op de resultaten- en detailpagina

#### Custom Slider
At the end of the week I created a custom slider. That was a nice learning-moment. It's hard to style a form input. But a slider... My god. I thought "Let me change the background-color, the width, height, padding, color, border, border-radius etc.". No! You first have to delete all default stylings, than do 30 minutes of google-searching and you'll be finally able to start styling your product. When I was finally done, I wanted a tooltip that follows the slider... That's when I decided never to challenge myself again

[Click here to see the slider](https://codepen.io/muise001/pen/bKjYoa)

#### Select with checkboxes
If the slider wasn't enough. I wanted to create a `<select>` with checkboxes in them. That would save alot of space and potentially look very slick. Also the custom select took way more time then needed. But in the end it was all worth it!

[Click here to see the custom select](https://codepen.io/muise001/pen/vrRoBV)

## Week Five
#### Fixing bugs
Week five was bug-fixing week. We all took alot of time to fix and create bugs. Offcourse the created bugs got fixed later. I spend alot of time making the homepage responsive. I'm very happy with the result.

![Mobile version](readme_assets/boegle-mobile.gif)

#### Promoting Boegle
##### Boegle the movie
For weeks we wanted to create a product-video. We figured that on Wednesday we'd had some free-time. So i reached out to a local studio :
>Geachte medewerker van studio Automat,
>
>Afgelopen weken ben ik met een klein groepje mensen bezig geweest om een nieuwe zoekmachine te bouwen voor de OBA. Deze zoekmachine is nu zo goed als af. Aankomende woensdag gaan we deze presenteren op de HvA voor docenten, begeleiders en de opdrachtgevers van de OBA. We zitten er zelfs aan te denken om onze applicatie op te geven voor de "golden dot awards".
>
>De reden dat ik jullie mail is om te vragen of jullie ons willen helpen om de presentatie van ons leven neer te zetten. Het lijkt ons geweldig om jullie prachtige studio te gebruiken om een productvideo in op te nemen. De laatste waarop we dit ?kunnen doen is aanstaande woensdag. We verwachten een uur of twee bezig te zijn. Uiteraard zullen we alles netjes opruimen.
>
>Graag horen wij snel van jullie. En wensen we jullie een hele fijne dag.
>
>Met vriendelijke groet,
>
>Emiel Muis

Within minutes I recieved an email back. It was possible to shoot a video there. I rushed to the drawingboard and drew a storyboard (wich can be found in my process-book). After learning the script we shot the video. Victor fortunately is very advanced in camera use and editing. Desley drove Victor around on a little trolly and I did the acting. I'm very pleased with the result. 

##### Boegle on a poster
That same day we created posters to market our product. These can be found on the bottom of this page.

# Boegle Team Report
Amsterdam OBA | To search a book
![A demo of the OBA searchbook](readme_assets/application-introduction-v1.gif)

## Table of contents

- [Description](#description)
- [Getting started](#getting_started)
- [Progression](#progression)
    - [Week 1](#week-1)
        - [User story](#user-story)
        - [User scenario](#user-scenario)
        - [Concept](#concept)
    - [Week 2](#week-2)
        - [Automate workflow](#automate-workflow)
        - [Coding](#coding)
        - [Presentation](#presentation)
    - [Week 3](#week-3)
        - [Product](#product)
        - [Testing](#testing)
    - [Week 4](#week-4)
        - [Testing](#testing-1)
    - [Week 5](#week-5)
        - [Mobile](#mobile)
        - [Poster](#poster)
        - [Product video](#product-video)


## Description
The OBA Search a Book is an application where an user can search for a book that they vaguely remembered. 

This application is created by Chanakarn Niyornram, Victor Zumpolle, Emiel Muis and Desley Aalderink commissioned by Openbare Bibliotheek Amsterdam. 

## Getting started

Install all dependencies
```
npm install
```

Create .env file in directory and add your preferences
```
HOST = 3000
PUBLIC_KEY = public key name
SECTRET_KEY = secret key name
```

Start application
```
npm start
```

Standard port is 3000
```
localhost:3000
```

## Progression

*The progression section gives a weekly insight to what the team is working on, what for problems we've encountered and how we've dealth with the problems during our project.*

### Week 1

The focus of the first week lays on understanding and debriefing the client problem. From there we're creating an user story and an user scenario that gives us an idea what the visitors of the OBA wants and how the perfect scenario would be. And last but not least creating a concept for solving this solution.

#### User story

The high school student comes in the OBA and is looking for a book. With a description without title and writer, the librarian can do nothing. The student can use the installation next to the desk to find his / her book. The books are filtered by - among other things -  the subject, thickness of the book and the color of the cover. The student finds the right book, can see where it is, whether it is available and then borrow the book.

#### User scenario

The high school student is looking for a book, of which he or she no longer knows the title and the writer. Through a web application, the student can find the book in the OBA.

#### Concept

To comes up with a concept, we first generate ideas that are enable to solve this problem. 

<details>
<summary>Click: to see mindmap of the ideas</summary>
<img src='readme_assets/mindmap.PNG' alt="Mind map of generated ideas">
</details>

After generating ideas, every member created their own concept of a web application that will solve the problem. The concept is than shown to the team and at the end of the day the team will pick an aspect of a concept that is suited for solving the problem really wel.

<details>
<summary>Click: to see concepts</summary>
<p>Wall of generated concept</p>
<img src='readme_assets/wall-of-generated-concept.jpg' alt="Wall of generated concept of every member">

<p>Zoomed in on a concept</p>
<img src='readme_assets/concept-one.jpg' alt="A zoomed in photo of one of the concept">
</details>

### Week 2

The focus of the second week is setting up a development workflow and understand the API that is given from OBA.

#### Automate workflow

To streamline our development enviroment we're creating a taskrunner that will automate some of our work. Those work are:

- compilling sass
- combine javascript module
- watch files
- start server
- linter

There are a lot of taskrunner that we can use. To choose a correct taskrunner Desley has done research to some of the most used ones. You can find the document [here](). The list is created with a pro and con from each taskrunner and from that we choose one with the most pro. 

The taskrunner that we've settled with is Gulp. Gulp is written in Javascript which mean it's easy for us to start developing the automated task. It's also very easy to add a new automated task to the system.

When presented this to our mentor, he was not very pleased to the conclussion we've come up with. He advised us to use NPM Script, because it use less command and it takes less time to set-up and start developing.

After the presentation we have had a discussion about the feedback that is given by our mentor. We discussed if we're going to rewrite our Gulp taks in NPM Script - that mean a whole day work is gone - or are we're going to keep the Gulp taks.

After a long discussion we're going to rewrite the Gulp task in NPM Script because:

- We're already starting the server with __npm start__ so when we're adding some other automated tasks, than it's very logical to do this within the same command line.

- We have never work with NPM Script before, so NPM Script will be a new learning oppertunity for us. 

- When NPM install, all dependencies of the automated script will be installed, so when someone else clone our repository, than they will also have and understand the task that will be runned.

#### Git flow 

To be able to develop in a team, we're using git as our Version Control System and using Github as our platform for uploading our code. To avoid conflict we're are going to create branche whenever any feature is added. 

When presented this to Danny (our advisor), he found it a good idea, but it's not good enough to create consisteny and avoiding conflicts. With the help of Danny he presented idea's that we can use to create a better git flow. Those idea are:

- A convention for commit messages
- Pull request need to be checked before any merge
- Create a develop branch and merge this to the master whenever a new version is ready.
- Create a Github project that keep tracks of tasks and progress
- ~~Create a template for Issues~~~

With the help of Danny, we've implemented every ideas except the Template part, because we think it's unnecessary because the project is private for now.

#### Coding

To understand and create a better concept for the problem, we need to know which data the API is giving us. Two members worked on this.
The problem was that they a different module for this. One member worked with  Request module and the other with the Node-fetch module. This create conflict. 

After a discussion we choose to use Node-fetch. We choose this because, it use the same fetch syntax as the front-end. This means that other member of the team are able to understand the code better. Also it creates concistency in the code, between the front- and backend.

#### Presentation

We pitch our idea and concept to Mark (product owner) to get feedback and to know what he's opions is about the concept.

<details>
<summary>Click to see: photo of the presentation</summary>
<p>Presentation</p>
<img src='readme_assets/presentation.jpg' alt="A zoomed in photo of one of the concept">
</details>

### Week 3

The focus of week 3 is to create a proof of concept and test this out with real users.

#### Product

When we first starting to create this applicatoin, we intentionally didn't focus  on the appearence, because we want this application firstly to work. 

This is an image of the early version of our application.

![early version of the Zoek 'n Boek application](readme_assets/earlyVersion.PNG)


#### Testing
To make this application really great and to see if our product really work, we need to test this with real users. Mark created an appoinment with one of the Highschool in the area for us to test. However because of miscomunication we aren't able to test the application further. 

But we still need to know if our app works, so we test our app with our colleague and our mentor.

<details>
<summary>Click to see: photo of the test</summary>
<p>Test with colleague</p>
<img src='readme_assets/testing-colleague.jpg' alt="Photo of the test with a colleage">

<p>Test with mentor</p>
<img src='readme_assets/testing-mentor.jpg' alt="Photo of the test with our mentor">
</details>

__Feedback (in dutch)__
- Doelgroep = Jeugd of none (wegens fout API)
- Slider
     - Krijgt mousedown (voor constante feedback)
     - Min = 50 of minder
     - Max = 500 of meer
     - Begint met animatie
     - Moet meer opvallen
- Titel, auteur en taal overruled een hoop
- Form vragen moeten "vragender"
- Placeholder moet òf meer placeholder-achtig òf verdwijnen na :focus
- Knoppen onderin moeten een animatie krijgen
- Kleur van de tekst moet veranderen als de kleur van de kaft verandert
- Resultatenknop
     - Font-weight moet hoger
     - background-color moet worden verandert
     - moet meer opvallen
     - animeren na het kunnen tonen van resultaten
- Cutsom Select moet scrollen na het openen om de mogelijk tot scrollen te verduidelijken
- State 4 naar 2 na gebruik slider gaat kapot door het verkeerd verwijderen van class "none"
- Er moet een terugknop komen op de resultaten- en detailpagina

### Week 4
The focus of week 4 is to work further and improve the application with the feedback that is given. And also to test it with real users.

#### Testing
After improving our applicaton we went to a highschool in our area. We test our application with five users and every test is done individually. 

[Link to our testplan (in dutch)](readme_assets/testplan.pdf)

<details>
<summary>Click to see: feedback of the test (in dutch)</summary>
<p>Feedback</p>
<img src='readme_assets/feedback1.jpeg' alt="Photo of feedback">
<img src='readme_assets/feedback2.jpeg' alt="Photo of feedback">
<img src='readme_assets/feedback3.jpeg' alt="Photo of feedback">
<img src='readme_assets/feedback4.jpeg' alt="Photo of feedback">
</details>

### Week 5
The focus of week 5 is to improve our application and to make the application useable for mobile so that even a user at home is able to use the application.
We also created a poster and a product video for our end presentation.

#### Mobile
We made the application useable for mobile and this is how it looks.
![Mobile version](readme_assets/boegle-mobile.gif)

#### Poster
We've also made poster to put at our stand for the end presentation.

<details>
<summary>Click to see: some posters</summary>
<p>poster</p>
<img src='readme_assets/poster1.jpeg' alt="Poster">
<img src='readme_assets/poster2.jpeg' alt="Poster">
<img src='readme_assets/poster3.jpeg' alt="Poster">
<img src='readme_assets/poster4.jpeg' alt="Poster">
<img src='readme_assets/poster5.jpeg' alt="Poster">
<img src='readme_assets/poster6.jpeg' alt="Poster">
</details>
