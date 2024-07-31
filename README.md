# Personal Voice Assistant  Rai

## Overview

This project is a personal voice assistant named **Rai**, designed to perform various tasks through voice commands. Rai can search Wikipedia, open websites, capture images, provide weather updates, tell the time, and more. The assistant uses speech recognition and texttospeech technologies to interact with users.

## Features

 TexttoSpeech (TTS): Provides spoken responses using thepyttsx3` library.
 Speech Recognition: Listens to and processes user commands using thespeech_recognition` library.
 Weather Updates: Retrieves current weather information using the OpenWeatherMap API.
 Wikipedia Search: Searches for information on Wikipedia and reads out the results.
 Website Interaction: Opens websites such as YouTube, Google, Gmail, and Stack Overflow.
 Computational Queries: Answers computational or geographical questions using the WolframAlpha API.
 Time Announcement: Provides the current system time.
 News Updates: Opens news headlines from Times of India.

## Requirements

 Python 3.x
 Libraries:
  speech_recognition
  pyttsx3`
  wikipedia`
  webbrowser`
  requests`
  wolframalpha`
  opencvpython` 
 API Keys:
   OpenWeatherMap API key
   WolframAlpha API key

# Outcome

Rai, the personal assistant, greets users with messages like "Good Morning," "Good Afternoon," or "Good Evening" based on the time of day. It listens for commands and performs actions such as opening websites (YouTube, Google, Gmail), capturing images, and checking the weather using real API requests. Rai can also provide the current time, answer questions related to computational topics, and handle errors related to unrecognized speech or connection issues.
