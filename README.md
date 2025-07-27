# Vault
A web application to upload files, notes and store username and password for different websites. This project is under development. Selenium Webdriver will be added. 


# How to install:
1. Using terminal clone this repo by this command:
````
git clone https://github.com/yourusername/Vault.git
````

2. Once the files is in your system, you can open it in IDE of your choice with `Maven`.
3. In the terminal of IDE, type:
````
mvn clean install
````
4. Then, you can start the `VaultApplication.java` or in terminal you can type:
````
mvn spring-boot:run
````
5. Then the embedded server `Tomcat`, will start the application on port `9000`.

# End Points available:
* For `User`: 
  * `GET` /home
  * `GET` /login
  * `GET` /signup
  * `POST` /signup
* For `File`:
  * `POST` /file/upload
  * `GET` /file/delete
  * `GET` /file/download
* For `Note`:
  * `POST` /note/new
  * `GET` /note/delete
  * `GET` /note
* For `Credential`:
  * `POST` /credential/new
  *  `GET` /credential/delete
  *  `GET` /credential


# Contributors
This project welcomes contributions and suggestions. Feel free to fork the repository and submit pull requests.

  
# Usage:
* Going to `http://localhost:9000` in web browser. We get the `Login` page as default page.