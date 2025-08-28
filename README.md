# requirement-analysis

## What is Requirement Analysis?
**Requirement Analysis** is the process of identifying, gathering, analysing, and documenting the needs and expectations of stakeholders for a software system.  
It is one of the most important phases of the **Software Development Lifecycle (SDLC)** because it lays the foundation for design, development, and testing.

---

## Why is Requirement Analysis Important?
Requirement Analysis is one of the most critical phases in the SDLC. Its significance can be summarised as follows:

### 1. Foundation for the Project
- Provides a blueprint for design, coding, testing, and deployment.
- Defines the scope and boundaries of the system, reducing ambiguity.

### 2. Reduces Risk of Failure
- Misunderstood or missing requirements are a leading cause of software project failures.
- Early clarification prevents costly errors later in the lifecycle.

### 3. Saves Time and Cost
- Resolving requirement-related issues during analysis is cheaper than fixing them later.
- Helps avoid rework and delays.

### 4. Enhances Communication
- Acts as a bridge between stakeholders and the development team.
- Ensures a shared understanding of system objectives.

### 5. Improves Quality Assurance
- Clear, testable requirements allow testers to design precise test cases.
- Ensures the final product aligns with business needs and user expectations.

### 6. Supports Change Management
- Proper requirement management allows changes to be tracked and controlled.
- Prevents scope creep and keeps the project aligned with goals.

---

## Key Activities in Requirement Analysis

### 1. Requirement Gathering
- Collect information from stakeholders (clients, users, business managers).
- Methods: **interviews, surveys, questionnaires, observations**.

### 2. Requirement Elicitation
- Engage with stakeholders to refine requirements.
- Methods: **workshops, brainstorming, conflict resolution**.
- Goal: uncover both explicit and implicit needs.

### 3. Requirement Documentation
- Record requirements in a structured format (e.g., **Software Requirement Specification (SRS)**).
- Ensures clarity, consistency, and reference throughout SDLC.

### 4. Requirement Analysis and Modelling
- Study and structure requirements for **feasibility, consistency, and completeness**.
- Tools: **data flow diagrams, use case diagrams, process models**.

### 5. Requirement Validation
- Confirm documented requirements match stakeholder needs.
- Methods: **reviews, walkthroughs, prototypes, test-case mapping**.
- Prevents misunderstandings before development.

---

## Types of Requirements

### Functional Requirements
Define **what the system should do** — features, services, and behaviors.

**Examples (Booking Management System like Airbnb):**
- Users can search for properties by location, date, price, and amenities.
- Hosts can list properties with description, price, photos, and availability.
- Users can create accounts, log in, and manage profiles.
- Guests can book properties and receive email confirmations.
- The system supports secure payment processing.
- Hosts can accept or reject booking requests.

### Non-Functional Requirements (NFRs)
Define **how the system should perform** — performance, usability, reliability.

**Examples (Booking Management System like Airbnb):**
- System should handle **1M concurrent users** without performance degradation.
- Search results must load within **3 seconds** during peak traffic.
- System availability should be **99.9% uptime**.
- Payments must comply with **PCI DSS security standards**.
- Support **multi-language and multi-currency** features.
- Mobile app must be compatible with the latest iOS and Android versions.

✅ **Summary**:  
- Functional = *Features* (what it does)  
- Non-Functional = *Quality attributes* (how it works)

---

## Use Case Diagrams
A **Use Case Diagram** visually represents how users (**actors**) interact with a system.  
It shows functional requirements by illustrating relationships between users and use cases (tasks/services).

**Benefits:**
- **Clarity**: Simple and intuitive way to capture functional requirements.  
- **Communication**: Bridges gap between stakeholders and developers.  
- **Scope Definition**: Defines system boundaries.  
- **User-Centered Design**: Focuses on user needs.  
- **Foundation for Development**: Guides detailed design and test cases.
<img width="1536" height="1024" alt="alx_booking_uc" src="https://github.com/user-attachments/assets/018c82bb-2ad2-4a88-a759-13687853b601" />

---

## Acceptance Criteria
**Acceptance Criteria** are predefined conditions that a software product must meet to be accepted by stakeholders.  
They define the boundaries of a requirement and clarify what “done” means.

**Importance:**
- **Clarity**: Eliminates ambiguity with expected outcomes.  
- **Alignment**: Ensures all parties share the same understanding.  
- **Quality Assurance**: Basis for test case design.  
- **Scope Control**: Prevents scope creep.  
- **Customer Satisfaction**: Ensures stakeholder expectations are met.  

---


