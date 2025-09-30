# Requirement Analysis  

## What is Requirement Analysis?  
Requirement Analysis is the process of identifying, documenting, and managing the needs and expectations of stakeholders for a system or project. It forms the foundation of software development, ensuring that the final product addresses the right problems and delivers value.  

During requirement analysis, developers and stakeholders collaborate to clarify what the system should do, how it should behave, and the constraints under which it must operate.  

---

## Why is Requirement Analysis Important?  
Requirement Analysis is crucial because it ensures that the final system meets user needs, aligns with business goals, and avoids costly rework.  

- **Clarity**: Eliminates misunderstandings by defining the scope and objectives clearly.  
- **Prioritization**: Helps determine which features are essential and which are optional.  
- **Communication**: Acts as a bridge between stakeholders (business owners, users) and the development team.  
- **Risk Reduction**: Identifies potential issues early, saving time and costs later.  
- **Quality Assurance**: Provides measurable criteria for testing and validation.  

---

## Key Activities in Requirement Analysis  
1. **Requirement Elicitation** – Gathering requirements from stakeholders using interviews, surveys, workshops, etc.  
2. **Requirement Documentation** – Clearly recording functional and non-functional requirements.  
3. **Requirement Validation** – Ensuring requirements are feasible, complete, and aligned with objectives.  
4. **Requirement Management** – Tracking changes to requirements throughout the project lifecycle.  

---

## Types of Requirements  
Requirements can be categorized into several types to ensure coverage across business, user, functional, and non-functional needs.  

1. **Business Requirements** – High-level objectives of the organization (e.g., maximize hotel occupancy).  
2. **User Requirements** – Needs of end-users (e.g., customers should be able to search hotels by location).  
3. **Functional Requirements** – Define system behavior (e.g., allow booking cancellations up to 24 hours before check-in).  
4. **Non-Functional Requirements** – Define performance, scalability, and security expectations (e.g., search results must load in ≤2 seconds).  

### Case Study: Hotel Booking System  
- **Business Requirement:** Increase customer satisfaction by offering multiple payment options.  
- **User Requirement:** Travelers can filter hotels by price, location, and availability.  
- **Functional Requirement:** The system must send booking confirmation emails after successful payment.  
- **Non-Functional Requirement:** The system must handle 1000 concurrent booking requests without downtime.  

---

## Acceptance Criteria  

### What is Acceptance Criteria?  
Acceptance Criteria (AC) are predefined conditions that a software product or feature must meet to be accepted by stakeholders or end users. They serve as the **definition of done**, ensuring clarity, measurability, and alignment across teams.  

### Why is Acceptance Criteria Important?  
- **Eliminates Ambiguity:** Provides a clear understanding of what needs to be achieved.  
- **Guides Development:** Developers know exactly what functionality to implement.  
- **Supports Testing:** Testers can validate features against specific, measurable conditions.  
- **Improves Quality:** Ensures features truly meet user and business needs.  
- **Boosts Confidence:** Stakeholders trust that requirements are fulfilled.  

### Types of Acceptance Criteria  
1. **Functional Criteria** – Define behaviors (e.g., system prevents double booking).  
2. **Non-Functional Criteria** – Define qualities (e.g., booking API must respond in ≤2 seconds).  
3. **Regulatory Criteria** – Ensure compliance (e.g., payment processing must meet PCI-DSS standards).  

### Case Study: Hotel Booking System  
- A customer can search for hotels by location, price, and date filters.  
- The booking service prevents reservations if no rooms are available.  
- Payment processing must support at least two options (credit card, PayPal, or mobile money).  
- After booking, a confirmation notification is sent instantly to both customer and manager.  
- Search results must load within **2 seconds** for 95% of user queries.  

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
