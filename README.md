# Kiwi Math - OwlHacks 2024 Winning Project - Inclusive Education
This project follows the theme of Inclusive Education. It is called "KiwiMath". KiwiMath is a website built for high-schoolers who struggle in Mathematics by evaluating their skills and progress.

**Link to demo:** https://youtu.be/oSEbcB-Dp0M

## How It's Made:

**Tech used:** HTML, CSS, JavaScript, React, Python, Flask, MongoDB, OpenAI

The Project was built using the React framework for the frontend. It first greets you with an authentication screen which is connected to MongoDB, where it stores a user's information. If the user doesn't have an account, they'd have to create one, where the front page allows it to. This was achievable by using Flask for backend, where it just uses a function to push and pull data out and into the database on MongoDB. Once logged in, the user is greeted by a main menu consisting of options: Learn, Assessment Test, Options and Profile. Learn page allows the user to access a personalized learning plan based off of an Assessment Test that they should have taken. To take an Assessment Test, the program takes the user's grade and pulls the appropriate test for the user according to their grade by using Flask on the backend to pull the test out of the external MongoDB database. Once completed, the program assesses the user's knowledge in math and plans the learning path for the user

## Lessons Learned:

During the development of the Kiwi Math, I gained valuable insights into both back-end architecture and database design. One key lesson was the importance of structuring the database effectively to support a range of topics tailored for grades 9-12, which helped me understand how to optimize data retrieval for different user queries. I also integrated the ChatGPT 4.0 API to provide users with dynamic feedback and personalized learning experiences, showcasing the potential of AI to enhance education. Additionally, I learned the significance of creating a robust API to facilitate seamless communication between the front-end and back-end, ensuring a smooth user experience. This project highlighted the necessity of thorough testing, as it helped me identify and resolve issues early on, ultimately leading to a more reliable application. Overall, this experience enhanced my skills in full-stack development and reinforced the value of planning and iteration in the software development process.
