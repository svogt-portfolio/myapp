# myapp - node.js

My first node.js app!  

Complete credit goes to this tutorial: [Express.js & Node.js Course for Beginners - Full Tutorial](https://www.youtube.com/watch?v=G8uL0lFFoN0)

Install appropriate tools in your environment (git, nvm, npm/node.js, postgresql, sequelize-cli).  Install and start your app as follows:
  
    # Clone repository.
    git clone ...
    
    # Start from <app_root> in terminal.
    cd <app_root>
    
    # Install app node_modules
    npm install
    
    # Edit <app_root>/config/config.js to add information about the database.  
    # Run any db migrations.
    
    sequelize db:migrate
        
    # Run the app in a terminal window as follows.  Stop with ^C.  Log messages go to window where you are running the app.
    DEBUG=myapp:* npm start
    
    # Access the app from your browser as:
    http://localhost:3000

This is a 'development' environment app, so we use nodemon rather than node to run the app.  Nodemon monitors the code for changes and restarts the app when that happens so that you don't have to restart the app manually to incorporate code changes.
