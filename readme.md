# Employee Directory - AJACKUS Assignment

## Overview

This is a simple Employee Directory web application built for the AJACKUS assignment. It allows users to view, search, filter, sort, add, edit, and delete employee records. The UI is fully responsive and user-friendly.

### Project Structure

```
index.html         # Main application file (HTML, CSS, JS in one file)
readme.md          # Project documentation
screenshots/       # Screenshots of the application
```

## Setup & Run Instructions

1. **Clone or Download the Repository**
   - Download the project files to your local machine.

2. **Open the Application**
   - Simply open `index.html` in your web browser (Chrome, Firefox, Edge, etc.).
   - No server or build step is required; all logic is client-side.

3. **Usage**
   - Use the search bar and filters to find employees.
   - Add new employees using the "Add Employee" button.
   - Edit or delete employees using the respective buttons on each card.
   - Pagination controls are available at the bottom.

## Screenshots

> Place screenshots in the `screenshots/` folder and reference them here.

![Employee Directory Screenshot](screenshots/employee-directory.png)

## Reflection

### Challenges Faced

- **Single-file constraint:** All logic, styles, and markup are in one file, which can make maintenance harder.
- **No backend:** Data is stored in-memory, so changes are lost on refresh.
- **Form validation:** Ensuring robust validation for all fields and edge cases.

### Improvements for Future

- **Persistent storage:** Integrate with a backend or use browser storage (localStorage) to save employee data.
- **Modular codebase:** Split code into separate HTML, CSS, and JS files for better maintainability.
- **Accessibility:** Improve ARIA roles and keyboard navigation.
- **Testing:** Add automated tests for UI and logic.
- **Bulk actions:** Support for importing/exporting employee data.

---
© 2025 Employee Directory App - AJACKUS Assignment