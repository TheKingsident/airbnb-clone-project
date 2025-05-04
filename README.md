# airbnb-clone-project

## Team Roles
- Backend Developer: Responsible for implementing API endpoints, database schemas, and business logic.
- Database Administrator: Manages database design, indexing, and optimizations.
- DevOps Engineer: Handles deployment, monitoring, and scaling of the backend services.
- QA Engineer: Ensures the backend functionalities are thoroughly tested and meet quality standards.
- Product owner (PO)
- Project manager (PM)
- UI/UX designer
- Software architect
- Software developer
- Quality assurance (QA) engineer
- Test automation engineer
- DevOps engineer

## Technology Stack
- Django: A high-level Python web framework used for building the RESTful API.
- Django REST Framework: Provides tools for creating and managing RESTful APIs.
- PostgreSQL: A powerful relational database used for data storage.
- GraphQL: Allows for flexible and efficient querying of data.
- Celery: For handling asynchronous tasks such as sending notifications or processing payments.
- Redis: Used for caching and session management.
- Docker: Containerization tool for consistent development and deployment environments.
- CI/CD Pipelines: Automated pipelines for testing and deploying code changes.

## Database Design
- users: A user can have zero or multiple properties
- properties: A property can have multiple bookings, but not within the same similar periods
- bookings:  A booking to one property and never clashing with another booking for the same property at the same time
- payments: Unique to each property, booking and user
- reviews: A property will have 0 or as many reviews as possible

## Feature Breakdown
- User Authentication
- Property management
- Booking system
- Payment Processing
- Review system

## API Security
The API will be secured using rate limiting, authentication and authorisation to prevent unauthorised access and abuse

## CI/CD Pipeline
- GitHub Actions
- Docker
