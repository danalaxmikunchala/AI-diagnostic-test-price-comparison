# AI Diagnostic Test Price Comparison

## About the Project

AI Diagnostic Test Price Comparison is a web application developed to help users explore diagnostic tests and compare laboratory prices based on available data.

The application allows users to search for diagnostic tests, select a location, view available laboratories, compare listed prices, and open navigation directions for a selected laboratory.

It also includes an interactive assistant that can handle queries related to diagnostic tests, laboratories, prices, and locations. Voice input is supported through the browser.

This project was developed as a collaborative academic project.

---

## Project Objectives

The main objectives of this project are:

- To provide an easy way to search for diagnostic tests
- To display laboratory options based on location
- To compare diagnostic test prices
- To identify lower-priced options from the available dataset
- To provide laboratory location and navigation support
- To provide an interactive text and voice-based assistant
- To present diagnostic laboratory information through a simple web interface

---

## Key Features

### 1. Diagnostic Test Search

Users can search for diagnostic tests available in the dataset.

### 2. Location-Based Search

Users can select a city or area to find relevant laboratory options.

### 3. Price Comparison

The application displays the listed prices of diagnostic tests from different laboratories so users can compare them.

### 4. Lower-Priced Option

The application can identify a lower-priced laboratory option among the matching records available in the dataset.

### 5. Laboratory Information

Users can view laboratory names and related location information.

### 6. Navigation

Users can open Google Maps directions for a selected laboratory.

### 7. Interactive Assistant

The application provides an interactive assistant for queries related to:

- Diagnostic tests
- Laboratory names
- Prices
- Locations
- Available services

### 8. Voice Input

Users can provide queries using microphone input through browser-based speech recognition.

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Application development |
| Flask | Backend web framework |
| Pandas | Data processing |
| HTML | Web page structure |
| CSS | User interface styling |
| JavaScript | Frontend interaction |
| CSV | Diagnostic test and laboratory dataset |
| Google Maps | Navigation |
| Web Speech API | Voice input |

---

## Project Structure

```text
AI-diagnostic-test-price-comparison/
│
├── app.py
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   └── lab_prices.csv
│
├── static/
│   ├── css/
│   │   └── style.css
│   │
│   └── js/
│       └── script.js
│
└── templates/
    └── index.html