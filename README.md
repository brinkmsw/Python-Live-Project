# Python-Live-Project

## Introduction
For two weeks I took part in a project through the Tech Academy to simulate a real devolper enviroment.  I, and a few other students, work on the same project adding our own apps and pulling and pushing our own code.  The experience was eye opening, I learned alot about Python, the Django Framework, APIs, Beautiful Soup, and proper version control.  Below you will find snippets of my code and an in depth explaination of the process.


## CRUD Functionality
One of our main objectives for the project was to develop an app from the ground up with CRUD (Create, Read, Update, and Delete) functionality.  We also exercised an Agile project management methodology with a Scrum approach, meeting for daily standups and establishing what we worked on, what we were working on next, and any roadblocks we had run into.  Our first set of user stories were to establish that main objective.  We managed our day and workload thourgh Azure DevOps, which was the first time for me.

### 0. Prep
Our first task was to create an idea for an application and establish a page on the website where our app would reside.  As we were approaching Christmas, I decided to make an app that someone could use to story a wishlist of gifts.  

### 1. Create
We next established a model. this wasn't the first time I've worked with Django, but it was the first time I was creating something with this type of functionality from the ground up.

### 2. Read
Next we needed a way to see our model on the webpage, and display its details.  

### 3. Update and Delete
Finallaly, in order to have true CRUD functionality, we needed a way for a user to update and delete the indivdual items they created.

### 4. APIs
After establishing that part of the project, I moved on to add APIs to the project.  Keeping with the theme, I found an API call that pulls a Christmas Theme Joke.  Learning how to parse through the json was a great learning experience.

## 5. Beautiful Soup
Next, I learned about Beautiful Soup and data scrapping.  This is where I ran into my first real roadblock.  Getting the data from the website was easy enough, but I was having alot of trouble getting the lines of data displaying with the right identation.  This was due to the fact the data scrapping was grabbing the line breaks.  I ended up finding a way ti strip out that content so I could display the way I wanted it to look.

## 6. Saving API
One of our last stories was to save the content from the API.  It also gave me an oppertunity to fix a small bug I found with the API where it was displaying apostrophes wrong.  It took some serious debugging, but I found that the API info I was getting back was using a non unicode character for the apostrophe, and the parser was interrpeting it strangely. I was able to do a simple replace command to fix that.  Learning how to pass the information into a model to save it was a neat experinece.

## 7. Final code
Lastly, I prettied up the front end display.  If I had more time I would have incorporated more javascript, but overall I am proud of the end product.
