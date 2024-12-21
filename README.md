## PlacePicker

A React application to create a personal collection of places you'd like to visit or have already visited. The app utilizes geolocation to sort places by proximity, dynamically updating your collection and providing an engaging user experience.

---

## Project Screen Shot(s)

<img width="1382" alt="PlacesPicker" src="https://github.com/user-attachments/assets/28d55553-8b4d-461f-bc18-3d10c1ecfad8" />

---

## Features

- **Geolocation Sorting**: Automatically sorts available places based on proximity to the user's current location.
- **Place Selection**: Add places to your personal collection with a single click.
- **Dynamic Updates**: Updates your collection of places in real time as you interact with the app.
- **Local Storage Integration**: Persist selected places even after refreshing the page.
- **Modal for Confirmation**: A sleek confirmation dialog when removing a place from your collection.
- **Responsive UI**: Works seamlessly across various device sizes and screen resolutions.

---

## Installation and Setup Instructions

1. Clone down this repository.
2. Navigate to the project folder in your terminal.
3. Install dependencies:

   ```bash
   npm install
4. To run the application, use:
   ```bash
   npm start
5. open your browser and go to:
   ```bash
   http://localhost:3000

---

---

## Reflection

### Context
This project was built to practice handling side effects and state management in React. It focuses on effectively using the `useEffect` hook and integrating React side effects like local storage and geolocation.

### What I Set Out to Build
I aimed to build a functional app that dynamically updates based on geolocation and user interaction while deepening my understanding of:
  - **State Management**: Using `useState` to track modal state, selected places, and sorted places.
  - **Side Effects**: Leveraging `useEffect` for geolocation and persistent local storage.
  - **Reusable Components**: Breaking down the UI into reusable, functional components like `Places`, `Modal`, and `DeleteConfirmation`.
  - **User Interaction**: Providing a seamless and intuitive experience for selecting and managing places.

### Challenges
One challenge was effectively using `useEffect` to fetch and sort places by geolocation. Another challenge was managing the synchronization between local storage and React state to ensure data persistence.

---

## Libraries and Frameworks Used

- **React**: For building the user interface and managing the application state.
- **CSS**: Custom styles for responsive and clean UI.
- **Browser Geolocation API**: To fetch the user’s location and sort places dynamically.

