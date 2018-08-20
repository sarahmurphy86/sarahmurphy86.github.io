> **“If the user can’t use it, it doesn’t work.”** *Susan Dray*

---
# About me
<img src="https://sarahmurphy86.github.io/assets/profile_pic.png" alt="Cartoon Profile Picture of Sarah" width="14%" height="21%" align="left">
I am passionate about technology and human behaviour, and how they interact with one another. I want to design and build software that feels intuitive, user friendly and accessible.

If you like what you see, please get in touch via email [sarah.graham86@gmail.com](mailto:sarah.graham86@gmail.com) or through <a href="http://www.linkedin.com/in/sarah-murphy-173966120" target="_blank">LinkedIn</a>
* * *

# My work
<img src="https://sarahmurphy86.github.io/assets/edinburgh_fringe_festival_image.png" alt="Text on image reads Portfolio- Edinburgh Fringe Review" width="30%" height="50%" align="left"> As a long time user of the  Edinburgh Fringe Festival website, I have always struggled to find shows by time. Therefore, I thought this would be a great opportunity to address the problem with a design solution. Take a look at my work by clicking the link below.

<a href="https://docs.google.com/presentation/d/10Pxz8xr1g2LSgOuYFKRa_3YhODiO78Ybx4sgXYjqlQs/edit?usp=sharing" target="_blank"> Edinburgh Fringe Review</a>

<img src="https://sarahmurphy86.github.io/assets/bbc_project_image.png" alt="Text on image reads Portfolio- The BBC Project" width="30%" height="50%" align="left"> As part of my final project at <a href="https://codeclan.com" target="_blank"> CodeClan</a>, I was tasked to to build an interactive educational app for the BBC.

Scroll down the page to take a look at how I went about doing this. 
* * *

# The BBC project

The BBC were looking to improve their online offering of educational content by developing some interactive apps that display information in a fun and interesting way. Working collaboratively in a team of four, my goal was to produce a full stack web application (vanilla JavaScript, Express and Mongo).


>We chose to design an app aimed at children 8 to 11 years old to help them recognise geographical points of interest. The user will be shown an image of a famous landmark, and be asked to click a map to show where in the world they think this famous landmark is located. The user will then find out if their guess was correct, and will be shown some interesting facts on the famous landmark and the country it is in. 

## What problem was I trying to solve?
1. The BBC believe that children do not understand where the different countries are in the world.
2. The BBC believe that children have little knowledge of human/man-made and natural/physical geography.


### My approach...

#### Proto-personas
I decided to design a number of proto-personas to answer the following questions:

<img src="https://sarahmurphy86.github.io/assets/sherlock_cartoon.png" alt="Cartoon image of Sherlock Holmes with a magnifying glass" width="14%" height="21%" align="left"> 
* Who are our users?
* How do they behave?
* What do they want?

**Example proto-persona**
<img src="https://sarahmurphy86.github.io/assets/scott_proto_persona.png" alt="Cartoon image of a boy standing front of some goalposts with a football" width="14%" height="21%" align="left"> **Who:** Scott, aged 10, primary school pupil
**Behaviours:** Likes to play football with his friends and gets bored easily in class
**Needs and goals:** Scott wants to get better at geography so he can pass the end of year test


#### User needs

I then documented the user needs to understand what success looked like based on the proto-personas.

| As a...                    | I want to...                                                                                                | So that ...                                               |
|:---------------------------|:------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------|
| Ten year old boy           | Learn about where the countries of the world                                                                |I can improve on my geography and pass he end of year test | 
| Eight year old girl        | Play a cool game                                                                                            |I can have a competition with my friends                   |         
| Person who is colourblind  | Be able to interact with the app easily, and not need to rely on colours alone to navigate through the site |I can join in the fun too                                  |
| Primary school teacher     | Have an educational game that is free to use and and I can share with my class                              |My students can learn about geography and have fun doing it|

To validate the proto-personas, I asked some real life children (my niece and nephews) what was important to them....

The resounding response was that it needed to be *add image here**

 * * *                                                            

#### The user journey

Once I had a clear idea of who the users were and how I would meet their needs, I wanted to create a simple user interface. 

First of all, I need to work out how the users would interact with the app and how the system would respond. To do this, I designed a simple user journey based on my proto-persona Scott.

