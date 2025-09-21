# Smartweather Gradio

An interactive weather forecasting app built with **Gradio** and **Python** to fetch real-time weather data.  
Users can enter a city name and instantly view current weather conditions such as temperature, humidity, and description.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)
  

---

## Overview
Smartweather Gradio demonstrates how to integrate a weather API with a simple web interface.  
It uses **Weather Union** (or your chosen weather provider) to retrieve live data and **Gradio** to build an easy, interactive user experience directly from a Jupyter notebook.

---

## Features
- 🌦️ Fetches live weather data using Weather Union API  
- 🌐 Location-based search by city name  
- ⚡ Instant output with a clean Gradio interface  
- 📊 Displays temperature, humidity, pressure, and weather description  

---

## Installation
Follow these steps to run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/SreejayaT/Smartweather_Gradio.git
   cd Smartweather_Gradio
2. **Requirements**
   pip install gradio requests geopy matplotlib pandas numpy
3. **Set API Key**
   Obtain a Weather Union API key (or the API used in the notebook) and place it either:
   - In a .env file as WEATHER_API_KEY=your_key_here, or
   - Directly inside the notebook in the cell where the API call is made.
4. **Usage**
    - Launch Jupyter notebook: jupyter notebook Smartweather.ipynb
    - Run all cells in order.
    - After execution, Gradio will display a local URL in the output.
    - Open the URL in your browser, enter a city name, and view live weather details.
5. **Dependencies**
| Package                         | Purpose                             |
| ------------------------------- | ----------------------------------- |
| `gradio`                        | Interactive web UI                  |
| `requests`                      | Make HTTP calls to weather API      |
| `geopy`                         | Location lookup (if used)           |
| `matplotlib`, `pandas`, `numpy` | Optional for plots or data handling |

7. **Project Structure:**
   Smartweather_Gradio/
├─ Smartweather.ipynb   # Main Gradio weather app
├─ README.md            # Project documentation
└─ requirements.txt     # Dependencies (create if missing)

8. **Future Enhancements:**
   🌍 Add multi-day or hourly forecasts

   🖼️ Include weather icons or radar maps

   ☁️ Deploy to Hugging Face Spaces or a web server for public access

   ⚡ Improve error handling for API failures or invalid input

