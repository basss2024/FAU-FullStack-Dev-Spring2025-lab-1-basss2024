# Shamiah Bass
#Z23526337

Lab 1 for `lab-1-basss2024`, created by GitHub Classroom.
# Number of Hours Spent: 20 hrs
---

## **Project Overview**
This project demonstrates the implementation of a React application using Vite. The app is a timetable calendar that allows users to schedule events with their names, locations, and color-coded labels.

---

## **Setup Instructions**

### **Step 0: Create a New React Project Using Vite**
1. **Download and Install Node.js**: Ensure Node.js is installed on your system.
2. **Initialize the Project**:
   - Open the terminal in VS Code.
   - Navigate to your project directory using `cd`.
   - Run the following commands:
     ```bash
     npm create vite@latest
     ```
     - Name the project `timetabled`.
     - Choose `React` as the framework and `JavaScript` as the language variant.
   - Move into the project directory:
     ```bash
     cd timetabled
     npm install
     ```
3. **Run the Application**:
   - Start the development server with:
     ```bash
     npm run dev
     ```
   - Open the application in your browser using the link provided by Vite (e.g., `http://127.0.0.1:5173`).

---

## **Implemented Features**

### **Step 1: Update App.jsx and App.css**
- Added a title (`h1`) and subtitle (`h2`) to the app.
- Updated the CSS for a clean, responsive layout using the following rules:
  - Centered content in the browser window.
  - Applied modern font styles.

### **Step 2: Create the Calendar Component**
- Created a `Calendar` component in the `src/components` directory.
- Added a placeholder message: "Testing the calendar component."
- Imported and rendered the `Calendar` component in `App.jsx`.

### **Step 3: Create a Grid for the Calendar**
- Updated the `Calendar` component with a table layout:
  - Added headers for days of the week (Sunday–Saturday).
  - Included rows representing time blocks (8am–5pm).
- Styled the grid for proper spacing and alignment.

### **Step 4: Create the Event Component**
- Created an `Event` component to represent events on the calendar.
- Displayed a test event (`Test Event Name`) using `<h5>` within the component.
- Imported and integrated the `Event` component into the calendar.

### **Step 5: Pass Props to the Event Component**
- Enhanced the `Event` component:
  - Added support for `event` and `color` props to dynamically update event names and background colors.
  - Updated CSS to include styles for `green`, `blue`, and `pink` themes.

### **Step 6: Add Multiple Events to the Calendar**
- Replaced empty `<td>` cells in the calendar grid with multiple `Event` components.
- Added event names and colors for various time blocks and days of the week.

### **Stretch Feature: Add Event Locations**
- Included a `location` prop in the `Event` component.
- Displayed event locations using an `<h6>` element below the event name.

---

## **Stretch Goals**
- [ ] Add advanced features such as filtering, sorting, or searching events.
- [ ] Implement event editing and deletion functionality.

---

## **Usage**
1. Start the application using `npm run dev`.
2. View the timetable in your browser.
3. Interact with the events displayed on the calendar.

---

## **What I Learned**
- **React Basics**:
  - Building functional components.
  - Passing and using props to create reusable components.
- **CSS Styling**:
  - Aligning and styling grid layouts.
  - Using dynamic class names for conditional styling.
- **Project Setup**:
  - Setting up and running a React project with Vite.
  - Structuring a project with components and modular CSS.

---

## **Feature Checklist**

- [x] Add events to the calendar.
- [x] Include event locations.
- [x] Implement styling for the calendar.
- [ ] Add more advanced features (e.g., filtering events).

---

## **Video**

![lab1bass](https://github.com/user-attachments/assets/dd16aad0-f947-45b0-a109-fc861120a9b1)




## **Snippet of Vite**
![image](https://github.com/user-attachments/assets/546f9d1f-330f-4153-9b5b-10969d23a8ec)



## **Final Notes**
In this lab, I learned how to use React components and create a calendar. The hardest part for me was fixing the indents and parentheses. I kept getting errors and had to go back and fix the key characters. I also learned how to style using modular CSS, which was my favorite part!
However, I had some trouble with Vite at the start, as I kept encountering dependency issues. After troubleshooting, I realized that ensuring all dependencies were installed and verifying the Node.js version resolved the issue.
