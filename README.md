# STEPS FOR SETTING UP SASS PROJECT :-
### 1. Run command "npm init -y" to create "package.json" file.
### 2. Run command "npm install node-sass" to install "node-sass" package.
### 3. Add following command under "scripts" in package.json ->
        "sass": "node-sass -w scss/ -o dist/css/ --recursive"
### 4. create two folders "scss" and "dist" inside main project folder.
### 5. create "main.scss" file in "scss" folder and write SASS code in that.
### 6. run following command to convert scss file to css file -> npm run sass

# NOTE :-
### 1. all the development work is done in scss folder.
### 2. code which we deploy is written in dist folder which includes compiled css file and main html file.
