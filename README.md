# Revolut Requirements Engineering

Requirements Engineering project for the Revolut application.

## 1. Introduction

This project applies the Requirements Engineering process to the Revolut application. The objective is to identify, analyze, document and validate the main software requirements of the application.

Revolut is a digital financial application that allows users to manage money, make transfers, exchange currencies, use physical and virtual cards, view transactions and access other financial services.

## 2. Requirements Elicitation

The main features of the Revolut application were examined in order to identify the expected system requirements.

Main features identified:

- User registration and login
- Identity verification
- Bank account and IBAN management
- Money transfers
- Currency exchange
- Physical and virtual cards
- Card security controls
- Transaction history
- Spending analytics
- Notifications
- Savings and investment services

## 3. Functional Requirements

- FR1: The system shall allow users to create an account.
- FR2: The system shall allow users to log in securely.
- FR3: The system shall allow users to verify their identity.
- FR4: The system shall allow users to view their account balance.
- FR5: The system shall allow users to send money to other users or bank accounts.
- FR6: The system shall allow users to receive money.
- FR7: The system shall allow users to exchange currencies.
- FR8: The system shall allow users to create and manage virtual cards.
- FR9: The system shall allow users to manage physical cards.
- FR10: The system shall allow users to freeze and unfreeze cards.
- FR11: The system shall display transaction history.
- FR12: The system shall send notifications for transactions.
- FR13: The system shall allow users to view spending analytics.
- FR14: The system shall allow users to manage savings or investment services where available.

## 4. Non-Functional Requirements

- NFR1: The system shall protect sensitive user data using strong encryption.
- NFR2: The system shall require secure authentication mechanisms.
- NFR3: The system shall be available 24/7 except during planned maintenance.
- NFR4: The system shall process common user actions within a few seconds under normal conditions.
- NFR5: The system shall support a large number of concurrent users.
- NFR6: The system shall provide a simple and user-friendly mobile interface.
- NFR7: The system shall comply with applicable banking and data protection regulations.
- NFR8: The system shall log important security and transaction events for auditing purposes.
- NFR9: The system shall recover safely from failures without losing confirmed transaction data.
- NFR10: The system shall be compatible with commonly supported mobile operating systems.

## 5. Requirements Analysis and Negotiation

The identified requirements were analyzed and prioritized.

Security and legal compliance were considered the highest priority because Revolut handles sensitive financial information.

Core functions such as account access, money transfers, receiving money, balance viewing and transaction history were considered essential.

Currency exchange and card management were also considered important core features.

Spending analytics and notifications were considered useful but lower priority than security and transaction functions.

Savings and investment services may depend on the country and applicable regulations.

### Negotiated Requirements

- NR1: Secure authentication and protection of user data must be implemented before optional features.
- NR2: Money transfer, receiving money and balance viewing must be available as core functions.
- NR3: Transaction history must be reliable and accessible to the user.
- NR4: Card freeze and unfreeze functions must be immediately available for security reasons.
- NR5: Currency exchange should be provided where legally supported.
- NR6: Notifications should be available for important financial activities.
- NR7: Savings and investment services should only be offered where regulations and business rules permit.
- NR8: Performance and availability requirements must support the core financial functions.

## 6. Requirements Documentation

The requirements were documented using unique identifiers such as FR, NFR and NR.

Each functional requirement describes a service that the system must provide.

Each non-functional requirement describes a quality attribute or constraint of the system.

The requirements were written in a clear and structured form to improve readability and testability.

## 7. Requirements Validation

### Validation Report

- The requirements were reviewed for clarity and ambiguity.
- Functional requirements describe specific actions that the system must perform.
- Non-functional requirements describe quality attributes such as security, performance, availability and usability.
- No major conflicts were identified between the core functional requirements.
- Security and regulatory requirements were given high priority because the application handles financial data.
- Optional services such as savings and investments may vary depending on country and regulation.
- Most requirements are testable because expected system behavior can be verified.
- Some non-functional requirements, such as performance and availability, should be defined with more precise measurable values in a real project.
- The final requirements are considered consistent and suitable for the current scope of the project.

## 8. Volatile Requirements

The following requirements may change over time because of regulations, business decisions, technology or user needs:

- VR1: Identity verification requirements may change because of new KYC and anti-money laundering regulations.
- VR2: Transaction limits may change depending on country, account type or regulatory rules.
- VR3: Fees for transfers, currency exchange or card services may change according to Revolut business policies.
- VR4: Supported currencies may change over time.
- VR5: Investment and savings services may change depending on local regulations.
- VR6: Security and authentication methods may change as new technologies and threats appear.
- VR7: Supported mobile operating system versions may change as Android and iOS evolve.
- VR8: Card features and limits may change depending on user plan or subscription type.
- VR9: Data protection requirements may change because of new privacy laws.
- VR10: Notification and fraud detection rules may change to respond to new types of financial fraud.

## 9. Project Management

A GitHub Kanban board was created to manage the work.

The board contains the following stages:

- Todo
- In Progress
- Done

The activities of the Requirements Engineering process were tracked using this board.

## 10. Conclusion

This project applied the main stages of the Requirements Engineering process to the Revolut application.

Functional and non-functional requirements were identified, analyzed, negotiated, documented and validated.

Volatile requirements were also identified, and a GitHub Kanban board was used to organize and track the work.
