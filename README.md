NAME: Goshamahal Poojitha,
COMPANY: CODTECH IT SOLUTIONS, 
ID: CT08DS10422,
DOMAIN : Web Development,
DURATION: NOV 25 TO DEC 25 2024,
MENTOR: Neela Santhosh Kumar

### **Project Overview: Weather Forecasting App**

This project is a simple weather forecasting application built using HTML, CSS, and JavaScript. It allows users to input a city name and retrieve real-time weather information, including temperature, humidity, and weather description.

---

### **Features**:
1. **City Input**: Users can enter a city name in a text input field.
2. **Weather Information Display**: After fetching the weather data, the app displays key weather information like:
   - Current temperature in Celsius
   - Weather description (e.g., sunny, cloudy, etc.)
   - Humidity level
3. **Error Handling**: If a city is not found or there is an issue with fetching the data, the app will display an error message.
4. **Responsive Design**: The app features a simple, centered layout that adapts to different screen sizes.

---

### **Technology Stack**:
1. **Frontend**:
   - **HTML**: For the structure of the web page (form, buttons, etc.).
   - **CSS**: For styling the app's layout, including elements like buttons and text fields.
   - **JavaScript**: For handling user interactions and fetching data from the OpenWeatherMap API.
   
2. **Weather Data API**:
   - **OpenWeatherMap API**: This API provides real-time weather data, including temperature, humidity, and weather conditions. You need to sign up for an API key to use the service.

---

### **Flow of the Application**:
1. **User Input**: The user enters a city name into the input field and clicks the "Get Weather" button.
2. **API Call**: The JavaScript function `getWeather()` is triggered. It fetches data from the OpenWeatherMap API using the entered city name and the provided API key.
3. **Displaying Data**: The app processes the JSON data returned by the API and dynamically displays weather information (city name, weather description, temperature, humidity).
4. **Error Handling**: If the city is not found or the API call fails, an alert is shown to the user.

---

### **Code Breakdown**:
- **HTML**:
   - The `<input>` tag allows the user to enter the city name.
   - The `<button>` triggers the `getWeather()` function when clicked.
   - The `<div class="weather-info">` is where the fetched weather information is displayed.

- **CSS**:
   - The styling centers the app on the screen and gives it a clean look with rounded corners, padding, and shadow effects.
   - Button hover effects improve user interaction experience.

- **JavaScript**:
   - **`getWeather()`**: This function is responsible for:
     - Collecting the city name from the input field.
     - Constructing the API URL with the city name and API key.
     - Fetching weather data using the Fetch API.
     - Displaying the weather data in the `#weatherInfo` div.
     - Handling errors such as no city input or a city not found.

---

### **How to Use**:
1. Enter a valid city name in the input field.
2. Click the "Get Weather" button to fetch the weather data.
3. View the weather details, such as temperature, humidity, and weather description, displayed below the button.

---

### **Important Notes**:
- You will need to replace `'YOUR_API_KEY'` in the JavaScript code with a valid API key from [OpenWeatherMap](https://openweathermap.org/api).
- This app does not handle advanced features like multiple city searches, detailed forecast data, or maps, but those could be added in future iterations.

---

### **Possible Enhancements**:
1. **Multiple Forecasts**: Display a forecast for multiple days (hourly, daily) for more comprehensive weather data.
2. **Geolocation**: Use the browser's geolocation API to automatically detect the user's location.
3. **Error Handling Improvements**: Display specific error messages in the UI instead of using `alert()`.
4. **Styling Enhancements**: Enhance the UI/UX with responsive design and animations for smoother interactions.
   
--- 

