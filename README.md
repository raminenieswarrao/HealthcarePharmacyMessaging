# HealthcarePharmacyMessaging
This project demonstrates a pharmacy messaging system using Spring Boot, JMS, and IBM MQ. It facilitates communication between a pharmacy system and an insurance claim processor.

# Disclaimer
The code provided in this project is solely written as an example for learning purposes. It is original and not copied from any external source. The design and implementation are tailored to demonstrate a real-world healthcare pharmacy scenario.

# Install the IBM MQ Server (local)
This IBM MQ Server will be used to handle middleware messaging system for this project.
Source: https://developer.ibm.com/tutorials/mq-connect-app-queue-manager-windows/

# Agenda
Real-Time Scenario: Prescription Fulfillment and Claim Processing
Example Use Case:

Pharmacy System: Sends a prescription request (e.g., drug details, patient ID) to the IBM MQ queue.
Insurance System: Consumes the message from the queue, processes the claim, and sends an approval/denial response back to another queue.
Logs and dashboards track these interactions for auditing and monitoring purposes.
