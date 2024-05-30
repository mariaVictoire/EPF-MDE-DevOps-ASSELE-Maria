# Welcome to my deposit 😄!

Here you'll find the practical work I did following the “Devops in Action” guide.

> [!IMPORTANT]
> Rather than cluttering up my README, I've chosen to write reports for each part of the TP. They contain my answers to the questions asked, relevant code extracts and screenshots illustrating the various results obtained. You can consult these reports on this repository by following this link : [#Reports](https://github.com/mariaVictoire/EPF-MDE-DevOps-ASSELE-Maria/tree/main/Reports_TP)


## Part 01 - Docker Session

The aim of this part is to implement a three-tier web application, consisting of an HTTP server, a backend API and a database, using Docker containers for each component.

## Structure

The project is divided into three main parts:

1. Database: This section concerns the configuration and deployment of a PostgreSQL database using Docker.

   ![image](https://github.com/mariaVictoire/EPF-MDE-DevOps-ASSELE-Maria/assets/159890985/fb686002-31a1-4ab8-8895-8f134bbc89d4)


3. Backend API: Here, we deploy a backend API written in Java using Spring Boot. Docker is used to build and run the API.

5. HTTP Server: This part deals with the deployment of an HTTP server, such as the Apache HTTP Server, to serve a static home page. We also configure this server as a reverse proxy to redirect traffic to our backend API.

   ![image](https://github.com/mariaVictoire/EPF-MDE-DevOps-ASSELE-Maria/assets/159890985/c62d0cdd-78aa-4521-9e1f-62c2202272dc)


> [!NOTE]
> You can access the report for this section using the following link : [#part01_report](https://github.com/mariaVictoire/EPF-MDE-DevOps-ASSELE-Maria/blob/main/Reports_TP/part01_report.pdf)


## Part 02 - GitHub Action Session

In this part of the course, we'll be diving into the world of GitHub Actions. The aim is to set up a complete pipeline for testing and delivering our software application using GitHub Actions.

## Structure

The project is divided into several main sections:

1. Setup GitHub Actions

    First Steps into the CI World: Create a YAML file to define the continuous integration steps, with automatic tests on every commit.
    Build and Test Your Application: Use Maven to build and test the Java application, including unit and integration tests.
    First Steps into the CD World: Set up continuous delivery by creating and publishing Docker images to Docker Hub on every commit to the main branch.

2. Setup Quality Gate

    SonarCloud: Integrate SonarCloud to analyze code quality and ensure it adheres to best development practices.

 
![image](https://github.com/mariaVictoire/EPF-MDE-DevOps-ASSELE-Maria/assets/159890985/4c2d0fad-762f-4d9f-86c3-de5ff1ce2515)



3. Bonus: Split Pipelines (Optional)

    Separate Pipelines: Organize jobs into distinct workflows for better management and conditional triggering based on successful test completion.

 (ajouter image )

> [!NOTE]
> You can access the report for this section using the following link : [#part02_report](https://github.com/mariaVictoire/EPF-MDE-DevOps-ASSELE-Maria/blob/main/Reports_TP/part02_report.pdf)


## Part 03 - Ansible

## Structure


> [!NOTE]
> You can access the report for this section using the following link : [#part03_report](https://github.com/mariaVictoire/EPF-MDE-DevOps-ASSELE-Maria/blob/main/Reports_TP/part03_report.pdf)

