# CourseManager-React-SpringBoot
CourseManager Web App Using React-SpringBoot

# Course Manager Web App

The Course Manager Web App is a full-stack web application for managing course details. It provides a user-friendly interface for adding, viewing, updating, and deleting course information.

## Features

- Add new courses with a title and description.
- View a list of all available courses.
- Update course details.
- Delete courses by ID.

## Technologies Used

### Frontend
- React: A JavaScript library for building user interfaces.
- React Router: For client-side routing within the React application.
- Axios: A promise-based HTTP client for making API requests.
- Reactstrap: Bootstrap components for React.
- React Toastify: A library for displaying notifications.

### Backend
- Spring Boot: A Java-based framework for building RESTful APIs.
- Spring Data JPA: Simplifies database operations using Spring and JPA.
- Spring Web: Provides support for creating RESTful web services.
- Oracle Database: Used as the database backend for storing course information.

## Setup Instructions

```markdown

## Backend Setup

1. Navigate to the Spring Boot project directory (`course-manager-api` or similar).
2. Configure your Oracle database connection in `application.properties` or `application.yml`.
3. Build and run the Spring Boot application on port 2023.

cd course-manager-api
# Build and run using Maven
mvn spring-boot:run

## Frontend Setup
Navigate to the React project directory (course-manager-app or similar).
Install dependencies and start the development server.

cd course-manager-app
npm install
npm start
```

## API Endpoints (Port 2023)

### Add Course 
- **Endpoint:** `POST http://localhost:2023/api/add-courses`
- **Description:** Add a new course.
- **Request Body:** JSON object with course details (excluding `id`).
- **Example:** `curl -X POST -H "Content-Type: application/json" -d '{"id: xxxx, "title":"Course Title","description":"Course Description"}' http://localhost:2023/api/add-courses`

### Get Course by ID
- **Endpoint:** `GET http://localhost:2023/api/get-coursesById/{id}`
- **Description:** Retrieve a course by its ID.
- **Example:** `curl http://localhost:2023/api/get-coursesById/1`

### Get All Courses
- **Endpoint:** `GET http://localhost:2023/api/get-allCourses`
- **Description:** Retrieve a list of all available courses.
- **Example:** `curl http://localhost:2023/api/get-allCourses`

### Update Course
- **Endpoint:** `PUT http://localhost:2023/api/update-courses/{id}`
- **Description:** Update an existing course by its ID.
- **Request Body:** JSON object with updated course details (including `id`).
- **Example:** `curl -X PUT -H "Content-Type: application/json" -d '{"id": 1, "title":"Updated Title","description":"Updated Description"}' http://localhost:2023/api/update-courses/1`

### Delete Course by ID
- **Endpoint:** `DELETE http://localhost:2023/api/delete-coursesById/{id}`
- **Description:** Delete a course by its ID.
- **Example:** `curl -X DELETE http://localhost:2023/api/delete-coursesById/1`

## React Endpoints (Port 3000)

- **Home**: The landing page of the application.
  - **Endpoint:** [http://localhost:3000/](http://localhost:3000/)

![image](https://github.com/armyofthe-dead/CourseManager-React-SpringBoot/assets/129574484/0da6809f-4092-444a-8b80-8359b3b0deed)



- **Add Courses**: Page for adding new courses.
  - **Endpoint:** [http://localhost:3000/add-courses](http://localhost:3000/add-courses)
![image](https://github.com/armyofthe-dead/CourseManager-React-SpringBoot/assets/129574484/28e82666-a3f4-427c-abcc-a9e41769c535)


- **View Courses**: Page for viewing a list of all available courses.
  - **Endpoint:** [http://localhost:3000/view-courses](http://localhost:3000/view-courses)
![image](https://github.com/armyofthe-dead/CourseManager-React-SpringBoot/assets/129574484/efb35e15-8a02-43ea-90cf-e30dabb80925)


- **Update Courses**: Page for updating course details.
  - **Endpoint:** [http://localhost:3000/update-courses](http://localhost:3000/update-courses)
![image](https://github.com/armyofthe-dead/CourseManager-React-SpringBoot/assets/129574484/b3a697b4-3719-42d2-bcef-2cd8429e32a1)


- **Contact Us**: Contact information page.
  - **Endpoint:** [http://localhost:3000/contact-us](http://localhost:3000/contact-us)
![image](https://github.com/armyofthe-dead/CourseManager-React-SpringBoot/assets/129574484/8cda72cd-181c-4bc7-8739-70a4946f3fd2)


- **About Project**: Page providing information about the project.
  - **Endpoint:** [http://localhost:3000/about-project](http://localhost:3000/about-project)
  ![image](https://github.com/armyofthe-dead/CourseManager-React-SpringBoot/assets/129574484/807b523a-f9be-453a-815b-610ef2e5cf5d)


## Usage

Visit [http://localhost:3000](http://localhost:3000) to access the Course Manager Web App.
Use the provided features to manage course details.

## Contributing

Contributions to this project are welcome! Feel free to open issues or pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.


## Contact
For inquiries and collaboration, you can reach me at:

Email: jajurekunal@gmail.com

Feel free to explore the code, learn, and contribute.

## Happy coding!

