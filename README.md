# Sticky Notes React App

A simple React application that allows users to create and manage sticky notes.This app utilizes React hooks such as `useState`, `useEffect`, `createContext` and `useContext` to handle the state and display of sticky notes.

## Features

- Create new sticky notes with user input.
- Persistent storage of notes using `localStorage`.

## Technologies Used

- React
- CSS
- JS

## Installation

1. Clone the repository:

```bash
https://github.com/Oslinjohn20/React-Sticky-Notes.git


cd React-Sticky-Notes
npm install
npm start

```

open your browser and visit `http://localhost:3000` to view app.

## Usage

1. Open the app in your browser.

2. Clickc on the `Add Note` button to create a new sticky note.

3. Double-click on a note to edit its content.

4. Each sticky note can be customized by color for your importance prefence.

## Context API

The application uses React's Context API to manage the state of the sticky notes. The `StickyNotesContext` provides a centralized state that is consumed by various components.

## LocalStorage

Sticky ntoes are stored in the browsers `localStorage` to provide persistence across page reloads.

## Screenshot

![App Screenshot](./public/Screenshot%202024-01-31%20121520.png)
