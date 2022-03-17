__#Basic API#__

This API build is based on _Max Sandelin_'s tutorial for API construction, which in turn stems from his tutorial on building a Javascript/HTML/CSS todo list.

Along with a few Node addons including node_modules and MySQL2, knowledge of and use of SQL is also an important part of this tutorial. The simplest parts one needs can be set up fairly easily and quickly; for those unfamiliar or in need of a quick install, I recommend the tutorial by _Amit Thinks_.

*API Tutorial:* https://www.youtube.com/watch?v=0SiC1DClaFg

*Todo Tutorial:* https://www.youtube.com/watch?v=2wCpkOk2uCg

*MySQL Setup Tutorial:* https://www.youtube.com/watch?v=OM4aZJW_Ojs


__##How to Use This API##__

1. Clone the repo to your own coding folder: 

    $ git clone https://www.github.com/TheIanCannon/API-tutorial.git 
    <append your own chosen directory name if you desire>

2. Install MySQL if needed, then start up MySQL:

    $ mysql -u root -p;
    $ <enter password>

3. Start up the API and ToDo application:

    $ npm run api

4. Open your browser and go to:

    localhost:3000

5. Add ToDo items as you see fit, update them to Completed (or toggle them back from Completed), or delete them entirely from the list whether complete or not. With your console open, or the terminal in your coding application of choice (such as VSCode), you will be able to see the data added, updated, and removed with each click. Similarly using SQL, you can manually add/update/remove entries from the database created.

__##Next Steps##__

ReactJS is as always a favorite of modern applications. This API works with a JavaScript/HTML/CSS based interface using NodeJS, but after handling other projects requiring refactoring, I would like to refactor this one into ReactJS as well for further skill practice.