To start app, run `npm start` and open browser to localhost:3000

That will bring up the landing page to register or login.

Front end: Angular.js and bootstrap.css

Back end: node/express server, mongo db

Iterations:
1. Create functional app on the front-end.  Files involved: app.jade, and files in public directory. -Nate

2. Create user registeration for admins: Connect express server with mongo db.  When the user registers or logs in, the user is redirected to app.js. -curt

Admin users are users that can create bulk list of tasks.  Passwords should have a salt/hash. Usernames should be email format, passwords need to match password confirmations.  Etc, or up to Kurt at this point.

3. Create employee interface: When an employee logs in, they can see tasks that their admins have created, add tasks to complete, and submit completion of tasks.

4. Beyond: Add in unit and e2e testing.  Add in typescript.  Make the ui more intersting.