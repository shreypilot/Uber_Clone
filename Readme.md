src->
-components
-screens -> where put all our screens
-navigations 
->contexts -> you're gonna have to manage some data at the global level 
-reducers
-globals->for global data for example global styles and dummy data  
  -style.js -global styles are those  file which is used for various screens and components
  -data.js ->fetch data from here to create the ui quickly once we're done with the ui we're gonna delete this and start fetching data from ourserver which interacted the database which will be the mongodb in this case 


  SCREEN_WIDTH->get it from the dimensions api from react native dimensions object get dot get call this method and this will be window myth  we re goona from the windows object  and get the width and should be the width of ur screen


 headerShown: false in the options for a screen within a StackNavigator means that the navigation header (the bar at the top of the screen containing the title and sometimes buttons) will not be displayed for that specific screen. This is often used when you want to have a screen without any navigation header, or if you want to implement a custom header or handle navigation differently for that screen.