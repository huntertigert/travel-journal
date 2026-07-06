# Travel Journal 🌍

A React project that dynamically renders a travel journal from a data set, built as part of the Scrimba Frontend Developer Career Path.

## About

This app takes a list of travel destinations (stored in `data.js`) and dynamically generates journal entries for each one — including a location image, place name, and travel notes — using reusable React components.

## Tech Stack

- **React** – component-based UI
- **Vite** – fast dev server and build tool
- **JavaScript (ES6+)**
- **CSS**

## Project Structure

```
travel-journal/
├── components/     # React components used to render each journal entry
├── images/         # Destination images used in the journal
├── App.jsx         # Root component
├── data.js         # Travel destination data
├── index.html      # HTML entry point
├── index.jsx       # React app entry point
├── index.css       # Global styles
└── vite.config.js  # Vite configuration
```

## Getting Started

Clone the repo and install dependencies:

```bash
git clone https://github.com/huntertigert/travel-journal.git
cd travel-journal
npm install
```

Run the development server:

```bash
npm run dev
```

Then open the local URL Vite prints in your terminal (usually `http://localhost:5173`) in your browser.

## Features

- Dynamically renders journal entries from a central data source
- Reusable, component-based structure
- Responsive layout for viewing entries on different screen sizes

## Acknowledgements

This project was built as part of [Scrimba's](https://scrimba.com/) Frontend Developer Career Path.

## License

This project is for educational purposes as part of the Scrimba curriculum.
