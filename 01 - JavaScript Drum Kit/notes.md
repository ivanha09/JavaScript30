## Using flexbox to align div items on the page.

https://thoughtbot.com/blog/positioning

flex: 1;
min-height: 100vh;
align-items: center;
justify-content: center;

Keep these things in mind.

## Find the Keypress

https://stackoverflow.com/questions/16089421/simplest-way-to-detect-keypresses-in-javascript

## How to change a divs class

https://www.geeksforgeeks.org/change-an-element-class-javascript/

## Check if array includes a value

https://stackoverflow.com/questions/7378228/check-if-an-element-is-present-in-an-array

## Make div full-screen

https://stackoverflow.com/questions/1719452/how-to-make-a-div-always-full-screen
html, body {
height: 100%;
margin: 0;
}

        #wrapper {
            min-height: 100%;
        }

play sound
https://stackoverflow.com/questions/9419263/playing-audio-with-javascript

https://stackoverflow.com/questions/17636310/play-audio-and-restart-it-onclick

## background-size: cover

Makes sure the background image covers the entire screen even if it neeeds to stretch the image.

## help reset the git protocol

https://stackoverflow.com/questions/53012197/fatal-protocol-https-is-not-supported-in-git

git remote set-url origin https://github/.../ndas.git

## understanding flex: 1

https://developer.mozilla.org/en-US/docs/Web/CSS/flex
https://www.w3.org/TR/css-flexbox-1/#flex-common

## data-

https://developer.mozilla.org/en-US/docs/Learn/HTML/Howto/Use_data_attributes

if you need to add some kind of data attribute you could use data-

data-key="65"

## event.listener

window.addEventListener('action', function(event)){
console.log(event);
}

event would return the information about the KeyboardEvent

## querySelector(' ')

This would fine a specific attribute

## querySelectorAll(' ')

This would find all instances of it.

## es6 template literals - interpolation

https://flaviocopes.com/javascript-template-literals/
template literals use backticks ``.
`${ }` <- this is can take variables an expression an interpolate it into a string.

By using back ticks we can create the expressions in \${ }

## CSS transition

## classList.adding/removing/toggle

.classList.add
.classList.remove
.classList.toggle

## arrow function

=>

# Git from command line

…or create a new repository on the command line
echo "# JavaScript30" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/ivanha09/JavaScript30.git
git push -u origin master

https://rogerdudler.github.io/git-guide/
