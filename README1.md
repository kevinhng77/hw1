# Optimizing Horiseon's User Interface

## Description 

In the beginning of this project, Horiseon website was not very user friendly. The pictures were way smaller and the texts were not big at all. For someone who has any slight disability with using websites, this would've been a problem. Luckily, with the help of some HTML and CSS, these problems can easily be fixed. On top of that, some of the features also did not work. For example, the link for "Search Engine Optimization" did not work properly. Instead of guiding you towards the bottom of the page like it's supposed to, it simply refreshed the page. This was mainly due to some error in the code, which will be discussed later in the ReadMe. This is not to say that all of it was bad. The other two buttons worked perfectly well, and although they were just minor resizing issues, the layout and the colors and the rest of the images were excellent choices. The code also had a lot of problems with the way it was structured, as well as the semantics. THe HTML did not have any proper structure, and needed a lot of refactoring. 

Throughout this project, I learned a lot about how HTML works, how CSS links to HTML, and basically the whole structure of how this web development process works. This taught me a lot about git and how to push things to the web and save my progress. Overall this was a very good project to start with, going over everything that was taught in class and a good level of difficulty, whether you've never coded before, or have minimal coding experience.

[Finished Website](https://kevinhng77.github.io/hw1/)
[Github Repo](https://github.com/kevinhng77/hw1)


## Installation

First, by cloning the repository down to your computer, you can copy down the existing index.html file. Next, open it up with GitBash and type in "code ." , which should open up VSCode. From there, there were a lot of errors and things that needed to be fixed, which will be went over in the next section.


## Usage 

As stated above, there was a lot of code that needed refactoring. An example of this is in the image below. As you can see, the header, div, and nav are all correctly specified. Compared to before, there were a lot of divs. Although this is not wrong, and the code still works fine, it is not semantically correct, and would make a lot of coders and people who edit this code have a very hard time. Because it is not structured correctly, it would waste a lot of time confusing people as well as it not being efficient when it comes time to edit the properties in CSS. This is also exemplified throughout the html file as a lot of articles, asides, footer, h4, all needed changing.

[Example 1](./Assets/images/example-1.png)

Because of some of the renamings of the html file, this made the CSS file need some updating as well. For example, because we simply changed div to nav, this made it necessary to change nav in the CSS file as well.

[Example 2](./Assets/images/example-2.png)

 A lot of text sizing as well as picture resizing need to happen since it was not very user friendly. After resizing the pictures, you can see that it was way easier to read as well as easier to click. For people with disabilities, this is a great asset to them.

[Example 3](./Assets/images/example-3.png)

Finally, some bugs in the program were that some links did not click. This is in part due to how sloppy the HTML structuring was. Because of this, the original programmer probably missed a section in writing the code. The example below shows what the problem was.

[Example 4](./Assets/images/example-4.png)

## Credits

Special shoutout to TA Kyle Vance for assisting me with this project. He helped me learn the structure in which files should be presented in Github, as well as figure out some things about how Github pages works.


## License

N/A

## Badges

N/A

## Features

N/A

## Contributing

N/A

## Tests

N/A