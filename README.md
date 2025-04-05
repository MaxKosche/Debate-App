# Debate-App
Initial Prompt to cursor: Create a web app that lets users input a prompt to be debated on between different people. The people should be Plato, Aristotle, Socrates, Aquinas, Rene Descartes, and Lao Tzu. Allow users to filter which people they want to respond to the prompt. Add a slider to measure how long the debate between the people should be. Please create the app with simple vanilla HTML, CSS, and Javascript.
Cursor's response: Cursor created an app that allows the user to select between which historical figures they want to participate (at least two), and added an adjustable slider depending on how long they wanted the debate to be. Then, the figures will answer the prompt generated by the user.
Was it what you expected: Yes, though I had to incorporate an OpenAI key in order to improve quality responses that are limited between 2-3 sentences for cohesion, as well as error handlings.
Followup Prompts to Cursor:
Prompt 1; Add user registration and login to the app, and change the app to use persistent data with a Firebase Firestore database. Make it so the data is user specific-- each user has their own list of persons that they can record. Use the following Firebase project settings:
Cursor Response; Cursor added an authentication procedure with google firebase, and allowed debates to be saved in firebase so people could call back to them if there is something that they learned and wanted to note.
Prompt 2; How do I connect this project to a new GitHub repo?
Cursor Response; Cursor moved my API key and firebase to a .gitignore file to protect user and public data, then instructed me to run a set of commands to make an initial commit and push my code to GitHub
Summary: The final app is a web app that allows people to generate a debate between greek philosophers. The debates are timestamped and can be saved on firebase, and free of use.
