######################################################################## 🌦️ Weather App ####################################################################################

A modern, responsive **Weather Web Application** built with **HTML, CSS, and JavaScript** that provides real-time weather information for any city using the **OpenWeatherMap API**.

This project demonstrates API integration, asynchronous JavaScript, DOM manipulation, and responsive UI design.

---

## 🚀 Features

* 🌍 Search weather information for any city worldwide
* 🌡️ Display real-time temperature
* 💧 Show humidity percentage
* 💨 Display wind speed
* 🎯 Dynamic weather icons based on current weather conditions
* ⚠️ Error handling for invalid city names
* 📱 Fully responsive design for desktop and mobile devices
* 🎨 Clean gradient-based user interface

---

## 🛠️ Tech Stack

| Technology         | Purpose                                |
| ------------------ | -------------------------------------- |
| HTML5              | Structure of the application           |
| CSS3               | Styling and responsive layout          |
| JavaScript (ES6)   | Application logic and DOM manipulation |
| Fetch API          | Asynchronous API requests              |
| OpenWeatherMap API | Real-time weather data                 |

---

## 📂 Project Structure

```text
Weather-App/
│
├── index.html
├── style.css
├── script.js
├── images/
│   ├── clear.png
│   ├── clouds.png
│   ├── rain.png
│   ├── mist.png
│   ├── snow.png
│   └── ...
└── README.md
```

---

## ⚙️ How It Works

1. User enters the name of a city.
2. JavaScript sends an asynchronous request to the OpenWeatherMap API.
3. The API returns the latest weather information.
4. The application dynamically updates:

   * City name
   * Temperature
   * Humidity
   * Wind speed
   * Weather icon
5. If the city is invalid, an appropriate error message is displayed.

---

## 📸 Application Preview

> Add screenshots of your application here.

```
screenshots/
├── home.png
├── weather-result.png
└── invalid-city.png
```

---

## 🔑 API Setup

### Step 1

Create a free account at **OpenWeatherMap**.

### Step 2

Generate your API key.

### Step 3

Open `script.js` and replace:

```javascript
const apiKey = "YOUR_API_KEY";
```

with your own API key.

---

## ▶️ Running the Project

Clone the repository:

```bash
git clone https://github.com/yourusername/weather-app.git
```

Navigate to the project directory:

```bash
cd weather-app
```

Open `index.html` directly in your browser, or use the **Live Server** extension in Visual Studio Code for a better development experience.

---

## 💡 Key JavaScript Concepts Used

* Async/Await
* Fetch API
* Promises
* DOM Manipulation
* Event Listeners
* Template Literals
* Conditional Rendering
* Error Handling

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Consuming REST APIs
* Handling asynchronous operations
* Working with JSON data
* Building responsive user interfaces
* Updating the DOM dynamically
* Managing user input and validation
* Writing clean and modular JavaScript code

---



## 🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository, open an issue, or submit a pull request.

---


### ⭐ If you found this project helpful, consider giving it a star on GitHub!
