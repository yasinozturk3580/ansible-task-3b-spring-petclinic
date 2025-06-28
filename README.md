# ansible-task-3b-spring-petclinic
Spring PetClinic Sample Application
#####
 Task -  Install Spring  PetClinic  Sample  application:

Clone https://github.com/ikambarov/spring-petclinic.git or  https://github.com/spring-projects/spring-petclinic.git

Install the app on CentOS VM

Make sure web site is accessible at public IP over port 8080

Ansible Playbook should be idempotent

Use:
      -  Handlers
      -  Variables 
      -  Conditionals
      -  Roles

######
Manually on vm 
 
1 - create at least 2 gb vm on droplets
2 - yum install git -y
3 - git clone  https://github.com/spring-projects/spring-petclinic.git
4 - cd spring-petclinic
5 - sudo yum install -y java-17-openjdk java-17-openjdk-devel
6 - ./mvnw package
7 - java -jar target/*.jar
8- You can then access petclinic here: http://localhost:8080

<img width="1511" alt="Screenshot 2025-06-28 at 1 38 44 PM" src="https://github.com/user-attachments/assets/b6b90cc5-2665-4862-9e53-721e7dba44cb" />