![Diagram of the User Journey](https://sarahmurphy86.github.io/assets/user_journey.png)

#### Process map

I then needed to consider all the steps the user takes when interacting with the app and what decisions they need to make along the way. I believe that visually describing the user flow was important for the team, as it ensured that we all understood the series of events that would lead up to the end result.

![Process Map](https://sarahmurphy86.github.io/assets/process_map.png)

#### Interface sketches and wireframes

It was then time to get the pen and paper out, sketching a low-fidelity user interface. Following some initial feedback from the team (e.g. centering the submit button), I moved onto UXPin to produce some wireframes - you can see my iterative process below.

![Sketching](https://sarahmurphy86.github.io/assets/sketch_and_wireframe.png)

#### Prototype

My next step was to build an interactive mock-up of the site, so that I could bring the user interface to life. This meant my colleagues and I were able to experience what it would ‘feel’ like to navigate through the app, what the end product could look like and how the functionality should work before we began building it.

You can take a look at the prototype by clicking on the link below.

<a href="https://preview.uxpin.com/18620110def9cd42c43a7f5650fa077be6aa4d48#/pages//simulate/no-panels?mode=i" target="_blank"> Link to my HTML prototype</a>)

#### User testing

Once we had built a functional app, this seemed like a great opportunity to get some potential users to try it out and give us some feedback. 

<img src="https://sarahmurphy86.github.io/assets/user_testing_image_2.png" alt="Photograph of two participants testing the application" width="40%" height="60%" align="left"> 

I recruited three participants to test out our app based on my proto-personas. 

* 10 year old male - student
* 13 year old female - student
* 50 year old female - teacher and parent

The purpose of the user testing was to find out:
1. How the participants **interacted** with the app e.g did they understand the instructions and could they work out how to select a country on the map
2. Did they find the app **fun** to use?
3. Did they **learn** where the countries are in the world, or could they remember any of the facts about the countries?
4. What parts of the app did they **like or dislike**
5. What could I do to **improve** their experience with the app?


#### An iterative process...

The user testing was incredibly valuable, and provided some great ideas for how we could go about making improvements to the app.

With my colleagues we decided to:

1. **Ensure the submit button was visible** - our participants did not realise they needed to scroll down the page to click the button,  so we worked on CSS to reformat the layout of the page to ensure the submit button was visible without the need to scroll
2. **Colour overlay changed** - our participants thought that the country colour overlay (to indicate a country had been selected) indicated whether their guess was correct or not, so we changed the colour scheme from green to orange to reduce confusion
3. **Images of character** -  it became clear that the narrative behind of our app didn’t really flow e.g. our character is introduced in the instructions but doesn’t appear again, so we added the character to the pictures of the famous landmarks to ensure continuity of our story
4. **Landmark pin** -participant feedback indicated that it was hard to tell which country the pin landed on - so we worked on the pin to ensure it clearly indicated the country
5. **Voice over** - participants liked the voice-over that had been added to indicate whether they had guessed correctly, so we agreed to keep this feature 

#### Accessibility considerations

Designing an accessible app is something that is very important to me, and I wanted to ensure that the design choices we made were considerate of user needs. The ways we went about doing this were:-

1. Ensured that **!DOCTYPE html** was used in the HTML file and **alt-text** was added when we used images to make it accessible to people using assistive technologies such as a screen readers
2. Used the **British Dyslexia Association website** to research how to make the app dyslexia friendly. Their recommendation was to use a sans serif font, and to use dark print on a pale background which formed the basis for our design
3. One of our user needs was to “be able to interact with the app easily, and not need to rely on colours alone to navigate through the site”. We designed the app with this in mind, but I also tested the app using a site called **Colour Oracle**. This allowed me to check what our app looks if you don’t have 100% colour vision and gave me confidence that you can interact with it easily without relying in colour


#### Design improvements
After the user testing, I asked participants how I could make our app better…they had some great ideas and if we had more time for this project I would have liked to implement these.
* All participants liked the idea of “hotter” and “colder” clues dependent on your country guess
* All participants liked the ideas of a “hints” button 
* Participants would have liked this to be a game with a points system

#### Challenges
As with any project, there were challenges along the way such as:
* Ensuring that the team kept the user at the heart of the product  - not adding 'cool' features because we can
* Time constraints - we only had five days to design and build the application
* Adapting to working with a new team with different working styles 

#### Key takeaway
*  Designing and building something that is simple and easy to use from the user perspective is difficult.

### Want to take a look at the app?
You can find a link to the app on my GitHub account below. Once you have downloaded the code to your local repository you can find the instructions on how to install and run the app on the README.md file.
[Link to the JavaScript application](https://github.com/sarahmurphy86/JSProject-WhereInTheWorld).

