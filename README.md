## Run the project

### `npm start`

## Stuart Assessment:

I will start explaining things to improve as is the thing that has been bugging me the most, as I would have liked to improve a lot of things. 


First thing I wanted to improve is the architecture, I was inspired by the posts explained architecture section, as I wanted to experiment a bit with React ( I hadn't used it professionally in a while) I would have liked to tweak a lot of things about it (the architecture) to make components and hooks more reusable ( as you will see the map has a window listener which is specific to that component)so some global hooks to be used in components that want to listen to window resize,or global hooks that listen to user inputs and mutate state dynamically according to parameters etc.. 

The redux state architecture isn't optimal either as I should have created a Ui State to store values such as the status of the snackbar.

Another very important thing I would have liked to do to avoid unnecessary renders is memoizing functions and components with React.memo and React.useCllback.
I believe theres no need to memoize selectors right now, but redux reselect is a very nice library to do this... 
I also would have liked to create a production webpack configuration, and deploy the app.

The components and consistency of the code is not fully reviewed and I believe it could also be improved.

I havent had time to test anything , but If I am given more time I would happilly make all the mentioned improvements.

And also texts are passed to components directly as strings, I know that to make an app with the language to be changed dynamically this should be changed as well

## Architecture:
The architecture of this project has been based on:

https://medium.com/@Charles_Stover/optimal-file-structure-for-react-applications-f3e35ad0a145

https://blog.smartlogic.io/redux-design-patterns-reduxsauce/

## Tech Stack:
#### React

#### Webpack

#### Redux

#### Redux Sauce

#### Material-ui Snackbar:
 *I added the whole material ui library just for the snackbar as I just wanted to make something fast , but fixing this with webpack tree shaking could be possible ( i believe its doing some allready but haven't had time to dig into that more deeply).*
 
 and many more!!!# map-markers
