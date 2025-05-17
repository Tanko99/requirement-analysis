---
## Requirement Analysis In Software Development
---
## What is Requirement Analysis?
Requirement analysis refers to a phase in software development life-cycle (SDLC) where the project team identifies, analyzes, gathers and defines the requirements needed for the software product to be developed. There are usually two kinds of requirements which are; functional and non-functional requirements 

## Why is Requirement Analysis Important?
Requirement analysis is important because of the following reasons;
## ✅ 1. Ensures Clarity and Shared Understanding
- Requirement analysis helps developers, clients, and stakeholders understand and agree on what the system should do.
- It avoids miscommunication and ensures that all parties are on the same page before development begins.
## 💡 Example:
Without clear analysis, developers might build a single-room booking feature, while the client wanted multi-room bookings per transaction.

## ✅ 2. Reduces Cost and Rework
- Identifying errors or unclear requirements early prevents expensive fixes during development or after launch.
- Helps prioritize features, reducing waste of resources on unnecessary functionality.
## 💡 Example:
If the system is built without considering the cancellation policy logic, fixing it later might require code changes, database updates, and UI redesign.

## ✅ 3. Supports Better Design and Planning
- With well-analyzed requirements, architects and developers can make informed decisions about system architecture, technology stack, and timelines.
- Leads to a more efficient and realistic project plan.
## 💡 Example:
- Knowing that the booking system needs to support real-time availability influences the decision to use technologies like WebSockets or Firebase for live updates
- Would you like these formatted into a one-page study sheet or visual summary?









---

## Key Activities in Requirement Analysis

## 🧩 1. Requirement Gathering
- Involves collecting initial information from stakeholders (clients, users, managers).
-  Often done through interviews, questionnaires, brainstorming sessions, and market research.
-  Helps identify the basic goals, needs, and problems the system should solve.
-  Ensures early stakeholder involvement to avoid confusion later.
-  May include studying existing systems or documents for reference.

## 🕵️ 2. Requirement Elicitation
Focuses on extracting deep, detailed, and hidden requirements.
Uses techniques like:
- Workshops
- Observation (job shadowing)
- Use case analysis
- Prototyping
- Addresses implicit needs, assumptions, and domain-specific constraints.
- Often requires conflict resolution between contradictory stakeholder inputs.
- Helps refine vague ideas into actionable requirements.

## 📄 3. Requirement Documentation
Involves formally recording all gathered and elicited requirements.
Usually compiled into a Software Requirements Specification (SRS) document.
Types of documentation:
- Functional requirements (what the system does)
- Non-functional requirements (performance, security, usability)
- Use cases, user stories, acceptance criteria
- Creates a reference point for developers, testers, and clients.
- Should be clear, unambiguous, complete, and consistent.

## 🔍 4. Requirement Analysis and Modeling
Involves breaking down and understanding the structure, priority, and feasibility of requirements.Activities include:
- Identifying dependencies and conflicts
- Prioritizing requirements
- Checking for completeness and clarity
  
**Often uses models and diagrams:**
- Use case diagrams
- Data flow diagrams (DFD)
- Entity-relationship diagrams (ERD)
- Translates requirements into a format suitable for system design and architecture.

## ✅ 5. Requirement Validation
Ensures that requirements are:
- Correct – meet business needs
- Complete – cover all functionalities
- Consistent – free from contradictions
- Feasible – technically and financially viable
  
**Techniques used:**
- Reviews (peer, walkthroughs, inspections)
- Prototypes and mockups
- Client sign-off meetings
- Helps eliminate errors early, reducing cost and rework in later stages.
- Leads to final approval before the design phase begins.
---
## Types of Requirements
## 1. ✅ Functional Requirements
## Definition:
Functional requirements describe the specific behaviors, functionalities, or operations a system must perform. These are features or services the software should offer to meet user needs.

## Examples (Booking Management System):
- Users can create, update, and cancel bookings.
- The system must allow payment via credit card, PayPal, or wallet.
- Admin can view, filter, and manage all bookings.
- System should send email confirmations after each successful booking.
- Users can search for available rooms or services by price, location and availability..

## 2. ⚙️ Non-Functional Requirements
## Definition:
Non-functional requirements define the quality attributes of the system, such as performance, usability, reliability, security, and scalability. They do not describe specific behaviors, but rather how the system performs under various conditions.

## Examples (Booking Management System):
- The system should be able to handle up to 10,000 concurrent users.
- Response time for any page should be less than 2 seconds.
- The system must be available 24/7 with 99.9% uptime.
- All user data must be encrypted using AES-256 encryption.
- The interface should be mobile-responsive and accessible (WCAG 2.1 compliance).
---
## Use Case Diagrams
A Use Case Diagram is a type of UML (Unified Modeling Language) diagram that visually represents the interactions between users (actors) and a system. It shows what the system should do, not how it does it.

🧩 Key Components:
Actors: External entities (people, systems) that interact with the system (e.g., Customer, Admin).

Use Cases: Functionalities or services the system offers (e.g., Book Room, Cancel Booking).

System Boundary: A box that defines what is inside (system features) and outside (actors).

Relationships: Connections between actors and use cases (e.g., associations, includes, extends).

## ✅ Benefits of Use Case Diagrams
## 1. 👥 Improves Stakeholder Communication
- Simple visual format that's easy for both technical and non-technical stakeholders to understand.
- Helps stakeholders see what the system will do from a user perspective.

## 2. 🗂️ Clarifies System Scope
- Defines the boundaries of the system.
- Clearly shows which functionalities are part of the system and which are outside its scope.

## 3. 🛠️ Assists in Requirement Gathering
- Encourages thinking from a user’s point of view.
- Helps identify missing or unclear requirements during early development stages.

## 4. 📐 Lays the Foundation for Design and Testing
- Forms the basis for creating detailed use case specifications, scenarios, and test cases.
- Ensures coverage of all user interactions in the system.

## 5. 🔄 Supports Reusability and Modularity
- Use cases like "Process Payment" can be reused in multiple diagrams (e.g., hotel booking, ticket booking).
- Promotes modular thinking, which aids in software design and maintenance.


---
