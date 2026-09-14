# SeshatAIFE

Frontend submodule for the SeshatAI fullstack application. Handles the user interface, UI translation, and performs API calls towards the backend service ([SeshatAIBE](https://github.com/Adrian55Stack/SeshatAIBE)).

## Tech Stack

- **Framework:** Angular 19
- **Testing:** Jest
- **Linting:** ESLint
- **Code Quality:** SonarQube
- **Translation:** i18n / translation API

## Getting Started

### Prerequisites
- Node.js >= 18
- npm >= 9
- A valid translation API key

### Installation
```bash
npm install
```

### Development Server
```bash
ng serve
```
Navigate to `http://localhost:4200`.

### Build
```bash
ng build
```

### Testing
```bash
npm test
```

### Linting
```bash
npm run lint
```

## Code Quality

This project uses SonarQube for static code analysis. Configuration is defined in `sonar-project.properties`.

To run an analysis locally:
```bash
sonar-scanner
```

## Related

- [SeshatAIBE](https://github.com/Adrian55Stack/SeshatAIBE) — Backend submodule
- [SeshatAI](https://github.com/Adrian55Stack/SeshatAI) — Monorepo