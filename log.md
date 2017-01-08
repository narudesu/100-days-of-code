# 100 Days Of Code - Log

### Day 0x1: January 3, 2016
*1.5 Hours*

**Today's Progress**: I have set up the environment, downloaded React, Webpack, Babel and React Router. I have also set up a basic skeleton.

**Thoughts**: I am quite happy that I actually got out of my bed and went coding even though I have been quite tired after I came home from a long day at school. I hope that my commitment will not fade and that I will keep the momentum (rather small at the moment, but we'll get there, don't worry 👌 ).

**What I plan to do next**: I plan to set up the backend and implement an authentication for an authentication page. I will also set up Sequelize.js to work with the database.

**Links to work**:
[Day 0x1](https://github.com/narudesu/photo-voter/tree/9cbf05e6d6c34d92709d4beadcb63744024eb7d5)

### Day 0x2: January 4, 2016
*2.5 Hours*

**Today's Progress**: I have created a navbar at the frontend. I have set up the backend with express and babel. I also added a body-parser and an express-session to manage sessions in the future. I am using Sequelize to access my MySQL database.

**Thoughts**:

I'm not implementing the admin auth just yet.

It is quite easy to get distracted by solving a problem that does not need being solved right now, I spent way too much time on trying to make bootstrap navbar work. (gave up, not important at the moment).

Sequelize seems like a cool way to use databases, but I don't know how to use it at all. I hope I won't get stuck at trying to figure out how to write a complex join query. I also figured out that the admin page should be in a separate file.

My current idea of the project workflow:
1. Create the react app that voters will see, make it load images, use local data at this moment
2. Set up the REST API for obtaining all the data components from step 1 need, use database data
3. Figure out a way to make a modular voter authentication (I'll be using an app our school provides us to view our grades etc., but it should be modular so that other people may reimplement it easily)
4. Set up an admin page that will change the data in the database (creating competitions, adding photos, ...)
5. Style the app, add icons, animations, ...

**What I plan to do next**: I plan to create a /competitions route at the frontend that displays all competitions (present, future and past). Once the competition is clicked, the photos appear.

**Links to work**:
[Day 0x2](https://github.com/narudesu/photo-voter/tree/bca6be93d221cab3ef4aa50dd3ba07bc51ab0ed6)

### Day 0x3: January 5, 2016
*1.75 Hours*

**Today's Progress**: I have set up the competition routes and created the components. Competitions component renders a list of competitions that are color coded based on their actual state. When you click on a competition's name, you get to a more detailed view where you see the photos.

**Thoughts**: I'll probably use redux in the future, but for now I have just created a wannabestore that acts almost like a store to provide data to multiple components.

**What I plan to do next**: I plan to turn photos into cards to make it easier to view them. I will add some action buttons like Add a vote. I will start working on a fullscreen preview of a photo.

**Links to work**:
[Day 0x3](https://github.com/narudesu/photo-voter/tree/8860d9b38f1a9efe57e23cd5b575c57ab4539beb)

### Day 0x4: January 6, 2016
*2 Hours*

**Today's Progress**: I have created Photo tiles that display photo's name and vote count. They have a semi-transparent bottom pane that contains the text information. The photos themselves are zoomed in to ensure proper rendering of border ratios at all sizes.

**Thoughts**: Although I planned to use cards, tiles are much better as they allow a bigger portion of the photo to be displayed. The transparent pane also makes it easier to view the photo. The photo will probably need some alignment in the future, but the current centered rendering works now. The tile height will also need to be styled responsively to look better.

**What I plan to do next**: Next time, I am going to add the buttons for fullscreen view and adding to a vote basket. The vote basket is a place that will be used to contain photos you like the most so that you can compare them later and decide for the best one. I will also try to implement the fullscreen view.

**Links to work**:
[Day 0x4](https://github.com/narudesu/photo-voter/tree/791df4c8ea7376e66b5e7f8c9985fc3c0096ac8f)


### Day 0x5: January 7, 2016
*5 Hours*

**Today's Progress**: Today, I have worked on a project I am creating for an IoE competition. We are creating an advanced drunkness tester. I have created a webpage to display the results and a server to collect data from the actual devices. I'm not publishing the source code at the moment, but I might in the future. I've also created a basic WiFi connection code with an HTTP GET request on the device (ESP8266 NODEMCU 1.0 with Arduino IDE (I've hopefully typed this the right way, it has so many different names... so confusing))

**Thoughts**: Working on a different set of problems definitely helps. Also, trying to plug in a 2+ pin analog sensor into one analog port is tons of fun... Unfortunately, I don't have time for twitter (I need to sleep). I'll start doing the twitter stuff once I have more time. (damn, I need time so badly)

**What I plan to do next**: I'll hopefully won't need to write much competition code. So basically the stuff I hoped to do today.

**Links to work**:
[Day 0x5](#)

<!-- ### Day 0x1: January 3, 2016
*1.5 Hours*

**Today's Progress**:

**Thoughts**:

**What I plan to do next**:

**Links to work**:
[Day 0x1]() -->
