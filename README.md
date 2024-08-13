# Senior-Friendly AI Chatbot App
## Overview

This project is designed to create a web-based AI chatbot application, specifically targeted towards users aged 50 and above. The application aims to analyze the user's mood or requests and recommend location categories accordingly, such as restaurants, cafes, or parks. Upon receiving a recommendation, users can view the suggested locations on a map.

## Files

### `index.html`

- **Description**: This is the main webpage where the AI chatbot is implemented. It serves as the user interface for seniors to interact with the chatbot.
- **Features**:
  - **User Interaction**: The AI chatbot engages with users by analyzing their mood or requests.
  - **Category Recommendation**: Based on the analysis, the chatbot recommends a relevant location category (e.g., restaurants, cafes, parks).
  - **Navigation**: Users can proceed to view recommended locations on a map by clicking the "View Map" button, which navigates to `map.html`.
- need openai apikey, endpoint

### `map.html`

- **Description**: This page utilizes the Google Maps API to display the recommended locations on a map.
- **Features**:
  - **Category Display**: Shows locations corresponding to the category recommended by the chatbot in `index.html`.
  - **Marker Information**: Each location is marked on the map, and hovering over a marker reveals detailed information about the place, including its name and location.
- need googlemaps apikey
