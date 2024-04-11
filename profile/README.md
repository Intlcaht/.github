# Integrated Task Lifecycle Coordinator (ITLC)

Welcome to the Integrated Task Lifecycle Coordinator (ITLC) project repository! ITLC is a comprehensive platform designed to facilitate the entire lifecycle of tasks, from project creation to completion, while also managing financial transactions between clients and service providers. This README provides an overview of the project, its features, tech stack, installation instructions, usage guidelines, contribution guidelines, and licensing information.

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Tech Stack](#tech-stack)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction
The Integrated Task Lifecycle Coordinator (ITLC) platform streamlines the coordination process between clients and service providers by offering a suite of tools and features to manage projects, track orders, handle financial transactions, and more. It serves as a centralized hub for users to collaborate efficiently, ensuring transparency, accountability, and ease of use throughout the task lifecycle.

## Features
### 1. Project Management
- **Project Creation:** Clients can create projects from predefined templates or customize projects from scratch.
- **Real-time Notifications:** Service providers receive instant notifications when new projects are posted or bids are accepted.
- **Order Processing:** Service providers can accept bids and process orders through the platform.

### 2. Escrow Service Integration
- **Financial Management:** Users can deposit, withdraw, and transfer funds using the Escrow service within the platform.
- **Automated Payment Capture:** Payments made within the platform are automatically captured and reflected in the user's Escrow account.

### 3. User Authentication and Profile Management
- **Multi-Provider Authentication:** Users can securely log in to the platform using Google, Facebook, SMS, or passkey authentication methods.
- **Profile Customization:** Service providers can build their business profiles, including service tags, operation locations, hours, and blogs.

### 4. Order Tracking and Check-ins
- **Order Status Updates:** Clients can track order progress through a real-time check-in system within the platform.

### 5. Rating and Feedback System
- **Service Rating:** Clients can rate the services offered by service providers upon order completion.
- **Feedback Collection:** Collect feedback from clients to improve service quality.

### 6. Comprehensive User Interface
- **Intuitive UI/UX Design:** The platform features a user-friendly interface with smooth navigation and interactive elements.
- **Responsive Design:** Supports various device screen sizes and orientations for optimal user experience.

## Tech Stack
- **Frontend:** Flutter for building cross-platform mobile apps.
- **Backend:** Laravel for developing RESTful APIs and managing database operations.
- **Database:** MySQL for storing project, user, and financial transaction data.
- **Authentication:** Firebase Authentication for user authentication and secure data storage.
- **State Management:** Provider for managing app state and data flow.

## Installation
1. Clone this repository to your local machine.
2. Set up and configure the backend Laravel application by following the instructions in the `backend/README.md` file.
3. Set up and configure the frontend Flutter application by following the instructions in the `frontend/README.md` file.
4. Run both the backend and frontend applications locally to test the platform's features and functionalities.

## Usage
- Upon launching the app, users will be prompted to log in using their ITLC credentials.
- Navigate through the platform to access different features such as project creation, order processing, Escrow transactions, and profile management.
- Interact with the platform to create, manage, and track projects, communicate with service providers, and perform financial transactions seamlessly.

## Contributing
Contributions to the ITLC project are welcome! Please feel free to submit bug reports, feature requests, or pull requests to help improve the platform.

## License
This project is licensed under the [MIT License](LICENSE).
