## BNY Mellon – Pittsburgh, PA 7/20-12/22

**Unified Payments Postprocessor** – Created and maintained an internal payment validation and routing service written in Java using the Spring Boot development framework with an international team of 15 developers. This service unified all SWIFT financial transaction payment flows going through BNY Mellon along with several manual steps in order to improve maintainability and ease of use while preserving compliance with federal statutes. Transactions were sent asynchronously through a Kafka messaging queue. The service extracted messages from Kafka, transformed them into the proper data structure, and stored them in an Oracle Database using both the Hibernate ORM and handwritten SQL. Changes to this codebase were validated using a Continuous Integration/Continuous Deployment (CI/CD) pipeline through Gitlab.

Duties for this project included: 
 - Creating Kafka Listeners to receive new types of Kafka messages from the Preprocessor Team. 
 - Extracting data from Oracle Database into SWIFT data format and validating the compiled message.
 - Sending newly compiled messages to other BNY Mellon Microservices. 
 - Correcting issues with messages that failed validation.
 - Creating automated tests which were validated with CI/CD.

**International Financial Transfer Authorization** – Created and maintained a new application with an international team of 15 developers automating the authorization workflow of international financial transfers written in Java using the Spring Boot development framework. The application included forms coded in Angular.js, notifications over email or text, and digital authorization. Frequently 5 or more people needed to approve a transfer and depending on the nature of the transfer the forms presented were different. The results of the responses were stored and retrieved from an Oracle Database using the Hibernate ORM. This application ensured that any issues were handled in a timely manner due to the notification system and removed common issues, greatly improving efficiency.

Duties for this project included: 
 - Adding or removing interactive fields.
 - Creating the endpoints and functionality behind storing, retrieving, and validating field data.
 - Correcting front and back-end validation issues.
 - Creating automated tests which were validated with CI/CD.
 - Documenting the onboarding process for future developers.

## SCA Technologies (Co-op) – Pittsburgh, PA 5/18-9/19

**iOS/Android Customer Portal** – I was the lead developer in a 3-person team that built a mobile version of the company portal for franchise owners to see limited company reporting and commodity market state using Ember.js, Postgres, Java, and Apache Cordova. This resulted in increased transparency between the franchisees and their parent companies.

**Status Page** – Created a web-based status page with email or text notifications using Ember.js, Postgres, and RESTful Java with one other developer. Health of all involved services and APIs was determined by using a combination of Jira tickets and Graylog reports. This gave the end customer up-to-date information in the event of an outage and reduced call-center demand.

Duties for both projects included: 
 - Designing layout, workflow, and technologies for the application with input from the product owner.
 - Creating automated tests to be validated with CI/CD.
 - Presenting the completed project for feedback and incorporating that feedback.

## Education

University of Pittsburgh School of Computing & Information 2020 Bachelor of Science (BS), Computer Science