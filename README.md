# URL Shortener Backend

A Spring Boot-based backend application for shortening URLs. This service allows users to generate short links for long URLs, redirect to the original URLs, and manage their shortened links.

## Features

- Shorten long URLs to compact, shareable links
- Redirect short URLs to their original destinations
- RESTful API endpoints for URL management
- Persistent storage using a relational database
- Error handling for invalid or expired URLs

## Technologies Used

- Java 17+
- Spring Boot
- Maven
- JPA/Hibernate
- H2 (default) or MySQL/PostgreSQL (configurable)
- Lombok (for boilerplate code reduction)
- Redis for caching

## Getting Started

### Prerequisites

- Java 17 or higher
- Maven

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/AbhishekU19/URL-Shortener-Project.git
   cd URL-Shortener-Project
