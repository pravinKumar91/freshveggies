# freshveggies

**What is freshveggies project ?**

*This is Microservice project, demonstrating how microservices communicate with each other.*

**freshveggies** is the project listing vagetable information in the catalog through freshveggies-catalog (spring boot project).
This project is registered on the Eureka server freshveggies-discoveryserver (spring boot project). 
While fetching each vegetable information catalog calls for the vegetable information service through freshveggies-product (spring boot project). 
Those vegetables ids we get from the shops from the location id we passed to catalog. freshveggies-shops (spring boot project) is respinsible to
get all the shops from the location id and from those shops each vegetable information is fethed to display the vegetable price details.

**Abstract about the microservices**

Each microservice is working on different port with the help of embedded tomcat.
Pull all the projects and run them one by one inside IDE.
Only web services end points are defined the project no user interface has been defined.
You can only see the JSON as response in the browser.


**There are seperate spring boot applications listed below.**

**Eureka Server**
1) freshveggies-discoveryserver

**Eureka clients**
1) freshveggies-catalog
2) freshveggies-product
3) freshveggies-shops


***Thank you!!!***
