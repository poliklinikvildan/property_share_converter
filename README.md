# property_share_converter
Property Deed Share Converter
# Share Converter App - README

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Contributions](#contributions)
- [License](#license)
- [Support and Contact](#support-and-contact)

<div style="border: 1px solid #ccc; padding: 10px; display: flex; justify-content: center;">
  <a href="https://user-images.githubusercontent.com/134360221/258585247-64b47d26-d743-48f1-8ab7-cd1f86ca36b1" target="_blank">
    <img src="https://user-images.githubusercontent.com/134360221/258585247-64b47d26-d743-48f1-8ab7-cd1f86ca36b1" alt="Image" style="width: 30%;">
  </a>
</div>

## Overview

The Share Converter app is a single HTML file application that simplifies the reading and understanding of shares on property deeds. It is specifically designed to handle cases involving multiple individuals or entities sharing ownership of the same deed. The app provides a user-friendly interface for converting share values between two common formats: ratio (A:B) and numeric (percentage).

## Installation

The Share Converter app does not require any installation or setup. Simply download the `index.html` file and open it in any modern web browser.

## Usage

1. Open the `index.html` file in your web browser.
2. The app's main title, "SHARE CONVERTER," will be displayed at the top of the page.
3. The table will show three columns: "Names," "Share as Ratio (A:B)," and "Share as Ratio (Numeric)."
4. To convert a ratio to a numeric value, enter the ratio in the "Share as Ratio (A:B)" input field of the corresponding row. The app will automatically update the "Share as Ratio (Numeric)" input field with the converted percentage value.
5. To convert a numeric value to a ratio, enter the percentage in the "Share as Ratio (Numeric)" input field of the corresponding row. The app will instantly update the "Share as Ratio (A:B)" input field with the converted ratio value.

## How It Works

The Share Converter app utilizes JavaScript functions to perform real-time conversions between ratio and numeric formats.

- `convertToNumeric(ratioId, numericId)`: This function is triggered when the user enters a ratio value in the "Share as Ratio (A:B)" input field. It extracts the numerator and denominator, calculates the corresponding percentage, and updates the "Share as Ratio (Numeric)" input field.

- `convertToRatio(numericId, ratioId)`: This function is triggered when the user enters a numeric value in the "Share as Ratio (Numeric)" input field. It converts the percentage value to a ratio format and updates the "Share as Ratio (A:B)" input field.

## Features

- Real-time Conversion: The app provides instant conversions between ratio and numeric formats, allowing users to see the results immediately as they input share values.

- Robust Input Validation: The app ensures that the entered values are valid and interpretable, avoiding potential errors and providing accurate conversion results.

- Scalability: The app is designed to handle multiple rows, making it efficient for analyzing property deeds with multiple shareholders.

## Technologies Used

The Share Converter app is built using the following technologies:

- HTML: For creating the structure and elements of the app.
- CSS: For styling the app and ensuring a visually appealing interface.
- JavaScript: For implementing the conversion logic and interactivity of the app.

## Contributions

This project is currently a single-file application and does not actively seek contributions. However, feedback, bug reports, and suggestions are welcome. If you encounter any issues or have ideas for improvements, please feel free to open an issue in the repository.

## License

The Share Converter app is released under the MIT License. 

## Support and Contact

For any questions, support, or inquiries, please contact github username: poliklinikvildan.

Thank you for using the Share Converter app! We hope it simplifies your work with property deed shares.
