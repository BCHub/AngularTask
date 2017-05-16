To Run the Solution for the task, please note the following:

1. Start the Api project (without debugging, i.e. CTRL + F5) from Visual Studio


2. Install node.js from https://nodejs.org/en/download (get the latest version) if not alreeady installed.


3. After installing node.js, npm command window will become available. From the npm command, navigate to the location on the "C" drive where the application is saved(i.e. AngualrTask.UI). Next, run "npm intsall" command (this will install the node packages needed to run the app).

4. After all packages are installed, run "npm start" from the command window to start the node lite server that will run the angular app.


5. I created a Uri to get samples by status ID (number 2 on the Task instructions), however, I did not call that Uri in the app. This is because I implemented filtering for all properties of the sample object. Therefore, client side filter is available via a search input box.


6. When Adding a sample, I'm using the same user (user ID hard coded in the sample-form-component.ts save method) since I would technically need to create a login page to change the user.


8. The samples are sorted by the date descending, therefore, newly added sample will appear at the top of the list.


7. No pagination was implemented.
