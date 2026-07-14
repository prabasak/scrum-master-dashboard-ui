🚀 Key Features
===================
Modern Framework: Leverages the latest features of Angular 17.1.0, including improved performance and developer experience.
Reactive State Management: Utilizes RxJS, Observables, and Subjects to manage complex data streams and UI states efficiently.
Modular Architecture: Organized into scalable services and components for high maintainability.
Production Ready: Includes specialized configurations for Nginx and Docker to facilitate seamless deployment.
Enterprise Security: Integrated with GitGuardian and pre-commit hooks to ensure no sensitive information is ever leaked.

🛠 Technical Stack
===================
Framework: Angular 17.1.0
Language: TypeScript (81.8%), HTML (12.3%), CSS (5.7%)
Testing: E2E testing suite
Quality Gate: SonarQube integration (sonar-project.properties, SonarQG.sh)
CI/CD: Refactored GitHub Actions for automated UI deployment

📥 Getting Started
===================
Prerequisites
Node.js (latest LTS recommended)
Angular CLI
Python (required for security hooks)
Security Requirements (Mandatory)
This repository uses GitGuardian via pre-commit hooks to scan your code before every commit. You must run the following commands after cloning the repository to ensure your environment is compliant:
pip install pre-commit
pre-commit install

Installation
===================
Clone the repository.
Navigate to the project directory:
Install dependencies:
Development Server
Run npm start for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.

🏗 Project Structure
===================
The project follows a standard Angular 17 workspace structure with additional enterprise configurations:
/src: Main application source code including components, services, and assets.
/nginx: Configuration files for Nginx web server deployment.
/e2e: End-to-end testing scripts.
Dockerfile: For containerizing the UI application.
angular.json: Workspace-wide configuration for Angular CLI.

🛡 Quality & Security
===================
We maintain high code quality standards through:
ESLint & Prettier: For consistent code formatting and linting.
SonarQube: Integrated scripts (SonarQG.sh) to maintain the Quality Gate.
GitGuardian: Automated secret scanning.
