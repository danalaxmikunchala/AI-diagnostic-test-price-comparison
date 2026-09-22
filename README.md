# AI Diagnostic Test Price Comparison

## About the Project

Diagnostic Test Price Comparison is a web application developed to simplify the process of exploring diagnostic tests and laboratory prices.

The application brings test names, laboratory details, locations, and sample prices together in a single interface. Users can select a test and location to view available laboratory options and compare the prices provided in the dataset.

The project also provides an interactive assistant that can respond to queries related to diagnostic tests, laboratories, and locations. Voice input is supported through the browser.

This project was developed as a collaborative academic project.

---

## Project Goal

The goal of the application is to provide an easy-to-use platform for exploring diagnostic laboratory information.

Instead of manually checking different laboratory sources, users can use the application to:

- Search for a required diagnostic test
- Select a city or area
- View available laboratories
- Compare the listed test prices
- Identify a lower-priced option from the available data
- Open navigation directions for a selected laboratory
- Interact with the assistant using text or voice

---

## What the Application Does

The application combines a Flask backend with a web-based user interface.

When a user selects a diagnostic test and location, the Flask application processes the request and retrieves the matching records from the laboratory dataset.

The results are then displayed through the web interface, allowing users to examine the available laboratory options and their listed prices.

---

## Core Functionalities

### Diagnostic Test Search

Users can search for diagnostic tests available in the dataset.

### Laboratory Comparison

The application displays multiple laboratory options and their corresponding prices so that users can compare them.

### Location Filtering

City and area information can be used to narrow the available results.

### Price Analysis

The application can identify the lower-priced laboratory option among the matching records available in the dataset.

### Laboratory Navigation

A selected laboratory can be opened through a Google Maps direction link for navigation.

### Interactive Assistant

The assistant accepts natural-language questions about tests, laboratories, prices, and areas.

### Voice Interaction

Users can provide queries through microphone input using browser-based speech recognition.

---

## Technologies and Tools

The project uses the following technologies:

| Technology | Purpose |
|------------|---------|
| Python | Application development |
| Flask | Web application backend |
| Pandas | Data processing |
| HTML | Web page structure |
| CSS | User interface styling |
| JavaScript | Frontend interaction |
| CSV | Laboratory and test dataset |
| Google Maps | Laboratory navigation |
| Web Speech API | Voice input |

---

## System Flow

```text
User
  |
  v
Web Interface
  |
  v
Search / Filter / Assistant Query
  |
  v
Flask Backend
  |
  v
Pandas Data Processing
  |
  v
Laboratory Dataset
  |
  v
Results
  |
  +---- Test Information
  |
  +---- Laboratory Details
  |
  +---- Price Comparison
  |
  +---- Navigation