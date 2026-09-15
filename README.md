# SWYNEX-CLOUD-ARCHITECTURE-task
"Simple cloud architecture design(Client, load balancer, API server,database)--Internship task for SWYNEX technology"

## Components

**1. Client** — The user's browser or mobile app that sends requests.

**2. Load Balancer** — Distributes incoming requests across multiple app servers to prevent overload and ensure availability.

**3. App/Server (Business Logic)** — Handles core application logic, processes requests, and communicates with the database.

**4. Database** — Stores and retrieves the application's data.

## Flow

Client → Load Balancer → App/Server → Database

## Why this architecture?

- **Scalability**: Easy to add more app servers as traffic grows.
- **Reliability**: If one server fails, the load balancer redirects traffic to healthy ones.
- **Separation of concerns**: Each layer has a clear responsibility, making the system easier to maintain.

## Diagram

See the attached PDF (`task diagram.drawio.pdf`) in this repository for the visual diagram.
