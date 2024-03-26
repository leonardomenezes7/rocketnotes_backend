# RocketNotes API 📓

## 📁Project
Here is a description of the API developed in Node.js:

The API is designed to provide functionality for managing users, notes, and tags, allowing the creation, and deletion of notes, as well as the association of links and tags with those notes. Additionally, the API offers user authentication using JWT tokens to ensure the security of operations.

Key features:

User Management:

- Registration of new users with basic information such as username, email, and password.
- Update of user data, including password change and personal information.
- Note Management:

Creation of notes associated with specific users.
Update of note content.
Deletion of existing notes.
Link and Tag Relationship:

Association of links related to specific notes.
Association of tags with notes to facilitate organization and categorization.
User Authentication:

Generation of JWT tokens to authenticate users during API requests.
Protection of sensitive routes and operations, requiring valid authentication by JWT token.
The API architecture is developed using Node.js, leveraging frameworks such as Express.js for routing and middleware control, and JWT for user authentication. Data is stored in a SQLite , to ensure persistence and scalability.
