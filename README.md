# Currency-Converter

Overview
The Currency Converter is a simple web application that allows users to convert an amount from one currency to another. The exchange rates are fetched from an external API, and the application supports a wide range of currencies.

*Features*
Enter an amount to convert.
Select the source and target currencies from dropdowns.
Display the converted amount.
Automatically updates the exchange rate on page load and on user request.
Displays country flags corresponding to selected currencies.
Installation
Clone the repository:
sh
Copy code
git clone https://github.com/your-repository/currency-converter.git
Navigate to the project directory:
sh
Copy code
cd currency-converter
Open index.html in your preferred web browser.
Usage
Enter the amount you wish to convert in the input field.
Select the source currency from the "From" dropdown.
Select the target currency from the "To" dropdown.
Click the "Get Exchange Rate" button to view the converted amount.
The exchange rate will be updated and displayed automatically on page load.
File Structure
index.html: The main HTML file containing the structure of the web application.
style.css: The CSS file for styling the web application.
app.js: The JavaScript file containing the main logic for fetching exchange rates and updating the UI.
code.js: The JavaScript file containing the country list and their corresponding country codes.