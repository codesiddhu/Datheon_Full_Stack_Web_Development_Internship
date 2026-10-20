# my-Portfolio# 🌐 Personal Portfolio Website

Welcome to my personal portfolio website! This project showcases my skills, projects, and contact information as a developer. It is designed with a modern, responsive layout and includes interactive features to provide a smooth user experience.

## 🚀 Features

- **Responsive Design:** Works on desktops, tablets, and mobile devices.
- **Dark/Light Mode:** Switch between dark and light themes.
- **Smooth Navigation:** Easily navigate between portfolio sections.
- **Mobile Navigation:** Responsive hamburger menu for smaller screens.
- **Projects Section:** Displays projects with descriptions and technology tags.
- **Project Details Modal:** View additional information about projects.
- **Contact Section:** Contact me directly through email.
- **Modern UI:** Clean layout, animations, and interactive buttons.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Git and GitHub

## 📂 Project Structure

```text
my-portfolio/
├── index.html
├── style.css
├── script.js
└── README.md
```

## 💻 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

Replace `YOUR-USERNAME` and `YOUR-REPOSITORY` with your GitHub username and repository name.

### 2. Open the Project

Navigate to the project directory:

```bash
cd YOUR-REPOSITORY
```

### 3. Run the Website

Open `index.html` in your browser, or use the **Live Server** extension in Visual Studio Code.

## ✏️ Customization

You can personalize this portfolio by:

- Updating your name and professional introduction.
- Adding your profile picture.
- Listing your technical skills.
- Replacing sample projects with your actual projects.
- Updating your GitHub and LinkedIn profile links.
- Adding your resume and other relevant links.
- Updating your contact email address.

## 📧 Contact

**Sreedhar Royal**

