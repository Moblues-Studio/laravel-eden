# 🌿 Laravel Eden

Welcome to Laravel Eden, an open-source boilerplate designed to kickstart your Laravel projects using the latest Laravel Framework (version 11) integrated with the "Sneat Vuetify" system design for the front end, written in Vue. This project aims to provide a seamless local development environment using Docker, adhering to the best practices of software development, guidelines, and Git conventions. Laravel Eden leverages Laravel Pint for code design, ensuring consistent code formatting and cleanliness across the project.

## 🚀 Getting Started

These instructions will get your copy of the project up and running on your local machine for development and testing purposes.

### 📋 Prerequisites

Before you begin, ensure you have the following tools installed on your system:

- PHP
- Composer
- Node.js
- pnpm (or npm, yarn)
- Docker

### 🔧 Installation

Follow these steps to set up your local development environment:

1. **Install Composer Packages**:
   ```bash
   composer install
   ```

2. **Install Node Packages**:
   ```bash
   pnpm install
   ```

3. **Create Environment File**:
   ```bash
   cp .env.example .env
   ```

4. **Create an App Key**:
   ```bash
   php artisan key:generate
   ```

5. **Run Docker Containers**:
   ```bash
   ./vendor/bin/sail up
   ```

6. **Run Database Migrations**:
   ```bash
   ./vendor/bin/sail artisan migrate
   ```

7. **Run Development Server**:
   ```bash
   pnpm dev
   ```

8. **All Done**:
    Visit http://localhost in your web browser to see the application in action.

## 📐 Best Practices & Guidelines

To ensure quality and maintainability, we follow strict coding standards and best practices, including:

- **Git Conventions**: We adhere to a clear Git commit message convention to make our version history easy to navigate.
- **Code Design**: Laravel Pint is used for automatic code formatting and cleanup, ensuring a consistent code style across the project. It's recommended to configure your IDE to apply these formatting rules automatically.

## 🤝 Contributing

We welcome contributions to Laravel Eden! Please read our CONTRIBUTING.md file for details on our code of conduct and the process for submitting pull requests to us.

## 📄 License 

This project is licensed under the MIT License

## 👏 Acknowledgments

- Laravel Community for the comprehensive framework.
- The creators of Sneat Vuetify for the beautiful Vue components.
- All contributors and supporters of Laravel Eden.

----
Thank you for choosing Laravel Eden for your next project. Happy coding!
