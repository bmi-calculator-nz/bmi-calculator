# [BMI Calculator NZ](bmicalc.nz) - Visit NOW

A simple, responsive Body Mass Index (BMI) Calculator for New Zealand. This tool allows users to calculate their BMI based on their height, weight, age, and gender. It also includes a dynamic chart to visualize BMI categories and results. The calculator supports both metric and imperial units (cm, kg, inches, lbs).

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview

The BMI Calculator NZ is a web-based tool designed to help individuals calculate their BMI easily and quickly. The tool takes input for age, gender, height, and weight, then computes and displays the BMI along with a category (Underweight, Normal weight, Overweight, Obese). For children, BMI is calculated based on age and gender-specific percentiles.

## Features
- Input options for height and weight in both metric (cm, kg) and imperial (inches, lbs) units.
- Interactive chart to visualize the user's BMI in relation to standard BMI categories.
- Responsive design that adapts to different screen sizes, making it mobile-friendly.
- Age-based calculation: The tool calculates BMI differently for adults and children, adjusting for specific growth patterns.
- Form validation: Prevents invalid input with a visual shake effect for incorrect fields.

## Installation

To set up the BMI Calculator on your local machine, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/bmi-calculator-nz.git
    ```

2. Navigate to the project folder:

    ```bash
    cd bmi-calculator-nz
    ```

3. Open the `index.html` file in your browser. You can open the file directly, or host it via a local server.

    If you have Python installed, you can serve the app locally:

    ```bash
    # For Python 3.x
    python -m http.server 8000
    ```

4. Then, visit `http://localhost:8000` in your browser.

## Usage

1. Open the `index.html` file in your browser.
2. Fill in the gender, age, height, and weight fields.
3. Select the units for height and weight (cm/kg or inches/lbs).
4. Click the "Calculate BMI" button to view your result.
5. The BMI result and the BMI category (Underweight, Normal weight, Overweight, Obese) will be displayed.
6. The chart below the result will update dynamically to show where your BMI fits within the standard BMI ranges.

## How It Works

1. **Data Input:** The user enters their gender, age, height, and weight.
2. **BMI Calculation:**
    - For adults, BMI is calculated using the formula:

    ``` 
    BMI = weight(kg) / (height(m))^2 
    ```

    - For children, a simplified version of BMI is used, but it could be updated to include BMI percentiles.
3. **Validation:** If any input is invalid (like an out-of-range age, height, or weight), the field will "shake" to alert the user.
4. **Chart Display:** The chart is updated with the user’s BMI to show where it falls within the BMI categories.

## Technologies Used
- **HTML5** for structure.
- **CSS3** for styling and responsive design.
- **JavaScript** for interactivity and logic.
- **Chart.js** for rendering the BMI chart.

## Contributing

Contributions are welcome! If you want to contribute, follow these steps:

1. Fork the repository.
2. Create a new branch:

    ```bash
    git checkout -b feature-name
    ```

3. Make your changes.
4. Commit your changes:

    ```bash
    git commit -am 'Add new feature'
    ```

5. Push to your branch:

    ```bash
    git push origin feature-name
    ```

6. Open a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- **Chart.js:** For the interactive chart that visually represents BMI categories.
- **Inspiration:** From various BMI calculators available online.