- Email: [sreedharroyals632@gmail.com](mailto:sreedharroyals632@gmail.com)
- GitHub: (https://github.com/codesiddhu/my-Portfolio)
- 

## 🌍 Deployment

This portfolio can be deployed using:

- [GitHub Pages]:  https://codesiddhu.github.io/my-Portfolio/

## 📄 License

This project is intended for personal portfolio and learning purposes. You are welcome to use it as inspiration for your own portfolio.

---

⭐ Thank you for visiting my portfolio!
🚀 TaskFlow – Productivity Application
TaskFlow is a simple, responsive productivity application built using HTML, CSS, and JavaScript. It helps users organize daily activities, manage tasks, set deadlines, and track their progress.

The application supports complete CRUD operations and uses browser localStorage to save tasks, so they remain available after refreshing the page.

✨ Features
Create Tasks: Add new tasks with a title, category, and due date.
Read Tasks: View all saved tasks in an organized list.
Update Tasks: Edit existing task details.
Delete Tasks: Remove individual tasks or clear completed tasks.
Task Categories: Organize tasks into Work, Personal, Study, and Other.
Due Dates: Set deadlines and identify overdue tasks.
Mark as Complete: Mark tasks as completed using checkboxes.
Status Filters: Filter tasks by All, Active, or Completed.
Search Tasks: Quickly find tasks by title.
Drag-and-Drop: Reorder tasks using drag-and-drop.
Local Storage: Persist tasks in the browser across page reloads.
Responsive Design: Support desktop, tablet, and mobile screens.
Animations: Use CSS transitions and animations for a smoother experience.
🛠️ Technologies Used
HTML5
CSS3
JavaScript (ES6+)
DOM Manipulation
Browser localStorage API
HTML Drag and Drop API
📂 Project Structure
Task Manager & Productivity Tracker ├── index.html ├── style.css ├── script.js └── README.md

Step 2: Navigate to the Project Folder
cd Task Manager & Productivity Tracker
Step 3: Open the Application
Open index.html directly in your web browser.

Alternatively, open the project in Visual Studio Code and use the Live Server extension to run the application.

No additional dependencies or backend server are required.

📖 How to Use
Open the TaskFlow application in your browser.
Enter a task title in the input field.
Select a category: Work, Personal, Study, or Other.
Optionally, choose a due date.
Click Add Task to create the task.
Use the checkbox to mark a task as completed.
Click the edit button to update a task.
Click the delete button to remove a task.
Use the All, Active, and Completed filters to organize your task list.
Use the search field to find tasks by title.
Drag tasks to change their order.
Refresh the browser to verify that your tasks remain saved.
💾 Data Persistence
TaskFlow uses the browser's localStorage API to persist task data.

The application uses two main helper functions:

saveToLocalStorage() – Saves the current task array to browser storage.
loadFromLocalStorage() – Retrieves saved tasks when the application starts.
Tasks are stored as JSON under the key:

taskflow_tasks
Note: Data is stored locally in the browser and is not synchronized across devices or browsers. Clearing browser storage may permanently remove saved tasks.

🧪 Testing Checklist
 Create a new task.
 Display saved tasks.
 Edit an existing task.
 Delete a task.
 Select different task categories.
 Set and verify due dates.
 Mark tasks as completed.
 Filter tasks by All, Active, and Completed.
 Search tasks by title.
 Reorder tasks using drag-and-drop.
 Clear completed tasks.
 Refresh the page and verify data persistence.
 Test the interface on mobile and desktop screens.
🎯 Project Objective
The objective of this project is to demonstrate practical knowledge of JavaScript, DOM manipulation, event handling, array-based state management, localStorage, CSS animations, and responsive web design.

The application provides a lightweight solution for organizing personal and professional tasks without requiring an account or backend database.

🔮 Future Improvements
Add task priority levels.
Add task descriptions and reminders.
Implement dark and light themes.
Add calendar-based task management.
Support user accounts and cloud synchronization.
Add task completion statistics.
Integrate a backend database.
Sreedhar Royal

Email: sreedharroyals632@gmail.com
📄 License
This project is intended for educational and personal use. You may modify it for your own learning and development.



# 🌦️ Real-Time Weather Forecast & Climate Telemetry App

A responsive weather application built using **HTML, CSS, and JavaScript** that provides real-time weather information and a 5-day forecast for cities around the world using the OpenWeatherMap API.

## 🚀 Features

- 🌍 **Global City Search** — Search for weather information by city name.
- 🌡️ **Current Temperature** — View the current temperature and weather conditions.
- ☁️ **Dynamic Weather Icons** — Display icons based on current weather conditions.
- 💧 **Humidity** — Check the current humidity percentage.
- 💨 **Wind Speed** — View wind speed information.
- 🌡️ **Atmospheric Pressure** — Display atmospheric pressure.
- ☁️ **Cloud Cover** — Check cloud coverage.
- 📅 **5-Day Weather Forecast** — View upcoming weather forecasts.
- ⏳ **Loading Indicator** — Show a loading state while fetching data.
- ⚠️ **Error Handling** — Display helpful messages for invalid city names and network errors.
- 📱 **Responsive Design** — Adapt the interface to different screen sizes.

## 🛠️ Technologies Used

- **HTML5** — Application structure.
- **CSS3** — Styling, Flexbox, Grid, and responsive layouts.
- **JavaScript (ES6+)** — Application logic and asynchronous operations.
- **Fetch API** — Retrieve weather data from the API.
- **Async/Await** — Handle asynchronous requests.
- **OpenWeatherMap API** — Provide current weather and forecast data.

## 📂 Project Structure

```text
weather app/
├── index.html
├── style.css
├── script.js
└── README.md
```

## ⚙️ Setup and Installation

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

### 2. Open the Project

Navigate to the project directory:

```bash
cd weather app
```

Open the folder in Visual Studio Code.

### 3. Get an OpenWeatherMap API Key

1. Create an account at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).
2. Verify your email if requested.
3. Visit the [API Keys page](https://home.openweathermap.org/api_keys).
4. Copy your API key.

### 4. Configure the API Key

Open `script.js` and replace the placeholder API key with your own:

```javascript
const API_KEY = "5dae2f3edb05c8aafcee265a42b05496";
```

Keep the quotation marks around your key. Do not upload your real API key to a public repository.

### 5. Run the Application

1. Open the project in Visual Studio Code.
2. Install the **Live Server** extension if you do not already have it.
3. Right-click `index.html`.
4. Select **Open with Live Server**.
5. Search for a city, such as Hyderabad, London, or New York.

## 🌐 API Endpoints Used

The application uses the following OpenWeatherMap endpoints:

| Purpose | Endpoint |
|---|---|
| Geocoding | `https://api.openweathermap.org/geo/1.0/direct` |
| Current Weather | `https://api.openweathermap.org/data/2.5/weather` |
| 5-Day Forecast | `https://api.openweathermap.org/data/2.5/forecast` |

Refer to the [OpenWeatherMap API documentation](https://openweathermap.org/api) for details.

## 🧠 What I Learned

Through this project, I practiced:

- Integrating a third-party REST API into a web application.
- Using JavaScript's Fetch API and async/await.
- Handling API responses and errors.
- Working with JSON data.
- Updating webpage content dynamically using the DOM.
- Implementing responsive layouts with CSS Flexbox and Grid.
- Managing loading indicators and user-friendly error messages.

## 🔒 Security Note

For learning and local development, a client-side API key can be used for testing. However, JavaScript running in the browser is publicly accessible, so a key included in `script.js` can be discovered by users.

For production deployment, move API requests to a backend or serverless function and keep the API key in an environment variable. Configure any available API restrictions and usage limits.

## 🔮 Future Improvements

- Add hourly weather forecasts.
- Display interactive weather charts.
- Support Celsius and Fahrenheit conversion.
- Save favorite cities.
- Add geolocation-based weather.
- Display sunrise and sunset times.
- Add dark and light themes.

## 👨‍💻 Author

**Developer:** Your Name

## 📄 License

This project is intended for educational and portfolio purposes. Add a license file if you plan to distribute the project under a specific open-source license.
=======
# Weather-App
>>>>>>> 14f56497be2e534f682f718ea35d5afea8569270










⭐ If you find this project useful, consider giving the repository a star!
