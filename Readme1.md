Creating a new react app in Class-2 of Bootcamp.

I could create a react app using yarn create react-app  in cmd prompt which was working through local directory, But, upon deploying through Github Workflow to surge, It gae me an Error:  Access to node-module.cache and stopped deploying.

Now let's try creating a new react-app using "npm create-react-app" or otherwise "yarn create react-app".

<<----------------------------------      Command Line Code       ------------------------------------------>>

Microsoft Windows [Version 10.0.19045.5011]
(c) Microsoft Corporation. All rights reserved.

C:\Users\Work>cd C:\Users\Work\Documents\GitHub\Bootcamp2020\Bootcamp-C2-P2

C:\Users\Work\Documents\GitHub\Bootcamp2020\Bootcamp-C2-P2>node -v
v18.20.4

C:\Users\Work\Documents\GitHub\Bootcamp2020\Bootcamp-C2-P2>npx create-react-app .
Need to install the following packages:
create-react-app@5.0.1
Ok to proceed? (y)

Cannot create a project named "Bootcamp-C2-P2" because of npm naming restrictions:

  * name can no longer contain capital letters

Please choose a different project name.

C:\Users\Work\Documents\GitHub\Bootcamp2020\Bootcamp-C2-P2>npx create-react-app bootcamp-c2-p2

Creating a new React app in C:\Users\Work\Documents\GitHub\Bootcamp2020\Bootcamp-C2-P2\bootcamp-c2-p2.

Installing packages. This might take a couple of minutes.
Installing react, react-dom, and react-scripts with cra-template...


added 1314 packages in 7m

259 packages are looking for funding
  run `npm fund` for details

Installing template dependencies using npm...

added 46 packages, and changed 1 package in 44s

263 packages are looking for funding
  run `npm fund` for details
Removing template package using npm...


removed 1 package, and audited 1360 packages in 8s

263 packages are looking for funding
  run `npm fund` for details

8 vulnerabilities (2 moderate, 6 high)

To address all issues (including breaking changes), run:
  npm audit fix --force

Run `npm audit` for details.

Success! Created bootcamp-c2-p2 at C:\Users\Work\Documents\GitHub\Bootcamp2020\Bootcamp-C2-P2\bootcamp-c2-p2
Inside that directory, you can run several commands:

  npm start
    Starts the development server.

  npm run build
    Bundles the app into static files for production.

  npm test
    Starts the test runner.

  npm run eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

We suggest that you begin by typing:

  cd bootcamp-c2-p2
  npm start

Happy hacking!

C:\Users\Work\Documents\GitHub\Bootcamp2020\Bootcamp-C2-P2>

<<_____________  MashaAllah!  React App created successfully using "npm create-react-app"  _________________________>>




<<<---------------------      Terminal Code   --------------------------------->>>

PS C:\Users\Work\Documents\GitHub\Bootcamp2020\Bootcamp-C2-P2> git init
Reinitialized existing Git repository in C:/Users/Work/Documents/GitHub/Bootcamp2020/Bootcamp-C2-P2/.git/
PS C:\Users\Work\Documents\GitHub\Bootcamp2020\Bootcamp-C2-P2> git add .
PS C:\Users\Work\Documents\GitHub\Bootcamp2020\Bootcamp-C2-P2> git commit -m "First commit"
[main bd8ce6b] First commit     
 1 file changed, 5 insertions(+)
 create mode 100644 Readme.md   
PS C:\Users\Work\Documents\GitHub\Bootcamp2020\Bootcamp-C2-P2> git branch -M main
PS C:\Users\Work\Documents\GitHub\Bootcamp2020\Bootcamp-C2-P2> git push -u origin main

Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 502 bytes | 100.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/FarhadAbbasi/Bootcamp-C2-P2.git
   e23ac7a..bd8ce6b  main -> main
branch 'main' set up to track 'origin/main'.


Starting the development server...

One of your dependencies, babel-preset-react-app, is importing the
Compiled successfully!

You can now view bootcamp-c2-p2 in the browser.  

  Local:            http://localhost:3000        
  On Your Network:  http://192.168.0.103:3000    

Note that the development build is not optimized.
To create a production build, use npm run build. 

webpack compiled successfully



