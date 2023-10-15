

# Instagram Backend Design
#### This project is a basic representation of the backend structure for an Instagram-like application. It includes user authentication, user profiles, and post management.

## Technologies Used
- Java
- Spring Boot
- Hibernate (JPA)
- MySQL (or any other database of your choice)
## Models
### User
- Represents a user of the application.
- Contains fields for user information:
    - First Name
    - Last Name
    - Age
    - Email
    - Phone Number
### Post
- Represents a user's post.
- Contains fields for post information:
    - Post ID
    - Created Date
    - Updated Date
    - Post Data
    -  User
### AuthenticationToken
- Represents an authentication token for user sessions.
- Contains fields for token information:
    - Token ID
    - Token
    - Token Creation Date
    - User (the associated user)
## Controllers
### UserController
This controller handles user-related operations:

- Sign In: Allows users to sign in by providing valid credentials.
- Sign Up: Allows new users to create an account.
- Update User Details: Enables users to update their profile information.
### PostController
This controller handles post-related operations:

- Save Post: Allows users to create and save a new post.
- Get Post: Retrieves post details, including user information.
## API Endpoints
### User Endpoints
- POST /api/user/signin: Sign in with user credentials.
- POST /api/user/signup: Create a new user account.
- PUT /api/user/update: Update user details.
### Post Endpoints
- POST /api/post/save: Create and save a new post.
- GET /api/post/{postId}: Retrieve post details.
## Authentication
- User authentication is required for most endpoints.
- Use the token received during sign-in for all user operations.
## Project Summary
- This Student Application is built using Spring Boot and Java.
- It allows users to perform CRUD operations on student,book,laptop,address and course entities.
- The project follows a structured architecture with controllers, services, and repositories.
- Data is stored in a MySQL database with appropriate relationships.


## Acknowledgments

We would like to express our gratitude to the following individuals and projects for their contributions and support to the Instagram Backend design :

- **[Vishal Raj]**: Lead developer and project coordinator.
- **[Mainak Ghosh]**: Contributor to the project, helping with [SpringBoot to complete this project].
- **[maven]**: We utilized [maven] for [dependencies] in our project.
- **Stack Overflow Community**: For their invaluable assistance in resolving technical challenges.
- **Spring Framework**: For providing a robust and efficient platform for building our application.


We appreciate the  effort and support that made this project possible.



## Support

For support, email vishalrajbanti@gmail.com.

## thank you.
