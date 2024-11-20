# React Color Picker 🎨

This is a simple **React-based Color Picker** app that allows users to select a color using an HTML color input. The selected color is displayed dynamically in a styled box with its corresponding hex value.

## 🌐 Live Demo
![Color Picker Screenshot](my-react-app/src/assets/color-picker-screenshot.png)
[View the live project here!](https://laibatariq110.github.io/React-Color-Picker)

## 📂 Project Structure
The project consists of the following main files:

### Components:
- **`App.jsx`**: The root component rendering the `ColorPicker`.
- **`ColorPicker.jsx`**: The core component implementing the color-picking functionality using React's `useState`.

### Styles:
- **`index.css`**: Defines the styling for the app, including the layout and transitions.

### Entry Point:
- **`main.jsx`**: React's entry file where the `App` component is rendered into the DOM.

### Static File:
- **`index.html`**: The main HTML file, serving as the entry point for the app.

## 🚀 Features
- **Dynamic Color Selection**: Pick a color using an input element, and the selected color updates the background dynamically.
- **Hex Value Display**: Displays the hex value of the selected color inside the color display box.
- **Responsive Design**: A clean and simple design with a centered layout.

## 🛠️ Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/laibatariq110/React-Color-Picker.git
   ```
2. Navigate to the project directory:
   ```bash
   cd React-Color-Picker
   ```
4. Install the dependencies:
   ```bash
   npm install
   ```
6. Start the development server:
   ```bash
   npm run dev
   ```
8. Build for production:
   ```bash
   npm run build
   ```
10. Deploy to GitHub Pages:
    ```bash
   npm run deploy
   ```

## 🧩 How It Works
- **useState**: Manages the state of the selected color.
- **Dynamic Styling**: The div background is updated using the style prop with the current color.
- **Color Input**: An HTML <input type="color"> allows users to pick a color.
