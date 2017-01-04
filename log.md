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

<!-- ### Day 0x1: January 3, 2016
*1.5 Hours*

**Today's Progress**:

**Thoughts**:

**What I plan to do next**:

**Links to work**:
[Day 0x1]() -->
