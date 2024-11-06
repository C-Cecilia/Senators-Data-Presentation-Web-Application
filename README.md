# 🇺🇸 Senators Data Presentation Webpage

>A dynamic, interactive webpage built as part of my coursework for **COMP30680 - Web Application Development**. This project demonstrates my ability to create a webpage using HTML, CSS, and JavaScript to display and manipulate JSON data on US Senators without relying on external libraries.



## 📋 Project Overview

The goal of this project was to develop a responsive, interactive webpage that loads and presents data on US Senators from `govtrack.us` using vanilla JavaScript. This application provides users with the ability to filter and explore detailed information on senators, enhancing data accessibility and user engagement.


## 🌟 Features

### 🗳️ Party Affiliation Count
- Displays the total number of senators per party (e.g., Democrats, Republicans) based on JSON data.

### 🏛️ Leadership Roles
- Lists senators holding leadership roles, grouped by party, with the format:

### 📜 Senators List with Filtering Options
- Shows a full list of senators with details such as:
- Party Affiliation
- State
- Gender
- Rank (junior/senior)
- **Filters**:
- **Party**: Filter by specific party or view all.
- **State**: Filter by senators' state.
- **Rank**: Filter by senator rank.
- Filters are combinable, allowing users to refine results (e.g., filter by both party and state).

### 🔍 Detailed View of Selected Senators
- When a senator is selected, additional information is displayed, including:
- **Office Address**
- **Date of Birth**
- **Start Date in Office**
- **Social Media**: Twitter and YouTube IDs if available
- **Website**: Clickable link that opens in a new tab


## 🛠️ Technical Requirements

This project adheres to the following technical specifications:

- **Languages**: HTML, CSS, and JavaScript only (no external libraries).
- **No Page Reloads**: All interactions and data manipulations are performed dynamically on a single page.
- **Dynamic Data Loading**: All information is sourced directly from the JSON file, with no hardcoding.


## 🚀 Getting Started

1. **Clone this repository:**
2. **Open `senators.html`** in your development environment (such as VSCode).

3. **Run with Live Server**:
 - Use the **Live Server** extension in VSCode or similar tools to view the webpage.
 - In VSCode, right-click `senators.html` and select "Open with Live Server" to preview changes in real time.

4. **Interact with the webpage**:
 - Use the filters to explore data, and click on a senator’s name to view additional details.


## 🎓 Learning Outcomes

This project helped me deepen my understanding of:

- **JavaScript Data Handling**: Loading and parsing JSON data directly in JavaScript.
- **DOM Manipulation**: Dynamically displaying data and implementing user interactivity without page reloads.
- **HTML/CSS for Structure and Styling**: Structuring data presentations and building a user-friendly interface.
- **Filtering Logic**: Creating multi-criteria filtering options to allow users flexible ways to interact with data.


## 📜 Originality Disclaimer

*This project is entirely my own work, created for the COMP30680 Web Application Development course. All code was written by me without the use of any external code snippets or tutorials. Any resemblance to other work is coincidental, as this project was developed independently. Please respect academic integrity if referencing this project.*


## 📄 License

This project is created for educational purposes and is licensed under the MIT License.
