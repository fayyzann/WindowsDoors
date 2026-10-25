# WindowsDoors — Business Website Frontend

A multi-page, responsive React frontend for a windows and doors business. The repository includes pages for services, portfolio, frequently asked questions, and contact information.

## What this project shows

- Client-side routing with React Router
- Page-oriented React component structure
- Responsive styling with Tailwind CSS and CSS
- Material UI components and icons
- Dedicated pages for the company's services and project portfolio

## Tech stack

- React 18
- React Router 6
- Tailwind CSS 3
- Material UI 5
- Create React App (react-scripts)

## Project layout

```text
window_door/
├── public/
└── src/
    ├── Components/    # Navigation and footer
    ├── Pages/         # Home, About, Services, Portfolio, FAQ, Contact
    ├── Assets/        # Local frontend assets
    ├── App.js         # Route definitions
    └── index.js       # Application entry point
```

## Run locally

Requirements: a compatible Node.js and npm installation.

```bash
git clone https://github.com/fayyzann/WindowsDoors.git
cd WindowsDoors/window_door
npm ci
npm start
```

Then open http://localhost:3000.

## Build and test

```bash
npm run build
npm test
```

## Notes

This is an older frontend project using Create React App. It is presented as a React UI example rather than a production backend or AI project.

For more recent backend and AI work, see [Solace AI](https://github.com/fayyzann/solace-ai) and [TruckTrack](https://github.com/fayyzann/truck-track).
