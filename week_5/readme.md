## 0.html
We will make a HTML Page maybe sort of blog or something which is static in itself 

Since this is a Static Website hence REACT will not be needed

For Dynamic Websites this "Libraries" make it easier to do dom manipulation

## 1.html
Make a Simple Counter in HTML with working functionality

## Thing to worry about React
## State
## Component
## Re-Rendering

All Websites are divided into two parts :States and Components

## State :
An object that represents the current state of the app
It represents the dynamic things in your app (things that change)
For example, the value of the counter

Say for example top bar of linkedin only not while website

Dynamic Things:
{
  topbar: {
    home: 0, 
    myNetwork: "99+", 
    jobs: 0, 
    messaging: 0, 
    notificaitons:10
    }
  }

Dom rendering the state:
It is a re-usable, dynamic, HTML snippet that changes given the state

"button" is component
takes state(currentCount) as input

We give react State and Component
React takes care of updating them

Expect Dev to write code:
1.Give state of app
2.give individual component and structure
3.how state is connected to components

Now react just updates it under the hood

## Rerendering:
A state change triggers a re-render
A re-render represents the actual DOM being manipulated when state changes

A Counter App using state/components-counter.html
1.State initialisation

## Component
A function take props/state as input and return back html is Component

## counter.html
It uses the concept of State and Component with javascript to make a counter 

## counter-app
The equivalent code in react is in 'counter-app'

Apply same process for Project: counter-app

remove everything from index.css we will get again that html file

This was a static site written in dynamic style

making it dynamic

npm run build-sort of convert into html,css,js into dist folder
npm run dev-to u know run the file

And it is actually done

## To Do Application:
src/App.jsx

Start by defining simple todo state
Then Complicated string and render one after another

We can start by dumping whole(it will be dumbest way)

Problem:Very Ugly

Whenever rendering array-create a component given a single todo

Todo compenet created
Look at code 
try to understand it once again
look to make something from you side

## ToDo_2 :
it will be last class of week 5
i really don't know will see it

## Assignment (29.02.2024)->
week-5/level-1/Business/src/App.jsx,app.css
use them and we made the fucking buisness card,we were required to use the css hence did it using raw css
done for now

this is a side project->
hey,hey this folder was made by us for the part in the projects folder

move to week 6