# 🌤️ Weather Agent with OpenAI & WeatherAPI

This project demonstrates how to build a smart **Weather Agent** using **OpenAI's GPT-4** and real-time data from **WeatherAPI** to answer weather-related questions.

🧑‍🏫 Designed for beginner Python learners, this project teaches:
1. Function calling with OpenAI
2. Real-time API usage (WeatherAPI)
3. Secure credential handling in Google Colab
4. Python function design and error handling

---

## 🧠 How It Works


1. The user types a natural question (e.g., "Is it raining in New York?")
2. GPT-4 analyzes the input and decides whether to call the `get_weather()` function
3. If needed, it calls the function with the given location
4. Python uses WeatherAPI to fetch real-time weather
5. GPT combines the data and returns a user-friendly answer

---


## 🧠 Educational Goals
This project helps students:

1. Understand LLM tool use / function-calling
2. Learn how to fetch and process external data from APIs
3. Write modular and reusable Python code
4. Combine AI reasoning + real-world applications

---

## 🔮 Future Improvements

1. Add a Gradio or Streamlit UI for non-technical users
2. Handle more edge cases and API failures gracefully
3. Upgrade to a paid WeatherAPI plan for forecasting support

---

## 📄 License
This project is open-source under the MIT License.
