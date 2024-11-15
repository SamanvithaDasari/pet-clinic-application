The Spring PetClinic project is a sample web application developed using Spring Boot, designed to showcase how to build a modern Java-based application. It demonstrates core concepts of Spring, such as dependency injection, AOP, and Spring Data. The application simulates a simple pet clinic, allowing users to manage pets, owners, and visits. It can be built with either Maven or Gradle and supports running in various environments, including Docker, for easy setup and testing. The project is useful for developers seeking to learn or demonstrate Spring Boot applications.
The Spring PetClinic application leverages several key tools and technologies:

1. Spring Boot: A framework that simplifies building and deploying Java-based applications.
2. Spring Data: For interacting with databases using Java Persistence API (JPA).
3. Thymeleaf: A templating engine used for rendering the web interface.
4. H2 Database: A lightweight, in-memory database for managing clinic data.
5. Maven: Build tools for managing dependencies and packaging the application.

Steps
On the command line run:

git clone [https://github.com/spring-projects/spring-petclinic.git](https://github.com/SamanvithaDasari/pet-clinic-application)
Inside Eclipse or STS:

Open the project via File -> Import -> Maven -> Existing Maven project, then select the root directory of the cloned repo.

Then either build on the command line ./mvnw generate-resources or use the Eclipse launcher (right-click on project and Run As -> Maven install) to generate the CSS. Run the application's main method by right-clicking on it and choosing Run As -> Java Application.
You can then access the Petclinic at http://localhost:8080/.

HOME PAGE:
![Screenshot 2024-11-15 141009](https://github.com/user-attachments/assets/873ec924-bfd9-4afb-b992-ff1049c7a02f)

SERVICE BUTTONS:
![Screenshot 2024-11-15 141027](https://github.com/user-attachments/assets/8d8d83a7-dfb1-4551-a693-c9167d7d712a)

FIND OWNER TAB:
![Screenshot 2024-11-15 141038](https://github.com/user-attachments/assets/e0cd60fa-d11e-4435-945e-2ed34d0889b3)

OWNER LIST:
![Screenshot 2024-11-15 141054](https://github.com/user-attachments/assets/dc5ed834-b774-4caf-a94a-829271b457dc)

OWNER INFORMATION:
![Screenshot 2024-11-15 141107](https://github.com/user-attachments/assets/6a6fd14c-3be6-43dc-a98b-df866c894e41)

ADD NEW PET:
![Screenshot 2024-11-15 141119](https://github.com/user-attachments/assets/22b26a43-d5d7-4412-87e1-7c463682d079)

ADD NEW VISIT:
![Screenshot 2024-11-15 141133](https://github.com/user-attachments/assets/09f69e6b-1689-4605-a3d3-e537c0cf919f)

ADD OWNER:
![Screenshot 2024-11-15 141143](https://github.com/user-attachments/assets/1e83c47b-9840-438a-8d5b-42d9633c470b)

VET LIST:
![Screenshot 2024-11-15 141152](https://github.com/user-attachments/assets/8d82bf0b-3a51-4f8f-933a-1f47e8b7737e)


The Spring PetClinic application is a simulation of a pet clinic, designed to demonstrate Spring technologies. For a hospital administrator, this system allows managing patient records (pets), owner details, and visit logs. It provides easy access to scheduling, pet treatment, and overall clinic management. The interface is user-friendly, making it easier for admins to track and update records, enhancing clinic operation efficiency. The application serves as an ideal model for learning Spring-based enterprise applications.



