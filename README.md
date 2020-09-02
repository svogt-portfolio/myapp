# myapp_nodejs
First node.js app!  

Complete credit goes to this tutorial: [Express.js & Node.js Course for Beginners - Full Tutorial](https://www.youtube.com/watch?v=G8uL0lFFoN0)

Install appropriate tools in your environment (git, nvm, npm/node.js, postgresql, sequelize-cli). Install and start your app as follows:
  
    # Clone repository.
    git clone ...
    
    # Start from <app_root> in terminal.
    cd <app_root>
    
    # Install node_modules
    npm install
    
    # Run it in a terminal window as follows.  Stop with ^C.  Log messages go to window where you are running it.
    DEBUG=myapp:* npm start
    
    # Access it from your browser as:
    http://localhost:3000

This is a 'development' environment app, so we use nodemon to run it so we don't have to restart the app for every code change.
