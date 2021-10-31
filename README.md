# UIDAI_HackathonProject
 
I, Aayushi, with my teammates Shubham Kumar and Neha Sindhu have developed a java project for UIDAI hackathon on topic "Address Formatting" using J2EE framework.
In this project, we have formatted the address by removing the repetitive words in it.

**PROBLEM STATEMENT**

**Address Formatting Issue**
Imagine you belong to the capital city of India and you reside within IIT Delhi campus. You have just enrolled yourself to the aadhaar identity platform and after successful enrolment, you have received your letter containing the aadhaar number, demographics data such as name and address. Alas, in the address field you see the repetition of ‘Delhi’ multiple times, making the address a little convoluted. Like you, many of the residents especially those who are residing inthe urban areas see the repetition of the same content in the final address.

**SOLUTION**
a) In our project, we have used java servlet api and jdbc along with MySQL database.

b) The dependencies that we have used are mentioned below:-
1. mysql-connector-java-8.0.25 jar
2. Jstl-1.2 jar
3. Jsp-api-2.2.jar
4. Servlet-api-2.5

c) We have used Apache Tomcat v9.0 as a local server.

d) Working of the Code
1. Client page sends request to the Servlet API.
2. Servlet API validates and sends value to the database.
3. Database creates table, stores values in it and executes the required query
4. JSP takes response from the servlet
5. Client-page displays the required result

