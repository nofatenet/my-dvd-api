# my-dvd-api
My DVD Collection API

---

I have created this Repo so I can use it as a Mock Up for an Online Version of the JSON-SERVER DB!

1. Have a working Repo
2. Create a db.json
3. install json-server with: "npm install json-server"
4. Try it out localy with: "json-server --watch db.json"

---
The Goal is to have this API online on the Net, so we make a NODE Server:

5. Create .gitignore and insert: "node_modules"!
6. Git add to Repo: "git add .", "git commit -m add dvds", "git push origin HEAD"

    6.1 It does not work any longer: Need to push with a TOKEN, like this:
        git push "https://nofatenet:TOKEN_HERE@github.com/nofatenet/my-dvd-api"

7. Need a package.json for the Project, so get one with: "npm init".
8. Add JSON-SERVER to the dependencies, with "npm install json-server" again
9. Insert a "start": "node server.js" to the package.json under "scripts"
10. Create a server.js file

---
Still need a Service to Deploy it online. So we use HEROKU:

11. Install HEROKU CLI: https://devcenter.heroku.com/articles/heroku-cli#install-the-heroku-cli
12. To verify your CLI installation, use "heroku --version"
13. Add it to the Package: "npm install -g heroku"
14. Log IN: "heroku login"
15. Create a Project for Heroku: "heroku create my-dvd-api-online"
16. To Deploy to HEROKU, use "git push heroku main"
17. Let the browser open it with: "heroku open" - Working? Well Done!

---

To Do:

When PUSH, where do the credentials come from?

---

Integrate Data into "Video Drome" App.
