**Real-Time Weather Assistant using n8n + Vapi + Google Gemini + OpenWeather**

This project is an automated real-time weather update assistant built with n8n, integrated with Vapi for voice interactions, Google Gemini AI for intelligent response generation, and OpenWeather API to fetch live weather data.

🧠 Overview

The system enables users to interact via voice commands, which are processed using Vapi, routed through n8n workflows, and enriched with live weather data from OpenWeather. Responses are then generated using Google Gemini's AI capabilities and returned via voice—providing a seamless, intelligent, real-time weather assistant.

🔧 Technologies Used

n8n – Workflow automation platform for connecting APIs and services

Vapi – Voice assistant platform for real-time audio interactions

Google Gemini – Multimodal AI model for generating human-like responses

OpenWeather API – Real-time weather data source


⚙ Features

🎙 Voice interaction with users via Vapi

☁ Real-time weather updates for any location

🤖 AI-generated weather summaries and advice using Google Gemini

🔁 Automated, scalable workflows using n8n

🌍 Location-aware and dynamic weather data processing


🧩 How It Works

1. User speaks a weather-related query (e.g., “What’s the weather like in Mumbai?”)


2. Vapi captures the voice input and sends it to n8n


3. n8n triggers a call to OpenWeather API for real-time data


4. Weather data is passed to Google Gemini for intelligent interpretation


5. Gemini generates a friendly response (e.g., "It's 28°C in Mumbai with light showers. Carry an umbrella!")
