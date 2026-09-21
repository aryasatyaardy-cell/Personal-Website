# Easy to Edit Personal Website
This website are made to be easily accessed and edited so you can easily make your own personalised website!

Mainly, the purpose of this web is to showcase my past projects so I can showcase it easily to people, as I wanted to get a scholarship after highschool to study overseas

## Folder Structure

```
.
├── index.html        # Homepage, briefly showcase your projects  
├── about.html        # Your [About Me], duh
├── Project1.html     # Go deep into your projects  
├── Project2.html     # Go deep into your projects
├── Main.css          # Shared styling file as I can't be bothered to make dozens if I can use it for all
└── Assets/           # Assets that your web use such as .png, .svg, or others
    ├── Example.png
```

## Customising
``` <h1></h1> ``` Is used for titles

``` <h2></h2> ``` Is used for main texts, jus plain ol' boring texts

``` <h3></h3> ``` Same like ``` <h2></h2> ``` but for lists, it have a gap of margin between the ``` <h3> ``` and the right side

## in ``` index.html ```
Which is your homepage to showcase your project briefly

First is the project section which contained in ``` <div class="Project"> ```, you can always copy and paste it and add numbers after "Project" such as ``` <div class=Project1> ``` and add it in the ``` Main.css ``` file, more in ``` <div class="Project"> ```:

## Project div Example
I will be using ``` <div class="Project3> ``` as example

``` <div class="Project3Heading"> ``` Is used to add the number or date of your project in ``` <h1></h1> ```

``` <div class="Project3Body"> ``` Is used to explain your project briefly

### In ``` <div class="Project3Body"> ```
``` <div class="img"> ``` To replace image with your own project, I strongly suggesting picture in 1:1 ratio

``` <h1><h2><h3> ``` Is the text, the diffrence between h1, h2, h3 is explained on line 19

``` <div class="MoreButton"> ``` Is a button that when a user press, it direct them to ``` Project1.html ```, OR other external web

## Other Stuff
``` <div class="Project3"> ``` Is algined to the right

``` <div class="Project2"> ``` Is aligned to the left

This is for a criss cross effect

Also, it doesn't matter how many projects you put, keep ``` <div class="Project3"> ``` or ``` <div class="Project2"> ``` as it is, but never put it in another ``` <div class="Project3"> ``` or ``` <div class="Project2"> ```

# ``` Index.html ``` Structure
## Projects
``` 
<div class="Project3">
        <div class="Project3Heading">
            <h1>Project count/date</h1>
        </div>

        <div class="Project3Body">

            <div class="img">
                <img src="Assets/YourImage.png" alt="YourImageTitle">
            </div>

            <div class="Text">
                <h1>Title of Your Project</h1>
                <h2>Brief explanation of your text</h2>   ## You can always use one ``` <h2></h2> ```, but to add a new pharagraph, use new ``` <h2></h2> ``` 
                
                <div class="MoreButton">
                    <a href="ThisProjectsFullExplanation.html">Learn More</a>
                </div>

            </div>

        </div>
    </div>
    ```
