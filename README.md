# __apnaCollege-CSS

## CSS (Cascading Style Sheet)

### What is CSS?

It is a language that is used to describe the <mark>style</mark> of a document.

## Basic Format of CSS :

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


