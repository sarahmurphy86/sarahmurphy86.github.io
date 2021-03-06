> **“If the user can’t use it, it doesn’t work.”** *Susan Dray*

---
# About me
<img src="https://sarahmurphy86.github.io/assets/profile_pic.png" alt="Cartoon Profile Picture of Sarah" width="14%" height="21%" align="left">
I am passionate about technology and human behaviour, and how they interact with one another. I want to design and build software that feels intuitive, user friendly and accessible.

Please get in touch via email [sarah.graham86@gmail.com](mailto:sarah.graham86@gmail.com) or through <a href="http://www.linkedin.com/in/sarah-murphy-173966120" target="_blank">LinkedIn</a>
* * *

# My work
<img src="https://sarahmurphy86.github.io/assets/edinburgh_fringe_festival_image.png" alt="Text on image reads Portfolio- Edinburgh Fringe Review" width="30%" height="50%" align="left"> As a long time user of the  Edinburgh Fringe Festival website, I have always struggled to find shows by time. Therefore, I thought this would be a great opportunity to address the problem with a design solution. Take a look at my work by clicking the link below.

<a href="https://docs.google.com/presentation/d/10Pxz8xr1g2LSgOuYFKRa_3YhODiO78Ybx4sgXYjqlQs/edit?usp=sharing" target="_blank"> Edinburgh Fringe Review</a> (this link opens in a new window)

<img src="https://sarahmurphy86.github.io/assets/bbc_project_image.png" alt="Text on image reads Portfolio- The BBC Project" width="30%" height="50%" align="left"> As part of my final project at <a href="https://codeclan.com" target="_blank"> CodeClan</a>, I was tasked to to build an interactive educational app for the BBC.

Scroll down the page to take a look at how I approached this.
<br/>
<br/>
<br/>
* * *

# The BBC project

The BBC were looking to improve their online offering of educational content by developing some interactive apps that display information in a fun and interesting way. Working collaboratively in a team of four, my goal was to produce a full stack web application (vanilla JavaScript, Express and Mongo).


>We chose to design an app aimed at children 8 to 11 years old to help them recognise geographical points of interest. The user will be shown an image of a famous landmark, and be asked to click a map to show where in the world they think this famous landmark is located. The user will then find out if their guess was correct, and will be shown some interesting facts on the famous landmark and the country it is in. 

## What problem was I trying to solve?
1. The BBC believe that children do not understand where the different countries are in the world.
2. The BBC believe that children have little knowledge of human/man-made and natural/physical geography.


## My approach...

### Proto-personas
I decided to design a number of proto-personas to answer the following questions:

* Who are our users?
* How do they behave?
* What do they want? 

**Example:**<br/>
<img src="https://sarahmurphy86.github.io/assets/scott_proto_persona.png" alt="Cartoon image of a boy standing front of some goalposts with a football" width="21%" height="28%" align="left"> **Who:** Scott, aged 10, primary school pupil<br/> **Behaviours:** Likes to play football with his friends and gets bored easily in class<br/>
**Needs and goals:** Scott wants to get better at geography so he can pass the end of year test
<br/>
<br/>
### User needs

I then documented the user needs to understand what success looked like based on the proto-personas.

| As a...                    | I want to...                                                                                                | So that ...                                               |
|:---------------------------|:------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------|
| Ten year old boy           | Learn about where the countries of the world are                                                            |I can improve on my geography and pass the end of year test| 
| Eight year old girl        | Play a cool game                                                                                            |I can have a competition with my friends                   |         
| Person who is colourblind  | Be able to interact with the app easily, and not need to rely on colours alone to navigate through the site |I can join in the fun too                                  |
| Primary school teacher     | Have an educational game that is free to use and and I can share with my class                              |My students can learn about geography and have fun doing it|

 * * *                                                            

### The user journey

Once I had a clear idea of who the users were and how I would meet their needs, I wanted to create a simple user interface. 

First of all, I needed to work out how the users would interact with the app and how the system would respond. To do this, I designed a simple user journey based on my proto-persona Scott.

