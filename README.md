# 6.1-Webapps

#### User Experience (UX)
- User Experience (UX) relates to a person’s emotions and feelings when using a particular product or service, such as a website or application.

#### User Experience Design (UXD)
- User Experience Design (UXD) is the process of improving a person’s experience of using a particular product or service.
- Key facets include:
	- Usability
	- Accessibility
	- Desirability
	- Credibility
	- Usefulness
	- Value


#### What is a Wireframe?
- A wireframe is a mock-up of a web page’s structure
- It includes elements to demonstrate format and functionality
- Elements are organised to achieve a particular purpose or goal  
![](Wireframe%20ex.JPG)

![](htmlcss.JPG)

### headers
- h1
- h2
- h3 etc.

```html
    <h1>Webapps Course Content</h1>
    
    <h2 id ="design">Design</h2>

    <h2>HTML and CSS</h2>
    
    <h2 >Assessments</h2>

    <h3 class ="assessment">exam</h3>

    <h3 class ="assessment">project</h3>

```

![](htmlbasic.JPG)

```html
<!DOCTYPE html>
<html lang="en">
    
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="stylefirst.css" />
</head>
<body style="background-color: beige;">
    <link rel="stylesheet" href="style.css">
    <h1>Webapps Course Content</h1>
    <a href="Second.html" class="button1">Click me!</a>
    <a href="examples-para-anchor-image.html" class="button1">examples-para-anchor-image</a>

    <h2 id ="design">Design</h2>

    <h2>HTML and CSS</h2>
    <p>lorem ipsum lorem ipsum</p>
    <h2 >Assessments</h2>

    <h3 class ="assessment">exam</h3>

    <h3 class ="assessment">project</h3>
</body>
</html>
```

#### link to css using reference in header
```html
    <link rel="stylesheet" href="stylefirst.css" />
 ```
 - in css we can have class id and use attributes to identify and change the deign
 
```css

h1{
    color:blue;
    text-align: left;
    background-color: #f0f8ff;
    margin: 10%;
    font-family: cursive;
}


h2{
    color:blue;
    text-align:center;
    background-color: rgb(244, 244, 244);
    width:50%;
}


#design{
    color:rgb(34, 252, 204);
    text-align:center;
    background-color: rgb(231, 24, 24);
    width:70%;
}

.assessment{
    color:rgb(255, 255, 255);
    text-align:left;
    background-color: rgb(36, 9, 134);
    width:70%;
    font-weight: lighter;
}

a.button1{
    background-color: blanchedalmond;
    display: inline-block;
    padding: 0.5em 3em;
    border: 0.16em solid #FFFFFF;
    margin:0 0.3em 0.3em 0;
    box-sizing: border-box;
    text-decoration:none;
    text-transform:uppercase;
    font-family:'Roboto',sans-serif;
    color:#000000;
    text-align: center;
    transition: all 0.15s;
    }

a.button1:hover{
    color: #dddddd;
    border-color:#DDDDDD;
}
a.button1:active{
    color: #0000ff;
    border-color: #0800ff
}

```