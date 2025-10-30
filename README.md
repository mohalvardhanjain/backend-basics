# learning backend

Learning backend with javascript from chai aur backend youtube playlist

go to package.json after doing npm init and add this there:
"type": "module",

Set up for backend -> Run these commands in the terminal of backend folder

npm init
git init
git add .
git commit -m "add initial files for backend"
git branch -M main
git remote add origin https://github.com/mohalvardhanjain/backend-basics.git
git push -u origin main
mkdir public
cd public/
mkdir temp
touch .gitkeep
cd ../..
touch .gitignore
mkdir src
cd src/
touch app.js constants.js index.js
npm i -D nodemon 
(after installing nodemon as a devDependency go to package.json and in scripts add "dev": "nodemon src/index.js")
cd ..
touch .env
mkdir controllers db middlewares models routes utils
npm i -D prettier
cd ..
touch .prettierrc .prettierignore