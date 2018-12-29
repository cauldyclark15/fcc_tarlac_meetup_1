# FreeCodeCamp Tarlac Meetup 1

I am...

## Q&A

1. already in Software Development?
2. started [FreeCodeCamp Curriculum](https://www.freecodecamp.org/)?
3. your main objective of joining this group

## Vanilla JavaScript

1. programming language for the web (your browsers, Chrome, Firefox, Internet Explorer...)
2. programming language used in some servers
3. alongside HTML and CSS, JavaScript is one of the three core technologies of the World Wide Web.
4. madaling simulan, madaling execute

##### subukan natin

1. open your web browser
2. open developer tools
3. in devtools console, copy and paste the following

```javascript
const firstNumber = 15;
const secondNumber = 5;

const total = firstNumber + secondNumber;
console.log(total);
```

## Document Object Model

- The Document Object Model (DOM) is a programming API for HTML document. It defines the logical structure of documents and the way a document is accessed and manipulated. 

#### ano daw???

1. create a new file, name it index.html
2. copy and paste this piece of code (tiwala lang)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>FCC Tarlac</title>
</head>
<body>
    <h1>I can do this</h1>
    <h2>I can do this</h2>
    <h3>I can do this</h3>
    <h4>I can do this</h4>
    <p>No doubt</p>
    <small>No doubt</small>
    <div>No doubt</div>
</body>
</html>
```
3. right click on the file, open with your favorite browser
4. [reference](https://www.w3.org/TR/WD-DOM/introduction.html)

## Accessing the DOM

1. refresh your browser
2. copy and paste

```javascript
const onlyH1 = document.getElementById('headerOne');

onlyH1.textContent = 'HO HO HO';
```

#### pagsasanay
1. change the content of all elements inside the `<body>` tag

## JavaScript outside the browser

1. create a new folder named `webapp`
2. inside `webapp`, create a new file `server.js`
3. move your `index.html` to `webapp` folder
--- the rest of this part will be explain by the presentor ---

## React

- run this command from your terminal or command prompt `npm install -g create-react-app`

#### Vanilla/Plain JavaScript
```
const onlyH1 = document.getElementById('headerOne');

onlyH1.textContent = 'HO HO HO';
```

#### React JavaScript
```
<h1>HO HO HO</h1>
```

it is easier to visit [React JavaScript Website](https://reactjs.org/)

## React Native

- run this command from your terminal or command prompt `npm install -g create-react-native-app`

it is easier to visit [React Native Website](https://facebook.github.io/react-native/)

----------------------------------------------------------------------------

useful commands when creating new react or react native projects

- `create-react-app my-web-project` ---> to create a new web application React project
- `create-react-native-app my-mobile-project` ---> to create a new mobile application React Native project
