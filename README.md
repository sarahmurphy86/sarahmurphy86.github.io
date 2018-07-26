# “If the user can’t use it, it doesn’t work.” _Susan Dray_ 

---
I am passionate about technology and human behaviour, and how they interact with one another. I want to design and build software that feels intuitive, user friendly and accessible to all.

# The brief

The BBC are looking to improve their online offering of educational content by developing some interactive apps that display information in a fun and interesting way.


>We chose to design an app aimed at children 8 to 11 years old to help them recognise geographical points of interest. The user will be shown an image of a famous landmark, and be asked to click a map to show where in the world they think this famous landmark is located. The user will then find out if their guess was correct, and will be shown some interesting facts on the famous landmark and the country it is in. 


I would like to share the UX methods we used our project, and the accessibility considerations we made

## Discovery Methods

### Proto-personas

Who are our users, how do they behave and what are their needs and goals?

### User Needs:

What do our users need and what does success look like?

| As a...                    | I want to...                                                                                                | So that ...                                               |
|:---------------------------|:------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------|
| Eight  year old boy        | Learn about where the countries of the world                                                                |I can improve on my geography                              | 
| Ten year old girl          | Play a cool game                                                                                            |I can have a competition with my friends                   |         
| Person who is colourblind  | Be able to interact with the app easily, and not need to rely on colours alone to navigate through the site  |I can join in the fun too                                  |
| Primary school teacher     | Have an educational game that is free to use and and I can share with my class                              |My students can learn about geography and have fun doing it|

 * * *                                                            


## Design Methods:

### User Journey
![User Journey](https://sarahmurphy86.github.io/assets/user_journey.png)

### Sketching

![Sketching](https://sarahmurphy86.github.io/assets/JavaScript_project_sketch_landmark_view.jpg)


### Wireframes
![Wireframe 1](https://sarahmurphy86.github.io/assets/wireframe_version_1.png)

![Wireframe 2](https://sarahmurphy86.github.io/assets/wireframe_version_2.png)

![Wireframe 3](https://sarahmurphy86.github.io/assets/wireframe_version_3.png)

### Prototype

You can find a link to an interactive mock-up of the site on by downloading the HTML code below.

[Link to the HTML prototype](https://github.com/sarahmurphy86/JavaScript_group_project_ux/tree/master/JavaScript_protect_protype_version%200.1)

## Process Map:
![Process Map](https://sarahmurphy86.github.io/assets/process_map.png)


## User Testing:

*   3 users
    - 10 year old male - student
    - 13 year old female - student
    - 50 year old female - teacher and parent

![User testing image](https://sarahmurphy86.github.io/assets/user_testing_image.jpg)

### Design Changes:

Following our user testing, the following changes were made to the app:

1. **Submit button made visible** - worked on CSS to ensure that the button was visible on the page without scrolling.
2. **Colour overlay changed** - the colour overlay of the country was changed when it was clicked from green to orange.
3. **Submit button** -  the user thought that the green overlay indicated that the map was selected, as such a ‘submit button’ didn’t need to be clicked
4. **Correct country selected** - the user thought that the green overlay meant that they had selected the correct country.
5. **Images of Yang** -  our character was added to the famous landmarks to ensure that the narrative flowed
6. **Landmark pin** - work was done on this to ensure it was clear 
7. **Voice over** - added to the app to indicate whether the user had guessed correctly 

The users suggested the following improvements, if we had more time we would have liked to implement these:
* All users liked the idea of “hotter” and “colder” clues dependent on your guess
* All users liked the ideas of a “hints” button.
* Users would have like this to be a game


### Accessibility considerations that were implemented:

| Feature                               | Why                                                                                         | 
|:--------------------------------------|:--------------------------------------------------------------------------------------------|
| !DOCTYPE HTML                         | Helps screenreaders                                                                         |
| Font size set as a % or em            | Allows user to change font size to their liking                                             |
| Font is Sans Serif                    | Recommended on British Dyslexia Association website (font used is Dosis child friendly too) |
| Try to make colours dyslexia friendly | Most users prefer dark print on a pale background. Colour preferences vary                  |
| Alt text for images                   | Helps screen readers                                                                        |
| Test site with Colour Oracle          | Ensure site provides a good experience if you do not have 100% colour vision                |


## You can find a link to the app below:
[Link to the JavaScript application](https://github.com/sarahmurphy86/JSProject-WhereInTheWorld).

***
### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```
Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to the JavaScript application](https://github.com/sarahmurphy86/JSProject-WhereInTheWorld).
#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
