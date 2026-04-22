
<ul>
  <li><b> Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address? </b></li>
  <br>
  <p> The app that I developed aims to help individuals track their weight. The app provides a secure login for returning users and allows new users to create an account with a username, password, and phone number. The app then allows users to log their current weight on any screen, set a goal weight, displays the current weight and caculates how many pounds until the goal is reached, displays all logged weights in a grid, and notfies the user via SMS when they have reached their goal. </p>
  
  <li><b> What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful? </b></li>
   <br>
  <p> The resulting application needed four different screens to support the user's needs and create a user-centered exprience. Like many familair apps, the weight tracking app opens to a login page. This page includes two different option: login or create an account. This feature secures the user's data to their account profile and saves any user prefereces, such as allowing SMS notification. When a user is using the app for the first time, the app will request permission to send SMS notification, keeping the user in control their personal data and improving user trust. This then brings the app the the main activity, starting with the home page. The home page displays a quick status of the user's latest logged weight and calculates how many pounds until the set goal is reached. This page instantly delivers value, clarity, and motivation to the user without requiring cognitive effort. Between all main activity fragments, a navigation bar sits at the bottom of the screen so the user can easily switch between screens. The next screen provided on the navigation bar displays all logged weights. This provides the user a visual tracking display that allows them to idenitify trends in their daily weight. On these two pages, there is an add button to quickly and easily log a new weight. This design is particularly successful since the user will never have to navigate away from the current screen to complete the core logging action. Lastly, the profile page shows all the current user data: username, provided phone number, current weight, goal weight, and notfication toggle. All the fields except the username field is easily updatable, meaning if the user has a new goal or a new phone number, they do not need to make a new account to keep using the app. The notification toggle again gives the user full control whether they would like to recieve SMS notifcations for reaching their goal at any time. </p>
  
  <li><b> How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future? </b></li>
   <br>
  <p> When coding my app, I broke down each requirement and feature into parts and focused on implementing them in relevance of importance. For this project, I began by mapping each screen to eachother correctly-- the login button should take the user to the home page, then the records button should navigate to the records page, and the you button navigates to the profile page. Then I worked on validating the username and password for an appropriate authentication and so forth. This strategy ensures that the real problem (in this case: being able to log and track weight records) is solved first and the highest possible product value is delivered to the client. This strategy is incredibly useful in the future when working on large project with tight deadlines and resource budgets.  </p>
  
  <li><b> How did you test to ensure your code was functional? Why is this process important, and what did it reveal? </b></li>
   <br>
  <p> To ensure my code was function, I tested the app after each time a feature was implement. For example, after coding the logic to add a new weight record when the chevron was pressed on the profile page, I booted up the app, created an account, navigated to the profile screen, selected the current weight chevron. Then I validated that the correct dialog box opened, the box was able to be canceled by clicking off the box and with the cancel button, the edit text box would pull up with the number keyboard, the weight could be saved when the save button was pressed, and the app displayed and error toast when an invalid weight was submitted. This process is crucial to ensure that every part of the app works as expected and to reveal any bugs. If this proccess revealed an error or unexpected behavior, such as a success toast appearing when I expected an error toast, I would review the code and input debugging statements between actions. For example, when making sure the new records were inserted into the database without a visual, I included a Log.d statment into the DBHelper to print the records found in the database and report that it was added. </p>
  
  <li><b> Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge? </b></li>
   <br>
  <p> The most challenging part of this app design was creating the grid view. Most resources I found when looking for a tutorial to use a gridview widget with a SQL Lite database recommended to use a list view instead. I had no real idea of what was possible with the widget. Despite this, I did my best to learn how the gridview widget worked through simpler tutorials, then used what I knew from creating the dialog widgets to populate it. Once I had a simple grid of date and weight data, I then continued to improve the design by formatting the dates. However, it was still difficult to disinguish between each data item. I then enhanced the grid item layout with appropiately sized text, text styles, a colored header, and a colored body that contained each element.  </p>
  
  <li><b> In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience? </b></li>
   <br>
  <p> </p>
  
</ul>







