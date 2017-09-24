# Node-Express-Friend-Fiender

I created a compatibility-based "FriendFinder" application -- basically a dating app. This full-stack site takes in results your users' surveys, then compare their answers with those from other users. The app then displays the name and picture of the user with the best overall match. My application made up of two parts:
1. A front-end set of HTML/CSS/JS pages for entering and viewing data.
2. A back-end composed of Node/Express and basic JS for storing, updating, and comparing friends data.
I used:
* Servers;
* Routing;
* APIs;
* AJAX (GET and POST Requests).

## How app works

A user should answer 10 questions, each answer is on a scale of 1 to 5 based on how much the user agrees or disagrees with a question. 

![1](https://user-images.githubusercontent.com/28790452/30778424-2fd825b2-a09b-11e7-95eb-cf10436e2ba4.gif)

Once the user has found the current user's most compatible friend, the app displays the result as a modal pop-up.
   * The modal displays both the name and picture of the closest match.

![2](https://user-images.githubusercontent.com/28790452/30778425-2ff35080-a09b-11e7-9992-94778eaca7c4.gif)

Click [here](http://art-friend-finder.herokuapp.com/) to see app live.

## Project Installation

There are two methods to download the repository.

#### Method I: Familiar with Git?

Clone this repository, install dependencies, then run the project with the following:

```
> git clone git@github.com:artprofi91/Node-Express-Friend-Finder.git
> cd Node-Express-Friend-Finder
> npm install
```

#### Not Familiar with Git?

Click [here](https://github.com/artprofi91/Node-Express-Friend-Finder) then download the .zip file. Extract the contents of the zip file, then open your terminal, change to the project directory and:

```
> npm install
```
