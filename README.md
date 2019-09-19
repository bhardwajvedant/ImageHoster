Project title:
An Image Hoster similar to Imgur, one of the top 100 most visited websites in the world.

Motivation:
To get familiarise myself with concepts such as Spring MVC, JPA, PostgreSQL and unit testing.

Tech/framework used:

Java
HTML
Spring MVC
JPA
PostgreSQL
GIT

Installation:

To able to run the project, please download the PostgreSQL (pgAdmin) and do the following changes:
  
  1.You must manually create a database named ‘imageHoster’ in PostgreSQL with the user as ‘postgres’ using pgAdmin as the UI.

  2.Change the username and password in the stub file in the ‘src/main/java/imageHoster/config/JpaConfig.java’ file and ‘src/main/resources/META-INF/ persistence.xml’ file according to your PostgreSQL username and password.

Note that it is mandatory to assign at least one tag/category to an image while you upload the image. If you do not assign any tag to the image, the image will get uploaded in the application. But when you try to edit the image, the application throws an error.

Basic Working / Features:

  1.The application runs on localhost and the user is redirected to the landing page of the application displaying all the images in the application.

  2.A new user can register in the application by entering the details such as username, password, full name, email address, and mobile number, and after the   successful registration, he is redirected to the login page.

  3.The user can log in the application by entering the username and password, and after successful login to the application, the user is redirected to the user    homepage, displaying all the images in the application.

  4.After a user successfully logs in the application, he can click on the title of any image and the image details will be displayed including the description and tags of the image, along with the option to edit and delete the image.

  5.A user can also upload the image by entering the details such as image title, description, image file, and tags related to the image.

Reference Documentation:

  1.https://docs.spring.io/spring/docs/current/spring-framework-reference/testing.html#spring-mvc-test-framework
  2.https://spring.io/guides/gs/testing-web/
  3.http://www.springboottutorial.com/spring-boot-unit-testing-and-mocking-with-mockito-and-junit
  4.https://stackoverflow.com/questions/3804209/what-are-sessions-how-do-they-work
  5.https://dzone.com/articles/using-http-session-spring
  6.https://github.com/trein/dev-best-practices/wiki/Git-Commit-Best-Practices
  7.https://gist.github.com/SethRobertson/1540906/68feeabfe906ec1eb893e4fa45f402795ed6e62c

MIT © AshishInamdar02
