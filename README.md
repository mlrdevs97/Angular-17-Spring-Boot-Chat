# Real-Time Multi-User Chat Application

---

This is a **real-time, multi-user chat application** built with **Spring Boot** and **Angular**. It empowers registered users to seamlessly add contacts and engage in live communication through **WebSockets**. Security is a top priority, ensured by a robust **JWT-based authentication system** powered by **Spring Security**.

---

## Key Features

### Client-Side (Angular)

* **Reactive Data Flow:** Manages asynchronous data streams efficiently using **RxJS** for a highly responsive user experience.
* **Robust Forms & Validation:** Implements **reactive forms** with comprehensive data validation, including **custom validators** for specific business rules.
* **Smart Routing:** Utilizes Angular's routing capabilities with **guards** to control access to different parts of the application, ensuring a secure and logical user journey.
* **Secure HTTP Communication:** Integrates **interceptors** for seamless handling of **JWT tokens** in all HTTP requests, ensuring secure communication with the backend.
* **Optimized Route Loading:** Employs **resolvers** to pre-fetch data or execute actions before a route fully loads, enhancing perceived performance.
* **Type Safety:** Leverages **custom typing** to strictly structure and validate data throughout the application, leading to fewer runtime errors.
* **Component Management:** Effectively manages Angular components and their lifecycles for optimal performance and maintainability.
* **Centralized Logic:** Utilizes **services** to centralize business logic, facilitate HTTP communication, and enable smooth data exchange between components.
* **User Feedback:** Implements comprehensive **error handling** with clear and timely feedback to the user.
* **Real-Time Communication:** Establishes **real-time communication** with the server using **WebSockets**, enabling instant message delivery.

### Server-Side (Spring Boot)

* **Layered Architecture:** Designed with a **layered architecture** for improved code organization, maintainability, and scalability.
* **Data Persistence:** Achieves robust class modeling and **data persistence** using **Hibernate**.
* **Business Logic:** Develops essential **business logic** to ensure all server operations meet functional requirements accurately.
* **API Endpoints:** Handles **HTTP communication** through custom controllers, defining clear API endpoints for client interaction.
* **Database Operations:** Utilizes **custom repositories** for efficient and organized database operations.
* **Secure Authentication:** Implements a strong **JWT token-based authentication system** with **custom filters** for enhanced security.
* **Data Validation:** Includes comprehensive **data validation**, featuring the use of **custom annotations** for specific validation rules.
* **Robust Error Handling:** Provides robust **error handling**, including the creation of **custom exceptions** for specific error scenarios.
* **Data Transformation:** Creates **custom mappers** to facilitate seamless data exchange between database entities and Data Transfer Objects (DTOs).
* **Real-Time Communication:** Implements **WebSockets** to establish efficient and reliable **real-time communication** with the client.

---
