# Netlify

Getting started with deploying React Code on Netlify
Steps
One time Steps
Create an account on netlify.com
Go to the root directory of your folder and run
npm i netlify-cli
To deploy
You should have a build folder
Go to the project folder and run
npm run build
In the same folder, run
npx netlify deploy
and sign in if required
Choose Create & Configure a new site
Enter Optional Site name
In publish directory, enter "build"
If you use separate links for separate projects, run
npx netlify deploy --prod
Otherwise just use the Website Draft URL
