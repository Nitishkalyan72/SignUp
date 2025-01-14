# SignUp 

## Overview
The **SignUp** repository is a Java-based project that provides features for:
1. User Login
2. New User Registration
---

## Instructions 

### Step 1: Clone the Repository
Use the following command to clone the repository:
```bash
git clone https://github.com/your-username/SignUp.git
```

### Step 2: Navigate to the Project Directory
```bash
cd SignUp
```

### Step 3: Update the Configuration

1. **Modify `application.properties`**:
   - Navigate to `src/main/resources/application.properties`.
   - Update the configuration as per your requirements, such as:
     ```properties
     server.port=8080   # Change the port number if needed
     spring.datasource.url=jdbc:mysql://localhost:3306/your_database
     spring.datasource.username=your_username
     spring.datasource.password=your_password
     ```

2. **Modify `application.xml` (if needed)**:
   - Navigate to `src/main/resources/application.xml`.
   - Add or modify dependencies as required. For example:
     ```xml
     <dependency>
         <groupId>com.example</groupId>
         <artifactId>example-dependency</artifactId>
         <version>1.0.0</version>
     </dependency>
     ```

---

### Step 4: Build the Project
Run the following Maven command to clean and build the project:
```bash
mvn clean install
```

### Step 5: Run the Project
After successful build, you can run the application using your preferred IDE or directly with:
```bash
mvn spring-boot:run
```

---

## Access the Application
- **Login Feature**: [http://localhost:8080/req/login](http://localhost:8080/req/login)
- **Registration Feature**: [http://localhost:8080/req/signup](http://localhost:8080/req/signup)
- **Home Page**: [http://localhost:8080/index](http://localhost:8080/index)

---

## Additional Notes
- Ensure that the MySQL server is running if you're using a database.
- Check the logs during the Maven build process to resolve any missing dependencies or errors.
