# __apnaCollege-CSS

## <mark>CSS</mark> (Cascading Style Sheet)

### What is <mark>CSS</mark>?

It is a language that is used to describe the <mark>style</mark> of a document.

## Basic <mark>Format</mark> of CSS : 

![CSS Format](./img/image.png)

always use semicolon (;) after value.   

## How to <mark>Include</mark> Style :

## 1. Inline Styles
Writing style directly inline on each element.   
`<h1 style="color:red"> Apna College </h1>`

## 2. Using `<style>` tag :
Style is added using the `<style>` element in the same document  
It is feasible for only one page.   
```
<style>
    h1{
        color: red;
    }
</style>
```
 

 ## 3. External Stylesheet :
 Writing CSS in a separate document (css file) & linking it with HTML file.   
 extension of this css file is `.css`

 ### <mark>Linking</mark> HTML with CSS File :

 ```
 <head>
    // write always this line after `<title>` tag 
    <link rel="stylesheet" href="style.css">
 </head>
 ``` 
## <mark>Color</mark> Property :

Used to set the color of forground   
`color: purple;`   
`color: #ffffff;`    


## <mark>Background Color</mark> Property :

Used to set the color of background   
`background-color: purple;`   
`background-color: #ffffff;`    
we can also use `background : #000` but not recommended for to set background color


## Color Systems :

#### Named Color
 color = black;   
Each browser recognizes around 140-150 named colors.    
Eg- red, blue, pink, purple, magenta, teal etc.

#### RGB 

`color = rgb(0,0,0);`   
Red Green Blue (0-255)   
black is rgb(255, 0, 0)    
red is rgb(0, 0, 0)    
blue is rgb(0, 0, 255)    
yellow is rgb(255, 255, 0)    


