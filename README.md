# presentation - the interactive presentation tool

## Description
Prsntr.io makes presentations interactive.

Presentations used to be one-way: The presenter talked and walked through her slides, the audience listened and took notes - and spend time on Facebook. With Prsntr.io, the audience becomes interactive, and can go back to previous slides in case they missed something, provide live feedback for the presenter, ask questions, and discuss and answer other students' questions.

## Features
Prsntr.io integrates with Google Slides. The presenter logs in with her Google account, and gets a list of the Google Slides presentations for her account. When she picks a presentation, she is brought to a presenter dashboard that she can run her presentation from, and a projector view opens in a new window, to share with the audience. 

From the presenter dashboard she can move back and forth between slides, see her notes, see questions from the audience, and gets alerted if the audience thinks she is going too fast or too slow. She can also log in from her mobile phone, and can use that as a remote (swipe to move between slides), as well as a microphone. She also gets a link to share with the audience.

With that link, a member of the audience can see the presentation on his own computer or phone, move through slides on his own - useful if he missed something and would like to go back. If he logs in with Google or Facebook, he can also give feedback about the speed of the presentation to the presenter, ask questions and answer other students' questions.

## Tech stack
Prsntr.io is built in Javascript using React on the front end and Node on the backend with a Mongo database. It is built with the Meteor framework, which seamlessly integrates the front end with the back end. It is built with the max possible modularity, as every feature is put into its own NPM module and required. This not only ensures that the platform is easily modified and built upon, it also means that the project will automatically contribute to the open source community.

## MVP features
The Minimum viable product will be a website where a user can log in with Google, choose one of her presentations and see it in full screen mode served by Prsntr.io's server.
