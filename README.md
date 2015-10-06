# CSE5335-project-1
-----------

Name	: Sarath Kumar Siva Kumar
-----------

UTA ID	: 1001108398
-----------

Netid	: sxs8398
-----------

Webdata Managment and  Xml Project1
-----------

Website               : https://cse5335-sxs8398.herokuapp.com/
-----------


a. Server side framework : Ruby-on-rails

* I have chosen ruby-on-rails over nodejs as I want to learn something new and makes you adhere to its way of things out-of-box.
* It is fast for running so that any changes which are done, are implemented fastily. 
* Rails has ORM model which makes it easy to maintanence and database intregration. There is need to add pre-requiste to the web application while deploying. Just add the dependancy in the gemfile which does the work. This is one of the simpliest way to ads dependancy.

b. Client Side framework : Jquery

* It is easy to integrate  with any front end framework without any problem and has many built-in function which are ready-to-use.

c. Implementation which was easy

* Jquery finds easiest way to integrate with any kind of framework . 
* A simple script tag will do the work for all the external libraries to be included.
* Pushing the application into heroku server was the easiest thing to do. 
* Everything has to be written from the scratch for node.js unlike in Jquery.

d. Implementation which was hard

    Before starting ruby-on-rails, one has to neccessary knowledge about the control flow to develope the application. Once you have fully learned, you can make use of all function in it.The data to built the json was also difficult part.

e. OTHER than your client and server framework did you install

    For current requirement, we dont need anyother framework.

f. Ubuntu commands to deploy and run your server

######## Github

    git init
    echo "# CSE5335-project-1" >> README.md
    git commit -m "First"
    git remote add origin "https://github.com/SarathKumar-Sivakumar/CSE5355-project-1.git"
    git push -u origin master
    git clone https://github.com/SarathKumar-Sivakumar/CSE5335-project-1.git
  
######## Put all the project files in the folder

    git commit -m "Second"
    git push
  
######## Add collaborators for github

    Add GTA as collaborator for github        : emmons-uts
    Add Professor as collaborator for github  : samvarankashyap

######## Heroku

    wget -O- https://toolbelt.heroku.com/install-ubuntu.sh | sh
    heroku login
    heroku create cse5335-sxs8398
    git push heroku master

######## Add collaborators for heroku

    GTA as collaborator                       : heroku sharing:add samvaran.rallabandi@mavs.uta.edu
    Professor as collaborator                 : heroku sharing:add emmons@uta.edu
