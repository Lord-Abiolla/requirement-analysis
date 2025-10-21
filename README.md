# Requirement Analysis in Software Development


This repository helps the learner understand the need for Requirement Analysis in Software Development. Through a series of well-defined tasks, a learner will be able to create a well detailed blueprint of the requirement analysis phase for a booking management system.


## What is Requirement Analysis?

Requirement Analysis is a phase in Software Development lifecycle (SDLC) where the project team gathers, analyzes, and defines the requirements of the software product to be developed. It ensures that all stakeholders have a clean and mutual understanding of what the system should do and how it should perform.

## Why is Requirement Analysis Important?

- __Clarity and Understanding:__ It helps in understanding what the stakeholders expect from the software, reducing ambiguity.
- __Scope Definition:__ Clearly defines the scope of the project, which helps in preventing scope creep.
- __Basis for Design and Development:__ Provides a solid foundation for designing and developing the system.
- __Cost and Time Estimation:__ Facilitates accurate estimation of project cost, resources, and time.
- __Quality Assurance:__ Ensures that the final product meets the specified requirements, leading to higher customer satisfaction.

## Key Activities in Requirement Analysis.

### 1. Requirement Gathering 🗂️
- __Interviews:__ Conducting interviews with stakeholders to gather detailed information about their needs and expectations.
- __Surveys/Questionnaires:__ Distributing surveys to collect requirements from a larger audience.
- __Workshops:__ Organizing workshops with stakeholders to discuss and gather requirements.
- __Observation:__ Observing end-users in their working environment to understand their needs.
- __Document Analysis:__ Reviewing existing documentation and systems to understand current functionalities and requirements.
### 2. Requirement Elicitation ✍️
- __Brainstorming:__ Conducting brainstorming sessions to generate ideas and gather requirements.
- __Focus Groups:__ Holding focus group discussions with selected stakeholders to gather detailed requirements.
- __Prototyping:__ Creating prototypes to help stakeholders visualize the system and refine their requirements.
### 3. Requirement Documentation 📚
- __Requirement Specification Document:__ Creating a detailed document that lists all functional and non-functional requirements.
- __User Stories:__ Writing user stories to describe functionalities from the user’s perspective.
- __Use Cases:__ Creating use case diagrams to show interactions between users and the system.
### 4. Requirement Analysis and Modeling 📊
- __Requirement Prioritization:__ Prioritizing requirements based on their importance and impact on the project.
- __Feasibility Analysis:__ Assessing the feasibility of requirements in terms of technical, financial, and time constraints.
- __Modeling:__ Creating models (e.g., data flow diagrams, entity-relationship diagrams) to visualize and analyze requirements.
### 5. Requirement Validation ✅
- __Review and Approval:__ Reviewing the documented requirements with stakeholders to ensure accuracy and completeness.
- __Acceptance Criteria:__ Defining clear acceptance criteria for each requirement to ensure they meet the expected standards.
- __Traceability:__ Establishing traceability matrices to ensure all requirements are addressed during development and testing.

## Types of Requirements.

| **Functional Requirements** | **Non-Functinal Requirements**|
|-----------------------------|-----------------------------------|
| Describe what the system should do | Describe how the system should perform |
| Examples include user authentication, property search, booking system, user registration | Examples include Performance, security, scalability, usability, reliability |


## Use Case Diagrams.
A usecase diagram is a visual representation of interactions between users and the system.
It shows how different users (actors) interact with the system to achieve specific goals (use cases).

[alx_booking_usecase](./alx-booking-uc.png)

## Acceptance Criteria.

**Acceptance criteria** are conditions that a feature must meet to be accepted by the stakeholders.

Acceptance criteria serves the following purposes in Requirement Analysis:
- Ensure all parties have a clear understanding of feature requirements.
- Provide a basis for testing and validation.
- Help in maintaining quality and meeting user expectations.

Acceptance criteria for Checkout feature in a booking management system include:
- Display Checkout page: The system should display the checkout page showing booking details
- Payment Options: The system should display available payment methods
- Valid payment processing: The payment should be processed successfully, and the booking status should update.
- Confirmation Receipt: The system should display a booking confirmation page with a summary of the booking.
- Data Security: All sensitive data should be transmitted over a secure HTTPS connection, and no card details should be stored in plain text.
