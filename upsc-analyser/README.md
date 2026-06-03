# UPSC PYQ Analyser

This is a React application built with Vite that helps UPSC mains aspirants explore past year questions across General Studies, Anthropology, Essay topics, and subject microthemes.

## What this app does

- Visualizes UPSC mains PYQs from 2013 to 2025.
- Provides an overview of question count trends across GS sections.
- Lets users browse microthemes by GS section and inspect question details.
- Includes an Anthropology view for Paper I and Paper II questions.
- Offers essay topic browsing by year and thematic categories.
- Supports light/dark theme switching with a header toggle.

## Key features

- Section-wise breakdown for UPSC GS microthemes.
- 2025-specific question highlights and trend indicators.
- Expandable microtheme cards for detailed question lists.
- Persistent theme preference using `localStorage`.
- Responsive header tabs for fast navigation.

## Run locally

```bash
cd upsc-analyser
npm install
npm run dev
```

Then open the local Vite URL shown in the terminal.

## Build for production

```bash
cd upsc-analyser
npm run build
```

## Notes

The app is implemented entirely in `src/App.jsx` using inline styles and a small dataset in JavaScript objects. The theme toggle updates the visual palette and preserves the selected mode on refresh.
