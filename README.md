# react-forms-and-event-binding-with-life-cycle
react forms and event binding with life cycle class based and functional based 

```markdown
# React Application for Routing, Forms Binding, Event Binding, and Lifecycle Management

This React application demonstrates key concepts such as React Router for navigation, form and event binding, lifecycle methods in class components, and making REST API calls using Axios.

## Features

- **Routing with React Router DOM**: Navigate between different pages seamlessly.
- **Form Binding and Event Handling**: Bind form inputs dynamically with React's `useState` hook.
- **Lifecycle Methods in Class Components**: Manage component lifecycle with `componentDidMount`, `componentWillUnmount`, and more.
- **REST API Integration**: Fetch user data from a REST API using Axios.
- **Styling with CSS**: Custom styles with hover effects and Bootstrap for responsiveness.

## Commands Used

1. Install dependencies:
   ```bash
   npm install
   ```
2. Install required packages:
   ```bash
   npm install bootstrap axios react-router-dom
   ```

## Code Explanation

### App.js

- **Purpose**: Entry point of the application. Configures routing using `react-router-dom`.
- **Key Highlights**:
  - `<Router>` and `<Routes>` handle navigation.
  - Default route redirects to `/form-binding`.

### Parent Component

- **Purpose**: Demonstrates form binding and event handling.
- **Key Highlights**:
  - `useState` manages form data.
  - `formBind()` dynamically updates state based on form input changes.
  - `submitData()` handles form submission.

### Navbar Component

- **Purpose**: Navigation bar for page links.
- **Key Highlights**:
  - `Link` from `react-router-dom` is used for navigation.
  - Custom CSS for hover effects and link styling.

### LifeCycle Component

- **Purpose**: Demonstrates class component lifecycle methods.
- **Key Highlights**:
  - `componentDidMount` fetches data from a REST API.
  - Lifecycle methods (`constructor`, `render`, `componentWillUnmount`) are used appropriately.

### CSS Styling

- **Highlights**:
  - Custom gradients for buttons (`btn-primary`, `btn-secondary`, etc.).
  - Hover effects on thumbnails (`#shadow`) and navigation links.

## REST API Integration

- **API URL**:
  ```
  https://gist.githubusercontent.com/123-anubhav/8204c04e42866495796db9b155e1012d/raw/ebc855cc55890b1cf5cea0f25444bddbfb60388e/UsersData.json
  ```
- **Implementation**:
  - Axios is used to fetch data.
  - API data is mapped and displayed with proper formatting.

## Folder Structure

```
src/
├── components/
│   ├── Navbar.js
│   ├── Parent.js
│   └── LifeCycle.js
├── App.js
├── App.css
├── style.css
└── index.js
```

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project_directory>
   ```
3. Start the application:
   ```bash
   npm start
   ```

## Preview

### Form Binding
- Dynamically updates form fields and displays data in real time.

### LifeCycle Component
- Fetches user data and displays it in a responsive card layout.

### Navbar
- Provides links to different application pages with hover effects.

---

**Author**: Anubhav Srivastava  
**Technologies Used**: React, Bootstrap, Axios, JavaScript  
```
