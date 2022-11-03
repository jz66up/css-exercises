# Landing page Readme

#### Why I created this page
The reason I created this page is because it is along the journey of the CSS course I am taking to become a web developer. And this project would combine all the things I have learnt about CSS and put me to the test, which I succeeded in doing. 


### Landing page 
This is my Landing Page: [Landing Page](http://127.0.0.1:5500/odin/Foundations/css-exercises/flex/landingpagefinalproject/index.html).
Although it only looks good on a laptop and not the monitor as I haven't learnt how to make a website look proportional on every device regardless of screen size.

## What I learnt from creating this page
while making this page, I learnt many useful things that will help me in future projects. 

* Put every element in a class so flexbox can be performed on it and modify it the way you want it to be
* To use a font not from the default CSS fonts (for example Roboto in the example below), just copy the link of it from [Google Fonts](https://fonts.google.com/) and then paste it into the CSS like this:
    ```CSS
    @import url('https://fonts.googleapis.com/css?family=Roboto&display=swap');
    ```
* To make text wrap use the `inline-size` and `overflow-wrap` properties. 
  For example:
  ```CSS
    inline-size: 450px;
    overflow-wrap: break-word;
  ```  
  `inline-size` gives the text a max size that it cannot breach, and if it breaches `overflow-wrap` will break the words/word up
* To ensure the the website takes up the whole view height, just say
  ```CSS
    body {
    height: 100vh;
  }
  ```
* `border-radius` defines the radius of the element's corners and allows you to add arounded corners to elements, for examples buttons, to make your website look more appealing. 
  Simply just say 
  ```CSS
  border-radius: 3px;
  ```
* When there is a need to separate two groups of elements or arrange them in a particular way, for example a paragraph and a picture, put these two groups of things into a new container











## Conclusion
I learnt many different things along the journey of developing the fabulous website, and I owe it my deepest gratitude for brimming my head with the knowledge to further my journey into the web development world. 


### Credits
All the pictures in said website are obtained from the [unsplash.com](https://unsplash.com/). And also said website was based on the the structure of [Project: Landing Page](https://www.theodinproject.com/lessons/foundations-landing-page)of the [Foundatins Course](https://www.theodinproject.com/paths/foundations/courses/foundations) from the [Odin Project](https://www.theodinproject.com/dashboard)

