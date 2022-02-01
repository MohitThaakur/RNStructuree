# app

base Folder

## app/containers

Contains the screen of app.

## app/components

Contains stateless, lean components. which can be used anywhere without big updation


## app/helper

Contains util and helper class. These functions must be simple. 


## app/images

Contains images.we also can use assets folder too instead of this


## app/redux/modules

Contains feature based redux elements. Every module must be same name with related container.


### app/redux/modules/{ModuleName}.js

It must be contain action types, actions and reducer. We want keep simple every changes. 
If we split these domains to seperate files, When add a new action, a lot of file affected. We escaping this case.


### app/redux/middlewares

Contains first-party middlewares.


