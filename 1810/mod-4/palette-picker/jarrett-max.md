# Palette Picker Submission Form

 [Project Spec](http://frontend.turing.io/projects/palette-picker.html)

 # Basics

 #### Link to the GitHub Repository for the BE
[Hexbrush BE](https://github.com/jarretkong/hexbrush-be)

 #### Link to the Deployed BE
[Heroku BE](https://hexbrush.herokuapp.com/)

 #### Link to the GitHub Repository for the FE
[Hexbrush FE](https://github.com/maxbsilver/hexbrush-fe)

 #### Link to the Deployed FE
[Heroku FE](https://palit-picker.herokuapp.com/)

 ## Completion

 #### Were you able to complete the base functionality?

 Yes

 #### Link to an image of your wireframe(s)
- On GitHub FE repository

 #### Which extensions, if any, did you complete?
 
 - Ability to edit projects/palettes, but did not include the color selector.

 # Code Quality

 #### Link to a specific block of your code on GitHub (from either repository) that you are proud of
[good code](https://github.com/jarrettkong/hexbrush-be/blob/master/server.js)

 * Why were you proud of this piece of code?  
- Lines 196-219: DELETE projects endpoint. I was very happy with this code because it was the first time I had deleted from multiple tables in a relational database. I learned about how the databases were connected, and that deleting a foreign key is required before deleting any data with the primary key.

 #### Link to a specific block of your code on GitHub that you feel not great about
[bad code](https://github.com/MaxBSilver/hexbrush-fe/blob/master/src/components/App/App.jsx)

 * Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
- Lines 121-142: editPalette function. This code isn't very dynamic, and the way we solved it was to set an object in state with all of our edit configurations. We knew this isn't the optimal way to complete this, but it was a working solution and we hope to refactor it later.

 #### Link to Design Inspiration

 * Show us what you used as design inspiration (another color picker site, a dribbble UI element, a user flow, etc.) and explain what you stole from it  
- [This video](https://www.youtube.com/watch?v=DexyfHomC4Q) was the main inspiration for the app's UI. The overall functionality of both apps varies wildly, but the teardrop design came from this project.

 #### Reflection on New Concepts

 * Describe your thoughts on server-side testing  
- Server side testing itself is not a problem, but we are still a bit fuzzy on setting up different environments for different needs.
- We also struggled with Travis CI. The command line tool wasn't working on either computer we tried it on, even after installing. It builds and passes all the tests, and Heroku is current, but we were unable to link the two.
* Describe your thoughts in creating a single project whose codebase was distributed across multiple repositories

 -----


 # Instructor Feedback (Instructor Name)

 ## Specification Adherence

 **x score**: 

 ## User Interface

 **x score**: 

 ## Testing

 **x score**: 

 ## Workflow

 **x score**: 

 # Outcome: pass/fail