![Diagram of the User Journey](https://sarahmurphy86.github.io/assets/user_journey.png)

### Process map

I then wanted to consider all the steps Scott would take when interacting with the app and what decisions he would need to make along the way. I believe that visually describing the user flow was important for the team, as it ensured that we all understood the series of events that would lead up to the end result.

![Process Map](https://sarahmurphy86.github.io/assets/process_map.png)

### Interface sketches and wireframes

It was then time to get the pen and paper out, sketching a low-fidelity user interface. Following some initial feedback from the team (e.g. centring the submit button), I moved onto UXPin to produce some wireframes - you can see my iterative process below.

![Sketching](https://sarahmurphy86.github.io/assets/sketch_and_wireframe.png)

### Prototype

My next step was to build a mock-up of the app, so that I could bring the user interface to life. This meant my colleagues and I were able to experience how it ‘felt’ to navigate through the app, how it should work, and what the end product could look like before we began building it.

### User testing

Once we had built a functional app, this seemed like a great opportunity to get some potential users to try it out and give us some feedback. I recruited three participants to test out our app based on my proto-personas.

<img src="https://sarahmurphy86.github.io/assets/user_testing_image_2.png" alt="Photograph of two participants testing the application" width="50%" height="75%" align="left"> 

**Participants:** 

* 10 year old male - student
* 13 year old female - student
* 50 year old female - teacher and parent<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<p align="left">I wanted to find out:</p>
* How the participants interacted with the app e.g did they understand the instructions, and could they work out how to select a country on the map?
* If they found the app fun to use?
* If they learnt anything by using the app e.g where the countries are in the world, or if they could remember any of the facts about the countries?
* What parts of the app they liked or disliked
* What could I do to improve their experience with the app?

### An iterative process...

The user testing highlighted some difficulties the participants had when using the app, and gave me some ideas on how we could improve their experience.

My colleagues and I decided to make the following changes:

1. **Ensure the submit button was visible** - participants did not realise they needed to scroll down the page to click the submit button,  so we worked on CSS to reformat the layout of the page to ensure the submit button was visible without the need to scroll.
2. **Colour overlay changed** - participants thought that the country colour overlay (to indicate a country had been selected) indicated whether their guess was correct or not, so we changed the colour scheme from green to orange to reduce confusion.
3. **Images of character** -  it became clear that the narrative behind of our app didn’t flow e.g. our character was introduced in the instructions but didn't appear again, so we added the character to the pictures of the famous landmarks to ensure continuity of our story.
4. **Landmark pin** - participants found it difficult to tell which country the pin landed on, so we worked on the design of the pin to ensure it clearly indicated the country.
5. **Voice over** - participants liked the voice-over that had been added to indicate whether they had guessed correctly, so we agreed to keep this feature. 

### Making the app inclusive

Designing an accessible app is something that is very important to me, and I wanted to ensure that the design choices we made were considerate of users needs by:

1. Making the app accessible to people using assistive technologies such as screen readers, by ensuring the <!DOCTYPE html> declaration was used in the HTML file and the alt-text attribute was added to our image tags.
2. Used the <a href="https://www.bdadyslexia.org.uk/" target="_blank">British Dyslexia Association website</a> to research how to make the app dyslexia friendly. Their recommendation was to use a sans serif font, and to use dark print on a pale background which formed the basis for our design.
3. One of our user needs was to “be able to interact with the app easily, and not need to rely on colours alone to navigate through the site". We designed the app with this in mind, but I also tested the app using a site called <a href="http://www.colororacle.org/" target="_blank">Colour Oracle</a>. This allowed me to check what our app looks if you don’t have 100% colour vision and gave me reassurance that you can interact with it easily without relying on colour.

### Design improvements
After the user testing, I asked participants how I could improve the app…they had some great ideas, and if we had more time for this project I would have liked to implement these.
* All participants liked the idea of “hotter” and “colder” clues dependent on your country guess
* All participants liked the ideas of a “hints” button 
* Participants would have liked this to be a game with a points system

### Challenges
As with any project, there were challenges along the way...
* Ensuring that the team kept the user at the heart of the product  - not adding 'cool' features because we could
* Time constraints - we only had five days to design and build the application
* Adapting to working with a new team with different working styles 

### Key takeaway
*  Designing and building something that is simple and easy to use from the users perspective is difficult

### Want to take a look at the app?
You can find a link to the app on my GitHub account below.  Once you have downloaded the code to your local repository, the README.md file explains how to install and run the app.
<br/>
<br/><a href="https://github.com/sarahmurphy86/JSProject-WhereInTheWorld" target="_blank">Link to the JavaScript app</a>

