# CS465


Architecture
•	Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

Express HTML was used to develop the customer facing site and eventually was converted to a .hbs view to increase the rendering speeds as each component needed to be fully load at every refresh. With HTML being static and client facing it is unable to interact with the backend databases to update information. This is where JavaScript came into play as it is a frontend and backend coding language which adds dynamic elements to the webpage (pulled form MongoDB database). This was used in a SPA (Single-page application) so that each part didn’t need to be reloaded when the user completed some kind of action. 

•	Why did the backend use a NoSQL Mongo DB database?

The backend used a NoSQL Mongo DB because of the databases scaling and functionality which is easy to implement and use. 

Functionality
•	How is JSON different from JavaScript and how does JSON tie together the frontend and backend development pieces?

JSON is a convenient way to format an object’s data so that it can be turned into a JavaScript object. By being able to take any object data and turning it into a literal JavaScript object the Front end and backend pieces become connected and can be stored/used in a variety of ways. 

•	Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

When we created the Trip-Card and Trip Listing components is two instances where the full stack process was refactored to improve functionality and efficiencies. By reusing UI components and breaking down each part it allows the overall size of the application to be smaller and quicker.

Testing
•	Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.

Testing can be completed before or after layers of security have been added. Some things that can be used to test if the requested data returns retrieved data is PowerShell, Postman, and Chrome’s Developer tools. When the npm is running inside of PowerShell you can see the data requested and if it was provided. You can tell if there are issues and what is occurring by reading and understanding the codes (404 status means it’s not found, or a 201 status it did retrieve the data). Postman can be used to test the HTTP request and verify the layers of security added are working correctly. The Chrome Developer tool can help point you in the direction of a issues assuming one exists.

Reflection
•	How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
This course helped me grow immense and allowed me to be a better programmer who understand each component of the MEAN stack and how they work together. Originally web development didn’t interest me at all and I imagined it to be super complex, but after this class feel like I can push myself to master it and apply my learned skills in my daily life. 
