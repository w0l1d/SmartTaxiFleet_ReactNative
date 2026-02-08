# Smart Taxi Fleet

A full-stack taxi fleet management application with a **Spring Boot** backend and a **React Native** mobile frontend.

## Overview

Smart Taxi Fleet provides a complete platform for managing taxi fleets with real-time tracking, trip management, and driver/passenger interfaces. The monolithic backend handles business logic, routing, and data persistence, while the React Native mobile app delivers a cross-platform experience for both drivers and passengers.

## Tech Stack

### Backend
- **Java** — Spring Boot
- **Neo4j** — Graph database for route optimization
- **Google Maps API** — Geocoding and routing

### Frontend
- **React Native** — Cross-platform mobile app
- **TypeScript**
- **Google Maps SDK** — Real-time map rendering

## Project Structure

```
├── backend/          # Spring Boot REST API
│   └── ...
├── frontend/         # React Native mobile app
│   └── ...
└── package-lock.json
```

## Features

- Real-time driver location tracking on map
- Trip booking and assignment
- Route optimization using graph-based algorithms
- Driver and passenger role-based views
- Google Maps integration for navigation
- Fleet analytics and reporting

## Getting Started

### Backend

```bash
cd backend
./mvnw spring-boot:run
```

### Frontend

```bash
cd frontend
npm install
npx react-native run-android  # or run-ios
```

### Prerequisites

- Java 17+
- Node.js 18+
- Android Studio / Xcode
- Neo4j database instance
- Google Maps API key

## Academic Context

Built as part of the ILISI (Computer Engineering) curriculum, exploring monolithic architecture patterns for fleet management systems.

## License

This project is provided for educational purposes.
