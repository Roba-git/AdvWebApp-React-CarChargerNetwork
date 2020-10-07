# AdvWebApp-React-CarChargerNetwork
Course assignment for advanced web applications
Web Frameworks graded exercise

You grade on the course will be based on this exercise. The exercise can either solo or in team of two persons.

Topic

You are to use ReactJs and Express to implement a web application for an imaginary electric car charger network provider. The business of this company is to provide electric car chargers across the country. They need an application which their customers can use.

The basic functionality of the application is to provide information of the charger locations, status and pricing to the customers. The customer can use the application to start and stop the charging of his car when plugged in and then be billed of the charge.

There are two types of chargers:

· “Slow” 22kW chargers with Type 2 connectors.

· “Fast” 50-150kW chargers with CCS connectors.

Price of charging can be different options:

· Some of the slow chargers are free, but still require the application to be used to start the charging

· Some of the slow chargers are paid by the minute (0.20 e/min)

· Fast chargers are paid by consumed electricity (18 c/kWh)

Functional requirements for the web application

· User login system which authenticates and authorizes users to access the system

o User should be able browse the charger locations, status and general information without logging in

o Login is required to start the charging process

· Start charging once the user has connected his car to a charger

o The charge process is started by entering a four digit string to the system to indicate which charger the customer wants to use (“A4CV” for example). The application should display this four digit code and the code would be visible in the charge station as well.

· Monitor the ongoing charge and its costs

· Stop charging

· Browse available chargers ideally on a map (alternatively as a list of some sort) - Display at least 20 charging locations in Finland

o In both cases there should be a search functionality by the location / charger name

o Information of the charger type and its status should be visible easily to the user

§ Status (Free, Taken)

· View previous charges and their costs

o Display date and time information, charger location, its information, charge time, energy used and cost

o The actual payment of the charges is not covered by this application

Deliverables

Source code and running application in the cloud

You must deliver the source code of your application as a link to public github repository. In the repository there must be roughly equal amount of commits/contributions from all the team members if all team members wish to get equal grade. Remember to commit and push often. Having only single commit of the whole work will affect negatively to the grades.

Running application must be available in the public internet. AWS platform is recommended (training on this in class will be conducted on the 2.10.)

When you return your work return two links:

· Link to github repository

· Link to the server running the application

Return & schedule

Return process will be handled via moodle workshop available at course moodle site. The workshop will be configured so that everybody who returns a work will also be required to review and grade three other works. The review order will be randomized. Conducting the review is a requirement to pass the course.

Deadline on returning the work is on Wednesday 14.10. at 23.59. The review phase will begin immediately after that and must be completed by the latest on Friday 16.10. at 23.59.

If you cannot finish the application in time, then return it unfinished. That way you can still get a grade, just not the maximum 5.

Additionally when you return your work you must reserve a meeting with the teacher via email. In the meeting all team members must be present. The team will present the application, explain how it has been implemented and what were the responsibilities of the team members.

Notice that you should reserve the meeting well in advance. Do not expect to get a guaranteed delivery time for example the day before.

Grading

Maximum points from this exercise is 20p.

Feature scoring

User login system which authenticates and

authorizes users to access the system 4

Application displays chargers on a map, all

specified charger types and pricings displayed,

search functionality 6

Start and stop charging, see charging data and

costs 4

View previous charges and their costs 2

Application available in public internet and

deployed to AWS 4

Negative factors

Messy code (indentations, code in one or only few large files)

"React way of doing things not followed - direct dom manipulation, little or no use of components, no

clear state management"

Bad use of version control 
