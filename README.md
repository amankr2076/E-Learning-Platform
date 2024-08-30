# Online Education Platform (MERN App)

This project is a fully functional ed-tech platform designed to empower users to create, consume, and rate educational content. Built on the MERN stack—comprising ReactJS, NodeJS, MongoDB, and ExpressJS— aim of thisproject is to  provide a seamless and interactive learning experience for students while making education more accessible and engaging. Additionally, it offers a robust platform for instructors to showcase their expertise and connect with learners worldwide.

In the sections that follow, we will explore the technical aspects of the platform in detail, covering the following areas:

1)System Architecture: This section provides a high-level overview of the platform's components, including detailed diagrams illustrating the system architecture.

2)Front-end: Here, we will delve into the front-end architecture, user interface design, and the features and functionalities of the front-end. We will also discuss the frameworks, libraries, and tools used to build the front-end.

3)Back-end: This section covers the back-end architecture, detailing its features, functionalities, and the frameworks, libraries, and tools employed. We will also discuss the data models and database schema that power the platform.

4)API Design: We will provide an in-depth look at the API design, including a list of API endpoints, their functionalities, and sample API requests and responses.

5)Deployment: This section outlines the deployment process, including the hosting environment and infrastructure, as well as deployment scripts and configurations.

6)Testing: Here, we will discuss the testing process, covering the types of testing performed and the test frameworks and tools used to ensure the platform's reliability.

7)Future Enhancements: In this section, we will present a list of potential future enhancements to the platform. We will explain how these improvements could further enhance the platform, along with an estimated timeline and priority for implementing these changes.

In summary, This is a versatile and intuitive ed-tech platform designed to deliver an immersive learning experience to students and provide instructors with a global stage to share their expertise. The following sections will provide a comprehensive understanding of the platform's technical features and functionalities.



# System Architecture
This ed-tech platform consists of three main components: the front end, the back end, and the database. The platform follows a client-server architecture, with the front end serving as the client and the back end and database serving as the server.

**Front-end**<br>
The front end of the platform is built using ReactJS, ReactJS allows for the creation of dynamic and responsive user interfaces, which are critical for providing an engaging learning experience to the students. The front end communicates with the back end using RESTful API calls

**Back-end**<br>
The back end of the platform is built using NodeJS and ExpressJS,. The back end provides APIs for the front end to consume, which include functionalities such as user authentication, course creation, and course consumption. The back end also handles the logic for processing and storing the course content and user data.

**Database**<br>
The database for the platform is built using MongoDB, which is a NoSQL database that provides a flexible and scalable data storage solution. MongoDB allows for the storage of unstructured and semi-structured data. The database stores the course content, user data, and other relevant information related to the platform.

# Front End
The front end has all the necessary pages that an ed-tech platform should have. Some of these pages are:

***For Students:***
<ul>
  <li><strong>Homepage:</strong> This page will have a brief introduction to the platform, as well as links to the course list and user details.</li>
  <li><strong>Course List:</strong> This page will have a list of all the courses available on the platform, along with their descriptions and ratings.</li>
  <li><strong>Wishlist:</strong> This page will display all the courses that a student has added to their wishlist.</li>
  <li><strong>Cart Checkout:</strong> This page will allow the user to complete the course purchase.</li>
  <li><strong>Course Content:</strong> This page will have the course content for a particular course, including videos and other related material.</li>
  <li><strong>User Details:</strong> This page will have details about the student's account, including their name, email, and other relevant information.</li>
  <li><strong>User Edit Details:</strong> This page will allow the student to edit their account details.</li>
</ul>


***For Instructors:***
<ul>
  <li><strong>Instructor Dashboard:</strong> This page will have an overview of the instructor's courses, as well as the ratings and feedback for each course.</li>
  <li><strong>Instructor Insights:</strong> This page will have detailed insights into the instructor's courses, including the number of views, clicks, and other relevant metrics.</li>
  <li><strong>Course Management Pages:</strong> These pages will allow the instructor to create, update, and delete courses, as well as manage the course content and pricing.</li>
  <li><strong>View and Edit Profile Details:</strong> These pages will allow the instructor to view and edit their account details.</li>
  <li><strong>Admin Dashboard (Future Scope):</strong> This page will have an overview of the platform's courses, instructors, and students.</li>
  <li><strong>Admin Insights (Future Scope):</strong> This page will have detailed insights into the platform's metrics, including the number of registered users, courses, and revenue.</li>
  <li><strong>Instructor Management (Future Scope):</strong> This page will allow the admin to manage the platform's instructors, including their account details, courses, and ratings.</li>
  <li><strong>Other Relevant Pages (Future Scope):</strong> The admin will also have access to other relevant pages, such as user management and course management pages.</li>
</ul>
<br>

To build the front end, we use frameworks and libraries such as ReactJS, We also use CSS and Tailwind, which are styling frameworks that help make the user interface look good and responsive. To manage the state of the application, we use Redux, which is a popular state management library for React.

# Back End
Description of the Back-end Architecture: This Project uses a monolithic architecture, with the backend built using Node.js and Express.js, and MongoDB as the primary database.
<br>
Features and Functionalities of the Back-end: The back end of This Project provides a range of features and functionalities, including:

<ol>
  <li><strong>User Authentication and Authorization:</strong> Students and instructors can sign up and log in to the platform using their email addresses and password. The platform also supports OTP (One-Time Password) verification and forgot password functionality for added security.</li>
  <li><strong>Course Management:</strong> Instructors can create, read, update, and delete courses, as well as manage course content and media. Students can view and rate courses.</li>
  <li><strong>Payment Integration:</strong> Students will purchase and enroll in courses by completing the checkout flow, which is followed by Razorpay integration for payment handling.</li>
  <li><strong>Cloud-Based Media Management:</strong> This Project uses Cloudinary, a cloud-based media management service, to store and manage all media content, including images, videos, and documents.</li>
  <li><strong>Markdown Formatting:</strong> Course content in document format is stored in Markdown format, which allows for easier display and rendering on the front end.</li>
</ol>
<br>
Frameworks, Libraries, and Tools used: The back end uses a range of frameworks, libraries, and tools to ensure its functionality and performance, including:

<ol>
  <li><strong>Node.js:</strong> Node.js is used as the primary framework for the back end.</li>
  <li><strong>MongoDB:</strong> MongoDB is used as the primary database, providing a flexible and scalable data storage solution.</li>
  <li><strong>Express.js:</strong> Express.js is used as a web application framework, providing a range of features and tools for building web applications.</li>
  <li><strong>JWT:</strong> JWT (JSON Web Tokens) are used for authentication and authorization, providing a secure and reliable way to manage user credentials.</li>
  <li><strong>Bcrypt:</strong> Bcrypt is used for password hashing, adding an extra layer of security to user data.</li>
  <li><strong>Mongoose:</strong> Mongoose is used as an Object Data Modeling (ODM) library, providing a way to interact with MongoDB using JavaScript.</li>
</ol>


