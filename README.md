# HTML & CSS Full Course

## Visual Studio Code

Download Visual Studio Code [Here](https://code.visualstudio.com/)

Right click anywhere on your computer and create a new folder

Open Visual Studio Code

Create a new file such as `hello.txt`

Start writing in the newly created text file

You can also delete this file in VSCode

🙌 You now know the fundmentals of VSCode 🙌

## HTML

##### Absolute Basics

Create a file called `index.html`

Tell the browser it is reading HTML:

```html
<html>

</html>
```

Give the HTML document a head tag and body tag:

```html
<html>
    <head>

    </head>
    <body>

    </body>
</html>
```

Give your website a name:

```html
<html>
    <head>
        <title>My First Website</title>
    </head>
    <body>

    </body>
</html>
```

Give your website some text:

```html
<html>
    <head>
        <title>My First Website</title>
    </head>
    <body>
        <p>Hello World</p>
    </body>
</html>
```

Open up your HTML website by right clicking and opening it in a browser

##### Speeding Things Up with EMMET

Programmers never type everything out

In a new index.html page type '!'

Now press <kbd>TAB</kbd>

Your HTML should look like this:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport">
    <title>Document</title>
</head>
<body>

</body>
</html>
```

This code above is essentialy the building blocks of a modern HTML website

This code is optomized for search engines to know things such as this page being written in english

<head> contains information that is not displayed directly on the webpage

<body> is where most of your content goes such as text and images

##### Text

h1,h2,h3,h4,h5,h6 are all used for headings

p is used for paragraphs

```html
<body>
    <h1>My Title</h1>
    <h2>My Subtitle</h2>
    <p>This is some text</p>
</body>
```

##### Links

a or anchor tags are used to link to other webpages or websites

Let us try and add a link to wikipedia:

```html
<body>
    <h1>My Title</h1>
    <h2>My Subtitle</h2>
    <p>This is some text</p>
    <p>Click here to go to <a href="https://en.wikipedia.org/wiki/Main_Page">wikipedia yay!</a> You can learn lots!! </p>
</body>
```

##### Images

You can also link images

Search for your favourite image 

Right click the image and copy image adress

Use the power of the img tag!:

```<body>
<body>
    <h1>My Title</h1>
    <h2>My Subtitle</h2>
    <p>This is some text</p>
    <p>Click here to go to <a href="https://en.wikipedia.org/wiki/Main_Page">wikipedia yay!</a> You can learn lots!! </p>
    <img src="https://static.wikia.nocookie.net/littlewitch/images/f/f1/Akko_Kagari.png/revision/latest/top-crop/width/360/height/450?cb=20170822115827">
</body>
```

##### Adding Images Locally

Save your image to the folder where ```index.html``` is located

Name it something easy like ```awesome.png```

Link it like so: 

```html
<img src="awesome.png">
```

Now create a folder and name it 'pictures'

Move your image to pictures

Now try and show an image with this new location:

```html
<img src="pictures/awesome.png">
```

##### Adding and Linking Webpages

Create a new file and name it ```cool.html``` this will be the hub for your second webpage

Fill out cool.html remembering to link back to index.html !

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p>This is my cool page</p>
    <p>Go back to my home <a href="index.html">with this link</a></p>
</body>
</html>
```

Oh and lets make sure we can get to ```cool.html``` from ```index.html```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>My Title</h1>
    <h2>My Subtitle</h2>
    <p>This is some text</p>
    <p>Click here to go to <a href="https://en.wikipedia.org/wiki/Main_Page">wikipedia yay!</a> You can learn lots!! </p>
    <img src="pictures/akko.png">
    <p We are going to a cool page > <a href="cool.html">with this link!!!</a> </p>
</body>
</html>
```

##### Embedding Videos

Go to youtube.com

Go to your faviourite video

Click share then click embed

Paste this embed into your html

```html
<body>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/ok-plXXHlWw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</body>
```

##### Adding a favicon

Go to your head tag

Type link and keep pressing down until you highlight 'favicon'

Press tab and you would have created this piece of code:

```html
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
</head>
```

Now let us download a ```favicon.ico``` and move it to your websites folder




