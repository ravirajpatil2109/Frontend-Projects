# Temperature Converter

## Overview
This is a **Temperature Converter** application built using **JavaScript**. The application allows users to convert temperature values between different units (e.g., Celsius, Fahrenheit, and Kelvin). Users can input a temperature, select the unit to convert from, and select the unit to convert to. The tool will display the converted temperature once the "Convert" button is clicked.

## Features
- Convert temperature between Celsius, Fahrenheit, and Kelvin.
- User-friendly form for inputting temperature values and selecting units.
- The "Convert" button is enabled only when all fields are filled in.
- Displays the converted temperature dynamically without reloading the page.

## How it works
1. The user enters a temperature value.
2. The user selects the unit they want to convert **from**.
3. The user selects the unit they want to convert **to**.
4. Once all fields are filled, the "Convert" button becomes active.
5. Clicking the "Convert" button performs the conversion and displays the result below the form.

## Technologies Used
- HTML
- CSS
- JavaScript

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ravirajpatil2109/temperature-converter.git
2. **Open the project**: Open `index.html` in your browser to use the Temperature Converter.

## Screenshot
![Temperature Converter](https://github.com/user-attachments/assets/6b850ec4-20b2-486f-8318-8f36c733b70b)

## Formula Used
- Celsius to Fahrenheit: `(C × 9/5) + 32`
- Fahrenheit to Celsius: `(F - 32) × 5/9`
- Celsius to Kelvin: `C + 273.15`
- Kelvin to Celsius: `K - 273.15`
- Fahrenheit to Kelvin: `(F - 32) × 5/9 + 273.15`
- Kelvin to Fahrenheit: `(K - 273.15) × 9/5 + 32`

## Future Enhancements
- Add more temperature units (Rankine, Réaumur).
- Add a history of conversions for the user.
- Allow conversion between multiple temperature units at once.

## Contributing
Feel free to contribute by opening a pull request or raising an issue.
