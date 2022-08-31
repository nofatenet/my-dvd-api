# my-dvd-api
My DVD Collection API

---

I have created this Repo so I can use it as a Mock Up for an Online Version of the JSON-SERVER DB!

1. Have a working Repo
2. Create a db.json
3. install json-server with: "npm install json-server"
4. Try it out localy with: "json-server --watch db.json"

---
Need it online. So we use HEROKU:

5. Create .gitignore and insert: "node_modules"!
6. Git add to Repo: "git add .", "git commit -m add dvds", "git push origin HEAD"

    6.1 It does not work any longer: Need to push with a TOKEN, like this:
        git push "https://nofatenet:TOKEN_HERE@github.com/nofatenet/my-dvd-api"

7. Need a package.json for the Project, so get one with:
