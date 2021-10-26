1. Before deployment, you must first push your project to Github.
2. Go to Netlify and sign up for an account (you can use your Github account to sign up).
3. Navigate to your project directory and execute the following in the terminal:
○ npm run build
○ This will create a build directory with a production build of your app.
4. Install the netlify-cli globally by executing:
○ npm install netlify-cli -g
5. Finally, deploy your web app to Netlify by executing:
○ netlify deploy
6. When prompted, select “Create and configure a new site”, name your site and deploy the build directory.

https://reactdeploycpsc2600elvislam.netlify.app/