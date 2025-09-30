# Requirement Analysis  

## What is Requirement Analysis?  
Requirement Analysis is the process of identifying, documenting, and managing the needs and expectations of stakeholders for a system or project. It forms the foundation of software development, ensuring that the final product addresses the right problems and delivers value.  

During requirement analysis, developers and stakeholders collaborate to clarify what the system should do, how it should behave, and the constraints under which it must operate.  

### Importance of Requirement Analysis  
- **Clarity**: Eliminates misunderstandings by defining the scope and objectives clearly.  
- **Prioritization**: Helps determine which features are essential and which are optional.  
- **Communication**: Acts as a bridge between stakeholders (business owners, users) and the development team.  
- **Risk Reduction**: Identifies potential issues early, saving time and costs later.  
- **Quality Assurance**: Provides measurable criteria for testing and validation.  

### Types of Requirements  
1. **Functional Requirements** – Define what the system should do (e.g., “The user can log in with email and password”).  
2. **Non-Functional Requirements** – Define system qualities or constraints (e.g., performance, security, scalability).  
3. **Business Requirements** – High-level objectives of the organization or project.  
4. **User Requirements** – Expectations and needs of end-users interacting with the system.  

---

## Use Case Diagrams

### What are Use Case Diagrams?
A **Use Case Diagram** is a visual representation of how users (actors) interact with a system to achieve specific goals. It captures functional requirements by illustrating the relationships between actors and use cases.

**Benefits of Use Case Diagrams:**
- Provides a **clear overview** of system functionality.  
- Helps identify **interactions between users and the system**.  
- Facilitates communication between stakeholders and developers.  
- Acts as a **foundation for creating detailed requirements and test cases**.  

### Booking System Use Case Diagram
Below is the use case diagram for the **Booking Management Project**, showing the primary actors (User and Admin) and their interactions with the system:

![Booking System Use Case Diagram](alx-booking-uc.png)

## Acceptance Criteria

### What is Acceptance Criteria?
Acceptance Criteria (AC) are **predefined conditions that a software product or feature must meet to be accepted by the stakeholders or end users**. They serve as a checklist that determines whether the implementation of a requirement is complete and working as intended.  

### Importance of Acceptance Criteria in Requirement Analysis
- **Clarity and Alignment**: Ensures that stakeholders, developers, and testers share the same understanding of what “done” means for a requirement.  
- **Guides Development**: Helps developers know exactly what functionality is expected before coding begins.  
- **Facilitates Testing**: Provides testers with specific, measurable conditions to validate during quality assurance.  
- **Reduces Ambiguity**: Minimizes misunderstandings by converting vague requirements into concrete, testable statements.  
- **Improves Stakeholder Confidence**: Demonstrates that requirements are being met as expected, increasing satisfaction.  

---

### Example: Acceptance Criteria for the Checkout Feature

For a **Booking Management System**, the **Checkout** feature might have the following acceptance criteria:

- Users must be able to review their booking details (dates, room type, price) before payment.  
- The system must support at least two payment methods (e.g., credit card and PayPal).  
- Payment information must be securely encrypted and stored according to industry standards.  
- A confirmation message must be displayed immediately after successful payment.  
- The system must send a confirmation email with booking details within 5 minutes of checkout.  
- If payment fails, users must see an error message and be able to retry or select another payment method.  

---

