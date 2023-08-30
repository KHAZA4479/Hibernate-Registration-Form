# Hibernate-Registration-Form
Hibernate Registration Form Example with JSP, Servlet, MySQL
# Hibernate Registration Form Example

This project demonstrates a simple registration form implementation using JSP, Servlet, and Hibernate ORM, with data stored in a MySQL database.

## Technologies Used

- Java
- JSP (JavaServer Pages)
- Servlet
- Hibernate ORM
- MySQL

## Getting Started

1. **Database Setup:**
   - Create a MySQL database named `registration_db`.
   - Execute the SQL script located at `src/main/resources/database.sql` to create the `users` table.

2. **Configuration:**
   - Update the `hibernate.cfg.xml` file located at `src/main/resources` with your database connection details.

3. **Running the Project:**
   - Clone this repository.
   - Import the project into your preferred IDE.
   - Configure an Apache Tomcat Server in your IDE and deploy the project.
   - Access the application at `http://localhost:8080/YourProjectName/`.

## Project Structure

- `src/main/java/com/yourapp`
  - `model/User.java`: User entity class.
  - `util/HibernateUtil.java`: Hibernate configuration utility.
  - `dao/UserDao.java`: Data Access Object for user operations.
  - `servlet/RegistrationServlet.java`: Servlet for user registration.
- `src/main/webapp`
  - `WEB-INF/web.xml`: Servlet mapping and configuration.
  - `index.jsp`: Homepage.
  - `registration.jsp`: User registration form.

## Contributing

Contributions are welcome! If you find any issues or improvements, feel free to create a pull request.

# Hibernate Registration Form Example

![a](https://github.com/KHAZA4479/Hibernate-Registration-Form/assets/138356894/5555a4fd-3f66-4dd5-b81a-82d79934b258)
