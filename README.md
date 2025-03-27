<h1 align="center"> Digital Library Book Management System</h1>

<p align="center">
  A <b>Spring Boot + MySQL + Thymeleaf</b> application built using <b>Spring Tool Suite (STS)</b>. <br>
  This system allows librarians to <b>add, update, search, and delete</b> books while managing their availability.
</p>

---

##  Tech Stack  
- **Backend:** Spring Boot, Spring Data JPA  
- **Frontend:** Thymeleaf, Tailwind CSS  
- **Database:** MySQL  
- **IDE:** Spring Tool Suite (STS)  
- **Build Tool:** Maven  

---

##  Project Setup in Spring Tool Suite (STS)  

<h3>1] Clone the Repository</h3>
<p>Open <b>STS</b>, then:</p>

1. **Go to** `File` → `Import` → `Git` → `Projects from Git`  
2. Select **Clone URI**, then enter:  
   ```sh
   https://github.com/JivanRathod111/Digital_Library.git
3. Click Finish after cloning.

<h3>2] Configure MySQL Database</h3> <p>Create a MySQL database and update the <b>application.properties</b> file:</p>
 src/main/resources/application.properties

## Database Configuration
spring.datasource.url=jdbc:mysql://localhost:3306/library_db <br>
spring.datasource.username=root <br>
spring.datasource.password=your_passwordb <br>

## Hibernate Settings
spring.jpa.hibernate.ddl-auto=update <br>
spring.jpa.show-sql=true <br>
spring.jpa.database-platform=org.hibernate.dialect.MySQL8Dialect <br>
Note: Replace your_password with your actual MySQL password. <br>
The database library_db must be created before running the app.

<h3>3] Run the Application in STS</h3> <p>Follow these steps:</p>
Open STS and go to Project Explorer.

Right-click the project and select Run As → Spring Boot App.

The console should display:

Tomcat started on port(s): 8080
<h3>4] Access the Application</h3> <p>Once the application starts, open your browser and go to:</p>
<a href="http://localhost:8080/books" target="_blank">http://localhost:8080/books</a>

 ## Features  <br>
✔ Add Books - Enter book details and save them in the database. <br>
✔ View Books - Display books in a responsive grid layout. <br>
✔ Search Books - Search by ID or Title. <br>
✔ Update Books - Modify book details. <br>
✔ Delete Books - Remove books from the system. <br>

 UI Design (Dark Theme - "Raven's Wing" Palette)
<table> <tr> <th>Color</th> <th>Usage</th> </tr> <tr> <td><b>Deep Black (#000000)</b></td> <td>Background</td> </tr> <tr> <td><b>Dark Gray (#1A1A1A)</b></td> <td>Card Backgrounds</td> </tr> <tr> <td><b>Mid Gray (#404040)</b></td> <td>Inputs & Buttons</td> </tr> <tr> <td><b>Soft Gray (#BFBFBF)</b></td> <td>Text</td> </tr> <tr> <td><b>Accent Hover (#808080)</b></td> <td>Hover Effects</td> </tr> </table>
 Troubleshooting
<h3> MySQL Connection Failed?</h3> <ul> <li>Ensure MySQL is <b>running</b>.</li> <li>Check <b>username & password</b> in <code>application.properties</code>.</li> <li>Create database manually:</li> </ul>
sql

CREATE DATABASE library_db;
<h3> Tailwind CSS Not Working?</h3> <ul> <li>Ensure <b><code>styles.css</code></b> is correctly linked in Thymeleaf templates.</li> </ul>
 License
<p>This project is open-source under the <b>MIT License</b>.</p>
 Contributing
<p>Feel free to fork the repo and submit a <b>pull request</b>! </p>

 #Author <br>
 Jivan Rathod <br>
 Email: jivanrathod127@gamil.com <br>
 GitHub: [github.com/JivanRathod111](https://github.com/JivanRathod111) <br>
 Portfolio: [jivanrathod.netlify.app](http://jivanrathod.netlify.app) <br>



