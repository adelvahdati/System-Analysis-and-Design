**Lecture Notes: Architectural Patterns & Styles**

---

**1. Introduction to Software Architecture**

**Definition:** Software architecture defines the fundamental structures of a software system and the discipline of creating such structures and systems. It involves a set of significant decisions about the organization of the software system.

**Importance:**

* Affects performance, scalability, maintainability
* Facilitates stakeholder communication
* Enables reuse of components and patterns

---

**2. Difference Between Architecture Patterns and Design Patterns**

* **Architectural Patterns**: High-level solutions to broad structural problems (e.g., Microservices, Layered)
* **Design Patterns**: Mid-to-low level solutions to design problems within components (e.g., Singleton, Strategy)

---

**3. Common Architectural Patterns & Styles**

**a. Layered Architecture (N-tier)**

* Structure: Presentation, Business Logic, Data Access layers
* Benefits: Separation of concerns, ease of testing
* Use Case: Web applications, enterprise systems

**b. Client-Server**

* Structure: Clients send requests, server processes and responds
* Benefits: Centralized control, scalable server side
* Use Case: Web services, email systems

**c. Model-View-Controller (MVC)**

* Structure: Model (data), View (UI), Controller (input handling)
* Benefits: Separates UI from logic, easy to maintain
* Use Case: Web frameworks like ASP.NET MVC, Django, Ruby on Rails

**d. Microservices Architecture**

* Structure: Suite of small services, each running independently
* Benefits: Scalability, technology heterogeneity, fault isolation
* Use Case: Large-scale enterprise applications (Netflix, Amazon)

**e. Event-Driven Architecture**

* Structure: Components react to events, typically asynchronous
* Benefits: Loose coupling, real-time processing
* Use Case: IoT systems, financial apps, reactive systems

**f. Service-Oriented Architecture (SOA)**

* Structure: Services communicate over a network
* Benefits: Reusability, platform independence
* Use Case: Government systems, legacy integrations

**g. Pipe and Filter**

* Structure: Data flows through filters (processing units) via pipes
* Benefits: Reusability, concurrency
* Use Case: Data transformation, compiler design

**h. Peer-to-Peer (P2P)**

* Structure: All nodes act as both client and server
* Benefits: Resilience, decentralization
* Use Case: File sharing (BitTorrent), blockchain

---

**4. Selecting the Right Pattern**

**Criteria:**

* Application size and complexity
* Team skillset
* Scalability and performance needs
* Maintainability and testability
* Deployment and operational constraints

---

**5. Combining Patterns**

* Real-world systems often use a mix (e.g., Microservices + Event-Driven + Layered)
* Important to manage dependencies and interactions

---

**6. Summary**

* Architectural patterns provide templates for solving high-level design problems
* Selection depends on requirements, environment, and goals
* A strong architecture supports maintainability, scalability, and agility

---

**Discussion Prompt:**
"Choose an existing application (e.g., Netflix, a university portal, or a hospital system). Identify which architectural patterns it likely uses and justify your reasoning."

---

**End of Lecture Notes**
