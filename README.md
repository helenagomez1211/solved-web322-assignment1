Download Link: https://assignmentchef.com/product/solved-web322-assignment1
<br>
This first assignment will get you setup with your environment, tooling, and a Heroku account as well as introduce you to the development workflow used in this course (Visual Studio Code + Git + Heroku).

<h1>Specification:</h1>

For this assignment, we will be publishing our first web app on <a href="https://www.heroku.com/home">Heroku</a>.

<strong><u>Step 1:</u></strong> Installing Software

In order to create web applications and publish them online, you will need to download and install the following software.

<ul>

 <li><a href="https://code.visualstudio.com/download">Visual Studio Code</a></li>

 <li><a href="https://nodejs.org/en/download/">js</a></li>

 <li><a href="https://git-scm.com/downloads">Git</a></li>

 <li><a href="https://devcenter.heroku.com/articles/heroku-cli#download-and-install">Heroku CLI (Command Line Interface)</a></li>

</ul>

<h3><strong><u>Step 2</u></strong><strong>:</strong> Following the Guide</h3>

The next step involves following along with the “<strong>Getting Started With Heroku</strong>” Guide available on the <a href="https://web322.ca/getting-started-with-heroku">course website</a>.  You may skip the “<strong>Required Software</strong>” section, however if you need help verifying that the required software is installed correctly this section provides some additional information

<h3> <strong><u>Step 3</u>:</strong> Customizing the server code (server.js)</h3>

Once you have completed the guide (Step 2), and have a simple “Hello World” app running on Heroku, you must personalize the output:

<ul>

 <li>Instead of “Hello World” – change your app to output your full name and student number, for example “Mohammad Shamas – 037465064”</li>

 <li><strong>HINT</strong>: If you make any changes to your server.js file after publishing to Heroku, you will have to:

  <ul>

   <li>Commit your changes to your local git repo using the following procedure:

    <ul>

     <li>Click on the Source Control Icon in the sidebar that has a “1” on it in Visual Studio Code</li>

     <li>Enter a message (in the “Message” box) describing your change, ie “updated server.js”</li>

     <li>Click the checkmark above the message box to commit your changes.</li>

    </ul></li>

   <li>Push your changes to Heroku by issuing the command: ” git push heroku master” from the Integrated Terminal in Visual Studio Code</li>

  </ul></li>

</ul>